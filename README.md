# 地理学野外实习报告LaTex模板
该LaTex模板基于普通地质野外实习报告格式模板改编而成，***具体格式与Word格式有细微区别***
请使用XeLaTex编译器进行编译，模板格式具体信息可以在example.tex和example.pdf中查看。
[下载地址，持续更新](https://github.com/Plutoset/fieldpractice-geo)

### 2021-5-23 update
- 字体库更新为思源宋体和思源黑体
- 参考文献改用biber编译，采用GB/T 7714-2015标准
- 目录页参考实现文献左对齐

## 模板使用注意事项
- 请下载并且确保当前编译的.tex的文件夹路径下包括fieldpractice-geo.cls文件，以及figures文件夹，该文件夹包括院徽.png
- 请选择fieldpractice-geo作为文档类型，即开头语句为`\documentclass{fieldpractice-geo}`
- 请在`\begin{document}`开始前填写你的实习报告具体信息，具体案例可以查看example.tex文件。
- 请在`\begin{document}`后添加`\maketitle`一行。
- 若实习报告涉及参考文献，请在导言区添加`\addbibresource{你使用的bib文件名字带扩展名.bib}`，并且在正文结束后，`\end{document}`之前添加`\printbibliography[heading=bibintoc,title=参考文献]`一行。
- 常见的LaTex语句(插入图片，表格，公式和文内引用)已在example.tex中给出。
- 已加载的宏包在example.tex中给出，使用模板时不需要再次引用。
