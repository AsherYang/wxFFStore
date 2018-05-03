# 主页商品专区列表

点击首页发现列表--> 进入到对应的商品分区。

接口根据 category code 进行查询

## 接口

> https://sujiefs.com//api/home/hostGoodsList?page=1&size=10&cateCode=021&sort=1&skuval=&sign=694e9f6dec1f1d11475a5ac688d8d644&time=20180430155433

## 返回值

```
{
    "reason": "",
    "code": "0",
    "page_total": 5,
    "category": {
        "code": "022",
        "name": "春夏新品专区",
        "logo": "http://sujiefs.com/upload/images/20180322/201803221134300716543.jpg",
        "id": "2c9257a16126d14701612b52808100d6",
        "attrs": [
            {
                "attrValList": [{
                    "attrName": "品牌",
                    "attrNameId": 213,
                    "attrVal": "素洁",
                    "id": 556
                }],
                "attrName": {
                    "attrName": "品牌",
                    "categoryCode": "022",
                    "id": 213
                }
            },
            {
                "attrValList": [{
                    "attrName": "年份季节",
                    "attrNameId": 214,
                    "attrVal": "2018春季新款",
                    "id": 557
                }],
                "attrName": {
                    "attrName": "年份季节",
                    "categoryCode": "022",
                    "id": 214
                }
            }
        ]
    },
    "list": [
        {
            "marketPrice": 119,
            "saleCount": 6,
            "businessName": "广州素洁服饰公司",
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "thumLogo": "http://sujiefs.com/upload/images/20180423/201804231129454571221_thumbnail.jpg",
            "title": "新款韩版印花字母短款T恤衫 T18C076",
            "evaluateCount": 0,
            "price": 63,
            "name": "新款韩版印花字母短款T恤衫  T18C076",
            "stockNum": 80,
            "wholePrice": 60,
            "logo": "http://sujiefs.com/upload/images/20180423/201804231129454571221.jpg",
            "id": "2c9257a16136c3d60162f09204f04e9f"
        },
        {
            "marketPrice": 149,
            "saleCount": 78,
            "businessName": "广州素洁服饰公司",
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "thumLogo": "http://sujiefs.com/upload/images/20180314/201803141614502396659_thumbnail.jpg",
            "title": "2018女士时尚印花蕾丝长袖打底衫T18C0113",
            "evaluateCount": 0,
            "price": 63,
            "name": "2018女士时尚印花蕾丝长袖打底衫T18C0113",
            "stockNum": 600,
            "wholePrice": 59,
            "logo": "http://sujiefs.com/upload/images/20180314/201803141614502396659.jpg",
            "id": "2c9257a16136c3d601622396ecfd221d"
        },
        {
            "marketPrice": 119,
            "saleCount": 84,
            "businessName": "广州素洁服饰公司",
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "thumLogo": "http://sujiefs.com/upload/images/20180314/201803141132256826302_thumbnail.jpg",
            "title": "2018女士潮流条纹长袖上衣T18C028",
            "evaluateCount": 0,
            "price": 63,
            "name": "2018女士潮流条纹长袖上衣T18C028",
            "stockNum": 299,
            "wholePrice": 59,
            "logo": "http://sujiefs.com/upload/images/20180314/201803141132256826302.jpg",
            "id": "2c9257a16136c3d60162229606fc216b"
        },
        {
            "marketPrice": 175,
            "saleCount": 3,
            "businessName": "广州素洁服饰公司",
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "thumLogo": "http://sujiefs.com/upload/images/20180424/201804241601446726444_thumbnail.jpg",
            "title": "夏季印花棉修身针织T恤 T18C077",
            "evaluateCount": 0,
            "price": 75,
            "name": "夏季印花棉修身针织T恤  T18C077",
            "stockNum": 180,
            "wholePrice": 73,
            "logo": "http://sujiefs.com/upload/images/20180424/201804241601446726444.jpg",
            "id": "2c9257a16136c3d60162f6b189d14fee"
        },
        {
            "marketPrice": 249,
            "saleCount": 3,
            "businessName": "广州素洁服饰公司",
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "thumLogo": "http://sujiefs.com/upload/images/20180429/201804291348344307038_thumbnail.jpg",
            "title": "新款印花圆领蝙蝠袖拼接面料T恤 T18C080",
            "evaluateCount": 0,
            "price": 77,
            "name": "新款印花圆领蝙蝠袖拼接面料T恤 T18C080",
            "stockNum": 120,
            "wholePrice": 55,
            "logo": "http://sujiefs.com/upload/images/20180429/201804291348344307038.jpg",
            "id": "2c9257a16136c3d601630ff9a1ae5504"
        },
        {
            "marketPrice": 138,
            "saleCount": 95,
            "businessName": "广州素洁服饰公司",
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "thumLogo": "http://sujiefs.com/upload/images/20180314/201803141048246599455_thumbnail.jpg",
            "title": "2018女士百搭印花短袖上衣T18C027",
            "evaluateCount": 0,
            "price": 79,
            "name": "2018女士百搭印花短袖上衣T18C027",
            "stockNum": 600,
            "wholePrice": 75,
            "logo": "http://sujiefs.com/upload/images/20180314/201803141048246599455.jpg",
            "id": "2c9257a16136c3d60162226ca9842128"
        },
        {
            "marketPrice": 168,
            "saleCount": 126,
            "businessName": "广州素洁服饰公司",
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "thumLogo": "http://sujiefs.com/upload/images/20180314/201803141056200954178_thumbnail.jpg",
            "title": "2018女士百搭印花长袖上衣T18C025",
            "evaluateCount": 0,
            "price": 79,
            "name": "2018女士百搭印花长袖上衣T18C025",
            "stockNum": 599,
            "wholePrice": 75,
            "logo": "http://sujiefs.com/upload/images/20180314/201803141056200954178.jpg",
            "id": "2c9257a16136c3d601622272cc1f2138"
        },
        {
            "marketPrice": 199,
            "saleCount": 6,
            "businessName": "广州素洁服饰公司",
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "thumLogo": "http://sujiefs.com/upload/images/20180420/201804201408181830759_thumbnail.jpg",
            "title": "印花圆领短袖纯棉T恤 T18C073",
            "evaluateCount": 0,
            "price": 79,
            "name": "印花圆领短袖纯棉T恤  T18C073",
            "stockNum": 30,
            "wholePrice": 75,
            "logo": "http://sujiefs.com/upload/images/20180420/201804201408181830759.jpg",
            "id": "2c9257a16136c3d60162e1ad43754bca"
        },
        {
            "marketPrice": 168,
            "saleCount": 82,
            "businessName": "广州素洁服饰公司",
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "thumLogo": "http://sujiefs.com/upload/images/20180314/201803141101541265640_thumbnail.jpg",
            "title": "2018女士优雅印花长袖上衣T18C026",
            "evaluateCount": 0,
            "price": 79,
            "name": "2018女士优雅印花长袖上衣T18C026",
            "stockNum": 600,
            "wholePrice": 75,
            "logo": "http://sujiefs.com/upload/images/20180314/201803141101541265640.jpg",
            "id": "2c9257a16136c3d60162227f43762148"
        },
        {
            "marketPrice": 148,
            "saleCount": 65,
            "businessName": "广州素洁服饰公司",
            "businessId": "4028800457b6cf7a0157b7998c39001d",
            "thumLogo": "http://sujiefs.com/upload/images/20180315/201803151620335076856_thumbnail.jpg",
            "title": "2018女士韩版潮流镂空上衣T18C0114",
            "evaluateCount": 0,
            "price": 88,
            "name": "2018女士韩版潮流镂空上衣T18C0114",
            "stockNum": 299,
            "wholePrice": 83,
            "logo": "http://sujiefs.com/upload/images/20180315/201803151620335076856.jpg",
            "id": "2c9257a16136c3d60162239bf1862230"
        }
    ]
}
```
