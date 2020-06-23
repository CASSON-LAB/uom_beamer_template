# uom_beamer_template
Beamer template for LaTeX based presentations from the University of Manchester

Based upon https://github.com/mundya/unofficial-university-of-manchester-beamer/blob/master/README.md and is shared and modified under its GNU Public License. It's been modified to include a slide number in the bottom right hand corner of the slide. (All presentations should have slide numbers!) It also has the standard beamer navigation/search buttons on the bottom left of the slide. 

Notes:
 - Uses fontspec for Sans Serif fonts. Assumes is compiled with LuaLaTeX or similar.
 - To make slides use \documentclass[11pt,aspectratio=43,ignorenonframetext,t]{beamer} at the top of the document. 
 - To make handouts (slides with notes printed under them), first make slides, then recompile with the following at the top of the document: 
\documentclass[11pt,a4paper]{article} 
\usepackage{beamerarticle}
\setjobnamebeamerversion{main.beamer}
