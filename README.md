# NextGenITHub1-SMARTplus
For # SMART+ Platform – Nutrition Data Analytics & Reporting

This repository contains source code, documentation, and deployment guides for the SMART+ platform – a modular, offline-capable data collection and analytics tool for humanitarian nutrition assessments.

## 🔧 Key Features
- 🗂 Survey data ingestion from ODK/Kobo
- 📊 Automatic analysis of anthropometric & food security indicators
- 🌐 Multilingual UX (English, French, Arabic)
- 🔐 Secure RESTful APIs (GDPR & HIPAA compliant)
- 🧪 Unit, integration, and snapshot tests
- 📈 Dashboards using Power BI and Graphite

## 📚 Technologies
- Frontend: React, TypeScript
- Backend: FastAPI, PostgreSQL
- Mobile: React Native
- DevOps: Docker, AWS EC2, GitHub Actions
- Dashboards: Power BI, Graphite

## 📦 Deployment
```bash
docker-compose up --build
```

## 📁 Repository Structure
```text
SMARTplus/
├── README.md
├── LICENSE
├── .gitignore
├── docs/
│   ├── project-overview.md
│   ├── user-stories.md
│   ├── system-architecture.png
│   └── API-docs.md
├── frontend/
│   ├── package.json
│   ├── src/
│   │   ├── App.tsx
│   │   ├── components/
│   │   └── tests/
├── backend/
│   ├── requirements.txt
│   ├── app/
│   │   ├── main.py
│   │   ├── models/
│   │   ├── routes/
│   │   └── tests/
├── mobile/
│   ├── android/
│   ├── ios/
│   └── src/
├── database/
│   ├── schema.sql
│   └── seed_data.sql
├── dashboards/
│   ├── nutrition-metrics.pbix
│   └── performance-dashboard.json
└── deployment/
    ├── docker-compose.yml
    ├── AWS-setup.md
    └── ssl-config.sh

```

## 🤝 Maintainers
- Kayanja Jonathan – Project Manager
- Musinguzi Steven – Lead Developer
- Bunya Ronald – UX Designer
[README_SMARTplus.md](https://github.com/user-attachments/files/20147655/README_SMARTplus.md)
sample purpose
