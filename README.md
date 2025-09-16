# JGS-Thesis
包含课程论文模板（以预科课程论文要求为基准），未来可能包括毕业论文模板。
## 编辑环境配置
> 主要是本地环境和线上环境。前者主推TeXLive+VS Code实现（IDE不推荐），后者强推Overleaf（格拉斯哥有买相关资源）

### 本地LaTeX环境配置（TeX Live+VS code）
- 主要参考资源
  - 【LaTeX 环境配置 (macOS). Strik0r. LaTeX 教程.】https://www.bilibili.com/video/BV1xCNfejEMv?vd_source=03933c815d0479ac0dc2b0f082cd8fb8
  - 【知乎--VS Code 配置 LaTeX 时如何实现源代码与目标文件的分离】https://zhuanlan.zhihu.com/p/24397052814
- 额外说明
  - Thesis文件夹即为本地配置时推荐文件设置，src用于储存LaTeX源码（参考文献也保存于此，推荐使用Zotero），pic用于储存所用图片，out保存输出文件（编译的PDF即保存于此）。
  - 关于Json文件，应该是修改了3处，有一处不记得了，但无伤大雅。
    - 第一处：修改了”默认保存即编译“的设置
      ```Json
      "latex-workshop.latex.autoBuild.run": "never"
      ```
    - 第二处：编译默认设置由“上次使用”改为默认“xelatex -> biber -> xelatex*2”
      > LaTeX模板即是使用的该流程xelatex -> biber -> xelatex*2
      ```Json
      "latex-workshop.latex.recipe.default": "xelatex -> biber -> xelatex*2"
      ```

### Overleaf

## 关于课程论文模版部分说明

# 硕士论文
[硕士论文模板Github仓库地址]()
待更新
