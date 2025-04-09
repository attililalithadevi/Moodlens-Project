# Moodlens-Project
AI-Powered Emotion Detection System

**Overview**
MoodLens is an innovative emotion detection system built with Python, leveraging AI and computer vision to analyze facial emotions from images. Whether capturing a live photo via webcam or uploading an existing image, MoodLens uses the DeepFace library to detect emotions (e.g., happy, sad, angry) and visualizes results in an interactive bar graph. Designed for Google Colab with an intuitive ipywidgets-based interface, this project showcases a blend of technical skills and practical application.


![ML1](https://github.com/user-attachments/assets/57dd3cf4-37a6-480e-a263-818c3b68cc48)


![ML2](https://github.com/user-attachments/assets/0d0ec81b-7918-4459-809f-a37ff7c4f57f)



# Key Features
**Real-Time Webcam Capture:** Snap a photo directly from your webcam with a single click.
**Image Upload Option:** Analyze emotions from any uploaded image (.jpg, .jpeg, .png).
**Dynamic Visualization:** Displays the input image alongside a bar graph of emotion percentages.
**User-Friendly Interface:** Built with ipywidgets for an interactive experience in Colab.
**AI-Driven Insights:** Powered by DeepFace for accurate emotion recognition.



# Skills Demonstrated
**AI & Machine Learning:** Utilized pre-trained DeepFace models for emotion analysis.
**Computer Vision:** Processed images with OpenCV for real-time detection.
**Data Visualization:** Created dynamic bar graphs using Matplotlib.
**Interactive UI:** Implemented ipywidgets for a GUI-like experience in a cloud environment.
**Problem Solving:** Integrated webcam functionality via JavaScript in Colab.


# Installation
To run MoodLens locally or in Google Colab, ensure you have the required dependencies installed.

# Prerequisites
Python 3.x
Google Colab (recommended for full functionality)
Webcam (for capture feature)

# Dependencies
Run the following command to install the necessary packages:
""
pip install deepface opencv-python matplotlib numpy ipywidgets
""

# How to Run in Google Colab

**1.Open Colab:**
Go to Google Colab.
Create a new notebook.

**Upload the Code:**
Copy the code from MoodLens.ipynb (or the .py file) into a code cell.
Alternatively, upload the notebook directly from this repository.

**Run the Code:**
Click the play button (▶️) or press Shift + Enter.
Wait for the packages to install (takes ~1-2 minutes).

**Interact with MoodLens:**
A widget interface will appear with two buttons:
**Capture from Webcam:** Click to open your webcam, then click "Capture" in the video feed.
**Upload Image:** Click to upload an image file.
Results (image and emotion graph) will display below the buttons.


# Example Output
**Input Image:** Displayed on the left.
**Emotion Graph:** Bar chart on the right showing percentages for emotions (e.g., Happy: 85.3%).
**Text Result:** Below the graph, e.g., "This picture is having Happy emotion."


# Project Structure
MoodLens/
│
├── MoodLens.ipynb      # Main Jupyter notebook with the code
├── README.md           # This file

# Usage

**Webcam Capture:** Click "Capture from Webcam," allow camera access, and press "Capture" when ready.
**Image Upload:** Click "Upload Image," select a file, and wait for analysis.
**Results:** View the image, emotion percentages, and dominant emotion in the output.

# Potential Applications 

**Mental Health Tools:** Monitor emotional states for well-being apps.
**Customer Feedback:** Analyze reactions in real-time for businesses.
**Interactive Media:** Enhance gaming or educational platforms with emotion detection.

# Limitations

Requires a webcam and browser permissions for capture functionality.
DeepFace accuracy depends on image quality and face visibility.
Designed for Colab; local execution requires GUI adjustments (e.g., Tkinter).

# Future Enhancements

Add support for video emotion analysis.
Improve accuracy with custom-trained models.
Develop a standalone desktop app with PyQt or PySimpleGUI.

# Why Recruiters Should Care

**MoodLens demonstrates my ability to:**

Build practical AI solutions with real-world impact.
Integrate multiple technologies (AI, CV, UI) seamlessly.
Write clean, well-documented code (see line-by-line comments in the notebook).
Innovate in cloud-based environments like Colab.

# Contact

**Author:** Lalitha Devi Attili

**Email:** attililalithad03@gmail.com

**LinkedIn:** https://www.linkedin.com/in/lalitha-devi-attili/

**GitHub:** https://github.com/attililalithadevi
