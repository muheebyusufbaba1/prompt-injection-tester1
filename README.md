# 🔍 Prompt Injection Tester

A Python security tool that tests AI systems for **prompt injection vulnerabilities** — the #1 risk in the OWASP Top 10 for LLMs.

Built by **Mrbabs007 (The Impacter)** as part of an LLM Security learning journey.

---

## What It Does

- Fires 10 real prompt injection attack techniques against any AI system
- Assigns severity ratings: Critical / High / Medium / Low
- Colour-coded terminal output showing live results
- Generates a professional dark-themed HTML report
- Detects if the AI's secret was leaked in any response

---

## Attack Techniques Covered

| # | Technique | Severity |
|---|-----------|----------|
| 1 | Direct Instruction Override | Critical |
| 2 | Role Play Attack (DAN) | High |
| 3 | Fake Authority Attack | Critical |
| 4 | Reverse Psychology | Medium |
| 5 | Translation Trick | Medium |
| 6 | Indirect Extraction | High |
| 7 | Completion Attack | High |
| 8 | Hypothetical Framing | Medium |
| 9 | Distraction Attack | Low |
| 10 | Emotional Manipulation | Low |

---

## Setup

**1. Clone the repo**
```bash
git clone https://github.com/muheebyusufbaba1/prompt-injection-tester1.git
cd prompt-injection-tester1
```

**2. Install dependencies**
```bash
pip install groq colorama python-dotenv
```

**3. Add your API key**

Create a `.env` file:

Get a free key at: console.groq.com

**4. Run the tester**
```bash
python tester.py
```

**5. Open the report**

Open `injection_report.html` in your browser.

---

## Skills Demonstrated

- LLM Security & Prompt Injection (OWASP LLM01)
- Python scripting & API integration
- Security findings reporting
- Secure API key handling

---

## About

**Mrbabs007 · The Impacter**
- Starknet Wolfpack Member
- Covalent Alchemist
- B.Sc. Cyber Security Science
- Web3 Security Engineer

*Part of a 28-week LLM Security self-study roadmap.*