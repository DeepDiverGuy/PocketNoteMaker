## Note
This script was created for windows operating systems.
It may not work on Linux distributions.

## Description
This is a simple python script that takes a PDF file, 
creates images for each page in the pdf, stores those
in a folder and from that folder, merges 4 pictures 
in each docx page.

## Dependencies
- docx
- pdf2image
- The path for poppler binaries (poppler_path) in line 69 
should be accurate; please make sure the path is alright. 
If needed, change it.

## Set these variables before running this script
- path
- pdf_file_name
- standard_file_path
- w_i
- h_i

Instructions are inside the script accordingly.

## After running the program successfully
If the program successfully finishes, you will find a docx file in the same directory where the PDF file is. The file will contain all the pages from the PDF, 4 pages in each docx page. The width and height of each small page will be according to the variables set by you (w_i, h_i - in inches). Note that you need to set appropriate margins within the docx file so that each 2 corresponding pages lie exactly in one anothers opposite. It is necessary if you print the pages in both sides using a printer. This way when you cut the printed pages, they will be in a consecutive manner.

## History
I created this script originally for cheating on my exams. I had PDFs of the solutions and running this script, I could easily make docx files containg the whole PDF, which after printing were ready to be cut and made pocket notes. But I learned that no matter how advanced tools or techs I use, if I don't study well, my GPA would not be getting any better. I might hardly pass the exams using cheating papers, but getting a better CGPA really requires one to study well.
