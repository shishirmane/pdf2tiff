# pdf2tiff
Converts PDF to multi-page tiff file.

It uses PDFBox to read pdf and convert each page to an image. 
It uses ImageIO to write a multi-page image PDF. 
It use JAI-ImageIO plugin to render Tiff Content.

You can control the DPI of the output TIFF.

Usage:
1. PDF2TIFF_Converter.convert("<Input PDF Path>", "<Output TIFF Path>");
2. 1. PDF2TIFF_Converter.convert("<Input PDF Path>", "<Output TIFF Path>", <DPI>);

Defaults to 300dpi
