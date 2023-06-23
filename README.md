--
layout: page
title: ReadMe
tagline: Tuskegee Scholars
description: Research, Pedagogy, and Discovery
nav_exclude: true
---

# Research, Pedagogy, and Discovery Seminar
{: .mb-2 }
UC Berkeley and Tuskegee University
{: .mb-0 .fs-6 .text-grey-dk-000 }

This Summer 2023 Program presents an introductory data science curriculum that integrates research, pedgagogy, and discovery.

There are two parts:
- A 2-week "Coding Bootcamp" that teaches computing topics (without the data) and precedes an introductory data science course such as [Data 6](https://data6.org/). Uses material from [CS 61A](https://cs61a.org/), [Data 6](https://data6.org/), and [Data 8](http://data8.org/). Available at `bootcamp`.
- An 8-week Research, Pedagogy, and Discovery Seminar. Available from the top page.

## Website layout

This website is compiled through jekyll and GitHub pages.

`index.md` - main page
  `_announcements/` each announcement is listed here.
  `_modules_rpd/` each week's curriculum for RPD is listed here.
  `_modules_bootcamp/` each week's curriculum for coding bootcamp is listed here.

On command line:
```
ctrl-a: jump to front of line
ctrl-e: jump to back of line
option-left or right: tab between words
```

On finder:
```
Command-Up    # effectively cd ..
```


re-add SSH keys
```
cd # top directory
cd .ssh
ssh-add id_rsa # or id_ed25519
``` 

If jekyll is working, use the below command to launch a local version of your webpage:
```
bundle exec jekyll serve
```

To push to website:
```
git status
git add fname.md
git commit -m "Your commit message here"
git push
```

then wait until green "checkmark" on website

To update JupyterHub inks and links in general:
* Install Chrome plug-in nbgitpuller
* Navigate to the Python NOTEBOOK on github.com
* Copy the nbgitpuller link (you may have to change DataHub to https://datahub.berkeley.edu/, note the slash)
* Then open up the right week module (e.g. `_modules_bootcamp/week-01.md`), edit the links
* If working with a local website, then refresh to check things out
* Finally, git add/commit/push
