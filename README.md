# Template for building Journals for CCSC

## Steps to add a paper
0. import all related files: .tex, .bib, .png and .etc.
0. rename all files using the paper ID, e.g. paper23.tex, paper23.bib,
paper23_1.png, paper23_2.png.
0. update the file name references in the .tex file accordingly.
0. remove `\include{preamble}` line in .tex file.
0. check the correct `\input{copyright}` or  `\input{copyleft}` is used in .tex.
0. add the title and author information in the TOC.

## Front matter
0. define conference and journal information as variables in main.tex.
0. update committee and other information as necessary.
0. tweak spaces so that no text stick into margin, a short URL has no line break,
  images are not too small, and etc.
