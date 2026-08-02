<p align="center">
  <img src="ain-cover.png" alt="Ain Project Cover" width="100%">
</p>

<h1 align="center">عين | Ain</h1>
<h3 align="center">AI-Powered Municipal Infrastructure Assistant</h3>

<p align="center">
  A multi-agent AI system for analyzing, validating, and prioritizing citizen municipal infrastructure reports.
</p>

<p align="center">
  <a href="https://colab.research.google.com/github/judebingadeer/ain-municipal-infrastructure-assistant/blob/main/Ain_Municipal_Infrastructure_Assistant.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
  </a>
  &nbsp;
  <a href="https://sheets.new">
    <img src="https://img.shields.io/badge/Create-Google%20Sheet-16A34A?style=for-the-badge&logo=googlesheets&logoColor=white" alt="Create Google Sheet">
  </a>
</p>

> **Important:** GitHub displays the project files but does not run Gradio.  
> Click **Open in Colab**, run the cells in order, then the final cell generates a temporary public Gradio link.

---

## Project Overview

**Ain** converts unstructured citizen infrastructure reports into validated, structured municipal records. It extracts the issue, location, and description; reviews report quality; assigns priority; provides a confidence score; and optionally stores the result in Google Sheets.

<p align="center">
  <img src="project-overview.png" alt="Project Overview" width="95%">
</p>

---

## How It Works

Ain uses two specialized AI agents:

1. **Infrastructure Report Analyzer**  
   Extracts the issue type, location, and description.

2. **Infrastructure Quality Reviewer**  
   Validates the analysis, assigns priority, explains the reason, and returns the final JSON report.

<p align="center">
  <img src="how-it-works.png" alt="How Ain Works" width="95%">
</p>

---

## Development Process

<p align="center">
  <img src="development-stages.png" alt="Development Stages" width="95%">
</p>

<p align="center">
  <img src="agent-strategy.png" alt="Agent Strategy" width="95%">
</p>

---

## Tools & Technologies

<p align="center">
  <img src="tools-technologies.png" alt="Tools and Technologies" width="95%">
</p>

- Python
- CrewAI
- OpenRouter
- GPT-4o-mini
- Gradio
- Google Sheets
- Google Colab

---

## Results

<p align="center">
  <img src="result-preview-1.png" alt="Result Preview" width="95%">
</p>

<p align="center">
  <img src="result-preview-2.png" alt="Validated Result" width="95%">
</p>

---

## Run the Project

1. Click the **Open in Colab** button at the top.
2. Run the installation cell.
3. Enter a new OpenRouter API key when prompted.
4. Run the Google Sheets cell and approve access.
5. Run the final Gradio cell.
6. Open the generated `.gradio.live` link.

### Google Sheets

The notebook automatically creates or opens a spreadsheet named:

```text
Ain Infrastructure Reports
```

It also adds the required column headers automatically.

---

## Security

Never commit API keys, credentials, or tokens. If an API key was previously visible in any uploaded notebook, revoke it and generate a new one.

---

## Team

- Jwan Altamimi
- Jude Bingadeer
- Alnaifa Alshammari
- Sadeem Almuzaini
- Renad Aldosari
- Joud Aloraibi
