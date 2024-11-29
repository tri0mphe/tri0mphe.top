---
date: 2024-08-12
author: coy0te
lastmod: 2024-11-29 17:16:32
title: 中文图片测试blog333
---


```docker
FROM alpine:latest
COPY resource.tar /
RUN touch /resource.tar
RUN rm -f /resource.tar
ENTRYPOINT ["/bin/ash"]
```


![](图片1.png)