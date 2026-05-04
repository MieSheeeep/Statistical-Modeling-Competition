# 统计建模论文 LaTeX 项目

当前唯一编译入口是 `main.tex`。旧版 `main.tex` 已丢弃，现在的 `main.tex` 来自 revise 版本，正文内容已经按章节拆分到 `chapters/`。

编译命令：

```powershell
xelatex -interaction=nonstopmode -halt-on-error main.tex
xelatex -interaction=nonstopmode -halt-on-error main.tex
```

后续修改正文时，优先编辑 `chapters/` 下对应章节文件。
