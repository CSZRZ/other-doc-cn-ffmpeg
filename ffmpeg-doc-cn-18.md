## 字幕编码器
### dvdsub ###
这个编码器编码使用者DVD中的位图字幕格式。一般存储字VOBSUB文件中（包括*.idx *.sub），它也用于Matroska文件中。

#### dvdsub选项 ####

- even_rows_fix

    但设置为1，则让所有的行平顺。它解决了如果最后行是奇数行时可能非法截断的问题。这个选项仅仅在需要的地方添加了一个透明的行，它的开销很低，通常是一个平均字幕字节数。（位图特性上的一种修正）

    默认，work-around被禁止 
