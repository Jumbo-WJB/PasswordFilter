
//
我是如何获取全域用户明文密码的？
http://www.freebuf.com/articles/system/129412.html



## PasswordFilter Example

## 编译

打开 VS 64 位编译环境，执行

```
build.cmd
```

## 安装

1. 复制到 `%system32%` 目录
2. 修改 LSA Notification Package，添加 `SecureFilter` 字样

