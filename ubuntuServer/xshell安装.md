



# Xshell的使用

- 复制粘贴等命令
- 文件传输

## 1. 常用快捷键

**自定义修改快捷键**

<img src="pic/xshell%E5%AE%89%E8%A3%85.assets/image-20221117121645887.png" alt="image-20221117121645887" style="zoom: 25%;" />
打开会话窗口：`Alt + o`
切换打开的多个tab：`Alt+1~9` 或者 `Ctrl + Tab` 或者 `Shift + Tab`
断开连接：`ctrl + d` 退出登录，再按 `ctrl + d` 关闭当前窗口

## 2. 打开新连接

双击窗口的虚拟机名称即可打开一个登录用户相同的连接

<img src="pic/xshell%E5%AE%89%E8%A3%85.assets/image-20221117115944014.png" alt="image-20221117115944014" style="zoom:33%;" />



[参考链接](https://www.jianshu.com/p/4716cc35750f)

## 3. 文件传输

在主机（安装Xshell的机器）传输数据到Server使用FTP软件。

直接安装xFTP即可

<img src="pic/xshell%E5%AE%89%E8%A3%85.assets/image-20221117120110263.png" alt="image-20221117120110263" style="zoom:33%;" />





# Xshell简介

传输文件等可以使用Xshell。

Xshell在物理主机上安装之后，可以登录到ubuntuServer服务器，相当于将ubuntu server的shell终端拿到物理主机上在使用。



# Xshell安装

[安装教程](https://blog.51cto.com/u_15571262/5175767)

[Xshell下载地址](https://www.netsarang.com/en/xshell/)

1. 注册下载免费版本

2. 点击根据提示安装

3. 安装完成的界面

    <img src="pic/xshell%E5%AE%89%E8%A3%85.assets/image-20221117114716962.png" alt="image-20221117114716962" style="zoom:25%;" />



# Xshell连接Ubuntu Server

1. 新建会话

2. 填写Ubuntu server的IP地址

    在server中通过 `ip a`查看地址

3. 填写user password： 在server中安装时设置的username password

---

1. 新建会话

    <img src="pic/xshell%E5%AE%89%E8%A3%85.assets/image-20221117115046276.png" alt="image-20221117115046276" style="zoom:25%;" />

2. 填写Ubuntu server的IP地址

    - 下图中的服务器公网IP就是，物理主机（安装Xshell的主机）能ping通Server所用的IP地址

    <img src="pic/xshell%E5%AE%89%E8%A3%85.assets/image-20221117115104051.png" alt="image-20221117115104051" style="zoom: 33%;" />

3. 填写user password

<img src="pic/xshell%E5%AE%89%E8%A3%85.assets/image-20221117115225997.png" alt="image-20221117115225997" style="zoom: 33%;" />