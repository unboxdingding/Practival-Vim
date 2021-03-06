# 技巧56： 遍历改变列表
> 每次对文档修改后，vim都会记录当时光标所在位置，可以快速的在这些位置中跳转<br>
> `跳转列表`包含之前vim的所有文件的跳转情况，但是`改变列表`只是记录当前文件的改变情况


#### `:changes` 查看改变列表
#### `g;`,`g,`在改变列表中跳转，光标跳到之前和之后修改的位置
> 和行内搜索字符的命令`f{char}`类似，`;`,`,`分别向前和向后查找

2个特殊的跳转命令

1. `` `.`` 指向最后一次修改的地方，是不能重复使用的`g;`
2. `` `^`` 指向最后一次插入模式推出时的光标位置
3. `gi` 立刻跳转到最后一次插入模式跳出的位置，并进入插入模式，**快速的继续修改**


<br>  

|上一篇|下一篇|
|:---|---:|
|[技巧55 遍历跳转列表](tip55.md)|[技巧57 跳转到光标下的文件](tip57.md)|
