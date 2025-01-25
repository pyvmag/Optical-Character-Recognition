OCR Project
This is a Flask-based Optical Character Recognition (OCR) project that extracts text from uploaded images using the Tesseract OCR engine. The project also highlights detected text in the image with bounding boxes for visualization.

Features
Extract text from uploaded images.
Visualize bounding boxes around detected text in the image.
High-confidence text extraction using Tesseract.
Prerequisites
Python 3.12 or later.
Tesseract OCR installed and added to the system PATH.
Required Python libraries: Flask, pytesseract, opencv-python, Pillow, numpy.
Installation and Setup
Clone the repository and navigate to the project folder.
Install the required Python libraries:
Copy
Edit
pip install flask pytesseract opencv-python pillow numpy
Ensure Tesseract OCR is installed and configured.
Run the Flask application:
css
Copy
Edit
python main.py
Access the application in your browser at http://127.0.0.1:5000/.
Usage
Upload an image through the application interface.
View the extracted text and the image with highlighted bounding boxes.
Future Improvements
Add support for multiple images.
Enable text extraction from PDFs.
Implement multi-language OCR.
Dockerize the application for easier deployment.
