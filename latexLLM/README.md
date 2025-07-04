# latexLLM 使用说明

本文件夹中的 prompt 依赖本地 LaTeX 环境进行编译和渲染。

## 使用前提

- 需要在本地安装并正确配置 LaTeX（如 TeX Live、MiKTeX 等发行版）。
- 建议配置好 `pdflatex`、`xelatex` 等常用编译器，并确保其已添加到系统环境变量。

## 主要内容

- `The LaTeX testfile for vscode/`：包含多个 LaTeX 示例文件及相关资源，可用于测试和演示。
- 典型文件如：`business.tex`、`standard.tex`、`The testfile for vscode.tex`。
- `Figures/` 文件夹下包含示例图片和 PDF 图形。

## 使用方法

1. 确保本地已安装 LaTeX，并可在命令行中直接调用编译命令（如 `pdflatex business.tex`）。
2. 进入相应子文件夹，使用命令行或集成开发环境（如 VS Code 的 LaTeX Workshop 插件）编译 `.tex` 文件。
3. 编译后可在同目录下获得对应的 PDF 文件。

## 注意事项

- 若未正确安装 LaTeX，无法正常使用本文件夹中的 prompt。
- 推荐使用 VS Code 配合 LaTeX Workshop 插件获得更好的编辑和预览体验。

---

如有问题请查阅 LaTeX 官方文档或相关发行版的安装说明。