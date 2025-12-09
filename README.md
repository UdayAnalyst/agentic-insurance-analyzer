Agentic AI Insurance Claim Experience Analyzer

This project is an Agentic AI system built using the OpenAI Agents SDK.
It analyzes real customer claim experiences from platforms like:

Reddit

Quora

Twitter (X)

TikTok summaries

Online forums

Public user review sources

The system extracts real-world insights about how users experience insurance claims, including:

Claim approvals & denials

Delays, documentation issues

Customer service interactions

Smooth and successful claim processes

General complaints & positives

It then generates:

A clear summary

Structured insights

A full SWOT analysis

Optional UI for running queries easily

This helps consumers, analysts, and researchers understand how insurance companies actually perform from the perspective of real users.

Features
🔍 1. Claims-Focused Research Agent

Uses web search to gather real user stories about:

Claim handling experience

Customer support quality

Payout timelines

Any issues faced

Targets discussions from social platforms and public forums.

🧾 2. Structured Output (JSON)

The agent always returns clean JSON fields:

{
  "company": "",
  "product": "",
  "claim_difficulties": [],
  "claim_smooth_experiences": [],
  "common_complaints": [],
  "major_positives": [],
  "summary": ""
}

 3. SWOT Analysis Agent

Generates a strategic breakdown:

Strengths

Weaknesses

Opportunities

Threats

with special emphasis on claim performance.

 4. Simple Jupyter UI

A clean input form using ipywidgets:

Text input: Company

Text input: Product

“Run Analysis” button

Auto-rendered summary + SWOT

 Tech Stack

Python 3.12+

OpenAI Agents SDK

WebSearchTool

ipywidgets (for UI)

Jupyter Notebook

JSON for structured outputs

 Project Structure (Example)
/agentic-insurance-analyzer
│
├── notebook.ipynb               # Main Jupyter notebook
├── README.md                    # Project documentation
├── requirements.txt             # Python dependencies
└── demo.mp4                     # Optional demo video

🔧 Installation
pip install openai-agents ipywidgets


Enable widgets if using JupyterLab:

pip install jupyterlab_widgets


Restart the kernel after installation.

 Usage

Inside the notebook:

Enter the insurance company name

Enter the product/plan name

Click Run Analysis

View real claim experiences + SWOT summary

 Purpose

This project aims to:

Make insurance research more transparent

Replace marketing claims with real user experiences

Help people understand the actual claims process

Provide analysts with actionable insights

Demonstrate how agentic AI can automate complex research workflows

Contact

Feel free to reach out if you'd like to collaborate or explore this project further.

Author: Uday
