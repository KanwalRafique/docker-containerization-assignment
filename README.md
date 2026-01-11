<img width="1919" height="697" alt="Screenshot 2026-01-11 143922" src="https://github.com/user-attachments/assets/a5c0f557-932e-4c9d-918c-fb26f72b5ff1" />
## Docker Containerization Assignment

This repository contains **two containerized projects**:

- 🚀 **Next.js Docker** (`nextjs-docker`)  
- 🐍 **FastAPI Docker** (`fastapi-docker`)
- <img width="1906" height="913" alt="Screenshot 2026-01-11 150359" src="https://github.com/user-attachments/assets/86a19f2a-2c77-4d37-b063-2a89ebc47efd" />

---

## 🚀 Next.js Docker

**Steps to Run:**

```bash
cd nextjs-docker
docker build -t nextjs-docker .
docker run -p 3000:3000 nextjs-docker
````

Open in your browser: [http://localhost:3000](http://localhost:3000)

**Screenshot:**
![Next.js Output] <img width="1919" height="697" alt="Screenshot 2026-01-11 143922" src="https://github.com/user-attachments/assets/984c5f01-8848-453b-8a6a-a20ba13bcd0a" />

---

## 🐍 FastAPI Docker

**Steps to Run:**

```bash
cd fastapi-docker
docker build -t fastapi-docker .
docker run -p 8000:8000 fastapi-docker
```

Open in your browser: [http://localhost:8000](http://localhost:8000)
Docs: [http://localhost:8000/docs](http://localhost:8000/docs)

**Screenshot:**
![FastAPI Output]<img width="1735" height="989" alt="Screenshot 2026-01-11 150554" src="https://github.com/user-attachments/assets/0d262260-c753-4afb-9d5f-63d13e7bdc75" />

---

## 📂 Folder Structure

```
docker-containerization-assignment/
├─ nextjs-docker/
│  ├─ Dockerfile
│  ├─ package.json
│  ├─ package-lock.json
│  ├─ pages/
│  ├─ public/
│  └─ README.md
├─ fastapi-docker/
│  ├─ Dockerfile
│  ├─ main.py
│  ├─ pyproject.toml
│  ├─ uv.lock
│  └─ README.md
└─ .gitignore
```

> Large folders like `node_modules/`, `.next/`, `.venv/` are ignored by Git.

```

---

