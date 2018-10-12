## Introdution
课程《服务计算》作业：golang实现selpg。

相关链接：[课程链接](https://pmlpml.github.io/ServiceComputingOnCloud/ex-cli-basic)

主要是马两个基础教程：开发 Linux 命令行实用程序，Linux命令行程序设计

### 要求

编写一个能够从文件或者命令行输入起始页码和结束页码并将输出打印到命令行或者文件中的小程序

#### 输入(两种方式)
在命令行上指定文件名：
```
command inputFile
```
在这里，command应该读取inputFile文件

标准输入：
```
command
```
在这里，用户从终端键盘输入，用户输入Control-D前输入的所有内容为command的输入。

#### 输出
输出应该被写至标准输出，缺省情况下标准输出同样也是终端：
````
command
````
在这个例子中，command 的输出出现在屏幕上。

同样，使用 shell 操作符“>”（重定向标准输出）可以将标准输出重定向至文件。
````
command > output_file
````
还有输出错误文件，以及输出作为其他文件的输入。

### selgp使用

#### 安装
```
go get github.com/NikkariAoe/selpg.git
```

#### Help
```
$GOPATH/bin/hw1 -h
```
