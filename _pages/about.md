---
permalink: /
<<<<<<< HEAD
title: "Dr. Matthias Walle"
=======
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
>>>>>>> upstream/master
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<<<<<<< HEAD
=======
This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads!
>>>>>>> upstream/master

<br>

About me
======
<<<<<<< HEAD
I hold a B.Sc. and M.Sc. in Mechanical Engineering from the Technical University of Munich, where I specialized in computational biomechanics. I conducted my master's thesis at Harvard Medical School working with Dr. Ara Nazarian. In 2023, I completed my Ph.D. at ETH Zürich, focusing my research on developing CT-based imaging and computational methods to investigate bone health. My goal is to understand how mechanical stimuli contribute to bone health and to identify potential biomarkers that can monitor adverse changes in bone structure and strength caused by conditions like diabetes.
<br>
<br>
At the Bone Imaging Lab, my work explores how disease affects bone remodeling, as well as the effects of microgravity from space flight. I aim to leverage CT imaging and computer simulations to gain insight into the interplay between bone morphology, mechanical loading, and metabolic influences. My hope is that my research will uncover new ways to assess fracture risk and enable personalized approaches to improving skeletal health. I am committed to advancing the field of digital health by integrating biomechanics, computer modeling, and medical imaging to address critical challenges in bone health assessment and intervention.
<br>

My Research
======
## Bone Health in Diabetes
=======
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
>>>>>>> upstream/master

In a healthy adult, the body’s skeleton fully regenerates — or remodels — itself about every three to five years to maintain its strength. At the microscopic level, this process is orchestrated by cells, called osteocytes, which can sense and respond to local mechanical forces. Osteocytes direct bone-forming cells to regions where mechanical stimulations are high, and bone resorbing cells to areas where the stimulus is low. Through this process, excess bone tissue is removed, and new tissue is added where needed to maintain a metabolic balance.
<br>
<br>
Scientists have recently observed that diabetes may negatively impact our bone health and reduce bone strength. To unravel the underlying reasons, we developed novel methods that enable monitoring of local changes in the bone microstructure over time. Utilizing one of the world’s most powerful supercomputers at the Swiss National Supercomputing Centre (CSCS), this was possible at such high spatial resolution that cellular behaviour of the mechanobiological remodelling process could be studied.
<br>
<br>
There were, however, technological challenges that prevent the use of these techniques in clinical studies. Although these computations are fast on supercomputers, they were still too slow and cumbersome to run on computer systems available within the clinics. In FIDELIO, we worked with IBM to push bone imaging and computational methods for bone remodelling studies from bench (supercomputer) to the bedside (clinical computing) in the hospital environment. Ultimately, these precise diagnostic tools may be used to tailor medical treatment of diabetic patients to bone health individually.
<br>

<p align="center">
  <a href="http://www.youtube.com/watch?v=BO_79y9X6dA" title="Bone Health in Diabetes">
    <img src="http://img.youtube.com/vi/BO_79y9X6dA/0.jpg" alt="FIDELIO">
  </a>
</p>

<br>

<<<<<<< HEAD
## Microgravity and Space travel 
In our research, we explore bone recovery after extended periods without weight bearing load, such as during spaceflight. During these disuse experiences, bone loss occurs at an accelerated rate compared to normal bone turnover. We aim to further scientific understanding of the bone recovery process once normal loading resumes. Does bone regeneration occur? And if so, when, where and how much? We also question whether there may be a limited duration of opportunity for rebuilding bone at sites impacted by the lack of loading.
=======
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
>>>>>>> upstream/master
