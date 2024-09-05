# ResumeParser

This project extracts relevant information from resumes in PDF format, including skills, experience, education, and more. The extracted data is output as CSV and JSON files.

## Features
- Extracts technical and non-technical skills.
- Categorizes internships and jobs into technical and non-technical roles.
- Extracts educational details such as degree, course, CGPA, HSC, and SSC.
- Supports OCR fallback for non-standard PDFs.

## Getting Started

### Prerequisites
- Python 3.x

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AdiD-code/ResumeParser.git
   cd resume-info-extraction
   ```
   
2. **Install the dependencies**

The requirements.txt file includes the necessary Python libraries for the project. To install them, run:
Install Python libraries using pip:
   ```bash
   pip install -r requirements.txt
   ```

3. **Install Poppler**

For Windows: Download the binaries from [Poppler for Windows](https://github.com/oschwartz10612/poppler-windows) and add the path to poppler/bin to your system's PATH environment variable.

Set environment variables for Poppler (Windows only): Add the path to the poppler/bin directory to your system's PATH environment variable. This allows the program to find the Poppler tools.

For macOS: Use homebrew:
```bash
brew install poppler
```

For Linux: Install using your package manager:
```bash
sudo apt-get install poppler-utils
```

4. **Install Tesseract OCR (for OCR capabilities)**

For Windows: Download and install from [Tesseract at UB Mannheim.](https://github.com/UB-Mannheim/tesseract/wiki)

For macOS: Use Homebrew:
```bash
brew install tesseract
```

For Linux: Install using your package manager:
```bash
sudo apt-get install tesseract-ocr
```

Make sure to install additional system dependencies like Poppler and Tesseract as described above.

5. **Output**

The extracted data will be saved in both CSV and JSON formats. 

The output includes:
Technical and non-technical skills.
Details about internships and jobs, categorized by technical and non-technical roles.
Educational details such as degree, course, CGPA, HSC, and SSC.
Feel free to customize the file paths and commands as needed for your environment.
