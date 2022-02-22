# vim

vim 具有程序编辑的能力，可以主动的以字体颜色辨别语法的正确性，方便程序设计。

基本上 vi/vim 共分为三种模式，分别是

- **命令模式（Command mode）**
- **输入模式（Insert mode）** 
- **底线命令模式（Last line mode）**

## 命令模式

**光标移动：**

| 快捷键     | 含义                             |
| ---------- | -------------------------------- |
| h          | 左移一个字符                     |
| j          | 下移动一行                       |
| k          | 上移动一行                       |
| l          | 右移动一个字符                   |
| [n]j       | 向下移动n行，比如5j，向下移动5行 |
| ctrl+f     | 向下翻页                         |
| ctrl+b     | 向上翻页                         |
| [n]G       | 移动到第n行                      |
| 0          | 移动到行首                       |
| I(大写的i) | 移动到行尾开始输入               |
| o          | 下一行开始输入                   |

## 插入模式

- x：删除当前位置的字符
- dd：删除当前行
- u：撤销上一个命令

复制命令

    /[s]

[s]：表示要查找的字符

替换第一个

    :s/old/new

替换所有

```sh
:s/old/new/g
```

## 显示行号

```sh
：set number
```
