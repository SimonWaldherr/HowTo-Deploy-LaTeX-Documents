# Howto Deploy LaTeX Documents
## HowTo Deploy LaTeX (or Markdown) Documents as PDF (and DjVu) via [GitHub](https://github.com/github) and [TravisCI](https://github.com/travis-ci)

[![Build Status](https://travis-ci.org/SimonWaldherr/HowTo-Deploy-LaTeX-Documents.svg?branch=master)](https://travis-ci.org/SimonWaldherr/HowTo-Deploy-LaTeX-Documents) 
[![PDF Status](https://www.sharelatex.com/github/repos/SimonWaldherr/HowTo-Deploy-LaTeX-Documents/builds/latest/badge.svg)](https://www.sharelatex.com/github/repos/SimonWaldherr/HowTo-Deploy-LaTeX-Documents/builds/latest/output.pdf) 
[![GitHub Release](https://img.shields.io/badge/download-latest-brightgreen.svg)](https://github.com/SimonWaldherr/HowTo-Deploy-LaTeX-Documents/releases/latest) 
[![GitHub forks](https://img.shields.io/github/forks/SimonWaldherr/HowTo-Deploy-LaTeX-Documents.svg)](https://github.com/SimonWaldherr/HowTo-Deploy-LaTeX-Documents/network) 
[![GitHub stars](https://img.shields.io/github/stars/SimonWaldherr/HowTo-Deploy-LaTeX-Documents.svg)](https://github.com/SimonWaldherr/HowTo-Deploy-LaTeX-Documents/stargazers)   

This repository explains how to automate the process of converting LaTeX documents to [PDF](https://en.wikipedia.org/wiki/Portable_Document_Format)s or [DjVu](https://en.wikipedia.org/wiki/DjVu)-Files. You need no special software, everything gets done online.  

Dealing with TeX + PDF on GitHub (or other online repository hosting services) leads mostly to various problems, e.g.:

* having *large* binary files in a git repo (PDFs)
* having old files, large gap between source and PDF
* need of a local tex installation to update the PDF

the alternative is to only publish the LaTeX source, which has other problems:

* no preview on GitHub
* no preview after download
* no way to see the completed document on devices without TeX (e.g. mobile)

and what is the solution?

* building the binary files ([PDF](https://en.wikipedia.org/wiki/Portable_Document_Format) + [DjVu](https://en.wikipedia.org/wiki/DjVu)) on a Server
* save the files on publicly accessible servers (e.g. as [GitHub Release](https://help.github.com/articles/about-releases/))
* link to the [files](https://github.com/SimonWaldherr/HowTo-Deploy-LaTeX-Documents/releases/latest) from the README

[![Creative Commons Lizenzvertrag](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/) 

Download the PDF from the [latest Release](https://github.com/SimonWaldherr/HowTo-Deploy-LaTeX-Documents/releases/latest).

