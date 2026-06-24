BarcodeReader
=============

BarcodeReader is a barcode reader for Code128, Code93, Code39, Standard/Industrial 2 of 5,
Interleaved 2 of 5, Codabar and EAN-13 barcodes in javascript.
Supports multiple barcodes in one image and detects what type of barcodes there are.

It seems that the issue with smartphones might have been one of exif orientation tags so there's a fix in BarcodeReader now and also a fix for some kind of downsampling issue for iOS.



## Change Log

### v1.6.1

- Added video support to the jQuery plugin
- Fire event when barcode is decoded
- Refactored jQuery elements allowing support for your own
- Flipped video to make it easier to position the barcode
