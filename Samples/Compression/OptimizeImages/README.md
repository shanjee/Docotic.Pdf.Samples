# Optimize images in PDF document
This sample shows how to optimize existing images in PDF document.

Use one of PdfImage.RecompressWith* methods to optimize images in PDF document. Recompression of images is an effective way to greatly decrease size of the output PDF file.

You can also resize images in a PDF document. To do so please use one of the PdfImage.ResizeTo or PdfImage.Scale methods. Note that resizing of images is not supported in version for .NET Standard.

You can recompress images using Flate, Jpeg and CCITT compression schemes. Please note that recompression is often a lossy process.