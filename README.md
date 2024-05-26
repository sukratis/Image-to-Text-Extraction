## Introduction

The objective of this project was to develop a web application that allows users to upload an image and receive the extracted text from that image. This report details the approach taken, the technologies used, the implementation process, and the challenges encountered during the development.

## Approach

The approach involved building a simple web application using Flask, a lightweight web framework for Python. The application utilizes Tesseract OCR (Optical Character Recognition) to extract text from the uploaded images. The implementation was done in Jupyter Notebook to facilitate easy iteration and debugging.

## Technologies Used

- Flask: A micro web framework written in Python. It was used to handle web requests and serve HTML content.
- Flask-Ngrok: A package to run Flask applications on ngrok, which provides public URLs for local servers.
- OpenCV: A library for computer vision. It was used to process and convert images to a format suitable for Tesseract.
- Pillow: A Python Imaging Library (PIL) fork, it provides image processing capabilities.
- NumPy: A fundamental package for scientific computing in Python. It was used for array manipulation.
- Pytesseract: A wrapper for Google's Tesseract-OCR Engine, it was used to perform the OCR on images.
- Werkzeug: A WSGI utility library for Python. It was used for secure filename handling.

## Challenges Encountered

- **Tesseract Installation:** Ensuring that Tesseract was correctly installed and configured on the system path was crucial. This required setting the correct path in the code and ensuring the system could access Tesseract.
- **File Handling:** Handling file uploads securely and efficiently in a web application environment required careful consideration, especially regarding file paths and names.
- **Image Processing:** Ensuring the image was correctly processed before OCR was performed required understanding OpenCV’s image processing capabilities.
- **Template Rendering:** Ensuring the correct rendering of images and text in the HTML template required testing and debugging the template code.
