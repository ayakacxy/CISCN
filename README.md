
# 全国大学生信息安全竞赛作品赛 LaTeX 参考模板

这是本人和科大同学参加 2024 年第十七届全国大学生信息安全竞赛作品赛的作品报告的 $`LaTeX`$ 源代码，由本人按照全国大学生信息安全竞赛作品报告的官方 Word 版本格式自主修改。

## 文件结构

```text
├── main.tex            # 主 LaTeX 文件
├── figures/            # 图片文件夹
│   ├── figure1.png
│   └── ...
├── references.bib      # 参考文献
└── README.md           # 此说明文件
```

## 编译方法

1. 使用以下命令编译文档：
   ```bash
   xelatex main.tex
   bibtex main
   xelatex main.tex
   xelatex main.tex
   ```
   或者使用编译工具如 TeXStudio、TeXworks 或 Overleaf 等进行编译。

2. 在编译成功后，将生成的 PDF 文件保存为 `main.pdf`。

## 源代码地址

本项目**星鉴——支持多域多模型的机器生成文本检测系统**的源代码已托管在 GitHub上，欢迎访问：

- GitHub 地址：[https://github.com/](https://github.com/ayakacxy/StarDetection)

## 获奖情况

- 第十七届全国大学生信息安全竞赛作品赛一等奖
- 第十七届全国大学生信息安全竞赛作品赛最具创新创业价值奖
- 2024年中国网络安全创新创业大赛总决赛大学生创新创业作品赛最具投资价值奖第一名
![image](figures/image.png)


## 贡献和免责声明

如果你发现任何错误或问题，欢迎提出问题或提供贡献。你可以通过电子邮件联系我：cxy20031013@mail.ustc.edu.cn。

同时本项目并非官方模板，仅作为分享和参考，并不确保所有格式准确无误。如需使用本项目，请仔细对比官方模板并检查格式。


