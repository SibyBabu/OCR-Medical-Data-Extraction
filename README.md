# OCR-Medical-Data-Extraction

# 1. Introduction :
This project is to implement medical data extraction , and this project will auto classify and extract useful information from medicalcare documents.
Implemented this project by using libraries - Pytesseract(Runs On Google Optical Character Recognition-OCR), Computer Vision, Regex, PDF2Image.
At first we use PDF2Image library to convert PDF into image, clean the image with Computer Vision by Adaptive Thresholding Techinique and extract useful data by using Pytesseract(OCR) and regex.
This project works well on medicalcare documents(like extracting name, patient details, medicine) and this saves time as it reduces human work and saves time from 15 min to 2 min.

# 2. Major Libraries and tools :
Pdf2image - This library is used in this project to convert medical document pdf file to text
openCV - This library is used in this project for processing and cleaning the image by adaptive threshold method.
pytesseract - This library is used in this project for converting image containing useful information to text and this library runs on google optical character recognition engine (OCR).
regex - This library is used in this project for extracting useful and required text from text data .


# 3. Project tasks :
Collect and dataset.
Analyse the data and get useful insights from data .
Use pdf2image to convert pdf to image.
use computer vision (opencv) to process and clean the image by adaptive thresholding technique.
By pyteserract (OCR) convert the processed and clean image to extract the data .
By Regular expression (RE) extract useful information from the extracted text data.
