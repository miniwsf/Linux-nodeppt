title: nodeppt markdown 演示
speaker: 三水清
url: https://github.com/ksky521/nodeppt
transition: slide3
files: /js/demo.js,/css/demo.css,/js/zoom.js
theme: moon
usemathjax: yes

[slide]
## Linux分享
----

* Linux简介
* Shell命令
* 文件目录管理
[slide]
# Linux简介

[slide]
* Linux与windows系统区别
> C语言编写的程序 用户使用Linux的桥梁


[slide]
# Shell命令

[slide]
# Shell相关问题
----

* 问题一：Shell是什么？
> C语言编写的程序 用户使用Linux的桥梁

* 问题二：Shell和命令行的区别是什么？
> 命令行只是接受用户的命令输入，然后将命令传递给命令解释器。而Shell是命令行解释器，用户在命令行输入命令，运行在后台的Shell将命令转换成指令代码发送给操作系统。

[slide] 
# 常用的Shell命令

[slide]
## cd 切换目录
----

<pre><code class="markdown">
cd  /* 返回自己的用户主列表 */
cd ~  /* 返回自己的用户主列表 */
cd ..  /* 返回上一级目录 */
cd ../..  /* 返回根目录 */
...
</code>
</pre>

[slide]
## ls 浏览文件目录
----

<pre><code class="markdown">
ls -F  /* 在目录后面加上/，在链接文件后加@，在可执行文件加* */
ls -a  /* 显示所有文件，包括隐藏文件 */
ls -l  /* 查看文件各种属性（vdir） */
ls 路径  /* 查看该子目录下面的文件列表 */
...
</code>
</pre>

[slide]
## 查看目录和文件
----

<pre><code class="markdown">
cat  /* 查看文件内容 */
more  /* 相较于cat将文件内容全部显示出来，more是一页一页的显示（按下空格键向下翻一页，按enter键向下滚动一行，按Q键退出） */
head与tail  /* 阅读文件的开头与结尾 */
less  /* 更好的文本阅读工具 */
pwd  /* 显示当前所在的位置，即工作目录 */
grep  /* 查找文件内容,格式：grep 被搜索的关键词 被搜索的文件 */
...
</code>
</pre>

[slide]
## 其他
----

<pre><code class="markdown">
find   /* 查找文件 */
locate  /* 更快速的定位文件 */
whereis  /* 查找特定程序 */
who  /* 查看当前系统中有哪些人登录以及他们都工作在哪个控制台 */
whoami  /* 查看当前自己是什么身份登录 */
uname  /* 查看当前系统的版本信息（-a，查看当前操作系统所有有用的信息；-r，查看系统的内核版本信息） */
man  /* 方便的获取某个命令的帮助信息 */
whatis  /* 查看命令大概可以做些什么 */
apropos  /* 通过使用手册反查到某个命令 */
...
</code>
</pre>

[slide]
# 提高效率的小技巧
----

> 输入目录的前几个字符，按Tab键，自动补全文件名；如果以已键入字符开头的文件目录不止一个，那么连续按下Tab键两次，就会以列表的形式列出以已键入字符开头的所有文件。（此方法同样适用于linux命令）