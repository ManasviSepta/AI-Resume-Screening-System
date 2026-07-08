# 🤖 AI-Powered Resume Screening & Candidate Notification System

An intelligent recruitment automation solution built using **UiPath** and **Generative AI** that automates resume screening, candidate evaluation, and email notifications. The system compares resumes with a given Job Description, generates AI-based scores and recommendations, exports the results to Excel, and sends personalized emails to candidates.

---

## 📌 Overview

Recruiters often spend significant time manually reviewing resumes to identify suitable candidates. This project automates the entire initial recruitment process by leveraging **UiPath** and **Generative AI**.

The automation reads multiple PDF resumes, extracts candidate details, compares them against the provided Job Description, evaluates each candidate based on technical skills, experience, and education, generates an AI-powered recommendation, stores the results in an Excel report, and automatically sends personalized email notifications.

---

## ✨ Features

- 📄 Reads multiple PDF resumes automatically
- 🤖 AI-powered resume analysis using UiPath GenAI
- 🎯 Compares resumes with the Job Description
- 👤 Extracts candidate information:
  - Name
  - Email Address
  - Technical Skills
  - Education
  - Experience
- 📊 AI-based candidate evaluation:
  - Skills Score
  - Experience Score
  - Education Score
  - Overall Score
- 📌 Identifies missing skills
- ✅ Generates hiring recommendations (Selected / Rejected)
- 📧 Sends personalized email notifications automatically
- 📈 Exports evaluation results to Excel

---

## 🏗️ Workflow

                 Resume PDFs
                      │
                      ▼
              Read PDF Text
                      │
                      ▼
          AI Resume Evaluation
                      │
                      ▼
      Extract Candidate Information
                      │
                      ▼
 Compare Resume with Job Description
                      │
                      ▼
 Generate Scores & Recommendation
                      │
                      ▼
      Store Results in Excel
                      │
                      ▼
   Send Automated Email Notification
```

---

## 🧠 AI Evaluation Criteria

Each resume is evaluated based on:

| Criteria | Description |
|----------|-------------|
| Technical Skills | Matches candidate skills with job requirements |
| Experience | Evaluates projects, internships, and work experience |
| Education | Compares educational qualifications |
| Overall Score | AI-generated candidate suitability score |

---

## 📊 Recommendation Logic

| Overall Score | Recommendation |
|---------------|--------------- |
| **≥ 70**      | ✅ Selected   |
| **< 70**      | ❌ Rejected   |

---

## 📧 Automated Email Notification

### ✅ Selected Candidate
- Congratulatory email
- Resume successfully shortlisted
- HR team will contact the candidate for the next recruitment stage

### ❌ Rejected Candidate
- Thank you email
- Professional rejection message
- Encouragement to apply for future opportunities

---

## 📂 Project Structure

AI-Resume-Screening/
│
├── Data/
│   ├── JobDescription.txt
│   ├── Resume1.pdf
│   ├── Resume2.pdf
│   ├── Resume3.pdf
│
├── Output/
│   └── Results.xlsx
│
├── Main.xaml
├── project.json
└── README.md
```

---

## 🛠️ Technologies Used

- UiPath Studio
- UiPath GenAI Activities
- UiPath Integration Service
- Google Workspace Activities
- PDF Activities
- Excel Activities
- Newtonsoft JSON
- Generative AI
- Robotic Process Automation (RPA)

---
## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/AI-Resume-Screening-Using-UiPath-GenAI.git
```

### 2. Open the Project

Open the project in **UiPath Studio**.

### 3. Add Input Files

- Place all resume PDFs inside the **Data** folder.
- Update **JobDescription.txt** with the required job description.

### 4. Configure Connections

Configure the following:

- UiPath GenAI Connection
- Google Workspace Connection

### 5. Run the Project

Execute **Main.xaml**.

### 6. Output

After execution:

- AI evaluates all resumes.
- Results are generated in **Results.xlsx**.
- Personalized email notifications are sent automatically.

---
## 🎓 Learning Outcomes

This project demonstrates:

- Robotic Process Automation (RPA)
- AI-Powered Resume Screening
- Prompt Engineering
- Generative AI Integration
- JSON Parsing
- PDF Processing
- Excel Automation
- Email Automation
- End-to-End Recruitment Workflow Automation



If you found this project helpful, consider giving it a **⭐ Star** on GitHub.

It motivates me to build and share more AI and automation projects.
