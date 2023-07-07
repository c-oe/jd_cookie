# 说明

本项目使用Java语言翻译自 **scjtqs2** 使用Go语言的jd_cookie项目，项目地址：https://github.com/scjtqs2/jd_cookie

## v1.0 

**getSmsCode()** 先向jd发送获取验证码的请求，**checkSmsCode()** 使用验证码登录获取cookie

两个方法必须由同一个对象调用，否则向jd发送的数据不一致。

如果需要进行多次获取时，每次获取须创建一个 **SMSAction** 对象。
