# 🤖 AI Resume Screener

An AI-powered resume screening tool built with vanilla HTML/CSS/JS and the **Claude API**. Built as part of the Nutrabey AI Automation Intern assessment.

---

## 🚀 How to Use

**No installation. No server. Just open the file.**

1. Clone or download this repo
2. Open `ai-resume-screener.html` in any modern browser (Chrome, Firefox, Edge)
3. That's it — the app is ready to use

> **Note for reviewers:** An Anthropic API key is already embedded in the app. No setup required.

---

## ✨ Features

| Feature | Details |
|---|---|
| **AI Scoring** | Each resume scored 0–100 against the JD using Claude |
| **Candidate Ranking** | Automatically ranked by score |
| **Strengths & Gaps** | 3 specific strengths and gaps per candidate |
| **Recommendation** | Strong Fit / Moderate Fit / Not Fit |
| **Summary** | 2-sentence AI-written summary per candidate |
| **Progress Tracking** | Live per-candidate analysis progress |
| **Copy Report** | One-click plain-text report export |
| **Sample Data** | Built-in sample JD + 5 candidates to demo instantly |

---

## 🛠 Tech Stack

- **Frontend**: Vanilla HTML, CSS, JavaScript (zero dependencies)
- **AI**: [Claude claude-sonnet-4-20250514](https://www.anthropic.com/claude) via Anthropic API
- **Fonts**: Sora + JetBrains Mono (Google Fonts)

---

## 📸 How It Works

```
Job Description  ──┐
                   ├──► Claude API (claude-sonnet-4-20250514) ──► Score + Ranking
Candidate Resume ──┘                                             + Strengths/Gaps
                                                                 + Recommendation
```

The system sends each resume + JD to Claude with a structured prompt asking for a JSON response containing the score, strengths, gaps, recommendation, and summary. Results are ranked and displayed in a clean dashboard.

---

## 📁 Project Structure

```
ai-resume-screener/
├── ai-resume-screener.html    ← Everything. The entire app.
└── README.md     ← This file.
```

---

## 💡 Sample Data

Click **"↓ Load sample JD"** and **"↓ Load 5 sample candidates"** to instantly populate the tool with realistic demo data for the Nutrabey AI Intern role — no typing required.

---

*Built for Nutrabey AI Automation Intern Assessment — Problem 1: AI Resume Screening System*
