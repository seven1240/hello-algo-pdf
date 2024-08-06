# Hello 算法 PDF 编译脚本

PDF builder for hello-algo。

[《Hello 算法》](https://github.com/krahets/hello-algo)（以下简称《Hello》）是一本开源的算法书，官方有各种语言（包括编程语言和人类的语言）的版本，包括 PDF 版本。

我也写过几本书，也使用 Markdown。很多年前我写了[《技术图书排版》](http://freeswitch.org.cn/books/typesetting/)（以下简称《排版》），算是我写作过程的一些心得和副产品。为了验证《排版》的模板能力，我尝试编译了一下《Hello 算法》，虽然也花了不少功夫，但最终的结果还是比较完美。

《Hello》本身写得比较规范，处理起来就比较有规律，这大大降低了处理的难度。当然，由于《Hello》要适配 mkdocs 以及多种语言和多种格式的版本，在标准 Markdown 的基础上还做了一些扩展，这又增加了处理的难度。不过，最终结果还不错。与官方的 PDF 版本相比，本版本排版更大方一些，使用了 Noto Sans 字体，看起来更舒服一些。

当然，本版本也有一些不足之外，表现在：

- 表格标题的处理，由于原文使用了一种特殊的处理方式，暂无法做到自动标号和关联。
- 上图、下图等没有处理成“图1-1”等交叉引用格式，不知《Hello》原版使用了什么魔法。
- 封面及有些插图未翻译（未找到源文件）。
- 其他（欢迎提 issue）。

《Hello》原文一字未改，只是写了几个 Lua Filter 配合 Pandoc 和 Latex（XeLatex）编译成 PDF。后面我会把处理过程和源代码公布出来，供大家参考。

---

PDF 下载：

- 简体中文版
- 繁体中文版
- 英文版（English）：Since some C code is missing, I replaced with some C++ code, will fix later.

详见： <https://github.com/seven1240/hello-algo-pdf/releases> 。

---

另外，我也正在写一本编程书：[《大道至简，给所有人看的编程书》](https://note.mowen.cn/note/detail?noteUuid=Fj65tBfKpyvQrZEuFCmmT)（非开源），也是使用 Markdown 和《排版》模板排版的。
