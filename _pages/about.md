---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am a Ph.D. candidate in the Knowledge Engineering Group (KEG), Department of Computer Science and Technology, Tsinghua University (Sep 2023 – Jun 2026, expected), advised by Prof. Juanzi Li. 
I received in Computer Science and Technology from Beijing University of Posts and Telecommunications.

My research sits at the intersection of **large language models (LLMs)**, **knowledge engineering**, and **reasoning**. 
I have worked as a research intern at Zhipu.AI on building and post-training LLMs, and I was a visiting scholar at the NExT++ Research Centre, National University of Singapore (Mar 2025 – Sep 2025) hosted by Prof. Tat-Seng Chua. 
Earlier, I spent time in KEG-Tsinghua, Qiyuan Lab, and BUPT on topics spanning knowledge graphs, graph learning, and evolutionary game theory on networks.

You can find my publications on **[Google Scholar](https://scholar.google.com/citations?user=B4LmHSUAAAAJ)**.


## Research directions

I am dedicated to exploring how to (1) establish the science of large language models (Science of LLMs); and (2) enable LLMs with knowledge and reasoning skills to solve scientific tasks (LLMs for Science).

**1) Science of LLMs**  
I aim to build a *systematic science* of LLMs that connects internal model mechanics to observable behaviors.

- **Microscopic perspective:** Probe how hidden states, neurons, and sparse features arise and correspond to specific model behaviors; develop tools (e.g., sparse autoencoders) to interpret and **steer** model internals.  
- **Macroscopic perspective:** Study how architectural and training choices (data, objectives, RL, distillation) shape emergent capabilities such as implicit reasoning and robustness.

**2) LLMs for Science**  
I explore how LLMs can *assist and automate* the scientific workflow.

- **Knowledge-intensive QA and retrieval:** Combine parametric and retrieved knowledge for fact-seeking, multi-hop reasoning, and conflict resolution.  
- **Agentic research assistants:** Build multi-agent systems and evaluation protocols for end-to-end scientific inquiry (problem formulation → evidence gathering → reasoning → reporting).  
- **Learning from real-world feedback:** Use verifiable signals and reward models to help LLMs improve their research skills and factual reliability over time.


## Selected publications



<!-- \begin{enumerate}[itemsep=-1pt,topsep=0pt,leftmargin=20pt,label={[\arabic*]},ref=\arabic*]
    \item\label{seakr} \textbf{SeaKR: Self-aware Knowledge Retrieval for Adaptive Retrieval Augmented Generation} \\ 
        \textcolor[RGB]{100,0,0}{\textbf{\textit{Zijun Yao$^*$}}}, Weijian Qi$^*$, Liangming Pan, Shulin Cao, Linmei Hu, Weichuan Liu, Lei Hou, Juanzi Li. In \textit{ACL}, 2025. \textcolor[RGB]{160,0,0}{\textit{\textbf{Oral Presentation (2.9\% in Submission)}}}
    \item\label{viskop} \textbf{VisKoP: Visual Knowledge oriented Programming for Interactive Knowledge Base Question Answering} \\
        \textcolor[RGB]{100,0,0}{\textbf{\textit{Zijun Yao$^*$}}}, Yuanyong Chen$^*$, Xin Lv, Shulin Cao, Amy Xin, Jifan Yu, Hailong Jin, Jianjun Xu, Peng Zhang, Lei Hou, Juanzi Li. In \textit{Demo of ACL}, 2023. \textcolor[RGB]{160,0,0}{\textit{\textbf{Best Demo Award}}}
    \item\label{korc}  \textbf{KoRC: Knowledge oriented Reading Comprehension Benchmark for Deep Text Understanding} \\ 
        \textcolor[RGB]{100,0,0}{\textbf{\textit{Zijun Yao$^*$}}}, Yantao Liu$^*$, Xin Lv, Shulin Cao, Jifan Yu, Lei Hou, Juanzi Li. In \textit{Findings of ACL}, 2023.
    \item\label{knot} \textbf{Untangle the KNOT: Interweaving Conflicting Knowledge and Reasoning Skills in Large Language Models} \\ 
        Yantao Liu$^*$, \textcolor[RGB]{100,0,0}{\textbf{\textit{Zijun Yao$^*$}}}, Xin Lv, Yuchen Fan, Shulin Cao, Jifan Yu, Lei Hou, Juanzi Li. In \textit{LREC-COLING}, 2024.
    \item\label{rmbench} \textbf{RM-Bench: Benchmarking Reward Models of Language Models with Subtlety and Style} \\
        Yantao Liu, \textcolor[RGB]{100,0,0}{\textbf{\textit{Zijun Yao}}}, Rui Min, Yixin Cao, Lei Hou, Juanzi Li. In \textit{ICLR}, 2025. \textcolor[RGB]{160,0,0}{\textit{\textbf{Oral Presentation (1.2\% in Submission)}}}
    \item\label{transferable} \textbf{Transferable and Efficient Non-Factual Content Detection via Probe Training with Offline Consistency Checking} \\
        Xiaokang Zhang$^*$, \textcolor[RGB]{100,0,0}{\textbf{\textit{Zijun Yao$^*$}}}, Jing Zhang, Kaifeng Yun, Jifan Yu, Juanzi Li, Jie Tang. In \textit{ACL}, 2024.
    \item\label{lingualens} \textbf{LinguaLens: Towards Interpreting Linguistic Mechanisms of Large Language Models via Sparse Auto-Encoder} \\
        Yi Jing, \textcolor[RGB]{100,0,0}{\textbf{\textit{Zijun Yao}}}, Lingxu Ran, Hongzhu Guo, Xiaozhi Wang, Lei Hou, Juanzi Li. In \textit{EMNLP}, 2025.
    \item\label{implicit} \textbf{How does Transformer Learn Implicit Reasoning?} \\
        Jiaran Ye$^*$, \textcolor[RGB]{100,0,0}{\textbf{\textit{Zijun Yao$^*$}}}, Zhidian Huang, Liangming Pan, Jinxin Liu, Yushi Bai, Amy Xin, Liu Weichuan, Xiaoyin Che, Lei Hou, Juanzi Li. In \textit{NeurIPS} 2025. \textcolor[RGB]{160,0,0}{\textit{\textbf{Spotlight (3.5\% in Submission)}}}
    \item \textbf{Interpretable and Low-Resource Entity Matching via Decoupling Feature Learning from Decision Making} \\
        \textcolor[RGB]{100,0,0}{\textbf{\textit{Zijun Yao}}}, Chengjiang Li, Tiansi Dong, Xin Lv, Jifan Yu, Lei Hou, Juanzi Li, Yichi Zhang, Zelin Dai. In \textit{ACL-IJCNLP}, 2021.
\end{enumerate} -->

1. **SeaKR: Self-aware Knowledge Retrieval for Adaptive Retrieval Augmented Generation**  
   **Zijun Yao**\*, Weijian Qi\*, Liangming Pan, Shulin Cao, Linmei Hu, Weichuan Liu, Lei Hou, Juanzi Li  
   *ACL, 2025.* **Oral Presentation (2.9% in Submission)**

2. **VisKoP: Visual Knowledge oriented Programming for Interactive Knowledge Base Question Answering**  
   **Zijun Yao**\*, Yuanyong Chen\*, Xin Lv, Shulin Cao, Amy Xin, Jifan Yu, Hailong Jin, Jianjun Xu, Peng Zhang, Lei Hou, Juanzi Li  
   *Demo of ACL, 2023.* **Best Demo Award**

3. **KoRC: Knowledge oriented Reading Comprehension Benchmark for Deep Text Understanding**  
   **Zijun Yao**\*, Yantao Liu\*, Xin Lv, Shulin Cao, Jifan Yu, Lei Hou, Juanzi Li  
   *Findings of ACL, 2023.*

4. **Untangle the KNOT: Interweaving Conflicting Knowledge and Reasoning Skills in Large Language Models**  
   Yantao Liu\*, **Zijun Yao**\*, Xin Lv, Yuchen Fan, Shulin Cao, Jifan Yu, Lei Hou, Juanzi Li  
   *LREC-COLING, 2024.*

5. **RM-Bench: Benchmarking Reward Models of Language Models with Subtlety and Style**  
   Yantao Liu, **Zijun Yao**, Rui Min, Yixin Cao, Lei Hou, Juanzi Li  
   *ICLR, 2025.* **Oral Presentation (1.2% in Submission)**

6. **Transferable and Efficient Non-Factual Content Detection via Probe Training with Offline Consistency Checking**  
   Xiaokang Zhang\*, **Zijun Yao**\*, Jing Zhang, Kaifeng Yun, Jifan Yu, Juanzi Li, Jie Tang  
   *ACL, 2024.*

7. **LinguaLens: Towards Interpreting Linguistic Mechanisms of Large Language Models via Sparse Auto-Encoder**  
   Yi Jing, **Zijun Yao**, Lingxu Ran, Hongzhu Guo, Xiaozhi Wang, Lei Hou, Juanzi Li  
   *EMNLP, 2025.*

8. **How does Transformer Learn Implicit Reasoning?**  
   Jiaran Ye\*, **Zijun Yao**\*, Zhidian Huang, Liangming Pan, Jinxin Liu, Yushi Bai, Amy Xin, Liu Weichuan, Xiaoyin Che, Lei Hou, Juanzi Li  
   *NeurIPS, 2025.* **Spotlight (3.5% in Submission)**

9. **Interpretable and Low-Resource Entity Matching via Decoupling Feature Learning from Decision Making**  
   **Zijun Yao**, Chengjiang Li, Tiansi Dong, Xin Lv, Jifan Yu, Lei Hou, Juanzi Li, Yichi Zhang, Zelin Dai  
   *ACL-IJCNLP, 2021.*

<sup>\* Equal contribution</sup>





*Last updated: Nov 2025.*



<!-- This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

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
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
