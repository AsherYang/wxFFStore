# api doc

创作步骤：

1. 先把整体接口整体，输出各个接口的字段bean
2. 根据各个字段找出各接口之间的关系
3. 确认数据库，以及各数据表之间的外键关系，通常需要结合接口字段考虑
4. 实施开发接口

## 首页

### 首页封面列表

>  https://sujiefs.com//api/mall/discoverList?page=1&size=10&sign=1c0c67948371e91081fac39137d990c4&time=20180430145004

```
{"reason":"","code":"0","list":[{"code":"022","logo":"http://sujiefs.com/upload/images/20180322/201803221134300716543.jpg","id":"2c9257a16126d14701612b52808100d6","attrs":[{"attrValList":[{"attrName":"品牌","attrNameId":213,"attrVal":"素洁","id":556}],"attrName":{"attrName":"品牌","categoryCode":"022","id":213}},{"attrValList":[{"attrName":"年份季节","attrNameId":214,"attrVal":"2018春季新款","id":557}],"attrName":{"attrName":"年份季节","categoryCode":"022","id":214}}]},{"code":"021","logo":"http://sujiefs.com/upload/images/20180319/201803191401583397599.jpg","id":"2c9257a160e0cb1c0160ee3562e0024e","attrs":[{"attrValList":[{"attrName":"品牌","attrNameId":211,"attrVal":"素洁","id":554}],"attrName":{"attrName":"品牌","categoryCode":"021","id":211}},{"attrValList":[{"attrName":"年份季节","attrNameId":212,"attrVal":"2018全新升级版","id":555}],"attrName":{"attrName":"年份季节","categoryCode":"021","id":212}}]},{"code":"020","logo":"http://sujiefs.com/upload/images/20180308/201803081427506631167.jpg","id":"2c9257a15f37e4320160014d4dfc1650","attrs":[{"attrValList":[{"attrName":"品牌","attrNameId":208,"attrVal":"素洁","id":551}],"attrName":{"attrName":"品牌","categoryCode":"020","id":208}},{"attrValList":[{"attrName":"年份季节","attrNameId":209,"attrVal":"2017冬季","id":552}],"attrName":{"attrName":"年份季节","categoryCode":"020","id":209}}]}]}
```

#### 说明：

+ logo 尺寸：750*360 96dpi 24位深度 ==> 167kb


### banner 广告

> https://sujiefs.com//api/adverts/list?sign=3dbb945130215a42abbf51643202ee44&time=20180430145841

```
{"reason":"","code":"0","list":[{"advertUrl":"/pages/home_detail?code=020","createTime":{"date":28,"day":4,"hours":14,"minutes":11,"month":11,"nanos":0,"seconds":38,"time":1514441498000,"timezoneOffset":-480,"year":117},"id":"2c9257a1609b12a301609bbf5e790169","isdeleted":0,"limitFowards":0,"limitPrice":0,"locationFlag":1,"picUrl":"http://sujiefs.com/upload/images/20180319/201803191442069389248.jpg","presentAmout":0,"promoDesc":"","promoPicUrl":"","promoTips":"","sort":4,"status":1,"title":"嘉年华","type":1,"updateTime":{"date":19,"day":1,"hours":14,"minutes":42,"month":2,"nanos":0,"seconds":9,"time":1521441729000,"timezoneOffset":-480,"year":118}},{"advertUrl":"/pages/home_detail?code=020","createTime":{"date":28,"day":4,"hours":15,"minutes":52,"month":11,"nanos":0,"seconds":12,"time":1514447532000,"timezoneOffset":-480,"year":117},"id":"2c9257a1609b12a301609c1b71a601b4","isdeleted":0,"limitFowards":0,"limitPrice":0,"locationFlag":1,"picUrl":"http://sujiefs.com/upload/images/20180319/201803191607213912571.jpg","presentAmout":0,"promoDesc":"","promoPicUrl":"","promoTips":"","sort":5,"status":1,"title":"冬季","type":1,"updateTime":{"date":19,"day":1,"hours":16,"minutes":7,"month":2,"nanos":0,"seconds":24,"time":1521446844000,"timezoneOffset":-480,"year":118}},{"advertUrl":"/pages/home_detail?code=019","createTime":{"date":29,"day":5,"hours":16,"minutes":41,"month":11,"nanos":0,"seconds":58,"time":1514536918000,"timezoneOffset":-480,"year":117},"id":"2c9257a1609b12a30160a16f5d9a039b","isdeleted":0,"limitFowards":0,"limitPrice":0,"locationFlag":1,"picUrl":"http://sujiefs.com/upload/images/20180322/201803221353348299896.jpg","presentAmout":0,"promoDesc":"","promoPicUrl":"","promoTips":"","sort":11,"status":1,"title":"时尚英伦风","type":1,"updateTime":{"date":22,"day":4,"hours":13,"minutes":53,"month":2,"nanos":0,"seconds":36,"time":1521698016000,"timezoneOffset":-480,"year":118}},{"advertUrl":"/pages/home_detail?code=020","createTime":{"date":20,"day":5,"hours":17,"minutes":29,"month":9,"nanos":0,"seconds":14,"time":1508491754000,"timezoneOffset":-480,"year":117},"id":"2c9257a15f37e432015f391d7d8d00d5","isdeleted":0,"limitFowards":0,"limitPrice":0,"locationFlag":1,"picUrl":"http://sujiefs.com/upload/images/20180321/201803211341067195861.jpg","presentAmout":0,"promoDesc":"","promoPicUrl":"","promoTips":"","sort":12,"status":1,"title":"趁年轻穿自己想穿的","type":1,"updateTime":{"date":21,"day":3,"hours":13,"minutes":41,"month":2,"nanos":0,"seconds":8,"time":1521610868000,"timezoneOffset":-480,"year":118}},{"advertUrl":"/pages/home_detail?code=020","createTime":{"date":5,"day":4,"hours":19,"minutes":40,"month":9,"nanos":0,"seconds":45,"time":1507203645000,"timezoneOffset":-480,"year":117},"id":"2c9257a15eaf3ade015eec56806f08a9","isdeleted":0,"limitFowards":0,"limitPrice":0,"locationFlag":1,"picUrl":"http://sujiefs.com/upload/images/20180322/201803221355480509362.jpg","presentAmout":0,"promoDesc":"","promoPicUrl":"","promoTips":"","sort":13,"status":1,"title":"热销潮流必买单品","type":1,"updateTime":{"date":22,"day":4,"hours":13,"minutes":55,"month":2,"nanos":0,"seconds":48,"time":1521698148000,"timezoneOffset":-480,"year":118}},{"advertUrl":"/pages/home_detail?code=019","createTime":{"date":29,"day":5,"hours":17,"minutes":4,"month":11,"nanos":0,"seconds":15,"time":1514538255000,"timezoneOffset":-480,"year":117},"id":"2c9257a1609b12a30160a183c3ff03a5","isdeleted":0,"limitFowards":0,"limitPrice":0,"locationFlag":1,"picUrl":"http://sujiefs.com/upload/images/20180322/201803221356007729116.jpg","presentAmout":0,"promoDesc":"","promoPicUrl":"","promoTips":"","sort":15,"status":1,"title":"秋冬","type":1,"updateTime":{"date":22,"day":4,"hours":13,"minutes":56,"month":2,"nanos":0,"seconds":1,"time":1521698161000,"timezoneOffset":-480,"year":118}}]}
```

