===========
PyTools
===========

Python 工具(脚本)集合.

SimpleHTTPServerWithUpload
===========================

安装 ::

    $ py_ver=`python -V 2>&1 | awk '{print $2}' | cut -d '.' -f1`
    $ curl https://raw.githubusercontent.com/wixb50/DevOpsTools/master/PyTools/SimpleHTTPServerWithUpload/SimpleHTTPServerWithUpload_${py_ver}.py -s -o SimpleHTTPServerWithUpload.py


使用 ::

    $ python SimpleHTTPServerWithUpload.py


Docker Registry Management
===========================

安装 ::

    $ sudo -i
    $ curl https://raw.githubusercontent.com/wixb50/drm/master/registry.py -s -o /usr/local/bin/drm && chmod 755 /usr/local/bin/drm


使用::

    $ drm --help

详细见 `说明文档 <https://github.com/wixb50/drm>`__.

youtube-dl
==============

安装 ::

    $ sudo curl -L https://yt-dl.org/downloads/latest/youtube-dl -o /usr/local/bin/youtube-dl
    $ sudo chmod a+rx /usr/local/bin/youtube-dl


使用 ::

    $ youtube-dl --help

详细见 `说明文档 <https://github.com/rg3/youtube-dl>`__.

pyflakes
=========

Python的语法检查工具.

安装 ::

    $ pip install pyflakes


使用 ::

    $ pyflakes 文件|文件夹

详细见 `说明文档 <https://pypi.org/project/pyflakes/>`__.

ghp-import
===========

快速将本地静态文件夹提交到github pages工具.

安装 ::

    $ pip install ghp-import


使用 ::

    $ ghp-import output
    $ git push origin gh-pages
    # 或者
    $ ghp-import -p -m "Update github pages" output

详细见 `说明文档 <https://github.com/davisp/ghp-import>`__.

honcho
=======

python实现的Foreman，进程服务管理工具.

安装 ::

    $ pip install honcho


使用 ::

    $ honcho start # 启动Procfile的所有服务
    $ honcho export # 支持将命令导出为其他服务格式runit、supervisord、systemd、upstart

详细见 `说明文档 <https://github.com/nickstenning/honcho>`__.
