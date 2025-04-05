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

## Summary

Traditional resume screening is slow, manual, and often biased. TalentAI solves this by using intelligent agents that:
- Understand job requirements
- Parse and extract candidate qualifications
- Match and rank applicants based on relevance
- Provide clear justifications for each decision

This system is ideal for recruiters, HR teams, or platforms looking to scale their hiring process with AI.

---

## How to Run

### Prerequisites
- Python 3.8+
- OpenAI API Key (if using LLMs)
- Git

### Steps
```bash
# 1. Clone the repository
git clone https://github.com/yourusername/talentai-job-screening-assistant.git
cd talentai-job-screening-assistant

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the application
python src/main.py
Demo

Coming soon!
(You can add a screen recording, screenshots, or a link to a hosted demo here when ready.)


---

Contributors

[Usha Lakshmi Anumula] – AI Developer, Backend Lead

[Naga Lakshmi Gavalapalli] – Frontend Developer, UI/UX

---

License

This project is licensed under the MIT License.


---

Connect

For questions or contributions, feel free to open an issue or reach out on LinkedIn/GitHub!


