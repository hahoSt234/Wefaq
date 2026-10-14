# 🤝 Wefaq (وفاق) | AI-Powered Project Analysis & Team Building Platform

An AI-powered platform for analyzing project ideas, measuring project similarity, and building student teams.

---

## 💡 About The Project

**Wefaq (وفاق)** is an intelligent web-based platform designed to empower students and developers to structure, analyze, and refine their technical ideas. By combining front-end interfaces with workflow automation and large language models (LLMs), Wefaq helps users avoid project duplication, gain deep insights into their proposals, and find the right team members based on complementary skill sets.

---

## 🎯 System Workflow

The user journey in Wefaq consists of three core stages:

1. **Wefaq Assistant (مساعد وفاق):** Collects structured input about the project, including project name, domain, proposed solution, core problem, and target audience.
2. **Wefaq Analysis (تحليل وفاق):** Runs an AI analysis to provide detailed feedback on the proposal and calculates a **Project Similarity Index** against existing ideas.
3. **Team Formation (تكوين الفرق):** Suggests optimal team compositions and required skill sets based on the analysis output.

---

## ✨ Key Features

- 📝 **Structured Idea Onboarding:** Collects key project metrics (Domain, Problem Statement, Solution, Target Audience).
- 🧠 **Deep AI Idea Analysis:** Evaluates project viability, potential risks, and technical requirements.
- 🔍 **Similarity Detection:** Compares the idea against database records to prevent redundant project themes.
- 👥 **Smart Team Matching:** Recommends team roles and skill requirements tailored to the project's scope.
- ⚡ **Seamless Webhook Integration:** Connects the front-end interface directly to automation workflows.

---

## 🛠️ Tech Stack

- **Front-end:** HTML5, CSS3, JavaScript
- **Workflow Automation:** [n8n](https://n8n.io/)
- **AI & NLP:** Google Gemini API
- **APIs & Webhooks:** REST APIs / Webhook Integration

---

## 📁 Project Structure

```text
.
├── index.html       # Main web application interface
├── .gitignore       # Git ignore settings
└── README.md        # Project documentation
