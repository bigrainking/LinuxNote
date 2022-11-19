### 编辑命令

- Ctrl + a ：移到命令行首
- Ctrl + e ：移到命令行尾
- Ctrl + f ：按字符前移（右向）
- Ctrl + b ：按字符后移（左向）
- Alt + f ：按单词前移（右向）
- Alt + b ：按单词后移（左向）
- Ctrl + xx：在命令行首和光标之间移动
- Ctrl + u ：从光标处删除至命令行首
- Ctrl + k ：从光标处删除至命令行尾
- Ctrl + w ：从光标处删除至字首
- Alt + d ：从光标处删除至字尾
- Ctrl + d ：删除光标处的字符
- Ctrl + h ：删除光标前的字符
- Ctrl + y ：粘贴至光标后
- Alt + c ：从光标处更改为首字母大写的单词
- Alt + u ：从光标处更改为全部大写的单词
- Alt + l ：从光标处更改为全部小写的单词
- Ctrl + t ：交换光标处和之前的字符
- Alt + t ：交换光标处和之前的单词
- Alt + Backspace：与 Ctrl + w ~~相同~~类似，分隔符有些差别 [感谢 rezilla 指正]

### 重新执行命令

- Ctrl + r：逆向搜索命令历史
- Ctrl + g：从历史搜索模式退出
- Ctrl + p：历史中的上一条命令
- Ctrl + n：历史中的下一条命令
- Alt + .：使用上一条命令的最后一个参数

### 控制命令

- Ctrl + l：清屏
- Ctrl + o：执行当前命令，并选择上一条命令
- Ctrl + s：阻止屏幕输出
- Ctrl + q：允许屏幕输出
- Ctrl + c：终止命令
- Ctrl + z：挂起命令

### Bang (!) 命令

- !!：执行上一条命令
- !blah：执行最近的以 blah 开头的命令，如 !ls
- !blah:p：仅打印输出，而不执行
- !$：上一条命令的最后一个参数，与 Alt + . 相同
- !$:p：打印输出 !$ 的内容
- !*：上一条命令的所有参数
- !*:p：打印输出 !* 的内容
- ^blah：删除上一条命令中的 blah
- ^blah^foo：将上一条命令中的 blah 替换为 foo
- ^blah^foo^：将上一条命令中所有的 blah 都替换为 foo



# shell bash分别是什么？

**shell**

shell是机器的一层外壳，提供给人机交互的，用来**解释用户的一条条命令**，不局限于语言、形式。

比如在terminal输入一条命令，机器就会执行，这个terminal就是shell

比如用户在桌面系统上点击文件，机器执行打开文件，这个解释打开这个动作的器件就是shell。



因此Linux系统是bash就是shell

<img src="pic/1bash%E5%BF%AB%E6%8D%B7%E9%94%AE.assets/image-20221117111153763.png" alt="image-20221117111153763" style="zoom:33%;" /> <img src="pic/1bash%E5%BF%AB%E6%8D%B7%E9%94%AE.assets/image-20221117111211240.png" alt="image-20221117111211240" style="zoom: 50%;" />



**bash**

bash是Linux的shell中的一种也是最常见的（就是ctrl+alt+T出现的那个输入命令行的黑框框），ZSH也是

## [参考链接](https://blog.csdn.net/whatday/article/details/106072167)