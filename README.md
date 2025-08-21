#  FastAPI Backend for Kavya

##  Setup Instructions

### 1️ Clone the Repository
```bash
git clone https://github.com/ATRI-llm/Kavya/tree/main

```

### 2️ Create a Virtual Environment
```bash
python -m venv env
```

### 3️ Activate the Virtual Environment
- On **Windows (PowerShell)**:
  ```bash
  .\env\Scripts\activate
  ```
- On **Linux / macOS**:
  ```bash
  source env/bin/activate
  ```

### 4️ Install Dependencies
```bash
pip install -r requirements.txt
```

---

## 5 Running the Application
From the project root, run:
```bash
python -m app.main
```

The server will start at:
```
http://127.0.0.1:8000
```

---

## 5 API testing

- Swagger UI 👉 [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)  
- ReDoc 👉 [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc)

---



---

## 📂 Project Structure
```
.
├── app
│   ├── main.py      
│   └── models.py      
├── requirements.txt 
└── README.md        
```