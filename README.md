# BIT-thesis-LaTex
LaTeX Template for BIT thesis
该模板基于项目<https://github.com/BIT-thesis/LaTeX-template>修改，具体修改内容如下：
- 新增普通模式(normal)、自查重模式(selfSimilarCheck)和盲审模式(blindCheck)。提交学校的查重文件可以直接使用normal模式结果；自查重模式主要用于关闭图片、公式等内容的显示，以减少文章字符数和降低PDF转word过程中出现的乱码，节省查重费用支出。应结合$\backslash$insertContents等系列命令使用。对于土豪此选项没有任何卵用。。。。。；盲审模式主要根据盲审文件格式要求，隐去了作者、导师、致谢等信息，更改发表论文的格式
- 增加\makeVerticalenWords命令，修改英文单词树立排放时的显示效果。
- 增加书脊中作者姓名显示。
- 增加对mathptmx包的引用，修改公式字体为New Time Roman。
- 新增\pubitem命令，用于显示学术成果。在盲审模式下该命令将会隐去作者信息。
- 新增$\backslash$sayThanks命令，用于致谢。在盲审模式下该命令指定的致谢内容将不被显示。
- 新增\insertContents、\insertFigure、\insertTable、\insertEquation系列指令，该指令用于自查重模式下选择性指定不显示的内容。}
- 新增\ncite、\nupcite、\nref命令，自查重模式下将不显示。
- 修复了官方v1.5版本中文献引用标注显示的字号和颜色。
- 目录中章节标题取消加粗显示。
- 打印中文信息的命令更改为\makeChineseInfo,在盲审模式下不显示中英文个人信息。
- 修改英文信息中下划线的长度。
