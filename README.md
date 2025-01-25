
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
