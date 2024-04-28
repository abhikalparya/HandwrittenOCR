# Image-to-Text Conversion and Text Correction System

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-%23white.svg?style=for-the-badge&logo=OpenCV&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-%23F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-%2320BEFF.svg?style=for-the-badge&logo=Kaggle&logoColor=white)



## Objective
The objective of this project is to develop an AI-powered system capable of accurately converting written text from uploaded images into digital text and automatically correcting spelling and grammar errors in the converted text.

## Project Scope
This project encompasses the development of an end-to-end system that combines Optical Character Recognition (OCR) with Natural Language Processing (NLP) techniques to process images containing written text. The system will extract the text from the images and enhance its accuracy and readability through spelling and grammar corrections.

## Tasks
- **OCR Implementation:** Implement Optical Character Recognition (OCR) to extract text from images.
- **Text Correction Module:** Develop a module to correct spelling and grammar errors in the extracted text.
- **Integration and Testing:** Integrate the OCR and text correction modules into a cohesive system and thoroughly test its functionality and accuracy.

## Implementation

The implementation of the Image-to-Text Conversion and Text Correction System can be found here: [IPYNB File](https://github.com/abhikalparya/HandwrittenOCR/blob/main/handwriting-ocr.ipynb)

## Model Architecture

![model-graph](https://github.com/abhikalparya/HandwrittenOCR/assets/81465377/a5063d82-3689-4cc1-bf43-669a1f202f2e)

## Text Correction Module

The text correction module is designed to enhance the accuracy and readability of the extracted text by correcting spelling and grammar errors. 

The Text Correction Module is implemented as a set of Python functions that utilize external libraries for spell checking and grammar checking. These functions are invoked within the prediction pipeline after text extraction from images. The corrected text is then displayed alongside the original and predicted text for comparison and validation.



## Validation Sample Output

<img width="571" alt="validation_evaluation" src="https://github.com/abhikalparya/HandwrittenOCR/assets/81465377/22a95e34-bfa3-4caf-a3b7-f550a177bab1">


## Conclusion
The Image-to-Text Conversion and Text Correction System aims to provide a robust and efficient solution for converting written text from images into digital format while ensuring accuracy and readability through automated spelling and grammar corrections. By leveraging OCR and NLP techniques, the system offers a versatile tool for various applications, including document digitization, text extraction from images, and content correction.

## Future Enhancements
- **Language Support:** Extend language support for OCR and text correction to include multiple languages.
- **User Interface:** Develop a user-friendly interface for easy image upload, text extraction, and correction.
- **Performance Optimization:** Enhance the system's performance and accuracy through model optimization and tuning.
  
