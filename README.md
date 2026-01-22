# Traffic-and-Vehicle-Data-Analysis-Project-Establishment
##  Overview

This project analyzes vehicle movement data collected from toll systems to generate traffic insights. It includes an Automatic Number Plate Recognition (ANPR) system that detects Indian vehicle license plates using deep learning and stores extracted data for further analysis and reporting.

##  Tech Stack

* **Python** (Pandas, NumPy)
* **SQL**
* **YOLO** – License plate detection
* **OpenCV** – Image processing
* **PyTesseract** – OCR for number plate extraction
  
##  Features

* Automatic detection and extraction of Indian license plates
* Storage of vehicle numbers with timestamps in a database
* Cleaning and structuring of traffic data
* Traffic frequency and peak hour analysis
* Dashboard-ready datasets for reporting


##  Data Analysis

* Vehicle count per time interval
* Peak traffic hour identification
* Repeated vehicle frequency analysis
* Time-based traffic trends

##  Workflow

1. Capture vehicle images/videos from toll systems
2. Detect number plates using YOLO
3. Extract text using PyTesseract
4. Store number plates and timestamps in SQL database
5. Analyze traffic patterns using Python
6. Generate summary datasets for dashboards

##  Use Cases

* Toll plaza traffic monitoring
* Smart city traffic analysis
* Law enforcement vehicle tracking
* Operational traffic insights
