# 搜索所得商品列表

## 1. 点击分类，进行的搜索

分类 --> 二级分类

点击二级分类，是进行对应分类商品的搜索功能

### 1.1 接口

> https://sujiefs.com//api/mall/searchGoodsList?page=6&size=10&searchKeyWords=&cateCode=004007&sort=-1&skuval=&sign=d1260c4c7c83415023bccdcc6b69f293&time=20180606221032

### 1.2 返回值

接口与返回结果和 `host_category_goods_list.md` 类似

```
{
    "reason": "",
    "code": "0",
    "page_total": 3,
    "pageSize": 10,
    "category": {
        "code": "004005",
        "name": "时尚套装",
        "logo": "http://sujiefs.com/upload/images/20170816/201708161803492303325.jpg",
        "id": "2c9257a15de92f53015dea1b05ce0034",
        "attrs": []
    },
    "list": [
        {
            "marketPrice": 663,
            "code": "T18C071",
            "saleCount": 3,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20180416/201804161442294368291_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 152,
            "name": "上衣+半身裙两件套装裙 T18C071",
            "stockNum": 90,
            "logo": "http://sujiefs.com/upload/images/20180416/201804161442294368291.jpg",
            "id": "2c9257a16136c3d60162cd35215d4727",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 268,
            "code": "T18C017",
            "saleCount": 93,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20180317/201803171724467979428_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 198,
            "name": "2018女士优雅韩版气质套装T18C017",
            "stockNum": 1080,
            "logo": "http://sujiefs.com/upload/images/20180317/201803171724467979428.jpg",
            "id": "2c9257a16136c3d601623346cd3b2880",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 208,
            "code": "SJ20170810-22",
            "saleCount": 206,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20170814/201708141556474590388_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 69,
            "name": "冰丝针织套装 宽松T恤高腰系带七分裤 SJ20170810-22",
            "stockNum": 1294,
            "logo": "http://sujiefs.com/upload/images/20170814/201708141556474590388.jpg",
            "id": "2c9257a15dddc960015ddfb4797a0082",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 319,
            "code": "SJ20170706-33",
            "saleCount": 279,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20170808/201708081925595380686_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 78,
            "name": "重工立体荷叶装饰三件套包臀半身裙套装  SJ20170706-33",
            "stockNum": 1221,
            "logo": "http://sujiefs.com/upload/images/20170808/201708081925595380686.jpg",
            "id": "2c9257a15db2e750015dc199ed2803d0",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 188,
            "code": "SJ20170708-30",
            "saleCount": 330,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20170804/201708041045154063165_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 69,
            "name": "斜肩短袖上衣印花雪纺哈伦裤九分裤两件套 SJ20170708-30",
            "stockNum": 2670,
            "logo": "http://sujiefs.com/upload/images/20170804/201708041045154063165.jpg",
            "id": "2c9257a15d94319f015dab253c9c03a7",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 339,
            "code": "SJ20170816-29",
            "saleCount": 80,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20170818/201708181859162430178_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 83,
            "name": "网纱裙条纹针织连衣裙 马甲短外套三件套 SJ20170816-29",
            "stockNum": 1920,
            "logo": "http://sujiefs.com/upload/images/20170818/201708181859162430178.jpg",
            "id": "2c9257a15def6196015df5012fc60195",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 269,
            "code": "J17D619-19",
            "saleCount": 85,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20171003/201710031747451834466_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 108,
            "name": "气质休闲修身显瘦格子长袖西装外套 J17D619-19",
            "stockNum": 1995,
            "logo": "http://sujiefs.com/upload/images/20171003/201710031747451834466.jpg",
            "id": "2c9257a15eaf3ade015ee1a7d866054f",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 169,
            "code": "SJ20170708-29",
            "saleCount": 199,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20170804/201708041052071908887_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 69,
            "name": "2017夏季新款韩版洋气显瘦套装chic心机露肩上衣阔腿短裤两件套#",
            "stockNum": 301,
            "logo": "http://sujiefs.com/upload/images/20170804/201708041052071908887.jpg",
            "id": "2c9257a15d94319f015dab29f09803b2",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 159,
            "code": "SJ20170708-25",
            "saleCount": 321,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20170804/201708041109126846073_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 59,
            "name": "2017新款洋气格子套装裙夏季时尚短款无袖背心鱼尾半身裙两件套#",
            "stockNum": 179,
            "logo": "http://sujiefs.com/upload/images/20170804/201708041109126846073.jpg",
            "id": "2c9257a15d94319f015dab39759e03d3",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 169,
            "code": "SJ20170708-24",
            "saleCount": 169,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20170804/201708041125388968408_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 55,
            "name": "夏季新款时尚高腰套装女小清新chic露肩T恤条纹半身长裙两件套潮",
            "stockNum": 1331,
            "logo": "http://sujiefs.com/upload/images/20170804/201708041125388968408.jpg",
            "id": "2c9257a15d94319f015dab51118703da",
            "sourceFlag": 1,
            "status": 1
        }
    ],
    "totalCount": 27,
    "pageNum": 1
}
```

## 2. 点击首页搜索框，进行搜索

首页搜索框 --> 搜索

与上述第一种搜索的区别在于: 请求接口时，`cateCode`是否被赋值

### 2.1 接口

> https://sujiefs.com//api/mall/searchGoodsList?page=1&size=10&searchKeyWords=%E7%B4%A0%E6%B4%81&cateCode=&sort=-1&skuval=&sign=d1260c4c7c83415023bccdcc6b69f293&time=20180606221032

### 2.2 返回值

返回结果，与上述不同之处在于，没有`category`返回信息

```
{
    "reason": "",
    "code": "0",
    "page_total": 48,
    "pageSize": 10,
    "list": [
        {
            "marketPrice": 299,
            "code": "T18C082",
            "saleCount": 36,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20180511/201805111530496618166_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 138,
            "name": "高端刺绣绣花衬衫T18C082",
            "stockNum": 180,
            "logo": "http://sujiefs.com/upload/images/20180511/201805111530496618166.jpg",
            "id": "2c9257a16136c3d601634e28c6135f78",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 339,
            "code": "T18C081",
            "saleCount": 3,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20180510/201805101439594599532_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 128,
            "name": "猫头休闲圆领短袖t恤 T18C081",
            "stockNum": 120,
            "logo": "http://sujiefs.com/upload/images/20180510/201805101439594599532.jpg",
            "id": "2c9257a16136c3d6016348cc332b5e5d",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 249,
            "code": "T18C080",
            "saleCount": 3,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20180429/201804291348344307038_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 77,
            "name": "新款印花圆领蝙蝠袖拼接面料T恤 T18C080",
            "stockNum": 120,
            "logo": "http://sujiefs.com/upload/images/20180429/201804291348344307038.jpg",
            "id": "2c9257a16136c3d601630ff9a1ae5504",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 299,
            "code": "T18C079",
            "saleCount": 3,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20180429/201804291236238898911_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 128,
            "name": "新款中长款条纹碎花雪纺印花裙子 T18C079",
            "stockNum": 120,
            "logo": "http://sujiefs.com/upload/images/20180429/201804291236238898911.jpg",
            "id": "2c9257a16136c3d601630fb5eaca54ec",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 299,
            "code": "T18C078",
            "saleCount": 2,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20180429/201804291127369995957_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 128,
            "name": "韩版黑色气质显瘦复古雪纺长裙子 T18C078",
            "stockNum": 60,
            "logo": "http://sujiefs.com/upload/images/20180429/201804291127369995957.jpg",
            "id": "2c9257a16136c3d601630f73c62354d7",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 175,
            "code": "T18C077",
            "saleCount": 3,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20180424/201804241601446726444_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 75,
            "name": "夏季印花棉修身针织T恤  T18C077",
            "stockNum": 180,
            "logo": "http://sujiefs.com/upload/images/20180424/201804241601446726444.jpg",
            "id": "2c9257a16136c3d60162f6b189d14fee",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 119,
            "code": "T18C076",
            "saleCount": 6,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20180423/201804231129454571221_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 63,
            "name": "新款韩版印花字母短款T恤衫  T18C076",
            "stockNum": 80,
            "logo": "http://sujiefs.com/upload/images/20180423/201804231129454571221.jpg",
            "id": "2c9257a16136c3d60162f09204f04e9f",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 528,
            "code": "T18C075",
            "saleCount": 0,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20180420/201804201549403948912_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 142,
            "name": "碎花雪纺连衣裙 T18C075",
            "stockNum": 60,
            "logo": "http://sujiefs.com/upload/images/20180420/201804201549403948912.jpg",
            "id": "2c9257a16136c3d60162e20b1fe74c20",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 476,
            "code": "T18C074",
            "saleCount": 3,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20180420/201804201459280965974_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 142,
            "name": "韩版黑色高腰连衣裙 T18C074",
            "stockNum": 60,
            "logo": "http://sujiefs.com/upload/images/20180420/201804201459280965974.jpg",
            "id": "2c9257a16136c3d60162e1dc7bfc4bfb",
            "sourceFlag": 1,
            "status": 1
        },
        {
            "marketPrice": 199,
            "code": "T18C073",
            "saleCount": 6,
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "businessName": "广州素洁服饰公司",
            "thumLogo": "http://sujiefs.com/upload/images/20180420/201804201408181830759_thumbnail.jpg",
            "evaluateCount": 0,
            "price": 79,
            "name": "印花圆领短袖纯棉T恤  T18C073",
            "stockNum": 30,
            "logo": "http://sujiefs.com/upload/images/20180420/201804201408181830759.jpg",
            "id": "2c9257a16136c3d60162e1ad43754bca",
            "sourceFlag": 1,
            "status": 1
        }
    ],
    "totalCount": 471,
    "pageNum": 1
}
```
