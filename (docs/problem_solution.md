# Problem-Solution Summary

## Problem Statement
Recruiters spend hours screening resumes manually, which is inefficient, biased, and prone to errors. Companies need an automated and intelligent way to screen job applicants based on job requirements.

## Proposed Solution
TalentAI is a multi-agent GenAI-powered assistant that:
- Analyzes job descriptions.
- Screens resumes intelligently.
- Scores and ranks candidates.
- Explains the match (transparency).

## Architecture Overview
- Agent 1: Job Requirement Analyzer
- Agent 2: Resume Parser & Ranker
- Backend: Python + FastAPI
- Model: GPT-based LLM with scoring logic
- Output: Candidate ranking + Match explanation

## Tech Stack
- Python
- FastAPI
- OpenAI API
- LangChain / LlamaIndex
