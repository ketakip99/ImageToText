# 🧠 Image-to-Audio Converter for Accessibility | Machine Learning Project

## Overview
This project implements a machine learning-powered system that reads printed text from an image and converts it into audible speech. Designed with accessibility in mind, this tool empowers users—especially the visually impaired or audiobook enthusiasts—to access printed content through voice.

## Problem Statement
Not all books come with an audio version. Visually impaired readers often lack access to printed content. This system bridges that gap by digitizing text from physical media and vocalizing it using a user-friendly interface.

## Key Features
- 📸 **Image Input**: Upload scanned or photographed text images.
- 🔍 **OCR Engine**: Extracts text using Tesseract OCR.
- 🔊 **Text-to-Speech**: Converts extracted text into audio using gTTS.
- 🖥 **User Interface**: Simple Streamlit-based GUI for instant interaction.

## Tech Stack
- Python  
- OpenCV, Pytesseract  
- Google Text-to-Speech (gTTS)  
- Streamlit for GUI

## Dataset
The OCR engine was fine-tuned using 60,000+ samples across 94 characters, 8 fonts, and 4 styles.

## Outcome
The tool successfully processes image inputs to produce readable and audible outputs with high accuracy. It promotes inclusivity and showcases the real-world application of OCR and TTS models.

## References
- [Tesseract OCR Documentation](https://tesseract-ocr.github.io/docs/tesseracticdar2007.pdf)  
- [OCR Using KNN - TDS Article](https://towardsdatascience.com/optical-character-recognition-with-knn-classifier-10fd220ed797)
