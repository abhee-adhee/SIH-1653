# Smart India Hackathon Workshop
# Date:28.02.2025
## Register Number:212224040008
## Name:S ABINAV AADITYA
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
Key Features
1. Virtual Interview Panel (Boardroom Simulation)
3D avatars of interviewers for a realistic experience.
Multiple interviewer roles (HR, Technical, Managerial, etc.).
Speech-enabled AI interviewers to ask questions dynamically.
2. AI-Driven Questioning System
Initial ice-breaking questions, then in-depth technical/managerial queries.
Personalized questions based on the candidate's domain expertise.
Adaptive questioning – changes based on candidate responses.
3. Candidate Response Analysis
Supports voice-based and text-based responses.
AI evaluates response relevance, clarity, and confidence.
Speech-to-text conversion for analysis and scoring.
4. Real-Time Scoring & Feedback
Assigns a relevance score based on question and answer matching.
Provides instant feedback on strengths & weaknesses.
AI-generated report on interview performance.
5. Data & Analytics Dashboard for Recruiters
Tracks candidate performance over multiple interviews.
Identifies biases in questions and responses.
ML-powered hiring recommendations.
6. Gamification Elements (Optional)
Time-based challenges to simulate real-world pressure.
Performance badges & leaderboard to encourage improvement.

## Proposed Solution / Architecture Diagram
![image](https://github.com/user-attachments/assets/e9b7a96c-03d0-48bc-a1a5-44500255874f)


## Use Cases
Candidate Experience:

Enters a virtual boardroom.
AI-driven interviewers ask relevant questions.
Provides voice or text responses.
Gets instant AI feedback on answers.
Recruiter/Panel Experience:

Monitors live or recorded interviews.
Reviews AI-generated performance reports.
Filters candidates based on score analytics.
AI-Driven Analytics & Insights:

Detects response patterns & confidence levels.
Identifies biases in questioning.
Suggests improvements for candidates.

![image](https://github.com/user-attachments/assets/6ec9c246-666c-4095-b571-b6bd5e7a1120)


## Technology Stack
### **Tech Stack Overview** 🚀  

- **Frontend**: React.js, Next.js, Three.js (for 3D UI), WebRTC (real-time video).  
- **Backend**: Node.js with Express.js or FastAPI (Python) for APIs & business logic.  
- **AI/ML**: OpenAI GPT (question generation), TensorFlow/PyTorch (response evaluation), Deepgram/Whisper (speech-to-text).  
- **Database**: PostgreSQL (structured data), MongoDB (unstructured logs), VectorDB (AI training data).  
- **Cloud & DevOps**: AWS/GCP, Docker, Kubernetes, CI/CD (Jenkins/GitHub Actions).  

## Dependencies
- **Manpower Cost**: ₹2-3 crore (~₹10-15 lakh per developer for 12-18 months).
- **Cloud Infrastructure**: ₹20-30 lakh (AWS/GCP services, storage, compute, and AI APIs).
- **AI & Speech Processing APIs**: ₹10-15 lakh (OpenAI, Deepgram, Google STT).
- **Software & Licensing**: ₹5-10 lakh (3D UI tools, security, DevOps tools).
- **Miscellaneous (Testing, Maintenance, Support)**: ₹10-15 lakh.
