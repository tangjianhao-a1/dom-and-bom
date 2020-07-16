# 1.编程语言  
## 1-1.编程  
编程：就是让计算机为解决某个问题而使用某种程序设计语言编写程序代码，并最终得到结果的过程。  
计算机程序：就是计算机所执行的一系列的指令集合，而程序全部都是用我们所掌握的语言来编写的，所以人们要控制计算机一定要通过计算机语言向计算机发出命令。  
## 1-2.计算机语言  
计算机语言指用于人与计算机之间通讯的语言，它是人与计算机之间传递信息的媒介。  
计算机语言的种类非常的多，总的来说可以分成机器语言，汇编语言和高级语言三大类。  
实际上计算级最终所执行的都是机器语言，它是由“0”和“1”组成的二进制数，二进制是计算机语言的基础。    
## 1-3.编程语言  
可以通过类似人类的“语言”来控制计算机，让计算机为我们做事情，这样的语言就叫做编程语言（ProgrammingLanguage）。  
编程语言是用来控制计算机的一系列指令，他有固定的格式和词汇（不同编程语言的格式和词汇不一样），必须遵守。  
如今通用的编程语言有两种形式：汇编语言和高级语言。   

- 汇编语言 和机器语言实质是相同的，都是对硬件操作，只不过指令采用了英文缩写的标识符，容易识别和记忆。  
- 高级语言主要是相对于低级语言而言，它并不是特指某一种具体的语言，而是包括了很多编程语言，常用的有C语言·c++，java，c#，python，php，JavaScript，Go语言，Objective-C，Swift等。  
## 1-4.翻译器   
高级语言所编制的程序不能直接被计算机识别，必须经过转换才能被识别，为此，我们需要一个翻译器。  
翻译器可以将我们所编写的源代码转换为机器语言，这也被称为二进制。记住1和0.  
## 1-5 编程语言和标记语言区别  
- 编程语言有很强的逻辑和行为能力，在编程语言里，会看到很多if else，for，while等具有逻辑性和行为能力的指令，这是主动的。  
- 标记语言不用向计算机发出指令，常用于格式化和链接。标记语言的存在是用来被读取的，他是被动的。   
### 总结：  
1.计算机可以帮助人类解决某些问题  
2.程序员利用编程语言编写程序发出指令控制计算机来实现这些任务  
3.编程语言有机器语言，汇编语言，高级语言  
4.高级语言需要一个翻译器转换为计算机识别的机器语言  
5.编程语言是主动的有很强的逻辑性   
# 2.计算机基础    
## 2-1计算机组成  
a：硬件：   
输入设备：鼠标，键盘，手写板，摄像头等  
输出设备：显示器，打印机，投影仪等，  
CPU：负责处理数据与运算  
硬盘：负责存储数据，硬盘永久存储数据  
内存：暂时存储数据    
b：软件：   
系统软件：Windows，Linus，macOS
应用软件：浏览器，QQ，VSCode，Sublime，Word   
## 2-2.数据存储  
1.计算机内部使用二进制0和1来表示数据。  
2.所有数据，包含文件，图片等最终都是以二进制数据（0和1）的形式存放在硬盘中的。
3.所有程序，包括操作系统，本质都是各种数据，也以二进制数据的形式存放在硬盘中，平时我们所说的安装软件，其实就是把程序文件复制到硬盘中。  
4.硬盘，内存都是保存的二进制数据。   
## 2.3 数据存储单位  
bit<byte<kb<GB<TB.....  
- 位（bit):1bit可以保存一个0或者1（最小的存储单位）  
- 字节（Byte）：1B=8b  
- 千字节（KB):1KB=1024B  
- 兆字节（MB）：1MB=1024KB
- 吉字节（GB）：1GB=1024MB  
- 太字节（TB）：1TB=1024GB  
- ....   
## 2-4.程序运行  
硬盘》内存条》CUP  
1. 打开某个程序时，先从硬盘中把程序的代码加载到内存中  
2.CPU执行内存中的代码  
注意：之所以要内存的一个重要原因，是因为CPU运行太快了，如果只从硬盘中读取数据，会浪费CPU性能，所以，才使用存取速度更快的内存来保存运行时的数据。（内存是电，硬盘是机械）  
# 1.初识JavaScript   
## 1-1 JavaScript历史  
- 布兰登·艾奇，1961年出生  
- 在1995年利用10天完成JavaScript设计。  
- 网景公司最初命名为LiveScript，后来在与Sun合作之后将其改名为JavaScript。  
## 1-2.JavaScript是什么  
- JavaScript是世界上最流行的语言之一，是一种运行在客户端的脚本语言（Script 是脚本的意思）  
- 脚本语言：不需要编译，运行过程中由js解释器（js引擎）逐行来进行解释并执行  
- 现在也可以基于Node.js技术进行服务器端编程  
## 1-3.JavaScript的作用  
- 表单动态效验（密码强度检测）（JS产生最初的目的）  
- 网页特效  
- 服务端开发（Node。js）  
- 桌面程序（Electron）  
- APP（Cordova）  
- 控制硬件-物联网（Ruff）  
- 游戏开发（cocos2d-js）   
## 1.4 HTML/CSS/JS的关系  
HTML/CSS标记语言--描述类语言  
- HTML决定网页结构和内容（决定看到什么），相当于人的身体  
- CSS决定网页呈现给用户的模样（决定好不好看），相当于给人穿衣服，化妆  

JS脚本语言--编程类语言  
- 实现业务逻辑和页面控制（决定功能），相当于人的各种动作  

## 浏览器执行JS简介  
浏览器分成两部分，渲染引擎和JS引擎  
- 渲染引擎：来解析HTML与CSS，俗称内核，比如chrome浏览器的blink，老版本的webkit  
- JS引擎：也称为JS解释器。用来读取网页中的JavaScript代码，对其处理后运行，比如chrome 浏览器的v8  
浏览器本身并不会执行JS代码，而是通过内置JavaScript引擎（解释器）来执行JS代码。JS引擎执行代码时逐行解释每一句源码（转换为机器语言）。然后由计算机去执行，所以JavaScript语言归为脚本语言，会逐行解释执行。  
## 1-5。JS的组成  
JavaScript：  
1.ECMAScript（JavaScript语法）   
2.DOM（页面文档对象模型）  
3.BOM(浏览器对象模型)  
### 1.ECMAScript  
ECMAScript是由ECMA国际（原欧洲计算机制作商协会）进行标准化的一门编程语言，这种语言在万维网上应用广泛，它往往被称为JavaScript或JScript，但实际上后两者是ECMAScript语言的实现和扩展。  
ECMAScript：ECMAScript规定了JS的编程语法和基础核心知识，是所有浏览器厂商共同遵守的一套JS语法工业标准。  
### 2.DOM-文档对象模型  
文档对象模型（Document Object Model，简称DOM),是W3C组织推荐的处理可扩展标记语言的标准编程接口。通过DOM提供的接口可以对页面上的各种元素进行操作（大小，位置，颜色等）。  
### 3.BOM-浏览器对象模型   
BOM（Browser ObjectModel，简称BOM）是指浏览器对象模型，它提供了独立于内容的，可以与浏览器窗口进行互动的对象结构。通过BOM可以操作浏览器窗口，比如弹出框，控制浏览器跳转，获取分辨率等。 
# 1.JS初体验 
## .JS初体验  
JS有三种书写位置，分别为行内，内嵌和外部。  
### 1.行内式JS    
《input type="button" value="点我试试" onclick="alert('hello world')"/>   
- 可以将单行或少量JS代码写在HTML标签的事件属性中（以on开头的属性），如：onclick  
- 注意单双引号的使用：在HTML中我们推荐使用双引号，JS中我们推荐使用单引号  
- 可读性差，在html中编写JS大量代码时，不方便阅读；   
- 引号易错，引号多层嵌套匹配时，非常容易弄混；  
- 特殊情况下使用  
### 2.内嵌JS  
《script》   
alert（'Hello world');  
《/script》  
- 可以将多行JS代码写到《script》标签中  
- 内嵌JS是学习时常用的方式   
### 3.外部JS文件   
《script scr="my.js">《/script》   
- 利于HTML页面代码结构化，把大段JS代码独立到HTML页面之外，既美观，也方便文件级别的复用  
- 引用外部JS文件的script标签中间不可以写代码  
- 适用于JS代码量比较大的情况    
# 2.JS注释   
单行注释：ctrl+/   
多行注释：默认快捷键 shift+alt+a   
# 3.JavaScript输入输出语句   
为了方便信息的输入输出，JS中提供了一些输入输出语句，其常用的语句如下：   
方法|说明|归属  
-|-|-   
alert（msg）|浏览器弹出警示框|浏览器  
console.log（msg）|浏览器控制台打印输出信息|浏览器  （程序员测试用的）
prompt（info）|浏览器弹出输入框，用户可以输入|浏览器     
# 变量    
## 1-1变量概述：   
1. 什么是变量   
白话：变量就是一个装东西的盒子。  
通俗：变量是用于存放数据的容器。我们通过变量名获取数据。甚至数据可以修改。  
2. 变量在内存中的存储   
本质：变量是程序在内存中申请的一块用来存放数据的空间。  
类似我们酒店的房间，一个房间就可以看做是一个变量。  
## 1-2.变量的使用    
变量在使用时分为两步：1.声明变量，  2.赋值   
### 1.声明变量   
//声明变量  
var age；//声明一个名称为age的变量  
- var是一个JS关键字，用来声明变量（variable变量的意思）。使用该关键字声明变量后，计算机会自动为变量分配内存空间，不需要程序员管   
- age是程序员定义的变量名，我们要通过变量名来访问内存中分配的空间  
### 2.赋值   
age=10；//给age这个变量赋值为10  
- =用来把右边的值赋给左边的变量空间中，此处代表赋值的意思   
- 变量值是程序员保存到变量空间里的值   
## 1-3.变量的初始化  
var age=18； //声明变量同时赋值为18   
声明一个变量并赋值，我们称之为变量的初始化。  
## 1-4.变量语法扩展     
### 1.更新变量  
一个变量被重新赋值后，它原有的值就会被覆盖，变量值将以最后一次赋的值为准。  
### 2.同时声明多个变量   
同时声明多个变量时，只需要写一个var，多个变量名之间使用英文逗号隔开。  
vra  age = 10， name ='zs',  sex=2;   
### 3.声明变量特殊情况  
情况|说明|结果   
-|-|-
var age；console.（age）；|只声明 不赋值|undefined  
console.log(age)|不声明 不赋值 直接使用|报错  
age=10；console.log（age）；|不声明 只赋值|10  
## 1-5变量命名规范  
- 由字母（A-Za-z）.数字（0-9）.下划线（_).美元符号（$)组成，如usrAge，num01， _name  
- 严格区分大小写。var app；和var App；是两个变量  
- 不能以数字开头。18age 是错误的  
- 不能是关键字，保留字。列如：var，for，while  
- 变量名必须有意义，MMD BBD  nl-age  
- 遵守驼峰命名法，首字母小写，后面单词的首字母需要大写。myFirstName    

以下哪些是合法的变量名？   
第一组|第二组|第三组  
-|-|-  
var a 正确|var userName 正确|var theWorld   
var 1 错误|var $name 正确|var zhe world 错误   
var age18 正确|var_sex 正确|var zhe_world正确  
var 18age 错误| var &sex错误|var for错误    
## 1-6 小结  
- 为什么需要变量？  

因为我们一些数据需要保存，所以需要变量  
- 变量是什么？

变量就是一个容器，用来存放数据的，方便我们使用里面的数据   
- 变量的本质是什么？   

变量是内存里的一块空间，用来存储数据。    

- 变量怎么使用的？    

我们使用变量的时候，一定要先声明变量，然后赋值，声明变量本质是区内存申请空间，  

- 什么是变量的初始化？  

声明变量并赋值我们称之为变量的初始化
- 变量命名规范有哪些？  

变量名尽量要规范，见名知意-驼峰命名法

- 交换2个变量值的思路？

区分哪些变量名不合法    
学会交换2个变量值的思路  

# 数据类型  
## 1.数据类型简介  
## 1-1.为什么需要数据类型   
在计算机中，不同的数据所需占用的存储空间是不同的，为了便于把数据分成所需内存大小不同的数据，充分利用存储空间，于是定义了不同的数据类型。  
简单来说，数据类型就是数据的类别型号。比如姓名"张三",年龄18，这些数据的类型是不一样的。   
## 1-2 变量的数据类型  
变量是用来存储值的所在处，他们有名字和数据类型，变量的数据类型决定了如何将代表这些值的位存储到计算机的内存中，JavaScript是一种弱类型或者说动态语言，这意味着不用提前声明变量的类型，在程序运行过程中，类型会被自动确定。  
var age = 10；   // 这是一个数字型  
var areYouOk = '是的'  //  这是一个字符串   
在代码运行时，变量的数据类型是由JS引擎 = 右边变量值的数据类型来判断的，运行完毕之后，变量就确定了数据类型。  
JavaScript拥有动态类型，同时也意味着相同的变量可用作不同的类型：  
var x = 6；   //x为数字    

var x = 'Bill';   // x为字符串    
## 1-3 数据类型的分类   
JS把数据类型分为两类：  
- 简单数据类型（Number，String，Boolean，Undefined，Null）  
- 复杂数据类型（object）  
# 2.简单数据类型  
## 2-1简单数据类型（基础数据类型）  
JavaScript中的简单数据类型及其说明如下：  
简单数据类型|说明|默认值   
-|-|-
Number|数字型，包含整型值和浮点型值，如21，0.21|0   
Boolean|布尔值类型，如true，false，等价于1和0|false  
String|字符串类型，如"张三"注意sj里面，字符串都带引号|""   
Undefined|var a = null;声明了变量a 为空值|null  
  
## 2-2 数字型Number  
### 1.数字型进制  
最常见的进制有二进制，八进制，十进制，十六进制。  
1. 八进制数字的序列范围：0-7  
2. 十六进制数字序列范围：0-9以及A-F  

现阶段我们只需要记住，在JS中八进制前面加0，十六进制前面加0x   
### 2.数字型范围  
JavaScript中数值的最大和最小值    
alert (Number.MAX_VALUE); // 1.7976931348623157e+308  
alert (Number.MIN_VALUE);//5e-324    
- 最大值：Number.MAX_VALUE,这个值为：1.7976931348623157e+308   
- 最小值：Number.MIN_VALUE,这个值为：5e-32    
### 3.数字型三个特殊值  
- lnfinity，代表无穷大，大于任何数值  
- -Infinity，代表无穷小，小于任何数值  
- NaN,Not a number，代表一个非数值   
### 4.isNaN()  
用来判断一个变量是否为非数字的类型，返回true或者false     
isNaN(x),x是数字，返回false，x是一个非数字类型，返回true，  
var usrAge = 21；  
var isok = isNaN(userAge);   
console.log(isNum);  //false,21 不是一个非数字  
var usrName = "andy"   
consolo.log(isNaN(userName)); //true,"andy"是一个非数字   
## 2-3 字符串型String  
字符串型可以是引号中的任意文本，其语法为"双引号"和'单引号"  
var strMsg = "我爱北京天安门~";  //使用双引号表示字符串  
var strMsg2 = '我爱吃猪蹄~'; //使用单引号表示字符串  
//常见错误    
var strMsg3 = 我爱大肘子；  //报错，没使用引号，会被认为是js代码，但js没有这些语法   
因为HTML标签里面的属性使用的是双引号，js这里我们更推荐使用单引号。   
### 1.字符串引号嵌套  
JS可以用单引号嵌套双引号，或者用双引号嵌套单引号(外双内单，外单内双)    
### 2.字符串转义符  
类似HTML里面的特殊字符，字符串中也有特殊字符，我们称之为转义符。  
转义符都是\开头的，常用的转义符及其说明如下：  
转义符|解释说明   
-|-
\n|换行符，n是newline的意思  
\ \ | 斜杠\  
\ '|' 单引号   
\"|" 双引号   
\t|tab缩进   
\b|空格，b是blank的意思  
### 3.字符串长度  
字符串是由若干字符组成的，这些字符的数量就是字符串的长度。通过字符串的length属性可以获取整个字符串的长度。  
var str = '我是帅气多金的程序员！';   
alert(str.length);  //显示11    
### 4.字符串拼接   
- 多个字符串之间可以使用+进行拼接，其拼接方式为字符串+任何类型=拼接之后的新字符串   
- 拼接前会把与字符串相加的任何类型转成字符串，在拼接成一个新的字符串   

+号总结口诀：数值相加，字符相连   

### 5.字符串拼接加强   
var age = 18；   
console.log('豪哥'+age+'岁啦')    

- 我们经常会将字符串和变量来拼接，因为变量可以很方便地修改里面的值   
- 变量是不能添加引号的，因为加引号的变量就会变成字符串   
- 如果变量两侧都有字符串拼接，口诀“加加”，删除数字，变量写加中间    
## 2-4.布尔型Boolean    
布尔类型有两个值：true和false，其中true表示真（对），而false表示假（错）。   
布尔型和数字型相加的时候，true的值为1，false的值为0.   
console.log(true+1);//2   
console.log(false+1);//1     
## 2-5 Undefined和Null     
一个声明后没有被赋值的变量会有一个默认值Undefined（如果进行相连或者相加时，注意结果）  
# 3.获取变量的数据类型   
## 3-1.获取检测变量的数据类型   
typeof可用来获取检测变量的数据类型    
## 3-2.字面量   
字面量是在源代码中一个固定值的表示法，通俗来说，就是字面量表示如何表达这个值。  
- 数字字面量：8，9，10   
- 字符串字面量：'程序员','大前端'   
- 布尔字面量：true，false   
# 4.数据类型转换   
## 4-1.什么是数据类型转换   
使用表单，prompt获取过来的数据默认是字符串类型的，此时就不能直接简单的进行加法运算，而需要转换变量的数据类型，通俗来说，就是把一种数据类型的变量转换成另外一种数据类型。   
我们通常会实现3种方式的转换：   
- 转换为字符串类型   
- 转换为数字型   
- 转换为布尔型   
## 4-2.转换为字符串   
方式|说明|案例    
-|-|-
toString（）|转成字符串|var num= 1;alert(num.toString());   
String()强制转换|转成字符串|var num= 1；alert（String（num））；  
加号拼接字符串|和字符串拼接的结果都是字符串|var num=1；alert（num+"我是字符串");    
- toString()和String（）使用方式不一样。  
- 三种转换方式，我们更喜欢用第三种加号拼接字符串转换方式，这是一种方式也称之为隐式转换。     

## 4-3 转换为数字型（重点）   
方式|说明|案例
-|-|-  
parselnt（sting）函数|将string类型转成整数数值型|parseInt（'78')  
parseFloat(strig)函数|将string类型转成浮点数数值型|parseFloat（"78.21)  
Numbre()强制转换函数|将string类型转换为数值型|Number('12')   
js隐式转换(- * /)|利用算术运算隐式转换为数值型|'12'-0      
- 注意parseInt和parseFloat单词的大小写，这2个是重点   
- 隐式转换是我们在进行算数运算的时候，JS自动转换了数据类型     
## 4-4.转换为布尔型    
方式|说明|案例  
-|-|-
Boolean()函数|其他类型转成布尔值|Boolean('true');   
- 代表空，否定的值会被转换为false，如''.0 . NaN.null.undefined   
- 其余值都会被转换为true   
# 相关知识拓展  
## 1.解释型语言和编译型语言  
### 1.概述  
计算机不能直接理解任何除机器语言以外的语言,所以必须要把程序员所写的程序语言翻译成机器语言才能执行程序,  
程序语言翻译成机器语言的工具,被称为翻译器   
编程语言-----翻译器--------机器语言(二进制)   
- 翻译器翻译的方式有两种:一个是编译,另外一个是解释,两种方式之间的区别在于翻译的时间点不同   
- 编译器是在代码执行之前进行编译,生成中间代码文件  
- 解释器是在运行时及时解释,并立即执行(当编译器以解释方式运行的时候,也称为解释器)   
## 2.标识符.关键字.保留字  
### 1.标识符   
标识(zhi)符:就是指开发人员变量.属性.函数.参数取baoliuuzi的名字。   
标识符不能是关键字或保留字。   
### 2.关键字  
关键字：是指JS本身已经使用了的字，不能在用他们充当变量名，方法名。   
### 3.保留字  
保留字：实际上就是预留的"关键字",意思是现在虽然还不是关键字，但是未来可能会成为关键字，同样不能使用他们当变量名或方法名。  
# Javascript运算符   
## 1.运算符  
运算符（operator）也被称为操作符，是用于实现赋值，比较和执行算数运算等功能的符号   
JavaScript中常用的运算符有：  
- 算数运算符  
- 递增和递减运算符  
- 比较运算符  
- 逻辑运算符  
- 赋值运算符  
## 2.算数运算符   
### 2-1 算术运算符概述   
概念：算术运算使用的符号，用于执行两个变量或值的算术运算。   
运算符|描述|实例  
-|-|-   
+|加|10 + 20 = 30 |
-|减|10 - 20 = -10|
*|乘|10 * 20 = 200|   
/|除|10 / 20 = 0.5|  
%|取余数（取模）|返回除法的余数9%2=1  
### 2-2 浮点数的精度问题   
浮点数的精度问题  
浮点数值的最高精度是17位小数，但在进行算术计算时其精确度远远不如整数。  
不要直接判断两个浮点数是否相等  
### 2-3知识点问答  
1.我们怎么判断一个数能够被整除呢？  
它的余数是0就说明这个数能被整除，这就是%取余运算符的主要用途   
2. 1+2*3结果是？    
结果是7，注意算术运算符优先级，先乘除，后加减，有小括号先算小括号里面的    
### 2-4 表达式和返回值  
表达式：是由数字，运算符，变量等以能求得数值的有意义排列方法所得的组合   
简单理解：是由数字，运算符，变量等组成的式子   
表达式最终都会有一个结果，返回给我们，我们称为返回值       
## 3.递增和递减运算符  
### 3-1.递增和递减运算符概述   
如果需要反复给数字变量添加或减去1，可以使用递增（++）和递减（--）运算符来完成。   
在JavaScript中，递增（++）和递减（--）既可以放在变量前面，也可以放在变量后面，放在变量前面时，我们可以称为前置递增（递减）运算符，放在变量后面时，我们可以称为后置递增（递减）运算符。  
注意：递增和递减运算符必须和变量配合使用。  
### 3-2.递增运算符   
1.前置递增运算符   
++num前置递增，就是自加1，类似于num = num + 1 ，但是 ++num写起来更简单。   
使用口诀：先自加，后返回值    
2.后置递增运算符  
num++后置递增，就是自加1，类似于num = num + 1 ，但是num ++ 写起来更简单。   
使用口诀：先返回值，后自加    
### 3-3.前置递增和后置递增小结   
- 前置递增和后置递增运算符可以简化代码的编写，让变量的值+1比以前写法更简单    
- 单独使用时，运行结果相同   
- 与其他代码联用时，执行结果会不同  
- 后置：先原值运算，后自加（先人后己）  
- 前置：先自加，后运算（先己后人）  
- 开发时，大多使用后置递增减，并且代码独占一行，例如：num++；或者num--；  
## 4.比较运算符   
### 4-1.比较运算符概述   
概念：比较运算符（关系运算符）是两个数据进行比较时所使用的运算符，比较运算后，会返回一个布尔值（true/false）作为比较运算的结果。   
运算符名称|说明|案例|结果  
-|-|-|-    
<|小于号|1<2|true   
>| 大于号|1>2|false   
》=|大于等于号（大于或者等于）|2》=2|ture  
《=|小于等于号（小于或者等于）|3《=2|false  
==|判等号（会转型）|37==37|true    
！=|不等号|37！=37|false  
= ==   或 ！==|全等，要求值和数据类型都一致|37==="37"|false   
### 4-2.= 小结  
符号|作用|用法   
-|-|-   
=|赋值|把右边给左边  
==|判断|判断两边值是否相等（注意此时有隐式转换）  
== =|全等|判断两边的值和数据类型是否完全相同    
## 5.逻辑运算符  
### 5-1 逻辑运算符概述  
概念：逻辑运算符是用来进行布尔值运算的运算符，其返回值也是布尔值，后面开发中经常用于多个条件的判断   
逻辑运算符|说明|案例  
-|-|-   
&&|'逻辑与'，简称'与' and|true&&false  
&#124;&#124;|'逻辑或',简称'或'or|true&#124;&#124;false  
!|'逻辑非',简称'非'not|!true  
### 5-2.逻辑与&&  
两边都是true才返回true，否则返回false   
### 5-3.逻辑或||   
两边都为false才返回false，否则都为true   
逻辑非！   
逻辑（！）也叫左取反符，用来取一个布尔值相反的值，如true的相反值是false      
### 5-4 短路运算（逻辑中断）   
短路运算的原理：当有多个表达式（值）时，左边的表达式值可以确定结果时，就不再继续运算右边的表达式的值；   
1.逻辑与   
- 语法：表达式1&&表达式2   
- 如果第一个表达式的值为真，则返回表达式2   
- 如果第一个表达式的值为假，则返回表达式1   

2.逻辑或  
- 语法：表达式1||表达式2   
- 如果第一个表达式的值为真，则返回表达式1  
- 如果第一个表达式的值为假，则返回表达式2   
console.log( 123|| 456);  //123     
console.log( 0 || 456);  //456  
console.log( 123|| 456 || 789);  //123   
## 6.赋值运算符   
概念：用来把数据赋值给变量的运算符   
赋值运算符|说明|案例   
-|-|-  
=|直接赋值|var ursName="我是值"  
+=,-=|加，减一个数，后在赋值|var age = 10； age+=15  
*=，/=，%=|乘，除，取模，后在赋值|var age = 2；age *=5，  //10  
var age = 10   
age +=5；  //相当于age = age +5；  
age -=5；  //相当于age = age - 5；  
age *=5  //相当于age = age * 5；   
## 7. 运算符优先级   
优先级|运算符|顺序   
-|-|-  
1|小括号|（）  
2|一元运算符|++ --  ！  
3|算数运算符|先*/后+-  
4|关系运算符|》，》=，《，》=  
5|相等运算符|==，！=，===，！==  
6|逻辑运算符|先&&后||  
7|赋值运算符|=  
8|逗号运算符|，  
- 一元运算符里面的逻辑非优先级很高  
- 逻辑与比逻辑或优先级高   
   
# 1.流程控制   
在程序执行的过程中，各条代码的执行顺序对程序的结果是有直接影响的，很多时候我们要通过控制代码的执行顺序来实现我们要完成的功能。   
简单理解：流程控制就是来控制我们代码按照什么结构顺序来执行  
流程控制主要有三种结构，分别是顺序结构，分支结构和循环结构。这三种结构代表三种代码执行的顺序。   
# 2.顺序流程控制   
顺序结构是程序中最简单，最基本的流程控制，它没有特定的语法结构，程序会按照代码的先后顺序，依次执行，程序中大多数的代码都是这样执行的。  
# 3.分支流程控制if语句     
## 3-1 分支结构  
分支结构：条件执行——判断——1，2  

由上到下执行代码的过程中，根据不同的条件，执行不同路径代码（执行代码多选一的过程），从而得到不同的结果   
JS语言提供了两种分支结构语句  
- if语句  
- swich语句    
## 3-2 if语句  
### 1.语法结构  
// 条件成立执行代码，否则什么也不做  
if （条件表达式） {   
    //条件成立执行的代码语句    
    }    
    语句可以理解为一个行为，循环语句和分支语句就是典型的语句，一个程序是由很多语句组成，一般情况下，会分割成一个一个的语句。   
## 3-3. if else语句（双分支语句）   
1.语法结构   
//条件成立 执行if里面代码，否则执行else里面的代码   
if（条件表达式） {   
    //{如果}条件成立执行的代码  
    } else{  
        //{否则}执行的代码  
    }    
## 3-4. if else if 语句（多分支语句）  
### 1.语法结构   
// 适合于检查多重条件。   
if （条件表达式1） {   
    语句1；   
    } else if （条件表达式2） {  
        语句2；  
} else if （条件表达式3） {  
    语句3；  
} else {  
    //上述条件都不成立执行此处代码  
}    
# 4.三元表达式   
三元表达式也能做一些简单的条件选择，有三元运算符组成的式子称为三元表达式    
条件表达式 ？ 表达式1 ： 表达式2   
如果条件表达式为真，则返回表达式1的值，如果为假，则返回表达式2 的值。  
var num = 10；  
var result = num > 5 ? '是的' : '不是的'  //  表达式是有返回值的     
# 5.分支流程控制switch语句    
## 5-1 语法结构   
switch语句也是多分支语言，它是基于不同的条件来执行不同的代码。当要针对变量设置一系列的特定值的选项时，就可以使用switch。  
  var num = 1   

  switch (num) {  
      
       case 1:  
        console.log(1);
        break;
        case 2: 
        console.log(2);
        break;
        case 3: 
        console.log(3);
        break;  
        default: 
        console.log('没有匹配结果')
    }    
### 注意：   
1.我们开发里面，表达式我们经常写成变量。  
2.我们num的值和case里面的值相匹配的时候是全等 ，必须是值和数据类型一致才可以 num === 1   
3.break 如果当前的case里面没有break ，则不会退出switch ，是继续执行下一个case   
## 5-2 switch语句和if else if 语句的区别   
1.一般情况下，他们两个语句可以相互替换  
2.switch...case语句通常处理case为比较确定值的情况，而if···else··语句更加灵活。常用于范围判断（大于，等于某个范围）  
3.switch语句进行条件判断后直接执行到程序的条件语句，效率更高。而if··else语句有几种条件，就得判断多少次。  
4.当分支比较少时，if··else语句的执行效率比switch语句高。  
5.当分支比较多时，switch语句的执行效率比较高，而且结构更清晰。      
# 循环流程控制    
# 1.循环   
### 循环目的  
- 在实际问题中，有许多具有规律性的重复操作，因此在程序中要完成这类操作就需要重复执行某些语句   

 JS中的循环   
在JS中，主要有三种类型的循环语句：   
- for循环   
- while循环   
- do...while循环    
# 2.for循环   
在程序中，一组被重置执行的语句被称之为循环体，能否继续重复执行，取决于循环的终止条件。由循环体及循环的终止条件组成的语句，被称之为循环语句   
1.for重复执行某些代码，通常跟计数有关系   
2.for语法结构    
for （初始化变量;条件表达式;操作表达式） { 循环体 }     
3.初始化变量，就是用var 声明一个普通变量，通常用于作为计数器使用     
4.条件表达式，就是用来决定每一次循环是否继续执行，就是终止的条件  
5.操作表达式，是每次循环最后执行的代码，经常用于我们计数器变量进行更新（递增或者递减）   
## 2-1 for循环执行过程及语法   
     for (var i = 1; i<= 100; i++) {
    console.log('你好吗'); }    
  1.首先执行里面的计数器变量  var i = 1 . 但是这句话在for 里面只执行一次   
  2.去 i<= 100来判断是否满足条件，如果满足条件，就去执行 循环体 ，不满足条件退出循环   
  3.最后去执行i++，i++是单独写的代码，递增，第一轮结束   
  4.接着去执行 i <= 100 如果满足条件，就去执行循环体，不满足条件退出循环    
  5.可通过断点调试去浏览器去调试     
  ## 2-2.for循环重复相同代码   
     for (var i = 1; i <= 100; i++) {
     console.log('媳妇我错了')
   }
   
    var num = prompt('媳妇我错了');
    for (var i = 1; i <= num; i++) {
     console.log('媳妇我错了');
   }
  ## 2-3.for循环重复不相同的代码   
  for循环还可以重复不同的代码，这主要是因为使用了计数器，计数器在每次循环过程中都会有变化。   
     
     for (var i = 1; i <=100; i++) {
      if (i==1) {
        console.log('这个人今年1岁，它出生了');
      } else if (i == 100) {
        console.log('这个人今年100岁，它死了');
      } else {
        console.log('这个人今年'+ i +'岁了');
      }
    }     
## 2-4 for 循环重复某些相同操作    
for循环因为有了计数器的存在，我们还可以重复的执行某些操作，比如做一些算数运算。   
 
    // 求1-100  之间的整数累加和
     var num = 0  //求和的变量  
     for (var i = 1; i<= 100; i++) {
       num = num + i;
     }  //num += i;
     console.log(num);     
## 2-5 for循环案例     
 // 1.求1-100  之间所有数的平均值，需要一个sum和的变量，还需要一个平均值average变量
    var sum = 0
    var average = 0;
    for (var i = 1; i <= 100; i++) {
      sum = sum + i;
    }
    average = sum / 100;
    console.log(average);

    // 2.求1-100之间所有偶数和奇书的和
    var even = 0;
    var odd = 0;  
    for (var i = 1; i <=100; i++) {
        if ( i % 2 == 0) {
          even = even + i;
        } else {
          odd = odd + i;
        }
    }
    console.log('1~100之间所有偶数和是'+ even);
    console.log('1~100之间所有奇数的和是'+ odd);

    //3.求1-100之间所有能被3整除的数字的和
    var result = 0;
    for (var i = 1; i<=100; i++) {
      if ( i % 3 ==0) {
        result = result + i;
      }
    }
    console.log('1-100之间能够被3整除的数字的和是：'+result); 
       
  ## 求学生成绩案例

   var num = prompt('请输入班级总人数：');
       
var sum = 0;  //求和的变量
  var average = 0; //求平均值的变量
 
    for(var i = 1; i <= num; i++) {
     var score = prompt('请您输入第'+ i +'个学生的成绩');
     //从prompt取过来的数据是字符串型，需要转换为数字型
     sum = sum + parseFloat(score);
  }    

 average = sum / num;
 
 alert('班级的总成绩是' + sum);
  
  alert('班级平均分是：' + average);  
# 3.双重for循环   
## 3-1.双重for循环概述   
很多情况下，单程for循环并不能满足我们的需求，比如我们要打印一个5行5列的图像，打印一个倒直角三角形等，此时就可以通过循环嵌套来实现。   
循环嵌套是指在一个循环语句中在定义一个循环语句的语法结构，例如在for循环语句中，可以再嵌套一个for循环。这样的for循环语句我们称之为双重for循环。  
外层循环循环一次，里面的循环全部执行    
### 打印5行5列的字：  

    var str = '';
    for (var i = 1 ; i <= 5 ; i++) { //外层循环负责打印五行
    for (var j = 1 ; j <= 5 ; j++) { //里层循环负责打印五个星星
      str = str + '我';
    }
      str = str + '\n';
    }
    console.log(str);   
### 打印N行N列的字：
    var rows = prompt('请您输入行数：');
    var cols = prompt('请您输入列数：');
    var str = '';
    for (var i = 1; i <= rows; i++) {
      for (var j = 1; j <= cols; j++) {
        str = str + '我'
      }
      str = str + '\n'
    }
    console.log(str);  
### 倒三角：  
     var str = ''
     for( var i = 1; i<=10; i++) {
      for( var j = i; j <= 10; j++) {
        str = str + '我';
      }
      str = str + '\n';
    }
    console.log(str);    
### 正三角九九乘法表：  
    var str = ''
    for( var i = 1; i<=9; i++) {
      for( var j = 1; j <= i; j++) {
        str = str+j+'×'+i+'＝'+i*j+'\t'
      }
      str = str + '\n';
    }
    console.log(str);  
## 3-5 for循环小结  
- for循环可以重复执行某些相同代码  
- for循环可以重复执行些许不同代码，因为我们有计数器  
- for循环可以重复执行某些操作，比如算术运算符加法操作  
- 随着需求增加，双重for循环可以做更多，更好看的效果  
- 双重for循环，外层循环一次，内层for循环全部执行  
- for循环是循环条件和数字直接相关的循环  
- 分析比写代码更重要     
# 4.while循环  
while语句可以在条件表达式为真的前提下，循环执行指定的一段代码，直到表达式不为真时结束循环。    

    var num = 1;
    while (num <= 100) {
    console.log('你好呀')
    num++;






















