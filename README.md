[![Build Status](https://drone.io/github.com/beijinglug/fsfs-zh/status.png)](https://drone.io/github.com/beijinglug/fsfs-zh/latest)

Free Software, Free Society v3 Chinese Translation
=========================

在线阅读（Html）：<https://fsfs-zh.readthedocs.io/>

下载电子书（EPUB）：[这里下载](https://drone.io/github.com/beijinglug/fsfs-zh/files/fsfs-zh.epub)

如何参与
---------

**必看**：翻译时参考的术语表，请见[这里](glossary.md)。

### 翻译流程

- 总的原则是谁开的坑谁来填。翻译进度可参阅 issue #14
- 翻译之前先到 issue 里看看欲翻译的那篇文章有没有被人占据，以防冲突或重复劳动
- 开个新 issue 表明想要翻译的文章
- 翻译时以段落为单位，将译文写到原文下方即可，**不要删除**原英文，以备校对时使用
- 整篇文章翻译完之后顺便将自己的名字写到`README.md`文件的贡献者一栏，然后将所有 commit 一起提交 Pull Request 即可。
- Pull Request 被 merge 以后关闭对应的 issue。
- 提交 Pull Request 之前先自我检查一下，减少校对者的劳动

### 校对流程

- 任何已经翻译好的文章都可以校对，已翻译过的文章列表可参见 issue #14。
- 一边校对一边删除原文，校对完成一段删除一段原文。也可以全文都校对完成再删除原文。
- 校对时注意整篇文章的翻译用语必须一致，同时也要保证与整本书的[术语翻译](glossary.md)一致。
- 校对时注意调整 Markdown 格式，最终效果可以参考已经校对好的[appendix-a.md](docs/appendix-a.md)。
    - 所有文章的大标题均使用二级标题 `## 标题`，去掉标题前面的数字。其他子标题自动降低一级，如 `### 子标题`。Part 的标题使用一级标题，但不用写第几部分，直接翻译内容，`# GNU 工程与自由软件`
    - 脚注调整格式，原文中出现注释的位置，加上`[^文件名-1]`，然后在文末按照格式 `[^文件名-1]: 注释内容` 加上注释内容即可，删掉原先的`### [(1)] (FOOT1)`这种标识。
    - 版权声明和首次发布说明，比如`Copyright © 2015 Free Software Foundation, Inc.` 翻译后放到文首标题下方，并使用 `>` 将其改为引用格式。
	- 文中所有不相关的 Texinfo 和 HTML 代码符号都可以删掉。
    - 文中若出现译者/校对者的名字，请将其删除（安全考量），但若是引用其他网站或个人的翻译文章，应保留原翻译者、出处和授权许可（版权考量）。
- 校对完成一整篇文章后可以提交 Pull Requst，提交之前记得将自己名字写到`README.md`的贡献者一栏。

注意事项
--------
- 翻译和校对时注意修改格式，有些 texinfo 格式标示符需要转换成 Markdown 格式（比如尾注等），还有一些 Markdown 不支持的或者没有意义的可将其删除
- 中英文混排时，英文和中文之间留有空格，例如：`推广 Free Software 的理念`。若邻近标点符号则不需要空格，如：`Free Software（自由软件）`。
- 除代码和特例（比如域名），所有标点符号均为全角
- 翻译用语遵从自由软件用语标准，若不知如何翻译，可在译文后赘英文标注，如：`自由软件（Free Software）`。

贡献者
-------

| 贡献者 | 贡献内容 |
| ------ | -------- |
| @nadebula | 翻译了第三、四、六和七部分以及其他一些文章 | 
| @tonghuix | 翻译了一些文章，将某些既有翻译加入进来，大量校对 |
| @liushuyu | 翻译了 Linux and GNU 一文 |
| @persmle | 翻译了一些文章，大量校对 | 
| @MandyMY | 大量校对 |
| @biergaizi | 少量翻译 |
| @mytbk | 少量翻译和校对 |

授权许可
--------

GNU FDL 1.3 （GNU 自由文档许可证）
