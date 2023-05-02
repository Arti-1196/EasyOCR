# Optical Character Recognition [EasyOCR]


OCR, also known as Optical Character Recognition allows you to 'recognise' text from within a document, whether it be an image, a PDF or a table.

Easy OCR is a font-dependent printed character reader based on a template matching algorithm. 
EasyOCR is a Python library for Optical Character Recognition (OCR) that allows you to easily extract text from images and scanned documents. 

Keras-OCR is image specific OCR tool. If text is inside the image and their fonts and colors are unorganized. Easy-OCR is lightweight model which is giving a good performance for receipt or PDF conversion

It seems that pytesseract is not very good at detecting text in the entire image and converting str. Instead, text should be detected first with text detection and the texts have to given OCR engines.
While keras_ocr is good in terms of accuracy but it is costly in terms of time. Also if you’re using CPU, time might be an issue for you. Keras-OCR is image specific OCR tool. If text is inside the image and their fonts and colors are unorganized.
Easy-OCR is lightweight model which is giving a good performance for receipt or PDF conversion. It is giving more accurate results with organized texts like PDF files, receipts, bills. Easy OCR also performs well on noisy images.
Pytesseract is performing well for high-resolution images. Certain morphological operations such as dilation, erosion, OTSU binarization can help increase pytesseract performance.
