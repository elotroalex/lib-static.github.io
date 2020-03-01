---
objectid: ctrl-shift # a short identifier with no spaces, weird characters, etc.
title: "CTRL+Shift: Writing Practice at the Dawn of the Digital Age" #short descriptive title identifying main purpose/use and possibly technology
objectlink: https://ctrl-shift.org/ # link to the main tool/project site
description: "CTRL-Shift is an online collection of audio recordings, transcripts, process visualizations, and data analyses broken out from interviews conducted with 11 prominent contemporary American poets from across the United States. " # short description providing contextual information about the uses, technologies, examples, tools, and/or category the recipe addresses 
category: Qualitative Data Analysis; Oral History; Screwing-Around # Choose from: (Digital Collection; Institutional Repository; Research Guide; Qualitative Data Analysis; Oral History; Library Website; Critical Edition; OER; screwing-around;) or, if you have to, add a new one
technologies: Jekyll; CSV; SVG; JavaScript; Bootstrap; Voyant; YouTube; # list the required technologies (broadly speaking) important to and/or necessary for your recipe; separate by semi-colon. Include the site generator first. Example: jekyll; bootstrap;svg;
people: # list all people responsible for code development
- name: Devin Becker
  github: dcnb # provide the name / github ids of the person and/or people developing this recipe; separate multiple people by semi-colon
  website: https://devinbecker.org # optional -- points to site for individual. 
- name: Corey Oglesby
  github: dcnb # provide the name / github ids of the person and/or people developing this recipe; separate multiple people by semi-colon
  website: https://devinbecker.org # optional -- points to site for individual. 
- name: Lauren Westerfield
  github: dcnb # provide the name / github ids of the person and/or people developing this recipe; separate multiple people by semi-colon
  website: https://devinbecker.org # optional -- points to site for individual. 
images: # try and keep it to no more than 2-3 images. 
- filelocation: /images/ohd1.png # filename for image, including url, or extension and folder of this repository (i.e. '/images/picture.jpg')
  caption: Colorful, SVG-based visualization for interviews based on coded subjects.  # caption for image
- filelocation: /images/ohd2.png # filename for image, including url, or extension and folder of this repository (i.e. '/images/picture.jpg')
  caption: Interactive transcript page generated for each transcript CSV.  # caption for image  
code: 
- title: Interactive SVG-based/color-coded transcript visualization
  url: https://github.com/uidaholib/oral-history-as-data/blob/master/_includes/js/visualization-js.html; https://github.com/uidaholib/oral-history-as-data/blob/master/_layouts/visualization.html # link to where people can view the piece of code, preferabbly in a GitHub repo
  description: Liquid based SVG layout and interactive javascript features combine to build the color-coded horizontal bars that allow users to investigate transcripts via coded subjects. # brief description of the piece of code and how it's used. 
- title: Searchable/Filterable Transcript
  url: https://github.com/uidaholib/oral-history-as-data/blob/master/_includes/js/transcript-js.html; https://github.com/uidaholib/oral-history-as-data/blob/master/_layouts/transcript.html # link to where people can view the piece of code, preferabbly in a GitHub repo
  description: Liquid based layout using transcript CSVs and interactive javascript features for creating the search- and filter-able transcripts, using URL parameters and Liquid # brief description of the piece of code and how it's used. 
---

### Context

Oral History as Data (OHD) was initially developed by Devin Becker for use in his CTRL-Shift web project in order to visualize the coded subjects for each interview. It has since been more fully developed and implemented into oral history collection sites for the Voices of Gay Rode and Idaho Queered projects and used as the analysis tool for a qualitative study of University of Idaho researchers. The development of the tool has has been supported by funding from the University of Idaho Library's [Center for Digital Inquiry and Learning](http://cdil.lib.uidaho.edu) and IMLS.

### How To 
