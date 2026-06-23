# AI Resume Screening for HR

## Overview
This n8n workflow automatically screens resumes received through Gmail and matches them against a job description using AI.

## Workflow Process

1. Monitor Gmail inbox every 1 minute.
2. Download candidate resume from email attachments.
3. Upload resume to Google Drive.
4. Convert PDF into readable format.
5. Extract text from candidate resume.
6. Read Job Description document.
7. AI Agent compares resume with job requirements.
8. Generate structured candidate analysis.
9. Extract important information such as:
   - Candidate Name
   - Skills
   - Experience
   - Match Score
   - Strengths
   - Weaknesses
10. Store results automatically in Google Sheets.

## Features

- Automated Resume Screening
- AI-Based Candidate Matching
- Job Description Comparison
- Structured Candidate Evaluation
- Google Sheets Reporting
- No Manual Resume Review Required

## Tech Stack

- n8n
- Gmail
- Google Drive
- Google Sheets
- Groq LLM
- AI Agent
- Structured Output Parser

## Use Case

Designed for HR teams and recruiters to reduce manual effort in resume screening and shortlist suitable candidates faster.

## Workflow Screenshot

See the attached screenshot in this repository.

## Author

Chhavi Gupta
