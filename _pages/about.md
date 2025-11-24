---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

👋 欢迎来到我的个人主页
大家好！我是 XXX，来自 江西理工大学信息安全专业（2025级）。
这是我在大学里的第一个个人主页，用来记录我的学习、成长和项目。

我对 网络安全、编程、开源技术 很感兴趣，希望未来能够成为一名网络安全工程师或开发者。

🧭 关于我（About Me）
🎓 信息安全专业大一新生
💻 正在学习：C 语言、Git/GitHub、网络安全基础
🌱 兴趣领域：网络安全、Python、小型项目
✨ 目标：完成 10+ 小项目、参加一次 CTF、学好算法和编程基础
📘 我正在学习的课程
C 语言程序设计
计算机基础与网络基础
网络空间安全导论
高等数学
大学英语
🚀 我正在学习的技能
基础技能
Git 与 GitHub 基本操作
Markdown 写作
C 语言基础语法
Linux 基本命令（ls, cd, pwd, cat 等）
想要学习的技能
Python 编程
Web 安全入门
Wireshark 抓包与数据分析
简单 CTF 的练习（Web/密码学/Misc）
🧪 最近完成的学习成果
完成了 我的第一个 GitHub 仓库
编写了 第一份 Markdown 文件
使用 Git 实现了 add → commit → push
完成一次简单的 Wireshark 抓包实验
写了一个 学生管理系统（C语言课程作业）
💡 我的项目展示（Projects）
以下项目为课程作业或兴趣项目，大一阶段不要求复杂项目。

📘 学生管理系统（C语言）
一个可以添加、删除、修改学生信息的小程序，使用 TXT 文件存储数据。
👉 GitHub 项目链接：（你的链接）

🌐 我的个人主页（GitHub Pages）
使用 GitHub Pages + Markdown 创建的静态网站，这是我的第一个网站。
👉 GitHub 项目链接：（你的链接）

🕸 Python 小爬虫（可选）
一个用于爬取天气/新闻的小脚本，用来练习 Python。
👉 GitHub 项目链接：（你的链接）

🎯 我的大学四年计划
学好 C 语言、数据结构、计算机网络等基础课
至少完成 10 个小项目
参加一次 CTF 或编程比赛
进入实验室/兴趣小组（如网安协会）
学会一项长期兴趣爱好（摄影、跑步、音乐等）
🎮 兴趣爱好
🎬 喜欢的电影：星际穿越、模仿游戏
🎮 喜欢的游戏：Minecraft / 王者荣耀
🏃 爱好：跑步、健身、拍照
📚 喜欢学习新技术与动手制作小项目
📬 联系方式
GitHub: https://github.com/yourname
学校邮箱：yourname@edu.com
CSDN / Bilibili（可选）
❗ 为保护个人隐私，不建议公开手机号和微信。

感谢你访问我的主页！
如果你也对编程和网络安全感兴趣，欢迎交流与学习 🙌

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
