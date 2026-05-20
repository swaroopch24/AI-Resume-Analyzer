# 🚀 AI Resume Analyzer

An AI-powered web application that evaluates resumes, calculates ATS compatibility, detects skill gaps, and provides intelligent improvement suggestions using Google Gemini AI.

This project combines rule-based analysis with LLM intelligence to simulate how modern Applicant Tracking Systems (ATS) analyze resumes during hiring.

---

# 🎯 Problem Statement

Many resumes are rejected by ATS systems before reaching recruiters because of:

- Missing keywords
- Weak project descriptions
- Lack of measurable achievements
- Poor formatting and structure
- Missing technical skills

This project helps candidates improve their resumes instantly through automated AI-driven analysis.

---

# ✨ Features

- 📄 Upload Resume in PDF Format
- 🧠 Extract Resume Text Automatically
- 📊 ATS Compatibility Score Calculation
- 🧩 Missing Skills Detection
- 💡 Rule-Based Resume Suggestions
- 🤖 AI-Powered Recommendations using Gemini
- 🛡 API Failure Fallback Handling
- 🎨 Clean and Responsive Dashboard
- ⚡ Fast Resume Processing

---

# ⚙️ How It Works

1. User uploads resume PDF
2. System extracts text from resume
3. Skills are matched with predefined datasets
4. ATS score is calculated
5. Resume sections are validated
6. Gemini AI generates smart improvement suggestions
7. Results are displayed on the dashboard

---

# 🧠 System Architecture

```text
User Upload Resume
        ↓
PDF Text Extraction (PyPDF2)
        ↓
Skill & Keyword Analysis
        ↓
ATS Score Calculation
        ↓
Gemini AI Suggestions
        ↓
Dashboard Results Display
```

---

# 🛠 Tech Stack

- Python
- Flask
- PyPDF2
- Google Gemini API
- HTML5
- CSS3
- JavaScript

---

# 📂 Project Structure

```text
AI-Resume-Analyzer/
│
├── static/
│   ├── css/
│   ├── uploads/
│
├── templates/
│   ├── index.html
│   ├── result.html
│
├── app.py
├── requirements.txt
├── .env
├── README.md
```

---

# ▶️ Run Locally

## 1️⃣ Clone Repository

```bash
git clone https://github.com/swaroopch24/AI-Resume-Analyzer.git
```

## 2️⃣ Navigate to Project

```bash
cd AI-Resume-Analyzer
```

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

## 4️⃣ Create `.env` File

```env
GEMINI_API_KEY=your_api_key_here
```

## 5️⃣ Run Application

```bash
python app.py
```

## 6️⃣ Open Browser

```text
http://127.0.0.1:5000
```

---

# 📸 Screenshots

## 🏠 Landing Page

_Add Screenshot Here_

## 📊 Analysis Dashboard

_Add Screenshot Here_

---

# 🎯 Use Cases

- Students preparing for placements
- Resume optimization
- ATS preparation
- Skill gap analysis
- Career development guidance
- Internship applications

---

# 🛡 Reliability

If the Gemini API fails or quota exceeds, the system:

- Prevents application crashes
- Shows fallback recommendations
- Maintains smooth user experience
- Continues ATS analysis normally

---

# 🔮 Future Improvements

- Resume vs Job Description Matching
- AI Bullet Point Rewriting
- Recruiter-style Resume Rating
- Career Role Recommendations
- Downloadable PDF Reports
- Multi-Resume Comparison

---

# 👨‍💻 Author

**Swaroop Ch**  
Aspiring Software & AI Engineer

GitHub: https://github.com/swaroopch24

Project Link: https://github.com/swaroopch24/AI-Resume-Analyzer

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub and sharing it with others.
