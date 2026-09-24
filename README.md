# 🤖 LLM-Based Resume Parser & Candidate Evaluator

An AI-powered resume parsing and candidate evaluation system that uses Large Language Models (LLMs) to understand resumes, extract relevant candidate information, compare profiles with job requirements, identify skill gaps, calculate an overall match score, and generate a concise AI-powered final verdict.

This project was developed as part of my AI Engineering learning journey to explore how LLMs can be integrated into a practical real-world recruitment workflow.

---

## 📌 Project Overview

Recruiters often need to analyze a large number of resumes for a single job opening. Manually reviewing resumes and comparing candidate profiles with job requirements can be time-consuming.

This project aims to automate the initial candidate evaluation process using an LLM-based pipeline.

The system takes candidate resumes and job requirements as input and generates structured candidate evaluations containing:

- Candidate information
- Matching skills
- Missing important skills
- Experience analysis
- Overall match percentage
- Detailed candidate analysis
- Short AI-generated final verdict
- Candidate ranking

The goal is to transform unstructured resume information into structured and actionable recruitment insights.

---

## ✨ Key Features

### 📄 1. Resume Parsing

The system processes candidate resumes and extracts relevant information using an LLM.

Instead of depending only on traditional keyword extraction, the system uses the contextual understanding capabilities of an LLM to analyze the resume.

---

### 🧠 2. LLM-Based Candidate Evaluation

The LLM evaluates each candidate profile against the given job requirements.

The evaluation considers factors such as:

- Technical skills
- Programming languages
- Data Structures & Algorithms
- Tools and technologies
- Development experience
- Internship experience
- Relevant projects
- Communication-related skills
- Other role-specific requirements

---

### 🔍 3. Matching Skills Detection

The system identifies skills from the candidate's profile that match the required skills for the given role.

Example:

```text
Matching Skills:
- C++
- Python
- Data Structures
- Algorithms
- GitHub
- AWS
- CI/CD
- Docker
- Kubernetes
