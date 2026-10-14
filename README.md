# 🤝 Wefaq (وفاق) | AI-Powered Project Analysis & Team Building Platform

<p align="center">
  <img src="./screenshots/onboarding.jpg" alt="Wefaq Platform Interface" width="100%">
</p>

<p align="center">
  <b>An AI-powered platform for analyzing project ideas, measuring project similarity, and building student teams.</b>
</p>

---

## 💡 About The Project

**Wefaq (وفاق)** is an intelligent platform designed to empower students and developers to structure, analyze, and refine their technical ideas. By combining workflow automation and large language models (LLMs), Wefaq helps users avoid project duplication, gain deep insights into their proposals, and find the right team members based on complementary skill sets.

---

## 🎯 System Workflow

The user journey in Wefaq consists of three core stages:

1. **Wefaq Assistant (مساعد وفاق):** Collects structured input about the project, including project name, domain, proposed solution, core problem, and target audience.
2. **Wefaq Analysis (تحليل وفاق):** Runs an AI analysis to provide detailed feedback on the proposal and calculates a **Project Similarity Index** against existing ideas.
3. **Team Formation (تكوين الفرق):** Suggests optimal team compositions and required skill sets based on the analysis output.

---

## ✨ Key Features

- 📝 **Structured Idea Onboarding:** Easy-to-use form collecting key project metrics (Domain, Problem Statement, Solution, Target Audience).
- 🧠 **Deep AI Idea Analysis:** Evaluates project viability, potential risks, and technical requirements.
- 🔍 **Similarity Detection:** Compares the idea against database records to prevent redundant project themes.
- 👥 **Smart Team Matching:** Recommends team roles and skill requirements tailored to the project's scope.
- ⚡ **Seamless Webhook Integration:** Connects the front-end interface directly to automation workflows.

---

## 🛠️ Tech Stack

- **Front-end:** HTML5, CSS3, JavaScript / React
- **Workflow Automation:** [n8n](https://n8n.io/)
- **AI & NLP:** Google Gemini API
- **Data & APIs:** SerpAPI, REST Webhooks

---

## 📁 Repository Structure

```text
├── index.html              # Main web application interface
├── assets/                 # Styles, icons, and UI resources
│   ├── css/
│   └── js/
├── screenshots/            # UI preview images for documentation
│   └── onboarding.jpg
└── README.md               # Project documentation
