For adding images to the pdf, add a directory named images in which you have to add all the images you want to insert in the pdf as images and backgrounds. After this edit the tex file and remove "%" sign from the image commands in all frames which are like
for background images-->
> %\setbeamertemplate{background}
> %{\includegraphics[width=\paperwidth,height=\paperheight]{Your_Image_name.jpg}})

Then move to directory and run command:
 "pdflatex presentation.tex"

So your presentation is created. To view the pdf, run command:
"evince presentation.pdf"
