# AI-Based Resume Screening Platform

## Project Overview

The **AI-Based Resume Screening Platform** is designed to streamline the hiring process by leveraging AI to match candidates with job requirements. Recruiters can post job descriptions and upload resumes in bulk. The system uses **Mistral AI** to intelligently evaluate each resume, extract relevant details, and present a ranked shortlist of the most suitable candidates.


### GitHub Repositories

- **Main Project Repo**: [Resume Parser GitHub Repository](https://github.com/Himajachirutha/Resume-Parser)
##my contribution in this project 
- **Complete Code Commit**: [Final Commit - Resume Parser](https://github.com/Himajachirutha/Resume-Parser/commit/316ac26e99a985f5cc784346073029b79fed772e)

---

## My Contribution

- Developed the **core backend** using Flask.
- Integrated **Mistral AI** for intelligent resume analysis and ranking.
- Implemented **job posting**, **resume upload**, and **shortlisting logic**.
- Designed **subscription-based access control** and **user roles**.
- Built the **recruiter dashboard** with AI-generated insights and download options.

---

## Core Files

```bash
Resume-Parser/
├── app.py
├── templates/
│   ├── create_job.html
│   ├── payment.html
│   └── view_shortlist.html
└── utils/
    └── resume_processor.py
##  Sprint Objectives (Refer to Appendix)

| Sprint | Key Features Implemented |
|--------|---------------------------|
| Sprint 1 | Resume Parsing, Normalization, Error Handling |
| Sprint 2 | Resume & Job Upload UI, Subscription Flow |
| Sprint 3 | Mistral AI Integration, Dashboard UI |
| Sprint 4 | AI Insights, Resume Download, Final UI Polish |

---

## Commit Summary Table

### Sprint 1 Commits

| Date       | Commit Hash | Description                                                       | User Story | Task ID  |
|------------|-------------|-------------------------------------------------------------------|------------|----------|
| 5/21/2024  | `55b653a`   | Implemented resume parsing logic using NLP and OCR               | US1        | US1.1    |
| 5/22/2024  | `78d4f2b`   | Added error handling for incomplete resumes                      | US1        | US1.2    |
| 5/23/2024  | `92e1c4d`   | Normalized extracted data                                        | US1        | US1.3    |
| 5/24/2024  | `a1b2c3d`   | Integrated parser with job description matching                  | US1        | US1.4    |

---

###  Sprint 2 Commits

| Date       | Commit Hash | Description                                                                       | User Story | Task ID  |
|------------|-------------|-----------------------------------------------------------------------------------|------------|----------|
| 3/31/2025  | `c3a101b`   | Flask setup, login/signup, job input fields, and ZIP file upload implemented     | SC1.1, SC1.4 | #101, #102, #103 |

---

###  Sprint 3 Commits

| Date       | Commit Hash | Description                                                                       | User Story | Task ID          |
|------------|-------------|-----------------------------------------------------------------------------------|------------|------------------|
| 4/2/2025   | `fabd6e3`   | Readme updated, recruiter dashboard UI and Mistral AI parsing added               | SC1.1, SC1.2, SC1.3 | #201–#206         |

---

###  Sprint 4 Commits

| Date       | Commit Hash | Description                                                                       | User Story | Task ID          |
|------------|-------------|-----------------------------------------------------------------------------------|------------|------------------|
| 4/14/2025  | `316ac26`   | Final commit: UI, AI insights, download logic, subscription restrictions         | SC1.3, SC1.4 | #207–#211         |

---

##  Appendix: Work Summary Tables

###  Sprint 1 - Resume Parsing Core Logic

| User Story | Description                         | Task ID | Task                             | Hours | Status     |
|------------|-------------------------------------|---------|----------------------------------|--------|------------|
| US1        | Implement Resume Upload & Parsing   | US1.1   | Develop Resume Parsing Logic     | 10     |  Complete |
| US1        |                                     | US1.2   | Handle Poorly Formatted Resumes  | 5      |  Complete |
| US1        |                                     | US1.3   | Normalize Extracted Data         | 2      |  Complete |
| US1        |                                     | US1.4   | Send Data to Matching Agent      | 2      |  Complete |
| US2        | Analyze Job Descriptions            | US2.1   | Keyword Extraction, Similarity   | 7      |  Complete |
| US3        | Bias Mitigation                     | US3.1–US3.4 | Anonymization, Reporting         | 13     |  Complete |

---

###  Sprint 2 - Upload and Subscription Features

| User Story | Task Description                    | Task ID | Hours | Status     |
|------------|-------------------------------------|---------|--------|------------|
| SC1.1      | Job Description Upload UI           | #101    | 2h     | Complete |
| SC1.1      | Resume ZIP Upload                   | #102    | 3h     |  Complete |
| SC1.4      | Subscription Auth UI & Flow         | #103    | 3h     |  Complete |

---

### Sprint 3 - Mistral AI + Dashboard

| User Story | Task Description                    | Task ID | Hours | Status     |
|------------|-------------------------------------|---------|--------|------------|
| SC1.1      | Validate ZIP & Resume Limits        | #201–#202 | 6h   |  Complete |
| SC1.2      | Mistral AI & Matching Logic         | #203–#204 | 11h  |  Complete |
| SC1.3      | Recruiter Dashboard + Shortlist UI  | #205–#206 | 9h   |  Complete |

---

### Sprint 4 - Final Enhancements

| User Story | Task Description                    | Task ID | Hours | Status     |
|------------|-------------------------------------|---------|--------|------------|
| SC1.3      | AI Insights, Resume Download        | #207–#209 | 11h  |  Complete |
| SC1.4      | Resume Upload Restrictions          | #210–#211 | 9h   |  Complete |

---

## Tech Stack

- Python, Flask
- HTML, Jinja2 templates
- Mistral AI (via API integration)
- Resume parsing: `Spacy`, `PyPDF2`, `OCR (Tesseract)`
- SQLAlchemy, SQLite (local DB)
- Bootstrap CSS (for UI styling)

---

## Contact

Developed by **Himaja Chirutha**  
[GitHub Profile](https://github.com/Himajachirutha)  
Hosted Project: https://himajachirutha.github.io/chiruthahimaja04.github.io/
