---
layout: master
include: workshop

# location and address
location: Copenhagen, DTU campus
address: <a href="https://goo.gl/maps/7pGSSdzNVUKjbXrb8">Akademivej, 2800 Kongens Lyngby, building 358</a>, room 914
city: Copenhagen

# date and time
time: "9:00 - 17:00"    
dates: "March 17-19, 2020"   

# Add link to registration form here and specify when the registration opens and whether it is closed
registration_form: https://indico.neic.no/event/117/
registration_open_date: February 10, 2020
registration_is_closed: true

# names of instructors and helpers
instructors:
 - Radovan Bast
 - Max R. Eckardt
 - Emiliano Molinaro
 - Thor Wikfeldt
helpers: 
 - David Gray Marchant
 - Rasmus Munk
 - Elise Otterlei Brenne

# contact email address
contact: support@coderefinery.org

# normally no need to modify this
goals:
    The aim of this course is to demonstrate to and familiarize
    the workshop participants with best practices and tools in modern research
    software development. The main focus is on professional tools
    for efficiently writing and maintaining research software.
    Since most research code is developed in a collaborative
    setting, we will discuss tools and workflows which facilitate
    this process. Most of the content is also relevant to
    a single researcher.

# software that should be installed for the workshop (update if needed)
software:
  - title: Bash
    url: https://coderefinery.github.io/installation/bash/
  - title: Editor
    url: https://coderefinery.github.io/installation/editors/
  - title: Git
    url: https://coderefinery.github.io/installation/git/
  - title: Python
    url: https://coderefinery.github.io/installation/python/
  - title: (optional) Visual diff tools
    url: https://coderefinery.github.io/installation/difftools/
  - title: Jupyter and JupyterLab
    url: https://coderefinery.github.io/installation/jupyter
  - title: Snakemake
    url: https://coderefinery.github.io/installation/snakemake
  - title: Accounts
    url: https://coderefinery.github.io/installation/#accounts

# adjust schedule here if needed, and assign lessons to instructors
schedule:
  - date: Day 1
    morning:
      - time: 9:00 - 9:30
        title: Welcome and practical information (Radovan)
        url: https://github.com/coderefinery/workshop-intro/blob/master/README.md
      - time: 9:30 - 12:00
        title: Introduction to version control - part 1/2 (Thor)
        url: https://coderefinery.github.io/git-intro/
    afternoon:
      - time: 13:00 - 15:00
        title: Introduction to version control - part 2/2 (Thor)
        url: https://coderefinery.github.io/git-intro/
      - time: 15:30 - 17:00
        title: Social coding and open software (Max)
        url: https://cicero.xyz/v3/remark/0.14.0/github.com/coderefinery/social-coding/master/talk.md
  - date: Day 2
    morning:
      - time: 9:00 - 10:30
        title: Modular code development (Max)
        url: https://cicero.xyz/v3/remark/0.14.0/github.com/coderefinery/modular-code-development/master/talk.md
      - time: 11:00 - 12:00
        title: Collaborative distributed version control 1/2 (Emiliano)
        url: https://coderefinery.github.io/git-collaborative/
    afternoon:
      - time: 13:00 - 14:30
        title: Collaborative distributed version control 2/2 (Emiliano)
        url: https://coderefinery.github.io/git-collaborative/
      - time: 15:00 - 17:00
        title: Reproducible research and FAIR data (Thor)
        url: https://coderefinery.github.io/reproducible-research/
  - date: Day 3
    morning:
      - time: 9:00 - 10:30
        title: Documentation (Radovan)
        url: https://coderefinery.github.io/documentation/
      - time: 11:00 - 12:00
        title: Automated testing part 1/2 (Radovan)
        url: https://coderefinery.github.io/testing/
    afternoon:
      - time: 13:00 - 14:00
        title: Automated testing part 2/2 (Radovan)
        url: https://coderefinery.github.io/testing/
      - time: 14:30 - 16:30
        title: Jupyter (Emiliano)
        url: https://coderefinery.github.io/jupyter/
      - time: 16:30 - 17:00
        title: Concluding remarks and where to go from here (Radovan)
        url: https://github.com/coderefinery/workshop-outro/blob/master/README.md

---
