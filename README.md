TRACKBACK – AI-Powered Evidence Intelligence Platform

An AI-powered platform designed to investigate claims, analyze evidence, and help users identify potentially misleading information.

📌 About the Project

TRACKBACK is an AI-powered evidence intelligence platform that allows users to submit claims through text or voice and receive an AI-assisted investigation.

The system analyzes submitted claims, examines available evidence, and generates an investigation report with a verdict to help users understand the credibility of the information.

The platform aims to make information verification more accessible, organized, and understandable.

🎯 Objectives

- Simplify the process of investigating online claims.
- Use AI to assist in analyzing information and evidence.
- Support both text-based and voice-based claim submissions.
- Present investigation results in a clear and understandable format.
- Maintain investigation history for future reference.

✨ Key Features

1. AI-Powered Claim Investigation

Users can submit claims and receive AI-assisted analysis based on available information and evidence.

2. Voice-Based Investigation

Users can submit voice recordings, which are transcribed into text for investigation.

3. Evidence Analysis

The platform presents available supporting and contradicting evidence to help users understand the investigation.

4. Investigation Verdicts

Each investigation is categorized into one of three verdicts:

- Supported – Available evidence supports the claim.
- Contradicted – Available evidence challenges the claim.
- Insufficient Evidence – Available information is not enough to reach a reliable conclusion.

5. Investigation History

Previously investigated claims are stored and displayed so users can revisit their investigations.

6. Detailed Investigation Reports

Users can open individual reports to review investigation results and evidence.

7. Interactive Dashboard

The dashboard displays investigation statistics, recent activity, and visual summaries using charts.

🛠️ Technology Stack

Component| Technology
Frontend| HTML, CSS, JavaScript
Backend| Python, Flask
Database| SQLite
AI Integration| Groq API (if configured)
Data Visualization| Chart.js
Voice Processing| Speech transcription integration

🏗️ Project Structure

TRACKBACK/
│
├── app.py
├── investigation_engine.py
├── requirements.txt
├── .gitignore
├── .env
│
├── database/
│   └── trackback.db
│
├── static/
│   ├── css/
│   │   └── style.css
│   │
│   └── js/
│       └── script.js
│
├── templates/
│   ├── dashboard.html
│   ├── index.html
│   ├── investigate.html
│   └── report.html
│
└── README.md

Note: ".env" and the local database are excluded from the public repository.

⚙️ Installation and Setup

Prerequisites

- Python 3.10 or later
- pip (Python package manager)
- Git

Step 1: Clone the Repository

git clone https://github.com/NayanaCL/TRACKBACK.git

Step 2: Navigate to the Project Folder

cd TRACKBACK

Step 3: Install Dependencies

pip install -r requirements.txt

Step 4: Configure Environment Variables

Create a ".env" file in the project root directory.

Add your API key if your configured AI integration requires it:

GROQ_API_KEY=your_actual_groq_api_key

Replace the placeholder with your own API key. Never share or upload your API key publicly.

Step 5: Run the Application

python app.py

Step 6: Open in Browser

Visit:

http://127.0.0.1:5000/

The TRACKBACK application should now be accessible locally.

🔄 How TRACKBACK Works

1. Submit a Claim: Enter a claim as text or provide a voice recording.
2. Voice Transcription: Voice input is converted into text.
3. AI Investigation: The investigation engine processes the submitted claim.
4. Evidence Analysis: Available information is examined for supporting or contradicting evidence.
5. Verdict Generation: The system produces an investigation verdict.
6. Report Generation: Results and evidence are presented in a detailed report.
7. History Storage: The investigation is saved for future reference.

🌍 Applications and Use Cases

- Preliminary verification of information circulating online.
- Educational research and information analysis.
- Investigating potentially misleading claims.
- Understanding conflicting information from available sources.
- Supporting awareness about misinformation and digital literacy.

🔮 Future Enhancements

- Integration with additional trusted information sources.
- Improved real-time web search and evidence retrieval.
- Advanced source credibility analysis.
- Multilingual voice and text support.
- Improved AI reasoning and evidence comparison.
- Exportable investigation reports.
- Enhanced investigation analytics.

⚠️ Limitations

TRACKBACK is an AI-assisted investigation tool, not a replacement for professional fact-checking.

Its results depend on the availability, relevance, and reliability of accessible information. AI-generated conclusions may contain errors. Users should independently verify important claims using trustworthy sources.

👩‍💻 Project Information

Project Name: TRACKBACK
Project Type: AI / Web Application
Domain: Artificial Intelligence, Evidence Intelligence, Information Verification
Developed Using: Python, Flask, HTML, CSS, JavaScript, SQLite

---

TRACKBACK – Trace the Claim. Examine the Evidence. Understand the Truth.
