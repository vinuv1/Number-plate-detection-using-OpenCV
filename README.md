Number Plate Detection using OpenCV and Python

This repository contains a Python-based project that detects vehicle number plates using OpenCV, identifies the Indian state based on the plate’s alphanumeric code, and extracts the relevant details into an XML file.

🚀 Introduction

This project is designed to detect vehicle number plates from images or video streams using OpenCV.
Once the number plate is detected, the system:

Extracts the alphanumeric text.

Identifies the Indian state to which the vehicle belongs based on the first two characters of the number plate.

Saves all extracted information into an XML file for further use.

🔥 Features

Detect number plates from images or video streams

Extract the alphanumeric number from detected plates

Identify the Indian state using predefined state-code mapping

Save output (number, state, etc.) into an XML file

Easy to use, modular, and extendable for future improvements

🗺️ State Identification Logic

Indian vehicle number plates follow a format where the first two letters represent the state or union territory.

This project includes a predefined dictionary mapping state codes to state names.

Example State Codes
KA → Karnataka  
MH → Maharashtra  
DL → Delhi  
TN → Tamil Nadu  
...

📁 Output Format (XML Example)

An example of the XML output:

<Vehicle>
    <NumberPlate>KA01AB1234</NumberPlate>
    <State>Karnataka</State>
</Vehicle>

🛠️ Technologies Used

Python

OpenCV

XML Processing (Python's built-in libraries)

📌 Future Enhancements

Improve accuracy with deep learning–based detection models

Add OCR improvements using EasyOCR or Tesseract

Integrate with real-time CCTV feed

Create a GUI for user interaction
