# AI Resume Screening - HR Hiring Assistant

An n8n-based hiring automation that screens incoming resumes against defined job criteria using AI, helping HR teams shortlist candidates faster.

## 🎯 Problem

Manually reviewing every incoming resume against job requirements is slow and inconsistent, especially at scale — HR teams spend hours on initial screening before ever reaching the interview stage.

## ⚙️ How It Works

1. **Trigger**: New resume submissions are captured (e.g., via form, email, or upload).
2. **Parsing**: Resume content is extracted and structured.
3. **AI Evaluation**: An LLM compares the resume against defined job criteria (skills, experience, qualifications).
4. **Shortlisting**: Candidates meeting the criteria are automatically flagged/shortlisted.
5. **Notification**: Results are delivered to the HR team in a structured summary.

## 🛠️ Tools Used

- **n8n** — workflow orchestration
- **LLM API** (OpenAI / Gemini / Claude) — resume evaluation against job criteria
- **Form/Email trigger** — resume intake

## 📸 Workflow Screenshot

*(Add screenshot of your n8n canvas here)*

## 📄 Workflow Export

Full workflow JSON available in this repo — see `workflow.json`.

## 💡 Impact

Significantly reduces manual resume review time for HR teams by automatically shortlisting relevant candidates before human review.
