---
title:      "Quảng cáo trả tiền bằng Facebook Ads Manager"
description:   "Quảng cáo truyền thống có còn lợi thế so với marketing online?"
date:       2017-01-20
author:     "Vu, Nguyen"
header-img: "http://www.socialmediaexaminer.com/wp-content/uploads/2015/06/lk-ads-manager-app-placeit.jpg"    
keyword :   "Quang cao facebook"                 
long-keyword: "quang cao facebook"        
target-site: "http://digitalife.top"    
category: "Paid Ads"
tags: ["Tiêu đề bài viết seo"]
---

<!-- BEGIN POST_EXCERPT: mo ta ngan ve noi dung bai viet -->
Công cụ quảng cáo Facebook đã trở nên mạnh mẽ hơn bao giờ hết
<!--more-->
<!-- END  POST_EXCERPT -->


## Facebook Ads Manager UI

## Create folder      

    /opt/www/domain.top/www
    /opt/www/domain.top/sub

## Copy source to that folder 

    cp -r /path-to/src /opt/www/domain.top/des 

### Edit config._yml 
    -- Edit as following: 
    url: domain.top
    baseurl: "" # empty

## Add nginx server_name on based that domain

    -- Edit /etc/nginx/sites-enabled/jekyll 
    bypass proxy to: 127.0.0.1:port
    with port from: 4001 to 4999 (999 web socketservers)

**Nginx restart**

    service nginx restart

## Re-run bash to load websocket server on ports

    -- Edit bash /opt/jekyll.sh (point right port), then run: 
    /opt/jekyll.sh

### Tips
    -- To fix LF, run: 
    dos2unix /opt/jekyll.sh 

### Test by netstat
    netstat -peanut

Thanks 


  
