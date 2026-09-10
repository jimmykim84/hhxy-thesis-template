# 怀化学院本科毕业设计（论文）LaTeX 模版

适用于怀化学院本科毕业设计（论文）排版的 LaTeX 模版，基于 `hhxythesis.cls` 文档类，符合学校格式与 GB/T 7714-2005 参考文献规范。

## 目录结构

```
.
├── main.tex                  主文件（编译入口）
├── hhxythesis.cls            怀化学院论文文档类
├── gbt7714-2005.bst          参考文献样式（GB/T 7714-2005）
├── refs.bib                  参考文献数据库（BibTeX）
├── 毕业论文模版使用说明.md     模版使用说明（必读）
├── chapters/                 各章节源文件
│   ├── 00-abstract.tex       中英文摘要
│   ├── 01-preface.tex        绪论
│   ├── 02-miniprogram.tex    相关工作 / 小程序
│   ├── 03-requirement.tex    需求分析
│   ├── 04-technology.tex     技术路线
│   ├── 05-implement.tex      系统实现
│   ├── 06-test.tex           系统测试
│   ├── 07-summary.tex        总结与展望
│   ├── 08-reference.tex      参考文献（引用入口）
│   ├── 09-acknowledgement.tex 致谢
│   └── 10-appendix.tex       附录
└── figures/                  图片与图表
    ├── hhu_logo_trim.jpg     校徽
    ├── fig-architecture.pdf   架构图
    ├── fig-flowchart.pdf      流程图
    ├── fig-homepage.pdf       首页截图
    ├── fig-mvvm.pdf           MVVM 示意图
    └── fig-perf.pdf           性能图
```

## 使用方式

1. 阅读 **`毕业论文模版使用说明.md`** 了解完整配置与填写步骤。
2. 在 `chapters/` 各章节文件中撰写内容，在 `refs.bib` 中维护参考文献。
3. 使用 **XeLaTeX** 引擎编译（推荐 TeX Live 或 Overleaf），按模版说明顺序生成正文与参考文献。
4. 编译产物 `main.pdf` 不纳入版本库，请本地生成。

## 说明

- 本模板为非官方模板，仅参照本校学位论文格式制作，仅供排版参考；不代表学校官方要求，也不代表示例论文内容正确。如与学校最新官方文件冲突，以学校官方文件为准。
- 参考文献样式采用 `gbt7714-2005.bst`，符合 GB/T 7714-2005 规范。

## License

见 `LICENSE`（MIT）。
