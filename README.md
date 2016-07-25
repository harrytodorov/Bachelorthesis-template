# Bachelorthesis-template
This is the base LaTeX template for my Bachelor thesis at DHBW Stuttgart. The title page is formatted based on the rules set by the university(line spacing, page geometry, etc.). [Here](http://www.dhbw.de/fileadmin/user_upload/Dokumente/Dokumente_fuer_Studierende/Richtlinien_fuer_Bearbeitung_und_Dokumentation.pdf) is a reference at p.19 ... in German.

Using this you have to keep in mind, that the main language for the work is set to German. Meaning auto generated content from LaTeX (chapter names, contents, etc.) will be in German. You could easily change that setting [babel](http://ftp.fernuni-hagen.de/ftp-dir/pub/mirrors/www.ctan.org/macros/latex/required/babel/base/babel.pdf) main language to English. For citations [apacite](http://ctan.space-pro.be/tex-archive/biblio/bibtex/contrib/apacite/apacite.pdf) citation style is used. 

As a guide for creating this template I've used a [this](https://tug.org/pracjourn/2008-1/mori/mori.pdf) nice article.

The template has following structure:

/- additional

-- abstract (currently 2 abstracts: a german and an english one)

-- acronyms (file to define acronyms, they'll be printed at the end of the work)

-- erklaerung (containing Solemn declaration for DHBW Stuttgart)

-- quellen (place to define bibliographies)

-- title (Title page; DHBW format)

/- contents (where you put your chapters)

-- content that you should generate

/- images (self-explanatory)

/ main (the main file where the setup for the work is made; contains all used packages and defined commands, yet almost none)
