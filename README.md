# 🧭 RuleNavigator — Hackathon Rules. Simplified.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/menonmidhunm79-cloud/rule-navigator/blob/main/RuleNavigator_Colab.ipynb)

An AI-powered RAG assistant for hackathon rulebooks. Upload a PDF, DOCX or TXT rulebook and ask questions in plain English. Every answer comes with the rule text and page citation. Runs entirely in Google Colab (Python + Flask + vanilla HTML/JS).

<!-- Add your screenshots to /assets and uncomment:
![Landing](assets/landing.png)
![Dashboard](assets/dashboard.png)
-->

## Features
- **Upload & index**: PDF / DOCX / TXT rulebooks, parsed page by page and chunked for retrieval
- **Ask anything**: retrieval-augmented answers with source citations and page numbers
- **Two modes**: AI mode (Groq LLM answers) or *basic mode* (quoted rules with citations, no API key needed)
- **Dashboard**: rules by category, next deadline countdown, critical restrictions, recent questions
- **Deadline extraction**: dates and times pulled out of the rulebook automatically
- **Team Eligibility Checker**: check team size, age and status against the rules
- **Technology Compliance Checker**: check tools, APIs, AI assistants and paid services
- **Disqualification Risk Checklist**: the things that get teams removed, in one place
- **Rulebook Summary** and **Saved Answers**
- **Try sample rulebook** button for an instant demo

## Run it
1. Click the **Open in Colab** badge above
2. Run the cells top to bottom (installing packages takes about 1–2 minutes)
3. *(Optional)* paste a free Groq API key from <https://console.groq.com/keys> in cell 2, or press Enter to skip and use basic mode
4. Run the last cells to open the app inline or via a public tunnel link
5. Click **Try sample rulebook** to demo immediately

> The Cloudflare quick-tunnel link is public and temporary: it lives only while the Colab runtime is running. The "personal backup link" works only for your own Google account.

## Tech
Python · Flask · PyMuPDF · python-docx · pypdf · scikit-learn · sentence-transformers · FAISS · Groq API · vanilla JS/CSS

## Limitations
Single-user, in-memory demo state (resets when the runtime restarts). Check the official rulebook for anything critical; the assistant can make mistakes.

## License
MIT
