# README
## 项目介绍: 数据结构和算法 [`Data Structure & Algorithms`]

### 文档目录结构

```shell
(base) muyi@LyshmilyY:/Lyshmily.Y/GEE/408/DSA$ tree -L 1
.
├── .git
├── main
├── Markdown
└── PDF
```

> 1. `main` 是主文件, 是重新使用 `LaTeX` 排版的笔记, 目前只是开始, 计划一个月内完成
> 2. `Markdown` 是 `md` 文件, 是 `md` 类型的笔记, 后续会稍有更改
> 3. `PDF` 是 `md` 类型文件对应的 `PDF`, 计划使用 `Obsidian` 主题转化, 后续完成后上传

## main 文件夹

```shell
(base) muyi@LyshmilyY:/Lyshmily.Y/GEE/408/DSA/main$ tree -L 1
.
├── chap
├── config
├── figure
├── main.pdf
├── main.synctex.gz
├── main.tex
└── vavidbook.cls
```
> 1. `main.tex` 是主文件, `config\config.tex` 是设置文件, `vavidbook.cls` 是模版文件, 来源于 [LaTeX 工作室](https://www.latexstudio.net/index/details/index/mid/3485.html)
> 2. `chap` 是内容文件夹, `figure` 是图片文件夹
> 3. `main.pdf` 是编译好的 `pdf` 文件
> 4. `chap` 内部包含各个章节的内容, 在 `main.tex` 内采用 `input{../xx.tex}` 联合编译

## Others
1. 使用 `texlive 2023` 编译, 请确保安装了 `texlive` 环境
2. 关于 `vscode` 的配置, 一下是 `LaTeXWorkshop` 插件的配置, 请参考:[VSCode 中 LaTeX 环境配置](https://github.com/LyshmilyY/Math)
3. 代码框环境需要安装 `python` 包 `pygments`
4. `PDF` 阅读器推荐: `SumatraPDF`, 可以实现 `pdf` 和 `tex` 文件的联动, 也可以实现 `pdf` 文件的自动刷新, 下载地址: [SumatraPDF](https://www.sumatrapdfreader.org/download-free-pdf-viewer.html)
5. 可以在 `Win 10`, `Win11` 和 `Linux(Ubuntu)` 上编译, 但是在 `MacOS` 上没有测试过, 请自行测试
6. 模板说明文档: [vavidbook](https://github.com/Azure1210/VividBooK) 和 [elegantbook](https://github.com/ElegantLaTeX/ElegantBook), 有关于模板的一些选项和设置

## 字体安装 (Windows右键为所有用户安装)
1. 方正字体下载(提取码:njy9): [方正字体](https://pan.baidu.com/share/init?surl=BgbQM7LoinY7m8yeP25Y7Q)
2. 数学字体安装: `CMU-Typewrite-Font`: [CMU](https://fontmeme.com/fonts/cmu-typewriter-font/)
3. `Nerd Font` 字体安装: [NerdFOnt](https://www.nerdfonts.com/font-downloads)

## 打赏
如果您觉得本项目对您有所帮助, 欢迎打赏, 以激励作者继续努力, 生活不易, 鼠鼠叹气, 感谢支持!
<center class="half">
<img src="https://cdn.jsdelivr.net/gh/LyshmilyY/MuYiPicture/HomePage/%E6%94%AF%E4%BB%98%E5%AE%9D.jpg" width=150/>
<img src="https://cdn.jsdelivr.net/gh/LyshmilyY/MuYiPicture/HomePage/%E5%BE%AE%E4%BF%A1.png" width=150/>
</center>

## 推广
下面是一个考研的星球圈子(知识星球), 欢迎大家加入, 一起交流学习, 互帮互助, 一起进步!
![200](https://cdn.jsdelivr.net/gh/LyshmilyY/MuYiPicture/HomePage/%E6%98%9F%E7%90%83.png)
