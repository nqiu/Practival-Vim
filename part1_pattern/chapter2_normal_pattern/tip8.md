# 技巧8： 把撤销的单元切成块

## `u`: 撤销上一次操作

> **__一次操作__**:改变文档内文本的任意操作,`i`{insert some text}`<Esc>` 是一次修改

撤销操作可能只是一个字符,可能是一段话, 控制`<Esc>`键的使用可使撤销命令重复作用于单词\句子\段落,这样最好

## `<Esc>o` 好过 `<Cr>`

插入模式中,光标位于行尾, 如果需要另起一行, 有两种方式:

> 1. 直接回车(`<Cr>`)
> 2. 跳出插入模式后在下面新开一行插入(`<Esc>o`)

第二种方法更好: 撤销下一行的时候上一行的修改还在


<br>  

|上一篇|下一篇|
|:---|---:|
|[Tip7 停顿时请移开画笔](tip7.md)| [Tip9 尽量构造可重复的修改](tip9.md)|
