安装 —— PHPCMS V9 安装说明


本教程讲解的全新安装PHPCMS V9的方法（以虚拟空间上安装 PHPCMS V9为例演示）。
一、下载适合自己 PHPCMS V9 版本到本地或服务器

下载地址：[phpcms_v9.6.0_UTF8](http://www.phpcms.cn/html/download/)

说明：官方提供了 2 种不同的编码。包括 GBK 简体中文版(推荐)、UTF-8 简体中文版。如果您的站点主要是国内会员，推荐您使用 GBK 版本。
二、解压并上传 PHPCMS V9程序到服务器且修改相应目录权限
1、上传 PHPCMS V9程序到服务器上
![](http://v9.help.phpcms.cn/html/install/static/1.png)
install_package 这个目录下面的所有文件是我们需要上传到服务器上的可用程序文件；
readme 目录为产品相关说明、帮助文档等；
将其中 install_package 目录下的所有文件使用 FTP 软件以二进制方式上传到空间（以下截图中使用的 FTP 软件为 FileZilla），如下图所示：
![](http://v9.help.phpcms.cn/html/install/static/2.png)
2、设置相关目录的文件属性，以便数据文件可以被程序正确读写

使用 FTP 软件登录您的服务器，将服务器上以下目录、以及该目录下面的所有文件的属性设置为 777，Win 主机请设置 internet 来宾帐户可读写属性。

./ 根目录
./caches
./html
./index.html
./uploadfile
./phpsso_server/caches
./phpsso_server/uploadfile
![](http://v9.help.phpcms.cn/html/install/static/3.png)
![](http://v9.help.phpcms.cn/html/install/static/4.png)
三、安装过程

上传完毕后，开始在浏览器中安装PHPCMS V9，用你的网站域名+'/install '(例如：“http://www.abc.com/install”)，进入准备安装界面：
![](http://v9.help.phpcms.cn/html/install/static/5.png)
阅读授权协议后点击“开始安装”，系统会自动检查环境，如下图所示：
![](http://v9.help.phpcms.cn/html/install/static/6.png)
点击“下一步”，即进入模块安装以及设置 PHPSSO界面，如下图所示
![](http://v9.help.phpcms.cn/html/install/static/7.png)
检测成功，点击“下一步”，即进入目录权限检测界面，如下图所示
![](http://v9.help.phpcms.cn/html/install/static/8.png)
检测成功，点击“下一步”，进入数据库信息配置界面
![](http://v9.help.phpcms.cn/html/install/static/9.png)
点击“下一步”，开始安装
![](http://v9.help.phpcms.cn/html/install/static/10.png)
安装完成
![](http://v9.help.phpcms.cn/html/install/static/11.png)
![](http://v9.help.phpcms.cn/html/install/static/12.png)
