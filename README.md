# WHU 学位论文 LaTeX 模板（本地 Overleaf 版）

本仓库基于 [whutug/whu-thesis](https://github.com/whutug/whu-thesis) ，针对本地部署的 Overleaf（Overleaf Server/Community Edition）做了适配与优化，便于直接在本地 Overleaf 中编译与协作。

## 使用方法
1. 在本地 Overleaf 新建项目并导入本仓库（或直接上传压缩包）。
2. 将 `demo.tex` 设为主文件。
3. 选择编译器为 XeLaTeX（或 latexmk + XeLaTeX），参考文献使用 BibTeX。
4. 修改 `demo.tex` 中 `\whusetup` 的题目信息与个人信息；正文在 `pages/` 下按章节编辑。
5. 参考文献文件位于 `ref/`，按需替换为你的 `.bib` 文件。

## 本地命令行编译（可选）
```bash
latexmk -xelatex demo.tex
```

## 致谢
- 感谢 [whutug/whu-thesis](https://github.com/whutug/whu-thesis) 提供的优秀论文模板与持续维护。
