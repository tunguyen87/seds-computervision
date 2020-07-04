---
permalink: /
title: "CSCI 585 Computer Vision"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Fall 2020


Instructor: Prof. Nguyen Anh Tu
======
- **Classtime:** TBA
- **Class location:** Online
- **Office hours:** TBA
- **Email:** tu.nguyen@nu.edu.kz

Course Description
======
This course is a one-semester course intended for M.S. students in Computer Science and Data Science graduate programs. It enhances the student’s knowledge in computer vision concepts and approaches such as image formation, camera imaging geometry, feature detection and matching, stereo, image classification, scene understanding, and deep learning. In class, we will develop the intuitions and mathematics of the vision approaches. We will expose students to a number of real-world applications that are important to our daily lives. To further differentiate between theory and practice, we will guide students through a series of research projects such that they will have chance to implement cutting-edge computer vision algorithms. Students will also gain experience through research papers, with an emphasis on proper computer vision practices with appropriate applications.

**Due to COVID-19, this fall we will be conducting the course solely online... there will be no "in person" meetings. The online materials which we have created are the primary content for the course, and your primary interactions with the instuctor or TA will be via Piazza.**

Course aims
======
1. to expose students to various computer vision concepts and approaches such as image formation, feature detection and matching, stereo, motion estimation and tracking, image classification, scene understanding, and deep learning
1. to familiarize students with state-of-the-art computer vision techniques
1. to present students the various ways to further improve the performance of state-of-the-art computer vision techniques

Course learning outcomes 
======
By the end of the course the student will be expected to be able:
1.	to understand and explain concepts related to computer vision such as image formation, feature detection and matching, stereo, image classification, scene understanding, and deep learning.
1.	to be able to recognize and describe both the theoretical and practical aspects of computing with images. 
1.	to be able to successfully implement several interesting and cutting-edge vision algorithms which are widely used in real-world applications such as image retrieval, image captioning, face recognition, scene categorization, and activity recognition. 
1.	to understand the strengths and weaknesses of various computer vision approaches and apply them to new scenarios.
1.	to be able to read and understand scholarly articles in computer vision and come up with new ideas to solve the same problem, which may lead students to write their research paper in computer vision. 


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
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
