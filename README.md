# AI_Resume_Checker
Week-3 Internship Projects

⚠️ **Important:** The share link generated from Google Colab is temporary and will expire within **1 week**.

# Project Description
The application is built using Python and Gradio and can be run easily in Google Colab. It generates a shareable public link where users can upload their resumes and receive an evaluation score.

#Features
* Upload resume in PDF format
* Automatically extracts resume text
* Evaluates resume based on:
* Resume length
* Skills detection
* Email detection
* Experience section
* Education section
* Generates a resume score out of 100
* Provides suggestions for improvement
* Generates a public shareable link using Gradio

#Technologies Used
- Python
- Gradio – for creating the web interface
- pdfplumber – for extracting text from PDF resumes
- Google Colab – for running and hosting the project

#Installation and Setup
Step 1: Open Google Colab
Go to Google Colab and create a new notebook.
Step 2: Install Required Libraries
!pip install gradio pdfplumber
Step 3: Run the Python Code
Run the project code provided in the notebook.
Step 4: Launch the Application
app.launch(share=True)
This will generate a public link that opens the AI Resume Checker website.

#How it works
1. User uploads a resume in PDF format.
2. The system extracts text from the resume.
3. The program checks for skills, email, experience, and education sections.
4. A score is calculated based on these criteria.
5. The result and feedback are displayed to the user.

#Future Improvements
• Support DOCX resume uploads
• Advanced ATS resume scoring
• Integration with machine learning
• Resume keyword optimization
• Downloadable evaluation report
