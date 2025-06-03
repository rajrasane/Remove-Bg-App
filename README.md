# Remove Background App

A simple Flask web app to remove image backgrounds using `rembg` and `onnxruntime`.

## Tech Stack

- Flask (Python backend)
- rembg + ONNX (U-2-Net model)
- Docker for containerization

##  How to Run

### 🔹 Using Python

```bash
pip install -r requirements.txt
python app.py
```
- then visit http://localhost:5000

---


### 🔹 Using Docker

```bash
docker build -t remove-bg-app .
docker run -p 5000:5000 remove-bg-app
```

- then visit http://localhost:5000

<br>

---
---