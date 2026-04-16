# 🤖 AI-POWERED-RESUME-ANALYZER

An AI-powered Resume Analyzer that evaluates resumes against a given Job Description (JD), identifies missing skills, and predicts an ATS (Applicant Tracking System) score using Google Gemini API.

---

## 🚀 Features

* 📌 Input Job Description
* 📤 Upload Resume (PDF / DOCX)
* 🤖 AI-powered resume analysis using Gemini
* 🔍 Identify matching and missing keywords
* 📊 Generate ATS Score (out of 100)
* 🎯 Predict selection chances
* 💡 Smart suggestions to improve resume

---

## 🧠 How It Works

1. Extracts text from uploaded resume
2. Sends resume + job description to Gemini API
3. AI analyzes:

   * Skill matching
   * Keyword gaps
   * Resume quality
4. Generates:

   * ATS Score
   * Missing keywords
   * Suggestions
   * Selection probability

---

## 🛠️ Tech Stack

* **Frontend/UI:** Streamlit
* **Backend:** Python
* **AI Integration:** Google Gemini API
* **Libraries Used:**

  * PyPDF2
  * python-docx
  * google-generativeai

---

## 📦 Installation & Setup

### Prerequisites

* Python 3.x
* Gemini API Key from Google AI Studio

### Steps

1. Clone the repository:

```bash
git clone https://github.com/your-username/ai-resume-analyzer.git
cd ai-resume-analyzer
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Add your API key in `.env`:

```env
GOOGLE_API_KEY=your_gemini_api_key_here
```

4. Run the application:

```bash
streamlit run app.py
```

---

## 📂 Project Structure

```
ai-resume-analyzer/
│
├── app.py
├── requirements.txt
├── .env
└── README.md
```

---

## 🧪 Usage

1. Enter Job Description
2. Upload Resume (PDF/DOCX)
3. Click **Analyze Resume**
4. View:

   * ATS Score
   * Matching Skills
   * Missing Keywords
   * Suggestions
   * Selection Probability

---

## 📊 Sample Output

```
ATS Score: 85/100

Matching Skills:
Python, SQL, Machine Learning

Missing Keywords:
Power BI, Deep Learning

Suggestions:
- Add missing technical skills
- Improve project descriptions

Selection Chance:
High (80-100%)
```

---






## 📜 License

MIT License
