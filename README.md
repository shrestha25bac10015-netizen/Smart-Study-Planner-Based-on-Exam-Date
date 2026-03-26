
# 📚 Smart Study Planner

## Short Description

Smart Study Planner is a Python-based tool that generates a personalized study schedule based on subjects, syllabus size, and exam date. It helps students manage time efficiently and prepare systematically for exams.

---

# Project Overview

Smart Study Planner helps students organize their exam preparation automatically. Students enter their subjects, number of chapters, and exam date. The system then calculates the remaining days and distributes chapters across available days to generate a structured study plan.

This project improves productivity, reduces last-minute stress, and helps manage multiple subjects effectively.

---

# Dataset

This project does not require an external dataset.
The data is generated dynamically based on user input:

• Subject names
• Number of chapters
• Exam date
• Generated study schedule

All data is created and processed within the application.

---

# Structure of the Code

The project consists of the following main sections:

### 1. Import Libraries

Used libraries:

* Streamlit (User Interface)
* Pandas (Data handling)
* Datetime (Date calculations)

### 2. User Input Section

Collects:

* Number of subjects
* Subject names
* Chapters per subject
* Exam date

### 3. Study Plan Logic

* Calculate remaining days
* Calculate total chapters
* Distribute chapters across days
* Generate study schedule

### 4. Output Section

Displays:

* Study plan table
* Progress chart
* Success message

---

# Project Structure

```
Smart-Study-Planner/
│
├── smart_study_planner.py
├── README.md
```

---

# Installation

## Step 1: Install Python

Download Python from:
https://www.python.org/downloads/

---

## Step 2: Install Required Libraries

Open terminal and run:

```
pip install streamlit pandas
```

---

## Step 3: Run the Project

Navigate to project folder and run:

```
streamlit run smart_study_planner.py
```

---

## Step 4: Open in Browser

The project will open automatically at:

```
http://localhost:8501
```

---

# Features

• Automatic study plan generation
• Multiple subject management
• Exam countdown
• Progress visualization
• Simple interface

---
