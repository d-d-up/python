python常用的类库：

1.python自带的类库：
OS：常用系统交互
shutil：常用文件和目录操作
glob：使用通配符从目录中获取文件列表
sys：参数处理（for Windows）
getopt：参数处理（for Unix）
optparse：强大的命令行处理库
sys.stderr：重定向错误输出和程序终止
re：正则
zlib：压缩解压各种数据
gzip：压缩解压gzip格式的数据
pprint：格式化输出
textwrap：换行输出文本
locale：从本地格式化输出

2.python外部的类库
Tkinter———— Python默认的图形界面接口。Tkinter是一个和Tk接口的Python模块，Tkinter库提供了对 Tk API的接口，它属于Tcl/Tk的GUI工具组。

Python Imaging Library(PIL)————python提供强大的图形处理的能力，并提供广泛的图形文件格式支持，该库能进行图形格式的转换、打印和显示。
还能进行一些图形效果的处理，如图形的放大、缩小和旋转等。是Python用户进行图象处理的强有力工具。

Pmw(Python megawidgets)Python超级GUI组件集————一个在python中利用Tkinter模块构建的高级GUI组件，每个Pmw都合并了一个或多个Tkinter组件，

PyXML———— 用Python解析和处理XML文档的工具包，包中的4DOM是完全相容于W3C DOM规范的。它包含以下内容：
　　xmlproc: 一个符合规范的XML解析器。
　　Expat: 一个快速的，非验证的XML解析器。 还有其他
　　和他同级别的还有 PyHtml PySGML
  
PyGame———— 用于多媒体开发和游戏软件开发的模块。

PyOpenGL———— 模块封装了“OpenGL应用程序编程接口”，通过该模块python程序员可在程序中集成2D和3D的图形。

NumPy、NumArray和SAGE———— NumArray是Python的一个扩展库，主要用于处理任意维数的固定类型数组，

MySQLdb模块———— 用于连接MySQL数据库。还有用于zope的ZMySQLDA模块，通过它就可在zope中连接mysql数据库。

PyGTK ———— 用于python GUI程序开发的GTK+库。

PyQt ———— 用于python的Qt开发库。QT就是实现了KDE环境的那个库，由一系列的模块组成，有qt, qtcanvas, qtgl, qtnetwork, qtsql, qttable, qtui and qtxml，包含有300个类和超过5750个的函数和方法。PyQt还支持一个叫qtext的模块，它包含一个QScintilla库。该库是 Scintillar编辑器类的Qt接口。
　　PyMedia ———— 用于多媒体操作的python模块。它提供了丰富而简单的接口用于多媒体处理(wav, mp3, ogg, avi, divx, dvd, cdda etc)。可在Windows和Linux平台下使用。
　　Psyco ———— 一个Python代码加速度器，可使Python代码的执行速度提高到与编译语言一样的水平。
Python-ldap ———— 提供一组面向对象的API，可方便地在python中访问ldap目录服务，它基于OpenLDAP2.x。

smtplib模块 ———— 发送电子邮件。

　　ftplib模块 ———— 定义了FTP类和一些方法，用以进行客户端的ftp编程。我们可用python编写一个自己的ftp客户端程序，用于下载文件或镜像站点。如果想了解ftp协议的详细内容，请参考RFC959。
  
　　xmpppy模块 ———— Jabber服务器采用开发的XMPP协议，Google Talk也是采用XMPP协议的IM系统。在Python中有一个xmpppy模块支持该协议。也就是说，我们可以通过该模块与Jabber服务器通信，是不是很Cool。
　　
  下面这些就不详细介绍，只列出名字和功能
  
　　adodb ———— ADO数据库连接组件
  
　　bsddb3 ———— BerkeleyDB的连接组件
  
　　chardet ———— 编码检测
  
　　Cheetah ———— 构建和扩充任何种类的基于文本的内容
  
　　cherrypy ———— 一个WEB framework
  
　　ctypes ———— 用来调用动态链接库
  
　　Cx-oracle ———— 连接oracle的工具
  
　　DBUtils ———— 数据库连接池
  
django ———— 一个WEB framework

　　DPKT ———— raw-scoket网络编程
  
　　docutils ———— 用来写文档的
  
　　dpkt ———— 数据包的解包和组包
  
　　feedparser ———— rss解析
  
　　Kodos ———— 正则表达式调试工具
  
　　Mechanize ———— 爬虫连接网站常用
  
　　pefile ———— windows pe文件解析器
  
　　py2exe ———— 用来生成windows可执行文件
  
　　pycurl ———— URL处理工具
  
　　pydot ———— 画图的，graphiz
  
　　pyevent ———— Python的事件支持
  
pylint ———— 培养良好的编码习惯

　　Pylons ———— 又一个web framework
  
　　pypcap ———— 抓包的
  
　　pysqlite2 ———— SQLite的连接组件
  
　　python-dnet ———— 控制网络安全的其他设备
  
　　pythonwin ———— Python的Windows扩展
  
　　pywmi ———— 省了好多折腾功夫
  
　　reportlab ———— Python操作PDF的Libary。
  
scapy ———— 网络包构建分析框架,可编程的wireshark,有兴趣的google “Silver Needle in the Skype”

   scons ———— 项目构建工具，写好了模板用起来还是很方便的
   
　　sendpkt ———— Python发包
  
setuptools ———— 一套python包管理机制

　　simplejson ———— JSON的支持
  
sqlalchemy ———— SQL数据库连接池

SQLObject ———— 数据库连接池

twisted ———— 巨无霸的网络编程框架

　　winpdb ———— 自己的程序或者用别的库不太明白的时候就靠它了
  
　　wxPython ———— GUI编程框架,熟悉MFC的人会非常喜欢，简直是同一架构
