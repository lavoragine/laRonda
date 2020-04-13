# La ronda

Este repositorio contiene los archivo de La ronda, de Arthur Schnitzler. La colección de archivos parten del archivo fuente (laRonda.md) y su objetivo es la publicación en tres formatos (ebook, versión impresa vía ICML, y HTML). El workflow propuesto parte de markdown y utilizando pandoc se convierten en archivos de INDD, EPUB3 y HTML. 


## De donde vienen estas herramientas:
ver aquí:  wiki [wiki/From-Manuscript-to-EPUB](https://github.com/DigitalPublishingToolkit/Hybrid-Publishing-Resources/wiki/From-Manuscript-to-EPUB).

#### pandoc (converts md to txt)
Follow the instructions on
[http://pandoc.org/installing.html](http://pandoc.org/installing.html)



---

# TODO
* in `git clone` make depth 1 - no previous history
* rm -tf .git

* font in epub/ ; rm lib/

* integrate `epub_zip.py` and `epub_unzip.py` with `epub_process.py` so that latter does only processing

# Notes from workshop

html5lib missing from macs - fix in epub_process.py

clean up markdown: use pandoc -f markdown -t markdown (see book)

if there is no metadata in markdown md_stripmetada -> dont apply over to the command
