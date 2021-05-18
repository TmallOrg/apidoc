#同芙三期设计文档：
![](first-level.png)

### 总体来说分为三部分:
1. header (search,tag,)
2. body (category)
3. footer (recommend)

### header:
![](header.png)

### body:
![](body.png)

### footer:
![](footer.png)

### 主要是以body作为区分，样式包括：
![](body-1.png)
![](body-2.png)
![](body-3.png)
![](body-4.png)
![](body-5.png)


### body细分样式：
### list:[productDetail]

navi_type:

* type_healthBeauty (健康美容)
* type_education (教育培训)
* type_tourismAndPension (旅游养老)
* type_fresh (农业生鲜)
* type_eShop (网上商城)
* type_liveStreaming (视频直播)
* type_medicalTreatment (医疗抗衰)
* type_living (跳转到直播)
* type_video (跳转到视频)
* type_url (跳转到url)

#### category-1 (一长两短)
![](category-1.png)

```
category-1 

style: category-1 
{
	total-title-font-size:20,
	total-title-font-color:#333333,
	product-title-font-size:15,
	product-title-font-color:#FFF,
	product-price-font-size:#13,
	product-price-font-color:#FFF,
	product-marketPrice-font-size:#13,
	product-marketPrice-font-color:#FFF,
	product-image-1-w"id"th:50%,
	product-image-2-w"id"th:25%,
	product-image-3-w"id"th:25%,
	product-image-height: 50px
}
```

```
data

{
  style: category-1 
  title:"限时优惠",
  goodslist:[
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"面部补水，限时优惠",price:"1980",marketPrice:"2000"},
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"强效补水",price:"1980",marketPrice:"2000"},
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"强效补水SPA",price:"1980",marketPrice:"2000"},
  ]
}

```

#### category-2 (轮训)
![](category-2.png)

```
style: category-2
{
	product-image-height: 50px
}
```
```
data

{
  style: category-2
  goodslist:[
  {"id":"asdf","imagePath":"http://www.ba"id"u.com/img.png",url:"http://www.ba"id"u.com"},
  {"id":"asdf","imagePath":"http://www.ba"id"u.com/img.png",url:"http://www.ba"id"u.com"},
  {"id":"asdf","imagePath":"http://www.ba"id"u.com/img.png",url:"http://www.ba"id"u.com"},
  ]
}
```
#### category-3 (无限右滑)
![](category-3.png)

```
style: category-3
{
	product-image-height: 50px,
	product-image-w"id"th: 50px,
	product-title-font-size:15,
	product-title-font-color:#FFF,
	product-"subtitle"-font-size:15,
	product-"subtitle"-font-color:#FFF,
}
```
```
data

{
  style: category-3
  goodslist:[
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"面部脂肪填充","subtitle":"1000"},
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"面部脂肪填充","subtitle":"1000"},
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"面部脂肪填充","subtitle":"1000"},
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"面部脂肪填充","subtitle":"1000"},
  
  ]
}
```


#### category-4 (两短)

![](category-4.png)

```
style: category-4
{
	product-image-height: 50px,
	product-image-w"id"th: 50%,
	
}
```
```
data

{
  style: category-4
  title:""
  goodslist:[
    {"id":"asdf","imagePath":"http://www.ba"id"u.com/img.png",url:"http://www.ba"id"u.com"}, 
    {"id":"asdf","imagePath":"http://www.ba"id"u.com/img.png",url:"http://www.ba"id"u.com"},
  
  ]
}
```
#### category-5 (两短 2)
![](category-5.png)


```
style: category-5
{
	product-image-height: 50px,
	product-image-w"id"th: 50px,
	product-title-font-size:15,
	product-title-font-color:#FFF,
	product-"subtitle"-font-size:15,
	product-"subtitle"-font-color:#FFF,		
	product-desp-font-size:15,
	product-desp-font-color:#FFF,		
}
```
```
data

{
  style: category-5,
  title: 今日特惠
  goodslist:[
  {"id":"asdf","imagePath":"http://www.ba"id"u.com",title:"特价机票抢购","name":"深圳🛬广州",price:"1000",discout:"5.0"},
  {"id":"asdf","imagePath":"http://www.ba"id"u.com",title:"特价机票抢购","name":"深圳🛬广州",price:"1000",discout:"5.0"}, 
  
  ]
}
```

#### category-6 (四短-带标题)
![](category-6.png)

```
style: category-6
{
	product-image-height: 50px,
	product-image-w"id"th: 50px,
	product-title-font-size:15,
	product-title-font-color:#FFF,
	product-price-font-size:15,
	product-price-font-color:#FFF,		
	product-desp-font-size:15,
	product-desp-font-color:#FFF,		
	product-desp-bg-color:#FF000,
}
```

```
{
  style: category-6,
  title: 今日特惠
  goodslist:[
  {"id":"asdf","imagePath":"http://www.ba"id"u.com",title:"特价机票抢购","name":"深圳🛬广州",price:"1000",discout:"5.0"},
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"深圳🛬广州",price:"1000",desp:"仅剩5件"}, 
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"深圳🛬广州",price:"1000",desp:"仅剩5件"}, 
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"深圳🛬广州",price:"1000",desp:"仅剩5件"}, 
  
  ]
}
```

#### category-7 (一长带标题)
![](category-7.png)

```
style: category-7
{
	product-image-height: 50px,
	product-left-tag-font-size:15,
	product-left-tagfont-color:#FFF,
	product-right-tag-font-size:15,
	product-right-tag-font-color:#FFF,
	product-title-font-size:15,
	product-title-color:#FFF,
	
}
```

```
{
  style: category-7,
  goodslist:[
  {"id":"asdf","imagePath":"http://www.ba"id"u.com",title:"大品牌春季套装试穿",v"id"eoPath:"http://www.ba"id"u.com",visNum:"20",timeDis:"4:00"}  
  ]
}

```
#### category-8 (两短-带标题)
![](category-8.png)

```
style: category-8
{
	product-image-height: 50px,
	product-left-tag-font-size:15,
	product-left-tagfont-color:#FFF,
	product-right-tag-font-size:15,
	product-right-tag-font-color:#FFF,
	product-title-font-size:15,
	product-title-color:#FFF,
	
}
```

```
{
  style: category-8,
  goodslist:[
  {"id":"asdf","imagePath":"http://www.ba"id"u.com",title:"大品牌春季套装试穿",v"id"eoPath:"http://www.ba"id"u.com",visNum:"20",timeDis:"4:00"},
   {"id":"asdf","imagePath":"http://www.ba"id"u.com",title:"大品牌春季套装试穿",v"id"eoPath:"http://www.ba"id"u.com",visNum:"20",timeDis:"4:00"},
  ]
}

```


#### category-9 (无限右滑+分类)
![](category-9.png)

```
style: category-9
{
	product-image-height: 50px,
	product-image-w"id"th: 50px,
	product-title-font-size:15,
	product-title-font-color:#FFF,
	product-price-font-size:15,
	product-price-font-color:#FFF,		
	product-desp-font-size:15,
	product-desp-font-color:#FFF,		
	product-desp-bg-color:#FF000,
}
```

```
{
  style: category-9,
  title: 优选商家,
  tags:["全部","蔬菜","水果"]
  goodslist:[
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"同芙新鲜", desp:"新用户减100"},
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"同芙新鲜", desp:"新用户减100"},
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"同芙新鲜", desp:"新用户减100"},
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"同芙新鲜", desp:"新用户减100"},
  
  ]
}
```

### footer:
#### footer-1 (带tag-cell-tag)
##### style 1
![](footer-1.png)

##### style 2
![](footer-2.png)

```
style：footer-1
{

}
```
```
{
  "id":asdfasefasdf,
  style: footer-1,
  title: 优选商家,
  tags:[{"id":"asdf“,"name":"理我最近"},{"id":"asdf“,"name":"优选好评"},{"id":"asdf“,"name":"口碑优先"}]
  list:[
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"同芙美容连锁", commonNum:"2800评论", dis:"2.0公里", price:"1980起",discountlist:["新用户减100","满100减50"],tag"name":"项目",taglist:["日常护理","医学美容","面部补水"]},
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"同芙美容连锁", commonNum:"2800评论", dis:"2.0公里", price:"1980起",discountlist:["新用户减100","满100减50"],tag"name":"项目",taglist:["日常护理","医学美容","面部补水"]},
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"同芙美容连锁", commonNum:"2800评论", dis:"2.0公里", price:"1980起",discountlist:["新用户减100","满100减50"],tag"name":"项目",taglist:["日常护理","医学美容","面部补水"]},
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"同芙美容连锁", commonNum:"2800评论", dis:"2.0公里", price:"1980起",discountlist:["新用户减100","满100减50"],tag"name":"项目",taglist:[{"name":"日常护理",price:"0.0"},{"name":"医学美容",price:"0.0"},{"name":"面部补水",price:"0.0"}]}
  ]
}

```
#### footer-2 (瀑布流)
![](footer-3.png)


```
 "id":asdfasefasdf,
  style: footer-2,
  title: 优选商家,
  tags:[{"id":"asdf“,"name":"理我最近"},{"id":"asdf“,"name":"优选好评"},{"id":"asdf“,"name":"口碑优先"}]
  list:[
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"同芙美容连锁", rightTag:"月售899", w"id"th:"0.5",height:200, price:"1980起",discountlist:["新用户减100","满100减50"]},{"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"同芙美容连锁", rightTag:"月售899", w"id"th:"0.5",height:200, price:"1980起",discountlist:["新用户减100","满100减50"]},{"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"同芙美容连锁", rightTag:"月售899", w"id"th:"0.5",height:200, price:"1980起",discountlist:["新用户减100","满100减50"]},{"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"同芙美容连锁", rightTag:"月售899", w"id"th:"0.5",height:200, price:"1980起",discountlist:["新用户减100","满100减50"]},
  ]


```
#### footer-3 ()
![](footer-6.png)

```
 "id":asdfasefasdf,
  style: footer-3,
  title: 优选商家,
  tags:[{"id":"asdf“,"name":"理我最近"},{"id":"asdf“,"name":"优选好评"},{"id":"asdf“,"name":"口碑优先"}]
  list:[
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"同芙美容连锁", rightTag:"月售899", w"id"th:"0.5",height:200,leftTag:"1280"} ,
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"同芙美容连锁", rightTag:"月售899", w"id"th:"0.5",height:200,leftTag:"1280"}  ]
```

#### footer-4 (带头像)
![](footer-7.png)

```
 "id":asdfasefasdf,
  style: footer-4,
  title: 案例分享,
    list:[
  {
  "id":"asdf",
  "imagePath":"http://www.ba"id"u.com",
  "name":"同芙美容连锁",subModule:
  {
                "id": "asdfaefasdfasdf",
                ""name"": "张萌",
                "title": "主任医师",
                "desp": "50年工作经验",
                ""imagePath"": "http://112.74.166.59:5000/public/download/1616941007514"
            },
  {"id":"asdf","imagePath":"http://www.ba"id"u.com","name":"同芙美容连锁",subModule:
  {
                "id": "asdfaefasdfasdf",
                ""name"": "张萌",
                "title": "主任医师",
                "desp": "50年工作经验",
                ""imagePath"": "http://112.74.166.59:5000/public/download/1616941007514"
            }  ]
```


# Search Cell Style
## cell-1
![](cell1.png)

## cell-2
![](cell2.png)

## cell-3
![](cell3.png)

### 特别注意：
1.搜索商店时候：
shop 
category/searchshop

```
{
	"style":"cell-1",
    "list":[
        {
            "id": "asdfasdf",
            ""name"": "同芙健康连锁会员店",
            "address": "坂田大道富村弄",
            "longitude": 12.012,
            "latitude": 12.012,
            "phone": "1212312123",
            "score": "4.0",
            "colNum": "2000",
            "imageList": [
                "http://112.74.166.59:5000/public/download/1616941007514",
                "http://112.74.166.59:5000/public/download/1616941007514",
                "http://112.74.166.59:5000/public/download/1616941007514",
                "http://112.74.166.59:5000/public/download/1616941007514"
            ]
        },
        {
            "id": "asdfasdf",
            ""name"": "同芙健康连锁会员店2",
            "address": "坂田大道富村弄",
            "longitude": 12.012,
            "latitude": 12.012,
            "phone": "1212312123",
            "imageList": [
                "http://112.74.166.59:5000/public/download/1616941007514",
                "http://112.74.166.59:5000/public/download/1616941007514",
                "http://112.74.166.59:5000/public/download/1616941007514",
                "http://112.74.166.59:5000/public/download/1616941007514"
            ]
        }
    ]
}

```


2.搜索商品

```

{
	"style":"cell-1",
    "list":[
        {
            "v"id"eoList": [
                {
                    "id": "asdfaefasdfasdf",
                    "url": "http://www.ba"id"u.com",
                    "visNum": "20",
                    "timeDis": "4:00"
                },
                {
                    "id": "asdfaefasdfasdf",
                    "url": "http://www.ba"id"u.com",
                    "visNum": "20",
                    "timeDis": "4:00"
                }
            ],
            "title": "特价机票抢购",
            "discout": "5.0",
            "id": "asdfaefasdfasdf",
            ""name"": "0基础培训课程",
            "score": 4.0,
            "selNum": 100,
            "price": 1980,
            "commentNum": 2000,
            "marketPrice": 2000,
            "desp": [
                "课程形式：小班授课",
                "适用阶段:宁基础入门"
            ],
            "discountlist": [
                "新用户减100",
                "满100减50"
            ],
            "imageList": [
                "http://112.74.166.59:5000/public/download/1616941007514",
                "http://112.74.166.59:5000/public/download/1616941007514",
                "http://112.74.166.59:5000/public/download/1616941007514",
                "http://112.74.166.59:5000/public/download/1616941007514"
            ]
        }
    ]
}

```


# API 描述：

## 首页：

![](first-level.png)
![](home-exa.png)

### 红色部分： /tf/category/home
### 红色部分-cell 更多： /tf/category/home-category 
### 绿色部分：/tf/category/home-footer
---
## 商店详情

![](shop-detail.png)

### tf/category/shop

---

## 机构详情

![](shop-detail-sep.png)

### /tf/category/shopDetail
---

## 购物车分类
![](shop-card-all.png)
### 红色部分：/tf/category/shopMenu
### 绿色部分：/tf/category/shopAll
---

## 专家详情：
![](exp-detail.png)
### /tf/category/expert
---
![](pro-d.png)
### /tf/category/productDetail
---
## 各种推荐专用接口(用于各种详情下面的推荐)
### /tf/category/productRecommend

## 评论专用接口(用于更多评论)
### /tf/category/productCommend

## 筛选
![](search.png)

![](search-type2.png)

### /tf/category/searchType 包括排序和筛选(可多选)，头部分类（图片可以无）

### 搜索商店 /tf/category/searchshop
### 搜索商品 /tf/category/searchshop

## 服务
###预约服务详情 /category/service/schedule
### schedule, list两个对应两种不同的UI, schedule的优先级会更高

```
 "schedule":[],##当 schedule = 5-1 的时候会出现
 "list":[],
 "dsp":"预期说声哈"
```

##### 读取 schedule 字段

![](service-1.png)

##### 读取 list 字段

![](service-2.png)

----

### 我的-预约列表 /category/service/list
```
(全部)APPOINT_ALL, 
(预约到店)SERVICE_OFFLINE, 
(完成)SERVICE_FINSH, 
(取消)SERVICE_CANCEL,
```
![](service-list.png)

