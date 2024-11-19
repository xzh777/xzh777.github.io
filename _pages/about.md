---
permalink: /
title: "科研概况"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
刘翼鹏是电子科技大学信息与通信工程学院教授，国家级青年人才。他主要从事张量计算为基础的图像处理、机器学习、智能医疗、无线感知、数字优化研究工作。

他发表国际期刊和会议论文100余篇，其中30余篇论文发表在JSTSP、TSP、TIP、TMI、TPAMI、TKDE、TNNLS等IEEE期刊。撰写张量信号处理方向英文专著2本和编著1本。他的论文Tensor Regression发表在TNNLS等IEEE期刊《FnT in Machine Learning》，是其创刊16年唯一的第一/通讯作者来自中国单位的工作，他分别于2012年和2014年获得比利时弗拉芒政府海外主持支持奖2项，2020年获首届川渝科技学术大会优秀论文一等奖，2022年获国际多媒体信号处理研讨会(MMSP 2022)最佳演示论文奖(Best Demo Award)。2022年至今连续入选斯坦福大学评选的全球前2%顶尖科学家名单。

他是IEEE高级会员，中国电子学会高级会员，中国图象图形学学会高级会员，中国图象图形学学会青年工作委员会委员，中国计算机学会多媒体技术专委会委员。他担任国际期刊IEEE Signal Processing Letters的编委,Signal Processing: Image Communication (EIsevier) 的首席客座编委，系统工程与电子技术(英文版)客座编委;多次担任行业权威期刊和会议的组织、编辑和审稿工作。

他应邀在IEEE电路与系统学会旗舰会议ISCAS 2024、国际人工智能协会旗舰会议IJCAI 2022、IEEE多媒体领域旗舰会议ICME 2022、IEEE信 号处理学会旗舰会议ICIP 2020、IEEE智能计算学会旗舰会议SSCI 2020等10余个国际会议做3小时讲习班报告(tutorial) 。他是亚太信号与信息处理学会杰出讲座人(APSIPA Distinguished Lecturer for 2022-2023)。

他主持国家自然科学基金2项、科技部重点研发计划(国际合作)课题1项、四川省国际/地区科研合作项目1项、华为技术前沿技术研究项目1项、校医I交叉联合基金1项目;主研欧盟研究理事会高级项目1项、比利时法兰德斯自然科学基金1项、中国国家自然科学基金2项、四川省科技计划项目3项目。


A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
