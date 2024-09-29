Text Extraction with Tesseract OCR

This project utilizes Tesseract OCR along with Gradio to extract English and Hindi text from images. Users can upload an image, and the application will extract the text and highlight any specific terms they search for.

Features:
* Extracts text from images in English and Hindi.

* Allows users to search for specific text and highlights it in the image.

* User-friendly interface built using Gradio.


Requirements:
Python 3.x
Tesseract OCR
Required Python libraries

Installation:
 Set up the environment in Google Colab


Usage:

Upload an Image: Click the "Upload Image" button to upload the image you want to analyze.
Search for Text: Enter the text you want to search for in the "Search Text" input box.
View Results: The application will display the uploaded image with highlighted search terms (if found) and the extracted text below the image.

Code Overview:

* Converts the image to RGB format if it is in grayscale.
  
* Uses Tesseract to extract text from the image.
  
* Retrieves bounding boxes for detected text.

Screenshots
<img width="1440" alt="tessaract" src="https://github.com/user-attachments/assets/d50b11c1-6d51-47c3-9e58-299b9cdf4c46">

