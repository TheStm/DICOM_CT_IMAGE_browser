# DICOM CT IMAGE BROWSER

## Overview
The DICOM CT Image Browser is a desktop application that allows users to view DICOM (Digital Imaging and Communications in Medicine) images,
especially CT (computed tomography). The project was developed using Python, PySide6, along with several libraries for DICOM image processing and visualization.
## Getting started
 - Install Python 3.8 or higher
 - Clone the repository to your local machine
 - Create a virtual environment and activate it
 - Install the required dependencies using pip install -r **_requirements.txt_**
 - Prepare folder with dicom files and run _**dicom_browser.py**_

## Instruction

- Upload folder with dicom series
- You can draw lines on picture by left click and check an actual distance value
<figure>
<img src="/examples/line.jpg" alt="LINE" style="width:100%">
<figcaption align = "center"><b>Description</b></figcaption>
</figure>
- You can hover your mouse over the photo and check HU value
- You can change current dicom file using slider on the right
- You can change brightness and contrast using sliders under dicom picture
- You can apply filters or change color pallet
- You can apply and change the value of threshold using slider
- You can apply lungs mask
- You can turn on WAND mode, draw lines, chose ROI and check its real surface area

