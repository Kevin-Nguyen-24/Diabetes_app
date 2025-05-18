
# 🩺 Diabetes Prediction Web App

A simple and interactive web application that predicts whether a patient is likely to have diabetes using a machine learning model. Built with **FastAPI**, styled with HTML/CSS, and containerized with **Docker**.

---

## 📦 Features

- 🧠 Loads a pre-trained model (`model.pkl`)
- 🌐 Clean web-based user interface (HTML + JS)
- ⚡ Fast API for prediction
- 🐳 Docker support for easy deployment

---

## 🛠 Requirements

- Python 3.11+
- Docker (optional)
- `model.pkl` file (must be in the project root)

---

## 🚀 How to Run Locally (with Docker)

### 1. Clone the repository

```bash
git clone https://github.com/your-username/diabetes-app.git
cd diabetes-app
```

### 2. Build the Docker image

```bash
docker build -t diabetes-app .
```

### 3. Run the container

```bash
docker run -p 5000:5000 diabetes-app
```

### 4. Open your browser

Visit [http://localhost:5000](http://localhost:5000) and test the prediction form.

---

## 🧪 How It Works

- User inputs patient details in a form
- Data is sent to the `/predict` endpoint via POST
- Model processes the input and returns a prediction:
  - `0`: Likely **not diabetic**
  - `1`: Likely **diabetic**

---


## 📚 Technologies Used

- **FastAPI** for backend
- **HTML/CSS + JavaScript** for frontend
- **Pandas**, **Scikit-learn** for model integration
- **Docker** for containerization

---

## 🧑‍💻 Author

**Duc Phu Nguyen**  
📧 dpnguyen4@myseneca.ca  
🔗 [LinkedIn](https://www.linkedin.com/in/duc-phu-nguyen-052289264/)

---

## ⚖️ License

This project is licensed under the **MIT License**.
