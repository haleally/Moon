---
layout: post
title: "Assignment 3"
date: 2017-07-09
cetgories: jekyll update
---

<h1>**Assignment 3**</h1>

<h2>*Abstract*</h2>

Assignment 3 focused on taking a file in Markdown and converting it into alternate files types using a script. In my assignment, I chose to write my script to convert my resume into HTML, ODX, PDF, ODT, and RTF files. 

<h2>*Process*</h2>

I used the same basic command pandoc resume.md -o resume.[file type] for each different file type except PDF, which gave me some trouble.
For that conversion, I used pandoc -o resume.pdf --latex-engine=pdflatex resume.md because it's what Google said I should do. 
For funsies, I also included the command echo "Converted MD to FILE TPYE" for the user to be aware of what was going on as the script ran.

<h2>*Results*</h2>

[Source File](https://github.com/haleally/haleally-convert-documents/blob/master/resume.md/)
[Output HTML](https://github.com/haleally/haleally-convert-documents/blob/master/resume.html/)
[Output DOCX](https://github.com/haleally/haleally-convert-documents/blob/master/resume.docx/)
[Output ODT](https://github.com/haleally/haleally-convert-documents/blob/master/resume.odt/)
[Output PDF](https://github.com/haleally/haleally-convert-documents/blob/master/resume.pdf/)
[Output RTF](https://github.com/haleally/haleally-convert-documents/blob/master/resume.rtf/)
[Script](https://github.com/haleally/haleally-convert-documents/blob/master/haleally-convert-docs.sh/)
