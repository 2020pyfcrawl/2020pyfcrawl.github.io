---
permalink: /
title: #"Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Bio
<!-- * Basic config options: _config.yml
* Top navigation bar config: _data/navigation.yml
* Single pages: _pages/
* Collections of pages are .md or .html files in:
  * _publications/
  * _portfolio/
  * _posts/
  * _teaching/
  * _talks/
* Footer: _includes/footer.html
* Static files (like PDFs): /files/
* Profile image (can set in _config.yml): images/profile.png -->

I am a research intern in Carnegie Mellon University working with [Prof. Steven Wu](https://zstevenwu.com/), focusing on AI safety. Specifically, I am deeply interested in **identifying the vulnerabilities in machine learning (ML) models** and **developing practical safety solutions for ML applications**. I am also interested in advancing research on large language models (LLMs) and vision-language models (VLMs). Prior to this, I completed my M.S. in Information Security at Carnegie Mellon University, where I worked with with Prof. Steven Wu. I have obtained B.E. degree in Computer Science and Technology from Zhejiang University under the supervision of [Prof. Kai Bu](https://list.zju.edu.cn/kaibu/) on network security (in detail, [path validation](https://dl.acm.org/doi/abs/10.1145/2619239.2626323)).

**Interested topics:** AI Safety, ML privacy, LLM, VLM, etc.

**I am actively seeking PhD opportunities from 2026!**

## Publications
* Xiaoyu Wu, **Yifei Pang**, Terrance Liu, Steven Wu. "Breaking the Gold Standard: Extracting Forgotten Data under Exact Unlearning in Large Language Models" Arxiv. [[paper](https://arxiv.org/abs/2505.24379)]
* Xiaoyu Wu, **Yifei Pang**, Terrance Liu, Steven Wu. "Winning the MIDST Challenge: New Membership Inference Attacks on Diffusion Models for Tabular Data Synthesis" Theory and Practice of Differential Privacy 2025. [[paper](https://arxiv.org/abs/2503.12008), [code](https://github.com/Nicholas0228/Tartan_Federer_MIDST/tree/main), [poster](https://drive.google.com/file/d/1zzY-Ce7DSTSllyS4wv0gx05wQ9gZ69df/view?usp=sharing)]
* **Yifei Pang**, Sreenidhi Ganachari, Yuan Yuan, Steven Wu, Xiaojing Dong, Jin Xu, Zhenyu Yan. "A New Approach to Generate Individual Level Data of Walled Garden Platforms: Linear Programming Reconstruction" NeurIPS 2024 Workshop on Behavioral ML. [[paper](https://openreview.net/pdf?id=VVYnNKUzdH), [code](https://github.com/2020pyfcrawl/Linear_Programming_Reconstruction), [poster](https://drive.google.com/file/d/1QByWC_tbuQU_70IyFfu-4WsRVuWiSF5j/view?usp=sharing)]
* He, Anxiao, Kai Bu, Jiongrui Huang, **Yifei Pang**, Qianping Gu, and Kui Ren. "SwiftParade: Anti-burst Multipath Validation." IEEE Transactions on Dependable and Secure Computing (2023) [[paper](https://ieeexplore.ieee.org/document/10251632)]
* **Yifei Pang**, Anxiao He, Wenjie Hou, Yunyi Teng, Kai Bu, Qianping Gu, and Kui Ren. "SwiftOracle: Orthogonality-driven Private Multipath Validation", submitted to IEEE Transactions on Dependable and Secure Computing in Mar. 2025.

## Award
* Information Networking Institute Outstanding Student Services Award - Research Assistant (2025)

## Teaching
* Fall 2024: Teaching Assistant for 14740

## Others

I watch and play soccer, and am a fan of Liverpool Football Club (L.F.C.).


## to be continued


<!-- This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

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
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
