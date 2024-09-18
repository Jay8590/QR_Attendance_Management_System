# QR Attendance Management System

## Overview

The QR Attendance Management System is a Python-based application designed to manage student attendance using QR codes. The system includes the following components:

### Fonts Folder

- **Fonts/**  
  Contains font files used in the application for displaying QR codes and other text elements.

### Home.py

- **Home.py**  
  The main entry point of the application. Responsible for initializing the GUI and handling user interactions. Imports necessary modules and sets up the application's layout.

### Pages Folder

- **pages/**  
  Contains additional Python files defining specific pages or features within the application, such as:
  - Student attendance tracking
  - QR code generation
  - Settings and configuration

### Requirements.txt

- **requirements.txt**  
  Lists the dependencies required to run the application, including Python libraries and frameworks.

### Students_QR_Codes

- **Students_QR_Codes/**  
  Stores generated QR codes for each student, used for attendance tracking.

## System Requirements

- Python 3.x
- Required libraries and frameworks listed in `requirements.txt`

## Setup and Installation

1. Clone the repository or download the source code.
2. Install the required dependencies by running:
   ```bash
   pip install -r requirements.txt
3. Run the application by executing:
   ```bash
    streamlit run Home.py

