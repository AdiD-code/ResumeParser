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
   
2.**Install the dependencies**

Install Python libraries using pip:
   ```bash
   pip install -r requirements.txt
   ```

Install Poppler:

For Windows: Download the binaries from [Poppler for Windows(https://github.com/oschwartz10612/poppler-windows)] and add the path to poppler/bin to your system's PATH environment variable.
