# 🚀 Smart Job Recommendation System- BY Kshama_A_K

Welcome to the **Smart Job Recommendation System**, an AI-driven platform that simplifies job searching by offering personalized recommendations, skill gap analysis, and real-time job alerts. This project leverages modern web technologies, machine learning, and web scraping to provide users with highly relevant job opportunities tailored to their skills and career goals.

---

## 📁 Project Overview

This project is built with:

- 🖥️ **Frontend:** React.js  
- ⚙️ **Backend:** Node.js, Express.js  
- 🗄️ **Database:** MongoDB  
- 🤖 **AI & ML:** Python (job matching & skill analysis)  
- 🔍 **Web Scraping:** Puppeteer, Cheerio  
- 🔐 **Auth & Security:** JWT, secure login  

---

## 🔧 Folder Structure

```
job-portal/
├── backend/
│   ├── src/
│   ├── package.json
├── frontend/
│   ├── src/
│   ├── package.json
├── ai-ml/
│   ├── job_matching.py
│   ├── skill_analysis.py
│   └── requirements.txt
└── README.md
```

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/kshamak3149-create/job-portal.git
   cd job-portal
   ```

2. Make sure you have **Node.js** and **npm** installed.  
   - Download from [Node.js official site](https://nodejs.org/)  
   - Verify installation:
     ```bash
     node -v
     npm -v
     ```

3. Install dependencies for **backend & frontend**:
   ```bash
   cd backend && npm install
   cd ../frontend && npm install
   ```

4. Install **Python dependencies** for AI/ML:
   ```bash
   pip install -r ai-ml/requirements.txt
   ```

5. Start the **backend**:
   ```bash
   cd backend
   npm start
   ```

6. Start the **frontend**:
   ```bash
   cd ../frontend
   npm start
   ```

7. Start the **AI/ML service**:
   ```bash
   cd ../ai-ml
   python job_matching.py
   ```
   This service handles job matching & skill gap analysis.  
   Make sure it runs in parallel with the backend.

8. Access the application:
   - Frontend UI → [http://localhost:3000](http://localhost:3000)  
   - Backend API → [http://localhost:5000](http://localhost:5000)  
   - AI/ML Service → Runs separately on Python (specify port if applicable)  

---



Project Contributor: 
- **Kshamak Katrale** ([GitHub Profile](https://github.com/kshamak3149-create))  

