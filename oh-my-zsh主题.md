## uninstall oh-my-zsh

https://askubuntu.com/questions/963874/uninstall-oh-my-zsh

```
sudo chmod 777 ~/.oh-my-zsh/tools/uninstall.sh

~/.oh-my-zsh/tools/uninstall.sh
```

## 安装zsh

参考：https://juejin.cn/post/6844903942577618952

安装zsh

```shell
apt install zsh
```

查看当前shell

```shell
echo $SHELL
```

查看有哪些shell可以用

```shell
cat /etc/shells
---------
 yang@yang-virtual-machine  ~  cat /etc/shells
/bin/sh
/bin/bash
/usr/bin/bash
/bin/rbash
/usr/bin/rbash
/bin/dash
/usr/bin/dash
/bin/zsh
/usr/bin/zsh
```

更换shell：(重启电脑生效)

- 给当前用户更换

```shell
chsh -s /bin/zsh 
#给别的用户更换
chsh -s /bin/zsh root
------------------------------------
yang-virtual-machine# chsh -s /bin/zsh root
yang-virtual-machine# echo $SHELL
/bin/zsh
```

重启后查看当前shell：echo $SHELL



## 安装oh-my-zsh

> 安装有3种方法，但前两种总是出现连接错误（约莫是DNS污染）
>
> 因此使用最后一种

```shell
wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | zsh
```

## 

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

手动安装：

```shell
# 从git上把oh-my-zsh clone下来到根目录下
git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
# 再在根目录下copy一份.zshrc配置
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
```



## 配置oh-my-zsh

### 主题设置

https://juejin.cn/post/6844903942577618952

列出主题

```shell
ls ~/.oh-my-zsh/themes
```

更换主题

```shell
vim ~/.zshrc
```

修改配置文件：红色部分是需要修改的主题

<img src="../Operating System/一些方法.assets/image-20210305200027906.png" alt="image-20210305200027906" style="zoom: 33%;" />

重新加载配置文件

```
source ~/.zshrc
```

（如果没有生效，重启一次）

### 语法高亮(Enabling Plugins)

- Download zsh-syntax-highlighting by

```shell
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
```

`vim ~/.zshrc` find `plugins=(git)`

Append `zsh-syntax-highlighting` to `plugins()` like this

```shell
plugins=(git zsh-syntax-highlighting)
```

生效：

```
source ~/.zsh 并重启
```



- Reopen termina



