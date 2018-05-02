# api doc

创作步骤：

1. 先把整体接口整体，输出各个接口的字段bean
2. 根据各个字段找出各接口之间的关系
3. 确认数据库，以及各数据表之间的外键关系，通常需要结合接口字段考虑
4. 实施开发接口

## 首页 home.wpy

### 首页发现列表

> home_page_discover_list.md

#### 说明：

+ logo 尺寸：750*360 96dpi 24位深度 ==> 167kb


### 首页 banner 广告

> home_page_banner_adverts_list.md

## 详情页 home_detail.wpy

### 主页商品列表

> https://sujiefs.com//api/home/hostGoodsList?page=1&size=10&cateCode=021&sort=1&skuval=&sign=694e9f6dec1f1d11475a5ac688d8d644&time=20180430155433

```
{"reason":"","code":"0","page_total":3,"category":{"code":"021","name":"时尚套装专区","logo":"http://sujiefs.com/upload/images/20180319/201803191401583397599.jpg","id":"2c9257a160e0cb1c0160ee3562e0024e","attrs":[{"attrValList":[{"attrName":"品牌","attrNameId":211,"attrVal":"素洁","id":554}],"attrName":{"attrName":"品牌","categoryCode":"021","id":211}},{"attrValList":[{"attrName":"年份季节","attrNameId":212,"attrVal":"2018全新升级版","id":555}],"attrName":{"attrName":"年份季节","categoryCode":"021","id":212}}]},"list":[{"marketPrice":170,"saleCount":35,"businessName":"广州素洁服饰公司","businessId":"4028800457b6cf7a0157b7998c39001d","thumLogo":"http://sujiefs.com/upload/images/20171104/201711041932425797386_thumbnail.jpg","title":"韩版女装秋季新款系带条纹长袖衬衫 T17D807","evaluateCount":0,"price":68,"name":"新款系带条纹长袖衬衫 T17D807","stockNum":900,"wholePrice":63,"logo":"http://sujiefs.com/upload/images/20171104/201711041932425797386.jpg","id":"2c9257a15f37e432015f86d624980b73"},{"marketPrice":170,"saleCount":76,"businessName":"广州素洁服饰公司","businessId":"4028800457b6cf7a0157b7998c39001d","thumLogo":"http://sujiefs.com/upload/images/20171104/201711041906545460701_thumbnail.jpg","title":"韩版性感挂脖露肩衬衫长袖 T17D802","evaluateCount":0,"price":68,"name":"韩版性感挂脖露肩衬衫长袖  T17D802","stockNum":1599,"wholePrice":62,"logo":"http://sujiefs.com/upload/images/20171104/201711041906545460701.jpg","id":"2c9257a15f37e432015f86bf1a860b33"},{"marketPrice":169,"saleCount":0,"businessName":"广州素洁服饰公司","businessId":"4028800457b6cf7a0157b7998c39001d","thumLogo":"http://sujiefs.com/upload/images/20171020/201710201040167674622_thumbnail.jpg","title":"冬季新品腰带微喇开叉休闲裤 P17D709","evaluateCount":0,"price":68,"name":"冬季新品腰带微喇开叉休闲裤 P17D709","stockNum":6000,"wholePrice":63,"logo":"http://sujiefs.com/upload/images/20171020/201710201040167674622.jpg","id":"2c9257a15eaf3ade015f37b0d3441486"},{"marketPrice":169,"saleCount":63,"businessName":"广州素洁服饰公司","businessId":"4028800457b6cf7a0157b7998c39001d","thumLogo":"http://sujiefs.com/upload/images/20171020/201710201700188051868_thumbnail.jpg","title":"冬季欧美时尚镂空千鸟格衬衫设计感 T17D719","evaluateCount":0,"price":68,"name":"冬季欧美时尚镂空千鸟格衬衫设计感 T17D719","stockNum":499,"wholePrice":63,"logo":"http://sujiefs.com/upload/images/20171020/201710201700188051868.jpg","id":"2c9257a15f37e432015f3911b85000c8"},{"marketPrice":268,"saleCount":65,"businessName":"广州素洁服饰公司","businessId":"4028800457b6cf7a0157b7998c39001d","thumLogo":"http://sujiefs.com/upload/images/20171020/201710201409594109843_thumbnail.jpg","title":"格子半身裙 时尚高腰a字裙 S17D701","evaluateCount":0,"price":68,"name":"格子半身裙 时尚高腰a字裙 S17D701","stockNum":2500,"wholePrice":63,"logo":"http://sujiefs.com/upload/images/20171020/201710201409594109843.jpg","id":"2c9257a15f37e432015f3876624d003f"},{"marketPrice":169,"saleCount":46,"businessName":"广州素洁服饰公司","businessId":"4028800457b6cf7a0157b7998c39001d","thumLogo":"http://sujiefs.com/upload/images/20171005/201710051619563125881_thumbnail.jpg","title":"高腰不规则荷叶边鱼尾半身裙 S17D611-11","evaluateCount":0,"price":73,"name":"高腰不规则荷叶边鱼尾半身裙 S17D611-11","stockNum":2000,"wholePrice":69,"logo":"http://sujiefs.com/upload/images/20171005/201710051619563125881.jpg","id":"2c9257a15eaf3ade015eeba2a3000727"},{"marketPrice":269,"saleCount":69,"businessName":"广州素洁服饰公司","businessId":"4028800457b6cf7a0157b7998c39001d","thumLogo":"http://sujiefs.com/upload/images/20171104/201711041743482116501_thumbnail.jpg","title":"韩版宽松高腰金丝绒背带阔腿裤 P17D803","evaluateCount":0,"price":78,"name":"金丝绒背带阔腿裤 P17D803","stockNum":1500,"wholePrice":72,"logo":"http://sujiefs.com/upload/images/20171104/201711041743482116501.jpg","id":"2c9257a15f37e432015f8671e8900b10"},{"marketPrice":195,"saleCount":158,"businessName":"广州素洁服饰公司","businessId":"4028800457b6cf7a0157b7998c39001d","thumLogo":"http://sujiefs.com/upload/images/20171019/201710191701514264558_thumbnail.jpg","title":"条纹阔腿裤女新款运动休闲丝绒裤开叉 P17D707","evaluateCount":0,"price":78,"name":"条纹阔腿裤女新款运动休闲丝绒裤开叉 P17D707","stockNum":2500,"wholePrice":73,"logo":"http://sujiefs.com/upload/images/20171019/201710191701514264558.jpg","id":"2c9257a15eaf3ade015f33e54ffb1405"},{"marketPrice":195,"saleCount":131,"businessName":"广州素洁服饰公司","businessId":"4028800457b6cf7a0157b7998c39001d","thumLogo":"http://sujiefs.com/upload/images/20171020/201710201608069496801_thumbnail.jpg","title":"全棉V领系带衬衫喇叭袖绑带宽松上衣 T17D712","evaluateCount":0,"price":78,"name":"全棉V领系带衬衫喇叭袖绑带宽松上衣  T17D712","stockNum":3000,"wholePrice":73,"logo":"http://sujiefs.com/upload/images/20171020/201710201608069496801.jpg","id":"2c9257a15f37e432015f38de99a2009f"},{"marketPrice":198,"saleCount":75,"businessName":"广州素洁服饰公司","businessId":"4028800457b6cf7a0157b7998c39001d","thumLogo":"http://sujiefs.com/upload/images/20171020/201710201109278020723_thumbnail.jpg","title":"韩版高腰针织阔腿裤宽松港味九分裤 P17D724","evaluateCount":0,"price":78,"name":"韩版高腰针织阔腿裤宽松港味九分裤 P17D724","stockNum":1000,"wholePrice":73,"logo":"http://sujiefs.com/upload/images/20171020/201710201109278020723.jpg","id":"2c9257a15eaf3ade015f37c87e3814bb"}]}
```

