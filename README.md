AI Resume Screening & Candidate Ranking System

This project is an AI-powered resume screening and ranking system built using Streamlit, PyPDF2, scikit-learn, and pandas. It allows recruiters to upload multiple resumes in PDF format and rank them based on their similarity to a given job description using TF-IDF vectorization and cosine similarity.

Features

Upload multiple PDF resumes

Input a job description

Automatically extract text from resumes

Use TF-IDF vectorization to process text

Compute cosine similarity to rank resumes

Display resumes sorted by relevance score


Installation

Prerequisites

Ensure you have Python 3.8+ installed. You also need pip to install dependencies.

Steps

1. Clone the repository:

git clone https://github.com/satyam2003-cpu/project_resume_screening.git
cd ai-resume-screening


2. Install dependencies:

pip install -r requirements.txt


3. Run the Streamlit app:

streamlit run resume_app.py



Usage

1. Open the web app in your browser.


2. Enter the job description in the provided text box.


3. Upload PDF resumes using the file uploader.


4. The app will analyze and rank resumes based on their similarity to the job description.


5. The results are displayed in a sorted table with resume names and similarity scores.



Technologies Used

Streamlit – for building the interactive web UI

PyPDF2 – for extracting text from PDFs

scikit-learn – for TF-IDF vectorization and cosine similarity

pandas – for handling and displaying results


Fixing Common Issues

ModuleNotFoundError: If you get an error like No module named ‘streamlit’, run:

pip install streamlit

Empty Resume Text: If some resumes don’t get ranked properly, ensure they have selectable text (not scanned images).


Contributing

Feel free to fork this project and submit pull requests to improve it. If you find any bugs, open an issue.

License

This project is licensed under the MIT License.
