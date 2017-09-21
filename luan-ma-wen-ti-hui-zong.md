# 乱码问题汇总

总共有下面几种乱码的解决方案：

* 工程乱码
* 执行main函数时，控制台乱码
* 运行tomcat时，控制台乱码

**PS: 如果下面方案不生效时，打开IDEA安装目录找到idea.exe.vmoptions\(64位为idea64.exe.vmoptions\)文件，在文件末尾上 -Dfile.encoding=UTF-8**  
可以先做这一步，加上这个基本上很多都不会乱码了

## 工程乱码

打开File-Setting, 找到File Encodings这个选项，把encoding设置成你工程的编码即可，一般是UTF-8，如下图\(红框的地方\)，然后重新rebuild一下，基本就行了

![](/assets/1505981817968.png)

## 执行main函数时，控制台乱码

同样是打开setting，找到Build, Execution, Deployment &gt; Compiler &gt; Java Compiler， 设置Additional command line parameters 选项为 `-encoding utf-8` 然后rebuild下，重新运行：

![](/assets/1505982125675.png)

## 运行tomcat时，控制台乱码

然后在Server &gt; VM options设置为 -Dfile.encoding=UTF-8,重启tomcat

![](/assets/1505982450970.png)

