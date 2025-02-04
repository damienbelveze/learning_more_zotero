<!--

title: "Learning more with Zotero"  

author: Damien Belvèze

date: may 2025

email: damien.belveze@univ-rennes.fr 

attribute: [First steps with Zotero](https://liascript.github.io/course/?https://raw.githubusercontent.com/damienbelveze/CFCB_IA/main/deroule_cours.md#1) 
        by [Damien Belvèze](damien.belveze@univ-rennes.fr) 
        is licensed under [CC-by-sa](https://creativecommons.org/licenses/by-sa/4.0/?ref=chooser-v1)

language: fr 

link: lia.css

icon: ./images/etoile.png

comment: this guide is adapted to PhD students who want to improve and deepen their use  reference manager Zotero. Much of its content comes from the Zotero workshop libguide published by Formadoct and archived on [Internet Archive](https://web.archive.org/web/20210622005132/https://formadoct.doctorat-bretagneloire.fr/zotero_workshop/introduction)

import: https://raw.githubusercontent.com/LiaTemplates/citations/main/README.md

@onload
// this shall load an entire file at starttime that can be referenced
setTimeout(() => { window.bibliographyLoad("https://raw.githubusercontent.com/LiaTemplates/citations/main/bibtex.bib")}, 100)
@end

-->

# Learning more with Zotero

```ascii 



          _____                   _____               _____                   _____                   _____                   _____                   _____                   _____          
         /\    \                 /\    \             /\    \                 /\    \                 /\    \                 /\    \                 /\    \                 /\    \         
        /::\    \               /::\    \           /::\____\               /::\    \               /::\____\               /::\    \               /::\    \               /::\    \        
       /::::\    \             /::::\    \         /:::/    /              /::::\    \             /::::|   |              /::::\    \             /::::\    \             /::::\    \       
      /::::::\    \           /::::::\    \       /:::/    /              /::::::\    \           /:::::|   |             /::::::\    \           /::::::\    \           /::::::\    \      
     /:::/\:::\    \         /:::/\:::\    \     /:::/    /              /:::/\:::\    \         /::::::|   |            /:::/\:::\    \         /:::/\:::\    \         /:::/\:::\    \     
    /:::/__\:::\    \       /:::/  \:::\    \   /:::/____/              /:::/__\:::\    \       /:::/|::|   |           /:::/  \:::\    \       /:::/__\:::\    \       /:::/  \:::\    \    
   /::::\   \:::\    \     /:::/    \:::\    \  |::|    |              /::::\   \:::\    \     /:::/ |::|   |          /:::/    \:::\    \     /::::\   \:::\    \     /:::/    \:::\    \   
  /::::::\   \:::\    \   /:::/    / \:::\    \ |::|    |     _____   /::::::\   \:::\    \   /:::/  |::|   | _____   /:::/    / \:::\    \   /::::::\   \:::\    \   /:::/    / \:::\    \  
 /:::/\:::\   \:::\    \ /:::/    /   \:::\ ___\|::|    |    /\    \ /:::/\:::\   \:::\    \ /:::/   |::|   |/\    \ /:::/    /   \:::\    \ /:::/\:::\   \:::\    \ /:::/    /   \:::\ ___\ 
/:::/  \:::\   \:::\____/:::/____/     \:::|    |::|    |   /::\____/:::/  \:::\   \:::\____/:: /    |::|   /::\____/:::/____/     \:::\____/:::/__\:::\   \:::\____/:::/____/     \:::|    |
\::/    \:::\  /:::/    \:::\    \     /:::|____|::|    |  /:::/    \::/    \:::\  /:::/    \::/    /|::|  /:::/    \:::\    \      \::/    \:::\   \:::\   \::/    \:::\    \     /:::|____|
 \/____/ \:::\/:::/    / \:::\    \   /:::/    /|::|    | /:::/    / \/____/ \:::\/:::/    / \/____/ |::| /:::/    / \:::\    \      \/____/ \:::\   \:::\   \/____/ \:::\    \   /:::/    / 
          \::::::/    /   \:::\    \ /:::/    / |::|____|/:::/    /           \::::::/    /          |::|/:::/    /   \:::\    \              \:::\   \:::\    \      \:::\    \ /:::/    /  
           \::::/    /     \:::\    /:::/    /  |:::::::::::/    /             \::::/    /           |::::::/    /     \:::\    \              \:::\   \:::\____\      \:::\    /:::/    /   
           /:::/    /       \:::\  /:::/    /   \::::::::::/____/              /:::/    /            |:::::/    /       \:::\    \              \:::\   \::/    /       \:::\  /:::/    /    
          /:::/    /         \:::\/:::/    /     ~~~~~~~~~~                   /:::/    /             |::::/    /         \:::\    \              \:::\   \/____/         \:::\/:::/    /     
         /:::/    /           \::::::/    /                                  /:::/    /              /:::/    /           \:::\    \              \:::\    \              \::::::/    /      
        /:::/    /             \::::/    /                                  /:::/    /              /:::/    /             \:::\____\              \:::\____\              \::::/    /       
        \::/    /               \::/____/                                   \::/    /               \::/    /               \::/    /               \::/    /               \::/____/        
         \_____/                 _______          _____                   _________/              _________/             __________/                 \/____/                 ~~              
         /\    \                /::\    \        /\    \                 /\    \                 /\    \                /::\    \                                                            
        /::\    \              /::::\    \      /::\    \               /::\    \               /::\    \              /::::\    \                                                           
        \:::\    \            /::::::\    \     \:::\    \             /::::\    \             /::::\    \            /::::::\    \                                                          
         \:::\    \          /::::::::\    \     \:::\    \           /::::::\    \           /::::::\    \          /::::::::\    \                                                         
          \:::\    \        /:::/~~\:::\    \     \:::\    \         /:::/\:::\    \         /:::/\:::\    \        /:::/~~\:::\    \                                                        
           \:::\    \      /:::/    \:::\    \     \:::\    \       /:::/__\:::\    \       /:::/__\:::\    \      /:::/    \:::\    \                                                       
            \:::\    \    /:::/    / \:::\    \    /::::\    \     /::::\   \:::\    \     /::::\   \:::\    \    /:::/    / \:::\    \                                                      
             \:::\    \  /:::/____/   \:::\____\  /::::::\    \   /::::::\   \:::\    \   /::::::\   \:::\    \  /:::/____/   \:::\____\                                                     
              \:::\    \|:::|    |     |:::|    |/:::/\:::\    \ /:::/\:::\   \:::\    \ /:::/\:::\   \:::\____\|:::|    |     |:::|    |                                                    
_______________\:::\____|:::|____|     |:::|    /:::/  \:::\____/:::/__\:::\   \:::\____/:::/  \:::\   \:::|    |:::|____|     |:::|    |                                                    
\::::::::::::::::::/    /\:::\    \   /:::/    /:::/    \::/    \:::\   \:::\   \::/    \::/   |::::\  /:::|____|\:::\    \   /:::/    /                                                     
 \::::::::::::::::/____/  \:::\    \ /:::/    /:::/    / \/____/ \:::\   \:::\   \/____/ \/____|:::::\/:::/    /  \:::\    \ /:::/    /                                                      
  \:::\~~~~\~~~~~~         \:::\    /:::/    /:::/    /           \:::\   \:::\    \           |:::::::::/    /    \:::\    /:::/    /                                                       
   \:::\    \               \:::\__/:::/    /:::/    /             \:::\   \:::\____\          |::|\::::/    /      \:::\__/:::/    /                                                        
    \:::\    \               \::::::::/    /\::/    /               \:::\   \::/    /          |::| \::/____/        \::::::::/    /                                                         
     \:::\    \               \::::::/    /  \/____/                 \:::\   \/____/           |::|  ~|               \::::::/    /                                                          
      \:::\    \               \::::/    /                            \:::\    \               |::|   |                \::::/    /                                                           
       \:::\____\               \::/____/                              \:::\____\              \::|   |                 \::/____/                                                            
        \::/    /                ~~                                     \::/    /               \:|   |                  ~~                                                                  
         \/____/                                                         \/____/                 \|___|                                                                                      
                                                                                                                                                                                             





```

# How to deal with the storage limitation of Zotero cloud



# How to use Optical Character Recognition within Zotero dashboard

## What can you do with this plugin

By Ocerization, we mean the operation of using optical character recognition to index and make searchable the content of a PDF which was previously scanned as an image formated as a PDF 
Thanks to Zotero-ocr plugin (adapted to Zotero 7), it's possible to ocerize PDF provided they have a parent item. 
This plugin is usefull for researchers who need to work on photographs of printed material. 

## How does it work

This plugin needs some packages to be installed in order to be run through Zotero. 
The needed packages are **Tesseract-ocr** and **Poppler-Utils** 

Installation on GNU/Linux systems: 

```shell
sudo apt install tesseract-ocr
sudo apt install libtesseract-dev
# installs tesseract-ocr
# for other OS see here : https://tesseract-ocr.github.io/tessdoc/Installation.html
sudo apt-get -y install poppler-utils
# installs poppler-utils 
```

Now you should install zotero_ocr add-on from file the way we have already shown
The .xpi file of the last release [can be downloaded from there](https://github.com/UB-Mannheim/zotero-ocr/releases/tag/0.8.1)

Once you have installed this plugin, you will be able to open its settings (edit > settings > zotero-ocr)

<img src="images/zotero_ocr.png" alt="a pane with several options for tesseract-ocr">Zotero-ocr settings</img>

By default, the paths to tesseract & pdftoppm (a package of poppler-utils) are empty. 
If you leave these fields empty, it may work, but if it does not work, you will have to provide the paths to these utilities. 

In order to locate these packages, you may use the *whereis* command for GNU/Linux systems:

<img src="images/whereis.png" alt="two command lines on a terminal to locate tesseract-ocr and pdftoppm, the output gives the paths to these utilities that you need to provide to Zotero : on this installation, these paths are /usr/share/tesseract-ocr and /usr/bin/pdftoppm">command lines to locate tesseract-ocr and pdftoppm packages</img>

fill the empty fields with these paths. 

Go to your library and create two manuscripts (zotero-ocr and zotero-ocr-fr)
Attach to the first one  <a href="zotero_ocr/pdf_ocr.pdf" download>the following text</a>, and to the second one (zotero-ocr-fr) <a href="zotero_ocr/ocr_french.pdf" download>this document written in French</a> (the first one was written in English).

Open pdf_ocr.pdf (attached to the first manuscript item) in Zotero's viewer ; you may notice that the text within this document is not searchable. 
Now right-click on this PDF in your collection and select "OCR selected Pdf(s)"
After a few seconds (if there is only one page it will be quite immediate), Tesseract will ocerize this text. 
Now depending on the plugin settings, you may have different outputs

The indexed output may be stored as an item note if you left the option *save output as note* checked
or it may come as a second PDF (which content will be then searchable in contrast with the former one) if you have not kept the option "overwrite the initial pdf with the output" checked.
other files may have been added such as html files filled with the text contained by each PDF page (these files can be located in your storage library), provided you left the "save the output as html/hocr file" selected 

**Now this pdf can be searched within your Zotero library by using Zotero's inner search engine**. 

Be carefull : if your text is not written in English, two steps should be added to get the same results. 

You will need to install extra packages from [Tessdata repostiry](https://github.com/tesseract-ocr/tessdata)
For instance, if you need to ocerize French texts, you will need to download in your tessdata folder the following package: *fra.traineddata* ; for spanish texts, you will need *spa.traineddata* file, and so on...

Tessdata folder can be found under tesseract-ocr (see above). 

Then, let's assume the pdf is filled with french language, you will need to provide this information to zotero-ocr plugin. 

In the field "choose a language/script for recognition", add *fra* (or *spa* if the text was written in spanish)

Zotero-ocr should ocerize and index the content of your PDF and give you the output you have choosed to get (see above)
