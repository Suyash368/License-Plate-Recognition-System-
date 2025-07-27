# License Plate Recognition System using Machine Learning

This project implements a **License Plate Recognition (LPR)** system using Python and traditional Machine Learning techniques. The system is designed to detect license plates from vehicle images, segment the characters, and recognize them using a trained classifier.



## Table of Contents

- [Overview](#overview)
- [Workflow](#workflow)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Limitations](#limitations)


## Overview

The License Plate Recognition System is built in 3 stages:

1. **License Plate Detection**: Detect the rectangular plate area in the vehicle image.
2. **Character Segmentation**: Isolate individual characters from the detected plate region.
3. **Character Recognition**: Use a trained machine learning model to predict the alphanumeric characters.


##  Workflow

```text
Vehicle Image → Plate Detection → Character Segmentation → Character Classification → Output Text

Image is read and converted to grayscale.
Morphological operations and contour detection are used for plate detection.
Each character is resized and classified using a machine learning model (e.g., SVM or KNN).






