# URL Security Report Generator

## 🚀 Project Overview

This project uses the **VirusTotal API** together with a **Large Language Model (LLM)** to analyze URLs for security threats and generate comprehensive, easy-to-understand reports.

- **VirusTotal** scans URLs to detect malware, phishing, and suspicious activities.
- The **LLM** (Google Gemini or similar) interprets VirusTotal’s findings and creates natural language summaries.

Ideal for cybersecurity professionals or developers looking to automate URL threat detection and reporting.

---

## ⚙️ Features

- Submit URLs to VirusTotal for scanning
- Retrieve detailed threat statistics
- Use an LLM to generate a security report
- Built with LangChain for easy extensibility

---

## 📋 Requirements

- Python 3.8+
- Internet connection for API requests

### Python Dependencies

```bash
pip install langchain==0.3.13 langchain-core==0.3.63 langchain-openai==0.2.14 requests python-dotenv
