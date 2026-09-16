# AI-Powered Onion Quality Assessment and Grading System

## 📌 Project Overview

The AI-Powered Onion Quality Assessment and Grading System is a computer-vision-based application designed to assess the visible quality of onions and classify them into predefined quality grades.

The system analyzes an uploaded or captured onion image and evaluates visible characteristics such as size, shape, color, spots, damage, rot, sprouting, and other external defects.

The goal is to provide a standardized, transparent, and consistent method for onion quality assessment.

---

## 🎯 Objectives

- Automate onion quality assessment using computer vision.
- Analyze visible quality parameters from onion images.
- Identify external defects and quality issues.
- Assign a predefined quality grade.
- Provide a simple digital interface for users.
- Reduce inconsistency in manual quality inspection.

---

## 🔄 Project Workflow

1. Capture or upload an onion image.
2. Preprocess the input image.
3. Detect and analyze visible onion characteristics.
4. Evaluate quality parameters.
5. Identify visible defects.
6. Assign a predefined quality grade.
7. Display the final quality assessment.

---

## 🧠 Computer Vision Workflow

The system uses a computer-vision workflow consisting of:

- Image Input
- Image Preprocessing
- Feature/Quality Analysis
- Defect Detection
- Quality Evaluation
- Grade Classification
- Digital Result Generation

---

## 🤖 Use of IBM Bob in the Project

IBM Bob was used as an AI-assisted development environment throughout the project to support the design, development, and testing of the AI-powered Onion Quality Assessment and Grading System.

IBM Bob helped the team understand project requirements, structure the application workflow, and develop different components of the system.

It was used to assist in creating the computer-vision workflow, including image input, image preprocessing, quality-parameter analysis, and onion grade classification.

IBM Bob also helped in developing the user interface for uploading onion images and displaying the detected quality parameters and final grade.

During development, IBM Bob was used for:

- Code generation
- Code explanation
- Debugging
- Error identification
- Testing
- Improving project structure
- Feature implementation and modification

The team interacted with the AI assistant using natural-language instructions, which helped simplify technical development tasks.

---

## 🛠️ Technologies Used

- Python
- Computer Vision
- Image Processing
- Artificial Intelligence
- Machine Learning
- Streamlit
- IBM Bob

---

## 📂 Project Structure

```text
AI-Onion-Quality-Assessment/
│
├── README.md
├── app.py
├── requirements.txt
│
├── src/
│   ├── image_processing.py
│   ├── quality_analysis.py
│   └── grading.py
│
├── dataset/
│   └── README.md
│
├── test/
│   └── test_app.py
│
├── docs/
│   ├── project_report.pdf
│   └── project_ppt.pdf
│
└── images/
    └── sample_onion.jpg
