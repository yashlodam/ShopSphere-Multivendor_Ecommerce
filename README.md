# ShopSphere — Multi-Vendor E-Commerce Platform & Conversational AI Marketplace

> **Live Production URL**: [https://shopsphereecommerceweb.vercel.app/](https://shopsphereecommerceweb.vercel.app/)  
> **Architecture**: Decoupled Monorepo uniting React 19 SPA & Spring Boot 3.3 REST Services

---

## 📁 Repository Structure

```text
ShopSphere/
├── frontend/                # React 19 Single-Page Application (Vite 8, Redux Toolkit, Tailwind CSS, MUI)
│   ├── src/                 # Application source code (Customer, Seller, Admin portals)
│   ├── public/              # Static public assets
│   ├── package.json         # Frontend dependencies and build scripts
│   ├── vite.config.js       # Vite configuration
│   └── vercel.json          # Vercel deployment rewrites
├── backend/                 # Spring Boot 3.3 RESTful Web Services (Java 21, Spring Data JPA, PostgreSQL)
│   ├── src/                 # Java backend source code & database models
│   ├── pom.xml              # Maven dependencies & build configuration
│   ├── Dockerfile           # Production container configuration
│   └── mvnw / mvnw.cmd      # Maven wrapper executables
└── README.md                # Unified monorepo documentation
```

---

## 🚀 Quick Start

### 1. Backend Setup (Spring Boot 3.3 & Java 21)
```bash
cd backend
./mvnw spring-boot:run
```
- API Base URL: `http://localhost:5454`
- Swagger OpenAPI Docs: `http://localhost:5454/swagger-ui/index.html`

### 2. Frontend Setup (React 19 & Vite 8)
```bash
cd frontend
npm install
npm run dev
```
- Local URL: `http://localhost:5173`

---

## 🛠️ Tech Stack

- **Frontend**: React 19, Vite 8, Redux Toolkit 2.12, Tailwind CSS 4, Material-UI (MUI) 9, Recharts 3.8, Swiper 12
- **Backend**: Java 21, Spring Boot 3.3.4, Spring Security, Spring Data JPA, Hibernate, PostgreSQL 16, JJWT 0.12
- **AI & Cloud**: Google Gemini LLM (Tool Calling & Entity Extraction), Razorpay Payment Gateway, Vercel Edge Hosting
