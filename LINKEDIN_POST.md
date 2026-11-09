Hackathon rulebooks are 30 pages of fine print. One missed line can get a team disqualified. 😬

So I built RuleNavigator: an AI assistant that reads the rulebook for you.

Upload a PDF, DOCX or TXT and you can:
🔎 Ask questions in plain English and get answers with page citations
⏰ See every deadline extracted, with a countdown to the next one
👥 Check your team against the eligibility rules
🛠️ Check whether your tech stack, APIs and AI tools are allowed
🚨 Review a disqualification risk checklist
📋 Get a one-page rulebook summary

How it works: retrieval-augmented generation (RAG) with sentence-transformers + FAISS for search, a Groq LLM for answers, and a basic mode that quotes the exact rules when no API key is available.

Built with Python, Flask and vanilla JS, and it runs entirely in Google Colab. There is even a sample rulebook so you can try it in one click.

Code + one-click Colab: https://github.com/menonmidhunm79-cloud/rule-navigator

What's the strangest hackathon rule you have ever run into? 👇

#Hackathon #RAG #GenerativeAI #LLM #Python #Flask #OpenSource #BuildInPublic
