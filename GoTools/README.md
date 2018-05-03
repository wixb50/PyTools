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

**dcmp**

基于etcd的配置管理系统 (etcd v2).

安装
```
$ curl -L https://github.com/wixb50/DevOpsTools/releases/download/dcmp/dcmp-linux-amd64.tar.gz -o dcmp-linux-amd64.tar.gz
```

配置
```
# 新建配置文件config/config.yml内容为

listen: "0.0.0.0:8000"  # 监听的IP，端口

base_path: "/config"    #etcd读取的根目录

endpoints:              # etcd 接入地址
   - "http://127.0.0.1:2379"

# etcd ssl 配置
#
# ca_file: "/path/to/ca.crt"
# cert_file: "/path/to/client.crt"
# key_file: "/path/to/client.key"
```

使用
```
$ dcmp
```
详细见 [说明文档](https://github.com/silenceper/dcmp).

**autossh**

go写的一个ssh远程客户端,可一键登录远程服务器

安装
```
$ curl -L https://github.com/islenbo/autossh/releases/download/v0.2/autossh-linux-amd64_v0.2.zip -o autossh-linux-amd64.zip
$ unzip autossh-linux-amd64.zip # 进入文件夹编辑servers.json
```

使用
```
$ ./autossh
```
详细见 [说明文档](https://github.com/wixb50/autossh).
