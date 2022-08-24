---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello, I am a Ph.D student in the [Computer Science and Engineering](https://www.cse.msu.edu/) at [Michigan State University](https://msu.edu/). I received B.S. in [Computer Science](https://cs.yonsei.ac.kr/cs/index.do) at [Yonsei University](https://www.yonsei.ac.kr/en_sc/index.jsp). I am interested in applying Natural Language Processing (NLP) techniques to analyze political framing in media.

Education
======
* **B.S.** in Computer Science, Yonsei University, 2013
* **Ph.D** in Computer Science and Engineering, Michigan State University, 2025 (expected)

Publications
======
* <ins>Michelle Youngjin Kim</ins>, Kristen Johnson, **"CLoSE: Contrastive Learning of Subframe
Embeddings for Political Bias Classification of News Media,"** *COLING (2022)*
* Woojeong Jin, Dongjin Choi, <ins>Youngjin Kim</ins>, and U Kang, **“Activity Prediction from Sensor Data using Convolutional Neural Networks and an Efficient Compression Method,”** *Journal of KIISE (2018)*

Projects
======
* [May 2018 - Sep. 2018] **Building Lidar-Based Human Detection Technology**
  * *Samsung Electronics Co., Ltd.* Seoul, Republic of Korea
    * Developed a Lidar-sensor environment for data acquisition.
    * Acquired and extracted data for the experiment, using a Lidar sensor.
* [Sep. 2017 - Apr. 2018] **Building Energy Optimization Technology**
  * *Samsung Electronics Co., Ltd.* Seoul, Republic of Korea
    * Developed a model for activity prediction by improving Deep Residual Net.
    * Acquired and processed data for the experiment, using temperature, sound and video data.
    * Managed the project website that displayed activity prediction in real time.
* [Sep. 2016 - May 2017] **Parallelization of Laminar-IR**
  * *Capstone project* at Yonsei University, Seoul, Republic of Korea
    * Implemented unfolding of stream graphs onto multicore platforms, using double buffering technique and barriers for synchronization.
* [Sep. 2016 - Dec. 2016] **Recommendation System for the Best-Fit Keyboard Layout**
  * *Class project* at Yonsei University, Seoul, Republic of Korea
    * Implemented a deep learning model that recommends a mobile keyboard layout.
    * Acquired log file data of mobile users.

Internships
======
* [Summer 2021] MedKit Korea
  * Seoul, Republic of Korea
    * Collect social media data on autism and build a machine learning model for fact-checking.

Teaching Experience
======
* [Spring 2018] **Teaching Assistant**, Introduction to Data Mining
  * Seoul National University, Seoul, Republic of Korea
* [Summer 2014] **Teaching Assistant**, After-school computer science program 
  * Geumok Elementary School, Seoul, Republic of Korea
* [2009-2011] **Teaching Assistant**, SAT academy 
  * IvyPlan, Seoul, Republic of Korea
* [2006-2007] **English Tutor**, Voluntary program 
  * Domestic violence shelter, Seoul, Republic of Korea

Skills
======
* **Programming Languages**: Python, C++, C, Java
* **Libraries**: TensorFlow (Advanced), NumPy, SciPy, Pandas

<!-- A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
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

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
