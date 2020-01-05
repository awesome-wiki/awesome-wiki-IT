# Mac 相关

## 查看端口占用

```
sudo lsof -nP -iTCP:端口号 -sTCP:LISTEN
```

-n 表示不显示主机名
-P 表示不显示端口俗称

不加 sudo 只能查看以当前用户运行的程序

参考：
- [使用 lsof 代替 Mac OS X 中的 netstat 查看占用端口的程序](https://tonydeng.github.io/2016/07/07/use-lsof-to-replace-netstat/)
- []()