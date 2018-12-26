This simple tutorial is going to show you a command line tool pdf2htmlEX that converts PDF to HTML without losing format. Text is preserved as much as possible.

pdf2htmlEX renders PDF files in HTML, utilizing modern Web technologies, aims to provide an accuracy rendering, while keeping optimized for Web display.

It is optimized for modern web browsers such as Mozilla Firefox & Google Chrome.

This program is designed for scientific papers with complicate formulas and figures, so a precise rendering is also the #1 concern. But of course general PDF files are also supported.

<strong>Features:</strong>

Single HTML file output
Precise rendering
Text Selection
Font embedding & reencoding for Web
Proper styling (Color, Transformation…)
Optimization for Web
Type 3 fonts and Non-text object (Don’t worry, they will be rendered as images) are not supported yet. The following projects have been consulted for pdf2htmlEX:

pdftops & pdftohtml from poppler
MuPDF
PDF.js
Crocodoc
Google Doc

<strong>Install pdf2htmlEX in Ubuntu:</strong>

There is a Ubuntu PPA set up at ppa:coolwanglu/pdf2htmlex. For now, it supports only Ubuntu 12.04. Launch a terminal window from the dash home or press Ctrl+Alt+T. Copy and paste following commands into terminal and hit enter one by one to add the ppa and install pdf2htmlEX:

sudo add-apt-repository ppa:coolwanglu/pdf2htmlex

sudo apt-get update

sudo apt-get install fontforge 
sudo apt-get install poppler  if not install then sudo apt-get install python-poppler
sudo apt-get install pdf2htmlex

<strong>Usage:</strong>

To convert PDF to HTML use pdf2htmlEX, run this command:

pdf2htmlEX /path/to/foobar.pdf

For more:

pdf2htmlEX --help

Enjoy!

