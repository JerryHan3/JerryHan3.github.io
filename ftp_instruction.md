---
permalink: /ftp/
title: FTP服务器使用说明
---
# FTP服务器使用说明

要连接到FTP服务器并获取里面的文件，可以通过系统自带的文件浏览器，或者专用的FTP连接软件Filezilla。其中后者支持更安全的FTPS协议，故推荐使用。

手机上可以使用ES文件浏览器等第三方文件管理应用。

### 方法一：使用Windows资源管理器

1. 双击“此电脑”，打开一个资源管理器的界面。
2. 点击顶部显示路径的地址栏。

![](https://jerryhan3.github.io/img/ftp/inst1.png)

3. 直接把FTP服务器地址输入地址栏，并按下回车。

![](https://jerryhan3.github.io/img/ftp/inst2.png)

4. 系统将弹出一个窗口，要求输入用户名和密码。将提供的用户名和密码输进去，再按一次回车。

![](https://jerryhan3.github.io/img/ftp/inst3.png)

5. 稍等片刻即可看到文件列表，这和你本地上的文件列表是一样的。

![](https://jerryhan3.github.io/img/ftp/inst4.png)

6. **不要直接在窗口中双击打开文件！** 把它复制到你本地的硬盘。这会触发下载，视网速快慢需要等待一段时间。

![](https://jerryhan3.github.io/img/ftp/inst5.png)

7. 现在你可以打开**在本地的**文件了。关闭FTP服务器的文件窗口，系统会自动中断连接。

## 方法二：使用Filezilla软件

1. 访问[Filezilla中文网客户端下载页](https://www.filezilla.cn/download/client)，下载Filezilla客户端并安装。

> 官方的网站服务器在外国，下载太慢了，不推荐。

2. 打开安装好的Filezilla，你会看到这样的页面。

![](https://jerryhan3.github.io/img/ftp/inst6.png)

3. 在顶部的文本框中依次填入服务器地址 **（不要输入冒号及后面的数字！那是端口）** 、用户名、密码。端口处留空，因为使用的都是默认端口。

![](https://jerryhan3.github.io/img/ftp/inst7.png)

4. 点击“快速连接”按钮。当右下侧窗口中出现了文件列表，说明连接成功。

![](https://jerryhan3.github.io/img/ftp/inst8.png)

5. 左下侧窗口是你的本地硬盘。使用拖拽操作把服务器上的文件下载到本地硬盘上。

![](https://jerryhan3.github.io/img/ftp/inst9.png)

6. 下载完毕后关闭窗口，软件会自动断开连接。

7. 下次连接可点击“快速连接”按钮旁边的小三角，选中服务器地址快速连接。

![](https://jerryhan3.github.io/img/ftp/inst10.png)

注：为了数据传输更安全，使用本方法连接时可在地址开头的“ftp”后面加一个字母s。这样会使用更安全的协议进行连接。![](https://jerryhan3.github.io/img/ftp/inst11.png)


## 方法三：在手机上使用ES文件浏览器连接

1. 下载安装软件并打开。
2. 依次点击左上角三横杠→网络→FTP。

![](https://jerryhan3.github.io/img/ftp/inst12.png)

3. 点击右上角的“新建”按钮。

![](https://jerryhan3.github.io/img/ftp/inst13.png)

4. 选择“ftp”或“ftps”。

![](https://jerryhan3.github.io/img/ftp/inst14.png)

5. 在“服务器”一栏中粘贴服务器地址，然后删掉末尾的冒号及后面的数字。
6. 在相应位置输入用户名和密码，其他位置保持默认，按“确定”。

![](https://jerryhan3.github.io/img/ftp/inst15.png)

7. 界面里会多一个文件夹图标，打开后即可浏览服务器的文件。日后再次访问服务器，找到这个文件夹并打开即可。

注：不同软件的操作方法有所不同，具体请查阅软件的使用文档或自行百度。