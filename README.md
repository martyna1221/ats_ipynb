# ats_ipynb
Applicant tracking system using Python libraries

The provided Applicant Tracking System (ATS) code uses Python libraries to process and analyze job descriptions and resumes. 
These job descriptions are sourced from job posts that have been previously scraped from LinkedIn. The code extracts text from DOCX and PDF files, 
converting these documents into readable string formats. Leveraging Natural Language Processing (NLP) techniques such as TF-IDF Vectorization, 
the code calculates a similarity score between a resume and a job description, ranking it on a scale from 0 to 100. This score represents how well 
the resume aligns with the job's requirements. Additionally, it suggests improvements for a candidate's resume by identifying pivotal keywords 
present in the job description but missing in the resume, ensuring applicants are more tailored to specific job positions.
