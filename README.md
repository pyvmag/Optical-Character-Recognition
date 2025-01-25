<<<<<<< HEAD

# Optical Character Recognition (OCR) Web Application

This project is a web-based Optical Character Recognition (OCR) tool designed to extract and highlight text from uploaded images. Built with Python, Flask, and Tesseract OCR, the application offers a user-friendly interface for seamless text extraction, complete with confidence-rated bounding boxes to enhance accuracy.

---

## Features

- **Image Upload:** Easy-to-use interface for uploading image files.
- **Advanced Text Extraction:** Utilizes Tesseract OCR to extract text from images accurately.
- **Visual Annotations:** Highlights text regions with high confidence using bounding boxes.
- **Dynamic Output:** Displays extracted text and annotated images side-by-side.

---

## Installation and Setup

### Prerequisites

Ensure the following are installed on your system:

1. **Python 3.7 or higher**
2. **Tesseract OCR:** Download from [Tesseract GitHub](https://github.com/tesseract-ocr/tesseract).
3. **Python Packages:** Install dependencies listed in `requirements.txt`.

### Steps to Run

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Configure Tesseract OCR:
   - Install Tesseract OCR and note its installation path.
   - Update the `tesseract_cmd` variable in `main.py` to the Tesseract installation path, e.g.,
     ```python
     pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'
     ```

4. Run the application:
   ```bash
   python main.py
   ```

5. Access the app in your web browser:
   ```
   http://127.0.0.1:5000/
   ```

---

## Folder Structure

```
project/
├── main.py               # Main Flask application
├── templates/
│   └── index.html        # Frontend HTML template
├── static/               # Static assets (CSS, JS, images)
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---

## Technologies Used

- **Backend:** Flask
- **OCR Engine:** Tesseract OCR
- **Image Processing:** OpenCV, Pillow
- **Frontend:** HTML, CSS

---

## How It Works

1. **Upload an Image:** Users can upload an image via the interface.
2. **OCR Processing:** The application processes the image using Tesseract OCR, extracting text data and confidence levels.
3. **Highlighting Results:** Text regions with high confidence are annotated on the image with bounding boxes.
4. **Output Display:** Both the extracted text and annotated image are displayed on the results page.

---

## Contribution

Contributions are welcome! Feel free to fork the repository, submit issues, or create pull requests to enhance the project.

---

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

---
=======
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
>>>>>>> origin/main
