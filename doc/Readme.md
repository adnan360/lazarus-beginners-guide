# File Formats:
odt - can be opened with [LibreOffice](https://www.libreoffice.org/download/download/). Still (stable) versions are preferred when editing (choose the earliest version from the page).
svg - can be opened with [Inkscape](https://inkscape.org/en/).
kra - can be opened with [Krita](https://krita.org/en/download/krita-desktop/).
Outputs:
pdf - can be opened with SumatraPDF, Evince, qpdfview and many others
xhtml - can be opened with Firefox, GNU IceCat, Konqueror, Chromium etc.

# How to export
Images used in the book are saved as mainly .kra files. They can be exported into png images by File - Export. Then can be inserted into LibreOffice document.

The cover image is saved in svg format. To export PNG, use File - Export PNG Image, select "Page" as Export area, choose png filename, then click Export.

Do not insert an image and crop within the document. Please try to create a Krita (kra) file with the image, crop there, export and then use in the document.

# How to edit the book document
Before opening the book document, install font files from `assets/fonts/install` directory. All the fonts in the subdirectories are needed.

The book document strictly follows the styling. Please use appropriate styles from View - Styles and Formatting whenever possible.

# Exporting the book
Before submitting or exporting, right click the Table of Contents and click Update index.

From LibreOffice, choose File - Export as PDF..., select a file name and export.

To export as XHTML, choose File - Export, choose XHTML as file type, and save.