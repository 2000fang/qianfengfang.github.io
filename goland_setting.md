## [vscode](https://so.csdn.net/so/search?q=vscode&spm=1001.2101.3001.7020)中搭建Golang开发环境

### 第一步

下载Go安装包，地址：[Go语言中文网](https://studygolang.com/dl)，安装完成后的目录如下：

![](C:\Users\fangqianfeng\Pictures\Camera Roll\goland环境配置\1.png)

通过命令行查看当前版本：

![](C:\Users\fangqianfeng\Pictures\Camera Roll\goland环境配置\2.png)

### 第二步

配置[环境变量](https://so.csdn.net/so/search?q=环境变量&spm=1001.2101.3001.7020)，新建两个环境变量，如下：

![](C:\Users\fangqianfeng\Pictures\Camera Roll\goland环境配置\3.png)

其他平台的配置，可以参考[goproxy](https://goproxy.io/)官网。

### 第三步

打开vscode，安装一个Go插件，如下：

![](C:\Users\fangqianfeng\Pictures\Camera Roll\goland环境配置\4.png)

然后打开一个已有的文件夹，并创建一个hello.go的文件，此时，右下角会提示你要安装相应的应用，选择 Install All，等待安装即可，安装成功如下：

![7](C:\Users\fangqianfeng\Pictures\Camera Roll\goland环境配置\7.jpg)

![](C:\Users\fangqianfeng\Pictures\Camera Roll\goland环境配置\6.jpg)

到这里环境就搭建完成了

### 第四步

在hello.go文件中编写go程序

```go
package main

import "fmt"

func main() {
	fmt.Println("hello World")
}
```

在终端执行下面命令，就会生成**go.mod**文件

```go
go mod init gitee.com/mall_lucy/my_go_studycode
```

![](C:\Users\fangqianfeng\Pictures\Camera Roll\goland环境配置\8.png)

然后在终端运行hello.go就可以了，如下：

![](C:\Users\fangqianfeng\Pictures\Camera Roll\goland环境配置\9.png)