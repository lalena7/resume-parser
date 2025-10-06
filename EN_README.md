#Resume Parser & Analysis Tool

This project is designed to automatically process and analyze resumes from various sources, including Telegram chats (via API), local files, and potentially other platforms. The system filters and structures the data, extracts key information about candidates, evaluates their skills and experience, and generates conclusions and final reports for the HR department.

## Key Features

- **Resume Parsing**
Obtain and parse data from:
- Telegram chats (via API)
- Local text and table files
- Expandable to other formats (PDF, HTML, JSON, etc.)

- **Text Cleaning and Normalization**
- Removal of unnecessary characters, HTML tags, and formatting
- Bringing text to a uniform format for analysis

- **Candidate Filtering**

The system automatically selects relevant resumes:
- Resume selection from the entire data set
- Duplicate removal
- Filtering by work experience
- Checking for required and additional skills

- **Candidate Assessment with AI**
- Determining approximate level: Junior / Middle / Senior
- Highlighting work experience and key achievements
- Brief text analysis of candidate's compliance with job requirements

- **Report Generation**
- Generating CSV and XLSX files Detailed results
- Integration into HR systems is possible

## Technologies Used
- **Python** — primary development language
- **Telethon** — working with the Telegram API
- **Pandas**, **openpyxl** — data processing and report generation
- **tiktoken** — text tokenization for analysis
- **AI models** — semantic analysis of resume text

## Result
The system allowed HR specialists and recruiters to automate processing of a large number of resumes, speeding up the filtering and evaluation of candidates. The program significantly saved time and made candidate selection more convenient.

---

*The source code is not publicly available, as the project is part of a commercial development.*

**Contacts:**
- Email: siryenot@gmail.com
- Telegram: @siryenot
