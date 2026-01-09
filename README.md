# AI-Powered Résumé Matcher SaaS  
Full-stack application that scores résumés against job descriptions using NLP, ML embeddings, and keyword weighting. Built as a deployable SaaS product with frontend UI, backend API, and database.

## 🎯 Purpose
Provide job seekers with:
- Job match scores  
- Keyword optimization suggestions  
- Missing skills analysis  
- Tailored résumé recommendations  

## 🧠 Core Features
- NLP processing using spaCy + TF-IDF + embeddings  
- Résumé parsing + cleaning  
- Job description similarity scoring  
- Keyword extraction + ranking  
- Web dashboard for viewing results  
- REST API for scoring jobs programmatically  

## 🛠️ Tech Stack
### Backend:
- Python, FastAPI / Flask  
- spaCy, Scikit-learn  
- Pandas  
- PostgreSQL  

### Frontend:
- React + Vite  
- TailwindCSS  
- Chart.js for analytics dashboards  

### DevOps:
- Dockerized frontend + backend  
- Nginx reverse proxy  
- GitHub Actions CI/CD (optional)

## 📁 Folder Structure
```
resume-matching-saas/
 ├── backend/
 ├── frontend/
 ├── database/
 └── docker/
```

## 🧪 ML Pipeline
1. Tokenize résumé + JD  
2. Extract keywords  
3. Generate embeddings  
4. Compute similarity score  
5. Rank strengths + missing skills  

## ▶️ Run Locally

### Backend
```bash
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

### Docker (Full Stack)
```bash
docker-compose up --build
```

## 🚀 Future Enhancements
- User login + profile history  
- PDF résumé parser w/ layout detection  
- AI-generated résumé rewrite suggestions  
