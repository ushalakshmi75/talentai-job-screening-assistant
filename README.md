# TalentAI: Multi-Agent Job Screening Assistant

TalentAI is an intelligent assistant designed to automate and enhance the job screening process using Generative AI and a multi-agent system. It analyzes job descriptions, parses candidate resumes, and ranks applicants based on relevance and qualifications—saving time and reducing human bias.

## Features
- Multi-agent architecture for modular decision-making
- Job description analysis and skill extraction
- Resume parsing and semantic similarity scoring
- Candidate ranking with transparent match explanations

## Tech Stack
- Python
- FastAPI
- OpenAI API / LangChain
- PDF/DocX parsing tools
- GitHub Actions (CI/CD)

## Project Structure
.├── docs/                     # Documentation │   └── problem_solution.md   # Problem and solution explanation ├── src/                      # Source code │   ├── agent_1/              # Job requirement analysis │   ├── agent_2/              # Resume screening and ranking │   ├── api/                  # Backend endpoints │   └── main.py               # Entry point ├── data/                     # Sample data (resumes, job descriptions) ├── models/                   # Custom or fine-tuned models ├── requirements.txt          # Python dependencies ├── README.md                 # This file └── LICENSE
