Academic-Report-Beamer-Template

学术答辩Beamer PPT模板(含有大纲导航、页码、学校logo等，以简洁清晰为主)

# 文档结构

- Main.tex : 主文件入口，对应生成main.pdf 文件
- /figures/ : 图片文件
- /files/ : 存放各章节的tex文件

# 使用方法

打开main.tex 文件，使用xelatex编译器进行编译；

生成完整的(带有正确引用编号)的文件，使用四次编译：xelatex->bibtex->xelatex->xelatex

技巧：解决编译速度很慢：假如正在写第二章，则可以在main.tex 中将其他章节先注释掉。