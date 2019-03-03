1.print：

python2 >>> print("hello", "world")   结果为：('hello', 'world') 
python3 >>> print("hello", "world")   结果为：hello world

2.输入函数：

python2有两个输入函数：input和raw_input。
input函数返回的数据类型是根据本身自动推导的类型，raw_input返回的数据类型一定是字符串类型。
python3只有一个输入函数：input。
input函数返回的类型一定是字符串类型。

3.数据库模块：

python2:mysqldb
python3:pymysql

4.编码：

python2默认编码是ascii编码，
python3默认使用UTF-8

5.字符串：

python2字符串有两个类型：unicode：文本字符串  str：字节序列。
python3：str：字符串    byte：字节序列

6.迭代器：

python2中很多返回列表对象的内置函数和方法在python3中都改成了返回类似迭代器的对象。
python2中的range和xrange函数合并成了range。
python2中的迭代器必须实现next方法，python3改成了__next__（）。

7.nolocal：

python2中无法在嵌套函数中声明非局部变量。
python3中nolocal可以。
