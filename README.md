# Grid-2.0-Electronic-Invoicing-using-Image-Processing
A tool which converts PDF Invoice to Electronic Invoice using Image Processing.

### Tools and technologies used:
* Tessaract API`(for Optical Character Recognition)`
* Python
* Python REgex engine
* ImageMagick
* XlsxWriter
* Pytessaract `(Python wrapper for tessaract)`
### Requirements:
* Python 3.6+
* pip
* ImageMagick
* All pip based requirements in `requirement.txt`
### Installation:
* Install python 3.6+
* Install pip
* Install Imagemagick
* Install `requirements.txt` using pip.
### Using the product:
* Clone the project in a local directory.
* Open the local cloned directory.
* Use command line.
* Run command ` python final.py "full filename.pdf PATH" ` .
* Output will be shown in a excel file named `filename.xlsx` .
* The output excel file will be in the same local cloned directory .
### further improvements
* Improving the Accuracy upto 100%.
* Finding and removing the errors.
* Integrating user interface.

### OCR
Optical Character Recognition (OCR) is the conversion of images of typed, handwritten or printed text into machine-encoded text, whether from a scanned document, a photo of a document, a photo from a scene (billboards in a landscape photo) or from a text superimposed on an image (subtitles on a television broadcast).
### Tessaract OCR
![OCR Process Flow](https://miro.medium.com/max/700/1*iFK6nUOD9xCToOyVu48Phw.png)
Tesseract OCR is an open-source project, started by Hewlett-Packard. Later Google took over development. It can be used directly, or (for programmers) using an API to extract printed text from images. It supports a wide variety of languages. Tesseract doesn’t have a built-in GUI, but there are several available from the 3rdParty page. Tesseract is compatible with many programming languages and frameworks through wrappers. t can be used with the existing layout analysis to recognize text within a large document, or it can be used in conjunction with an external text detector to recognize text from an image of a single text line.

We need to make sure the image is appropriately pre-processed. to ensure a certain level of accuracy. This includes rescaling, binarization, noise removal, deskewing, etc.

![Tesseract 3 OCR process from paper](https://miro.medium.com/max/700/1*koItF8Mhlbg5W2ep662C5A.png)

<b>Tesseract OCR is quite powerful but does have some limitations.</b>
* The OCR is not as accurate as some available commercial solutions .
* Doesn’t do well with images affected by artifacts including partial occlusion, distorted perspective, and complex background.
* It is not capable of recognizing handwriting.
* It may find gibberish and report this as OCR output.
* If a document contains languages outside of those given in the -l LANG arguments, results may be poor.
* It is not always good at analyzing the natural reading order of documents. For example, it may fail to recognize that a document contains two columns, and may try to join text across columns.
* Poor quality scans may produce poor quality OCR.
* It does not expose information about what font family text belongs to.

### Imagemagick

ImageMagick is a free and open-sourcesoftware suite for displaying, creating, converting, modifying, and editing raster images.
<br/>
One of the basic and thoroughly-implemented features of ImageMagick is its ability to efficiently and accurately convert images between different file formats (it uses the command convert to achieve this).
<br/>
We have used Imagemagick to convert the PDF to image file.

### Python Regex engine

Regular expressions (called REs, or regexes, or regex patterns) are essentially a tiny, highly specialized programming language embedded inside Python and made available through the re module. Using this little language, you specify the rules for the set of possible strings that you want to match; this set might contain English sentences, or e-mail addresses, or TeX commands, or anything you like. You can then ask questions such as “Does this string match the pattern?”, or “Is there a match for the pattern anywhere in this string?”. You can also use REs to modify a string or to split it apart in various ways.

### Team - Pehli_baar
* Mohd Sadiq
* Vikram Chaurasia
* Srajan Gupta
