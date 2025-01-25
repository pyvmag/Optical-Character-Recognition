Optical Character Recognition (OCR) Web Application
This project is a web-based Optical Character Recognition (OCR) tool that extracts and highlights text from uploaded images. Leveraging Python libraries such as Flask and Tesseract OCR, this application provides a simple yet powerful interface for text extraction with confidence-based text bounding boxes.

Features
Image Upload: Users can upload an image via the web interface.
Text Extraction: Extracts text from the uploaded image using Tesseract OCR.
Highlighted Results: Confidence-rated bounding boxes for high-accuracy text regions.
Interactive Output: Displays extracted text and annotated images on the same page.
Installation and Setup
Prerequisites
Python 3.7 or higher
Tesseract OCR
Required Python packages (Flask, Pillow, opencv-python, numpy)
Steps to Run
Clone the repository:

bash
Copy
Edit
git clone <repository_url>
cd <repository_name>
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Ensure Tesseract OCR is installed and configured:

Download and install Tesseract OCR from Tesseract GitHub.
Update the tesseract_cmd path in main.py to point to your local Tesseract installation.
Run the application:

bash
Copy
Edit
python main.py
Access the app in your browser:

arduino
Copy
Edit
http://127.0.0.1:5000/
Folder Structure
php
Copy
Edit
project/
├── main.py               # Main Flask application
├── templates/
│   └── index.html        # Frontend template for the web interface
├── static/               # For static assets (CSS, JS, images)
└── requirements.txt      # Python dependencies
Technologies Used
Backend: Flask
OCR Engine: Tesseract OCR
Image Processing: OpenCV, Pillow
Frontend: HTML, CSS
How It Works
Upload an Image: Users can upload any image file through the interface.
Processing: The application uses Tesseract OCR to extract text and annotate regions with high confidence.
Display Results: Extracted text and the annotated image are rendered on the result page.
