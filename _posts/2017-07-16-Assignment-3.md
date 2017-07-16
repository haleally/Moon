---
layout: post
title: "Introduction and About"
date: 2017-07-09
cetgories: jekyll update
---

#**Assignment 3**

*Abstract*
Assignment 3 focused on taking a file in Markdown and converting it into alternate files types using a script. In my assignment, I chose to write my script to convert my resume into HTML, ODX, PDF, ODT, and RTF files. 

*Process*
I used the same basic command pandoc resume.md -o resume.[file type] for each different file type except PDF, which gave me some trouble.
For that conversion, I used pandoc resume.md -o resume.pdf --latex-engine=xelatex --template=my.latex because it's what Google said I should do. 
For funsies, I also included the command echo "Converted MD to FILE TPYE" for the user to be aware of what was going on as the script ran.

*Results*
[Source File]()
[Output HTML]
[Output DOCX]
[Output ODT]
[Output PDF]
[Output RTF]
[Script]
