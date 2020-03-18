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
1.implementation 'com.buyaomiege:requestinterceptor:1.0.1'  
2.addInterceptor(new RequestInterceptor(RequestInterceptor.Level.ALL))
### 日志打印不需要自己关闭，正式版自己关闭
