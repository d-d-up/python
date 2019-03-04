# javascript介绍
### JavaScript入门易学性
* JavaScript对初学者比较友好。
* JavaScript是有界面效果的（比如C语言却只有白底黑字）。
* JavaScript是弱变量类型的语言，变量只需要用var来声明。例：var a；
### JavaScript是前台语言
* JavaScript是前台语言，而不是后台语言。

* JavaScript运行在用户的终端网页上，而不是服务器上，所以我们称为“前台语言”。就是服务于页面的交互效果、美化，不能操作数据库。

* 后台语言是运行在服务器上的，比如PHP、ASP、JSP等等，这些语言都能够操作数据库，都能够对数据库进行“增删改查”操作。Node.js除外。
### JavaScript的组成
JavaScript基础分为三个部分：

* ECMAScript：JavaScript的语法标准。包括变量、表达式、运算符、函数、if语句、for语句等。

* DOM：文档对象模型，操作__网页上的元素的API__。比如让盒子移动、变色、轮播图等。

* BOM：浏览器对象模型，操作__浏览器部分功能的API__。比如让浏览器自动滚动。

PS：JS机械重复性的劳动几乎为0，基本都是创造性的劳动。而不像HTML、CSS中margin、padding都是机械重复劳动。

### JavaScript的特点
* （1）简单易用：可以使用任何文本编辑工具编写，只需要浏览器就可以执行程序。

* （2）解释型语言：事先不需要被编译为机器码再执行，逐行执行、无需进行严格的变量声明。

由于少了编译这一步骤，所以解释型语言开发起来尤为轻松，但是解释型语言运行较慢也是它的劣势。不过解释型语言中使用了JIT技术，使得运行速度得以改善。

* （3）基于对象：内置大量现成对象，编写少量程序可以完成目标
开始写第一行JavaScript代码
### JavaScript代码的书写位置
* （1）内嵌的方式：

页面中，我们可以在<body>标签里放入<script type=”text/javascript”></script>标签对儿，并在<script>里书写JavaScript程序：

		<script type="text/javascript">

		</script>
text表示纯文本，因为JavaScript也是一个纯文本的语言。

PS：在Sublime Text里，输入<sc后，按tab键，可以自动补齐。

* （2）外链式：引入外部JavaScript文件（放到body标签里，可以和内嵌的js代码并列）

	<script src="tool.js"></script>
  #### alert语句
我们要学习的第一个语句，就是alert语句。弹窗。如果写了两个alert()语句的话，网页的效果是：弹出第一个警告框，点击确定后，继续弹出第二个警告框

		<script type="text/javascript">
			alert("生命壹号");
		</script>
 #### 语法规则
 *学习程序，是有规律可循的，就是程序是有相同的部分，这些部分就是一种规定，不能更改，我们成为：语法。*

（1）JavaScript对换行、缩进、空格不敏感。每一条语句以分号结尾。
 
 （2）所有的符号，都是英语的。比如括号、引号、分号。

（3）严格区分大小写
### 注释
（1）html的注释：

<!-- 我是注释  -->
（2）CSS的注释：

	/*
		我是注释
	*/

注意：CSS只有/* */这种注释，没有//这种注释。而且注释要写在<style>标签里面才算生效哦。

（3）JavaScript的注释：

单行注释：

// 我是注释
多行注释：

/*
	多行注释1
	多行注释2
*/
备注：sublime中，单行注释的快捷键是ctrl+/，多行注释的快捷键是ctrl+shift+/。

### Javascript 网页中输出信息的写法
* 弹出警告框：alert("")

* 控制台输出：console.log("")
console.log("")表示在控制台中输出。console表示“控制台”，log表示“输出”。

控制台在Chrome浏览器的F12中。控制台是工程师、程序员调试程序的地方。程序员经常使用这条语句输出一些东西，来测试程序是否正确。

### 用户输入：
#### prompt()语句
prompt()就是专门用来弹出能够让用户输入的对话框。用得少，测试的时候可能会用。

JS代码如下：

			var a = prompt("请随便输入点什么东西吧");
			console.log(a);
上方代码中，用户输入的内容，将被传递到变量 a 里面。
prompt()语句中，用户不管输入什么内容，都是字符串。

alert和prompt的区别：

	alert("从前有座山");                //直接使用，不需要变量
	var a = prompt("请输入一个数字");   // 必须用一个变量，来接收用户输入的值




  
