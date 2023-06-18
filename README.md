# 说明

本项目使用Java语言翻译自大佬 **scjtqs2** 使用Go语言的jd_cookie项目，项目地址：https://github.com/scjtqs2/jd_cookie

## v1.0 

> **getSmsCode()** 先向jd发送获取验证码的请求，**checkSmsCode()** 使用验证码登录获取cookie
> 两个方法必须由同一个对象调用，否则获取不了jd返回的参数
