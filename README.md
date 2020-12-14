# paper-template

一个支持中英文的论文模板。

## 使用方法

tex文件夹有两个文件: paper.tex和ref.bib,分别是tex源码和参考文献。

编译步骤:

```
xelatex paper.tex

bibtex paper.aux

xelatex paper.tex
```

最后生成paper.pdf

## 最终效果

![avatar](intro.png)