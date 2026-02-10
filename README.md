# MetabaseBI

# Metabase BI - Aramorais

Business Intelligence environment using Metabase and Docker for analyzing data from a WordPress database.

This project provides a ready-to-use Metabase + PostgreSQL stack and connects to an existing MySQL (WordPress) database for dashboards and analytics.

---

## 🚀 Technologies

- Metabase  
- PostgreSQL (Metabase internal database)  
- MySQL (WordPress database)  
- Docker  
- Docker Compose  

---

## 📂 Project Structure

```bash
MetabaseBI/
├── docker-compose.metabase.yml
├── metabase-config/
├── postgres-init/
├── .env.example
├── .gitignore
└── README.md
```


---

## ⚙️ Requirements

- Docker  
- Docker Compose  

Check installation:

```bash
docker --version
docker-compose --version
```

---

##  🔐 Environment Variables

Create .env file from example:

cp .env.example .env


Edit .env:

```bash
METABASE_DB_PASSWORD=your_password_here
METABASE_SECRET_KEY=your_secret_key_here
```
---

## ▶️ Running the Project

Start containers:

docker-compose -f docker-compose.metabase.yml up -d
