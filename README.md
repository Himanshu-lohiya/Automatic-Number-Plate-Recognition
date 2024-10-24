# Automatic Number Plate Recognition (ANPR)

This project implements an Automatic Number Plate Recognition (ANPR) system using Optical Character Recognition (OCR). It processes images of vehicle number plates and extracts the registration numbers, converting them into readable text for further use in compliance systems or other applications.

## Features
- Detects and extracts number plates from images.
- Utilizes **EasyOCR** for Optical Character Recognition (OCR) of number plates.
- Outputs recognized text in uppercase format.
- Easily customizable to work with different image types and languages.


## Installation

To get started with the ANPR project, follow these steps:

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/Himanshu-lohiya/Automatic-Number-Plate-Recognition.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Automatic-Number-Plate-Recognition
    ```

3. Install the required dependencies using `pip`:
    ```bash
    pip install -r requirements.txt
    ```

4. Install **EasyOCR** and additional dependencies:
    ```bash
    pip install easyocr
    pip install opencv-python
    ```

