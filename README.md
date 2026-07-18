# AI Resume Analyzer

An AI-powered Resume Analyzer that parses resumes (PDF/DOCX), extracts structured information using Groq LLM and Pydantic, compares candidates against a job description, and ranks them based on their match score.

## Features

- Parse PDF and DOCX resumes
- Extract structured candidate information
- Analyze job descriptions
- AI-powered resume matching
- Candidate ranking
- JSON structured outputs using Pydantic

## Tech Stack

- Python
- Groq API
- Pydantic
- PyPDF
- python-docx
- python-dotenv

## Project Structure

```
AI-Resume-Analyzer/
│
├── resumes/
├── main.py
├── minor_project_resume_tester.py
├── README.md
├── pyproject.toml
├── uv.lock
└── .gitignore
```

## Installation

```bash
git clone https://github.com/YOUR_USERNAME/AI-Resume-Analyzer.git
cd AI-Resume-Analyzer
pip install -r requirements.txt
```

Create a `.env` file:

```
GROQ_API_KEY=your_api_key_here
```

Run:

```bash
python minor_project_resume_tester.py
```

## Sample Output

```
Processing: john_carter.docx

Score: 92

TOP 2 CANDIDATES

John Carter - 92%

Sarah Kim - 88%
```

## Future Improvements

- Streamlit Web UI
- FastAPI Backend
- Database Integration
- Batch Processing
- Resume Upload Interface

## Author

Mohammed Rizwan

GitHub: https://github.com/riizwannx
LinkedIn: https://www.linkedin.com/in/mohammedriizwan/
