# PyTools
Python 工具(脚本)集合.

**SimpleHTTPServerWithUpload**

安装
```
$ py_ver=`python -V 2>&1 | awk '{print $2}' | cut -d '.' -f1`
$ curl https://raw.githubusercontent.com/wixb50/PyTools/master/SimpleHTTPServerWithUpload/SimpleHTTPServerWithUpload_${py_ver}.py -s -o SimpleHTTPServerWithUpload.py
```

使用
```
$ python SimpleHTTPServerWithUpload.py
```

**Docker Registry Management**

安装
```
$ sudo -i
$ curl https://raw.githubusercontent.com/wixb50/drm/master/registry.py -s -o /usr/local/bin/drm && chmod 755 /usr/local/bin/drm
```

使用
```
$ drm --help
```
详细见 [说明文档](https://github.com/wixb50/drm).

**youtube-dl**

安装
```
$ sudo curl -L https://yt-dl.org/downloads/latest/youtube-dl -o /usr/local/bin/youtube-dl
$ sudo chmod a+rx /usr/local/bin/youtube-dl
```

使用
```
$ youtube-dl --help
```
详细见 [说明文档](https://github.com/rg3/youtube-dl).
