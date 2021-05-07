---
layout: post
title:  "新浪股票接口"
date:   2021-05-07 14:25:35 
category: 量化交易
tags: [股票]
---

## 关键词查询股票
``` 
http://suggest3.sinajs.cn/suggest/type=&key=茅台&name=suggestdata_1429775785401
```


## 股票最新行情
```
http://hq.sinajs.cn/list=sh601003,sh601001
```

## 最近二十天左右的每5分钟数据 
```
http://money.finance.sina.com.cn/quotes_service/api/json_v2.php/CN_MarketData.getKLineData?symbol=sz000001&scale=5&ma=5&datalen=1023
```
>参数：股票编号、分钟间隔（5、15、30、60）、均值（5、10、15、20、25）、查询个数点（最大值242）