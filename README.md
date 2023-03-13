# csdn2markdown
also known as [csdn to md] [csdn to markdown] [csdn 2 markdown]
language:[CN](###CN)/ [EN](###EN)

### CN

**目前该版本仅为Windows提供**

将CSDN的博客导出为Typora格式的markdown文件，它支持单篇或整个专栏所有文章的导出操作，并且可以将本次所有导出内容汇总在一起变成一篇文章。

为了更方便使用，shell脚本文件拥有基本的交互，可以进行转换模式选择，文章url输入等操作。

support files中有aria的配置文件和pandoc的配置文件，您还需要下载安装git

在对aria配置好，pandoc以及git安装好后

windows环境下双击run.sh即可使用，建议使用管理员模式。

也可以在该文件目录的cmd窗口输入 sh run.sh 使用

有需要注意的地方：

1.  两个python文件里import的库都要安装
2.  使用aria2来下载文章图片，本库里自带一个，解压后可以查看使用方法
3.  typora需要开启内联公式
4.  该转换仅针对typora格式，其他markdown编辑器可能会加载错误

### EN

**Currently this version is only available for Windows**

Export CSDN blog to Typora format markdown file, it supports the export operation of a single article or an entire column, and can summarize all the export content into a single article.

For ease of use, the shell script file has basic interactions, such as conversion mode selection, article url input, and so on.

The configuration files for aria and pandoc are available in support files. You will also need to download and install git

After aria is configured, pandoc and git are installed

In windows, double-click run.sh. You are advised to use the administrator mode.

You can also enter sh run.sh in the cmd window of the file directory

Some things to note:

1.   Install the imported libraries from both python files

2.   Use aria2 to download the article images, this library comes with one, unzipped you can see how to use

3.   typora needs to enable inline formulas

4.   This conversion only works for typora format, other markdown editors may load incorrectly
