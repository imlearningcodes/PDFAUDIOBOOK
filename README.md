# PDFAUDIOBOOK
This converts a PDF into a audiobook which can be listened to: anytime and anywhere. 


Lets see how it works!

The tools used here are-

1. pdfminer
2.gTTS
3.Google Colaboratory


Now Lets see what are each of them.


1.pdfminer

Unlike other PDF-related tools, it focuses entirely on getting and analyzing text data. PDFMiner allows one to obtain the exact location of text in a page, as well as other information such as fonts or lines. It includes a PDF converter that can transform PDF files into other text formats (such as HTML).

Hence, we can change the pdf according to our wishes. And then extract parts from it and make necessary changes.


2. gTTS

(Google Text-to-Speech), a Python library and CLI tool to interface with Google Translate’s text-to-speech API. Writes spoken mp3 data to a file, a file-like object (bytestring) for further audio manipulation, or stdout. It features flexible pre-processing and tokenizing, as well as automatic retrieval of supported languages.

Hence, the extracted parts of the pdf can be fed into the gTTS to get the desired output.


3. Google Colaboratory

Google Colaboratory is a free Jupyter notebook environment that requires no setup and runs entirely in the cloud.
Colab notebooks execute code on Google's cloud servers, meaning you can leverage the power of Google hardware, including GPUs and TPUs, regardless of the power of your machine. All you need is a browser. Colab is used extensively in the machine learning community with applications.

Colaboratory is integrated with Google Drive. It allows you to share, comment, and collaborate on the same document with multiple people.
