# hsc

#### 概要

HTTPのステータスコードとLinuxのエラーナンバーの概要部分のみを出力するスクリプト

(manを読めって話ではあるがそれすらめんどくさい横着者なのでサクッと見てる。。。)

##### 必要

* bash (連想配列を使用してるため4.3以降くらい)

##### イメージ

```
Linux errno
==================
 30 : Read-only file system
 22 : Invalid argument
114 : Operation already in progress
```

```
HTTP Response Code
==================
200 : OK
404 : Not Found
503 : Service Unavailable
```
