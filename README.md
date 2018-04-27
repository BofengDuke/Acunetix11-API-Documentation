# Acunetix11-API-Documentation

* Acunetix11伪API,非官方API文档。官方API需要 Enterprise edition licenses才能获取到。
* 本文档是根据原文档作者[Acunetix11-API-Documentation](https://github.com/h4rdy/Acunetix11-API-Documentation#acunetix11-api-documentation) 这份文档进一步修改,增加了scan模块和vulnerablility模块中获取漏洞信息的api.

## 获取API-KEY
Administrator--Profile--API Key

## 环境设置:

### Header设置:

```
X-Auth: API-KEY
Content-type: application/json; charset=utf8
```

### 接口设置
1. 传参内容均为Json格式
2. 接口均为https

## 文档目录(Contents)

* 1 . [Dashboard接口](./Document/Dashboard.md)
* 2 . [Targets接口](./Document/Targets/main.md)
    
    * a). [General设置](./Document/Targets/scan.md)
    * b). [Crawl设置](./Document/Targets/scan.md)
    * c). [HTTP设置](./Document/Targets/scan.md)
    * d). [Advanced设置](./Document/Targets/scan.md)
* 3 . [Scans接口](./Document/Scans/main.md)
* 4 . [Vulnerabilities接口](./Document/Vulnerabilities/main.md)
* 5 . [Reports接口](./Document/Reports/main.md)
     

