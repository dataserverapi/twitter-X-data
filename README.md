
# twitter(x)_data_servers
# 推特大数据推送
twitter数据采集推特数据采集
twitter数据服务,可提供日数据2亿推送 ,解决风控限制，次数限制，账号管理问题,
tiktok  主页 评论采集
#### 服务地址 联系 飞机 https://t.me/fofo123dd  
##### 一、  twitter搜索 列表 （可采全）

* Post:/twitter_api/search

| 名称  | 类型   | 含义                                   |
| ----- | ------ | -------------------------------------- |
| q   | String | 搜索内容,eg:lang:zh,北京         |

| token | String | 用户标识                               |
* 返回：

```json
```

##### 二、twitter用户列表（可采全）

* Post:/twitter_api/user_timeline

| 名称  | 类型   | 含义                                   |
| ----- | ------ | -------------------------------------- |
| id   | String | 用户标识,eg:1454736746621521928         |
| max_id  | String    | 从0起 ，获取最小id |
| token | String | 用户标识                               |
* 返回：
