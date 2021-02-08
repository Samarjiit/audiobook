# audiobook

creating an audiobook using python.
in this project we can convert pdf into the audio file.

## Packages Used:

pyttsx3: It is a Python library for Text to Speech. It has many functions which will help the machine to communicate with us. It will help the machine to speak to us

<br/>
PyPDF2: It will help to the text from the PDF. A Pure-Python library built as a PDF toolkit. It is capable of extracting document information, splitting documents page by page, merging documents page by page etc.

<br/>
<br/>
## STEPS
<br/>
Import the PyPDF2 and pyttx3 modules.
<br/>
Open the PDF file.
<br/>
Use PdfFileReader() to read the PDF. We just have to give the path of the PDF as the argument.
<br/>
Use the getPage() method to select the page to be read.
<br/>
Extract the text from the page using extractText().
<br/>
Instantiate a pyttx3 object.
<br/>
Use the say() and runwait() methods to speak out the text.
<br/>
