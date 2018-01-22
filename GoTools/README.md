# GoTools
Golang 工具集合.

**pet**

Simple command-line snippet manager, written in Go.

安装
```
$ curl -L https://github.com/wixb50/pet/releases/download/v1.0.0/pet-linux-amd64.tar.gz -o pet-linux-amd64.tar.gz
```

使用
```
$ pet --help
```
详细见 [说明文档](https://github.com/wixb50/pet).

**ctop**

Top-like interface for container metrics.

安装
```
$ sudo curl -L https://github.com/bcicen/ctop/releases/download/v0.6.1/ctop-0.6.1-linux-amd64 -o /usr/local/bin/ctop
$ sudo chmod +x /usr/local/bin/ctop
```

使用
```
$ ctop
```
详细见 [说明文档](https://github.com/bcicen/ctop).

**brook**

Brook is a cross-platform(Linux/MacOS/Windows/Android/iOS) proxy software.

安装
```
$ sudo curl -L https://github.com/txthinking/brook/releases/download/v20171113/brook -o /usr/local/bin/brook
$ sudo chmod +x /usr/local/bin/brook
```

使用
```
$ brook --help
```
详细见 [说明文档](https://github.com/txthinking/brook).

**gorelease.sh**

A helper script for releasing golang project.

安装
```
$ sudo curl -L https://raw.githubusercontent.com/wixb50/DevOpsTools/master/GoTools/gorelease/gorelease.sh -o /usr/local/bin/gorelease.sh
$ sudo chmod +x /usr/local/bin/gorelease.sh
```

使用
```
# 进入golang项目目录，执行
$ gorelease.sh [name] # name选填
```
打包文件存放在out目录下.
