##说明

进入开发文件根目录，首先安装那些需要的 ruby 配置

```
$bundle install
```

然后开启 HTTP serve ，还好mac 自带 python 环境，你只需在更目录下运行

```
$ python -m SimpleHTTPServer 9999           (后面9999是我指定的端口，你也可以自己指定)
```

然后就是开启监听了

```
$ guard start
```

这样你每次修改了文件夹里面的文件，网页都会自动刷新。具体监听哪些文件你也可以去配置里自己手动修改。
