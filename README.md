<div align="center">
  <h1>LessonBot – AI-Powered Lesson Automation 🤖📚</h1>
</div>

<div align="center">
Automate the creation of structured lessons using AI. Generates short, medium, and long lesson formats based on a topic, fully ready in Google Docs format.  
</div>

---

## 📖 Table of Contents

- [Project Overview](#-project-overview)
- [Repository Contents](#-repository-contents)
- [Setup Instructions](#-setup-instructions)
- [Usage](#-usage)
- [Screenshot](#-screenshot)
- [Notes & Tips](#-notes--tips)
- [Connect with Me](#-connect-with-me)

---

## 🎯 Project Overview

**LessonBot** is an automation workflow built using **n8n** and AI to generate lesson content in multiple formats.  

It allows anyone to quickly produce lessons in three formats: **Short, Medium, and Long**, making learning structured, fast, and consistent.

---

## 📂 Repository Contents

```bash
📁 lessonbot-ai-automation
├── 📁 workflow/
│   └── lessonbot-workflow.json       # Exported n8n workflow
├── 📁 lessons/
│   ├── short-lesson.docx             
│   ├── medium-lesson.docx            
│   └── long-lesson.docx              
├── 📁 screenshots/
│   └── workflow-overview.png         # Screenshot of n8n workflow
└── README.md                         # Project overview & instructions
```
---

## 🛠 Setup Instructions

### Import Workflow
- Open n8n and import the `lessonbot-workflow.json` file.

### Configure API Credentials
- Connect your **Google Docs** and **Google Sheets** accounts.  
- Make sure your **Google Drive API** is enabled for document creation.

### Test Workflow
- Describe the topic and select the lesson format in the google sheet.  
- Trigger the workflow to generate lesson docs in selected format.

### Access Lesson Docs
- Open the output docs in the `Generated_Lessons/` folder or your Google Drive.  

---

## ⚡ Usage
- Generate lessons for any topic.  
- Automate lesson creation for educational material, courses, or tutorials.  
- Easily customize the formats for your own styling or structure.

---

## 📸 Screenshot
*![n8n workflow](/screenshots/workflow-overview.png)*

---

## 📝 Notes & Tips
- Ensure your topic input is **clear and concise** for best results.  
- You can **use the same workflow** for multiple lesson topics.  
- Adjust AI prompts within n8n nodes to **modify lesson tone, complexity, or structure**.

---

## 📫 Connect with Me
I’m passionate about AI and productivity automation. Reach out or connect for collaborations!

- **Email:** mohammedgovani18@gmail.com  
- **LinkedIn:** [https://www.linkedin.com/in/razagovani/](https://www.linkedin.com/in/razagovani/)  
- **GitHub:** [https://github.com/gRaza25](https://github.com/gRaza25)
