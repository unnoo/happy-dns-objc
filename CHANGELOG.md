#Changelog
## 1.0.0 (2021-09-02)

* 新增 dns udp 解析 api
* 新增 doh 解析 api
* 调整 QNRecord api
* 调整 DnsManager Api，支持返回 IPv6
* 删除 QNDnspodFree init api

## 0.3.17 (2020-07-03)

### 修改
* qiniu  record增加source, dns manager增加query error handler

## 0.3.16 (2020-05-07)

### 修改
* qiniu  http dns 增加额外query接口

## 0.3.15 (2019-02-12)

### 修改
* qiniu  http dns 去掉

## 0.3.14 (2018-05-04)

### 增加
* qiniu  http dns 更新

## 0.3.13 (2018-04-03)

### 增加
* qiniu  http dns 支持

## 0.3.12 (2017-08-31)

### 修正
* 去掉一处无用的copy

## 0.3.11 (2017-08-31)

### 修正
* 偶发崩溃问题
* 一处注释错误

## 0.3.10 (2016-07-30)

### 增加
* ip status 上报
* 根据时区判断是否该启用httpdns

### 0.3.9 (2016-07-19)
＊ upversion for cocoapods

## 0.3.8 (2016-07-19)

### 增加
* getaddrinfo 支持

## 0.3.7 (2016-07-11)

### 增加
* 超时设置

## 0.3.6 (2016-07-05)

### 修复
* ip 轮换不采用随机策略，每次轮换位置确定
* 实现LruCache, 避免切到后台时丢失解析
* typo QNResover initAddres -> initAddress

## 0.3.5 (2016-05-31)

### 修复
* pod spec lint warning

## 0.3.4 (2016-05-31)

### 修复
* ipv6 判断网络变化的本地ip字符串缓存长度小于最长ipv6长度

## 0.3.2 (2016-05-26)

### 修复
* ipv6 ios8 doesnt work.

## 0.3.1 (2016-05-26)

### 修复
* ipv6 reslover bug

## 0.3.0 (2016-05-26)

### 增加
* ipv6 全面支持

## 0.2.4 (2016-05-10)

### 增加
* 使用txt resolve 防劫持
* ipv6 支持
* 代码格式化
* url query

## 0.2.3 (2015-10-30)

### 修正
* http dns 返回 typeA

## 0.2.2 (2015-10-12)

### 修正
* res_state 没有释放造成的内存泄漏

## 0.2.1 (2015-08-03)

### 修正
* 外部排序接口为空时，没有返回值

## 0.2.0 (2015-08-01)

### 增加
* Dnspod 企业版支持
* 外部排序接口

## 0.1.1 (2015-07-16)

### 增加
* localdns 劫持检测

## 0.1.0 (2015-07-15)

### 增加
* 利用本地IP检查网络变化

## 0.0.1 (2015-06-21)

### 增加
* localdns
* httpdns


