<!-- ---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

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

permalink: /
# 🚀 Amirhossein Nazeri  

📍 **Greenville, SC, USA**  
📧 [anazeri@clemson.edu](mailto:anazeri@clemson.edu)  
🔗 [GitHub](https://github.com/amirhnazerii) • [Google Scholar](https://scholar.google.com/citations?user=2V7M53cAAAAJ&hl=en) • [LinkedIn](https://www.linkedin.com/in/amir-h-nazeri/) • [Medium](https://medium.com/@amirhossein20n) • [YouTube](https://www.youtube.com/@amirhnazerii)  

---

## 👨‍💻 About Me  
I am an **AI Engineer and Researcher** passionate about developing cutting-edge AI solutions. My work spans from **AI-powered technical assistants** to **secure AI-driven object detection**. I thrive at the intersection of **machine learning, large language models (LLMs), and AI security**, optimizing workflows to drive efficiency and innovation.

---

## 💼 Work Experience  

### **Associate AI Engineer** - *JTEKT North America* (2024 - Present)  
🚀 Leading AI-driven initiatives in an **Azure-based** environment:  
- Developed an AI-powered **technical assistant** to **automate knowledge retrieval and report generation**.  
- **Doubled** report generation speed while enhancing coherence and reference validation.  
- Optimized **RAG pipelines**, LLM fine-tuning, and vector database integration.  
- Tech Stack: `Azure`, `GPT-4o`, `LangChain`, `LanceDB`, `BeautifulSoup`.  

### **Data Scientist** - *DataRoo LLC* (2023 - 2024)  
📊 Spearheaded an **AI-driven medical coding & billing** system:  
- Designed **prompt engineering & fine-tuning** strategies for accurate medical code generation.  
- Integrated with **Azure OpenAI** to enhance medical document processing.  
- Achieved **30% higher accuracy** and **40% lower costs** in EMR assessment compared to GPT-4o.  

### **Graduate Research Assistant** - *Clemson University* (2022 - Present)  
🔍 AI **security research** on state-of-the-art object detectors (**DETR, Faster R-CNN**):  
- Developed **statistical anomaly detection** to secure object recognition.  
- Experimented with adversarial attacks in **autonomous driving** datasets.  
- Tools: `PyTorch`, `CUDA`, `Bash Scripting`, `GitHub`.  

---

## 🎓 Education  
🎓 **Ph.D. in Automotive Engineering (AI-Focused)**, *Clemson University* *(GPA: 3.9/4, Expected July 2025)*  
🎓 **M.Sc. in Electrical & Computer Engineering**, *Texas Tech University* *(GPA: 3.8/4)*  

---

## 📜 Selected Research  
- **[Evaluating the Adversarial Robustness of Detection Transformers](https://arxiv.org/abs/2412.18718)**  
- **[Exploration of TPU Architectures for Optimized Transformer in Drainage Detection](https://ieeexplore.ieee.org/abstract/document/10826077)**  
- **[Entanglement Learning: An Information-Theoretic Framework for Adaptive Computer Vision](https://www.mdpi.com/1996-1073/17/4/868)**  

---

## 🛠️ Skills  
🔹 **Machine Learning & AI:** LLMs, Computer Vision, Adversarial AI, Deep Learning  
🔹 **Tech Stack:** Python, PyTorch, TensorFlow, LangChain, Azure, OpenAI API  
🔹 **Data Processing:** SQL, Pandas, NumPy, BeautifulSoup, RAG Pipelines  

---

🚀 **Open to Collaborations & AI Research Opportunities!** Let’s connect!  

📩 [Email Me](mailto:anazeri@clemson.edu) | 🌎 [Portfolio](https://github.com/amirhnazerii)
