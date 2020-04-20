<p align="center">
    <a href="https://bintray.com/beta/#/buyaomiege/RequestInterceptor/RequestInterceptor">
    <img src="https://img.shields.io/badge/Jcenter-v1.0.2-brightgreen.svg?style=flat-square" alt="Latest Stable Version">
</a>
</p>

# Interceptor
okhttp日志拦截格式化打印  
来源MVPArms  https://github.com/JessYanCoding/MVPArms  
Logtag:  
zfy-Req 看请求地址  
zfy-Res 看返回数据  
zfy-Re  请求地址和返回数据  
## 效果
![Image text](./art/效果.png)
## 使用
1.implementation 'com.buyaomiege:requestinterceptor:1.0.2'  
2.addInterceptor(new RequestInterceptor(RequestInterceptor.Level.ALL))

### 如果okttp冲突
```
implementation ('com.buyaomiege:requestinterceptor:1.0.2'){  
    exclude module: "okhttp"  
}
```