# Template for building Journals for CCSC

## Setup
1. clone this repo for a conference
2. change it to a new repo:
```
rm -rf .git
git init
git add -A
git commit -m "initial checkin"
```
3. define conference and journal information as variables in `variables.tex`.

## Steps to add a paper
1. import all related files: .tex, .bib, .png and .etc.
2. rename all files using the paper ID, e.g. paper23.tex, paper23.bib,
paper23_1.png, paper23_2.png.
3. update the file name references in the .tex file accordingly.
4. remove `\include{preamble}` line in .tex file.
5. check the correct `\input{copyright}` or  `\input{copyleft}` is used in .tex.
6. add the title and author information in the TOC.

## Front matter
1. define conference and journal information as variables in main.tex.
2. update committee and other information as necessary.
3. tweak spaces so that no text stick into margin, a short URL has no line break,
  images are not too small, and etc.
