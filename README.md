# 推荐！免费的 IP 归属地查询接口 API - IP9.COM.CN

#### 接口地址 GET
<!-- You can get started using VitePress right away using `npx`! -->

```URL
https://ip9.com.cn/get?ip=58.30.0.0
```

#### 返回结果示例 JSON

```JSON
{
  "ret": 200,               // 200为正常
  "data": {
    "country": "中国",      // 国家/地区
    "country_code": "cn",   // 国家/地区简码
    "prov": "北京",         // 省份
    "city": "北京",         // 城市
    "city_code": "beijing", // 城市简码
    "city_short_code": "bj", // 城市简码
    "area": "东城",         // 区县
    "post_code": "100000", //邮政编码
    "area_code": "010",    // 电话区号
    "isp": "中国移动", // 运营商
    "lng": "116.41005",    // 城市中心-经度
    "lat": "39.93157",     // 城市中心-纬度
    "long_ip": 975044608,  // longip
    "big_area": "华北"      // 国内大区划分
  },
  "qt": 0.001              // 查询时间-秒
}
```

#### 对接示例代码
各流行编程语言 [[对接示例代码](https://ip9-api.apifox.cn/api-225457832)]，包含 Java、Swift、Go、PHP、Python、C/C#、Rust、Javascript、ObjectC 等。

#### 免费使用限制
为了防止滥用，保障服务正常运行，每个IP的访问频率为 60次/分钟。 

#### 技术支持解答
QQ群 34706620

#### 企业私有化部署
毫秒响应，更稳定，不限QPS。Email: hezuo@fushutech.com

### Powered By Rainyun
大宽带高防云服务器 [[前往查看](https://www.rainyun.com/NTEwMTQ5_?s=home)]
