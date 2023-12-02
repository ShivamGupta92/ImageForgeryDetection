![build-passing](https://img.shields.io/badge/build-passing-brightgreen) ![test-passing](https://img.shields.io/badge/test-passing-brightgreen)

# Image Forgery Detection Project

## Overview
This project focuses on detecting image forgery using Error Level Analysis (ELA) and Edge Detection techniques. Image forgery refers to the manipulation or tampering of images to deceive viewers or convey false information. The combination of ELA and Edge Detection can enhance the accuracy of detecting forged regions within an image.

## Features
- Error Level Analysis (ELA): ELA is a forensic method that highlights areas in an image with different error levels, indicating potential manipulation. By comparing the error levels of different regions, we can identify discrepancies that may suggest forgery.

- Edge Detection: Edge detection is employed to identify abrupt changes in intensity, which can be indicative of manipulated or spliced regions within an image. The detection of edges helps in isolating potential areas of interest for further analysis.

## Dependencies
- Python 3.x
- OpenCV
- NumPy
- Matplotlib
Installation
Clone the repository:
```sh
git clone https://github.com/ShivamGupta92/ImageForgeryDetection.git
 ```
 
Navigate to the project directory:
```sh
cd image-forgery-detection
 ```

Install required dependencies
```sh
pip install -r requirements.txt
 ```

Run the forgery detection script:

```sh
python forgery_detection.py --image_path input/your_image.jpg
 ```
Replace your_image.jpg with the name of the image you want to analyze.

The script will generate output images in the output directory, highlighting potential forged regions.

Results
The results will be visualized in the output directory, providing insights into potential areas of forgery detected by ELA and Edge Detection techniques
