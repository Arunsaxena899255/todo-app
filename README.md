# 📝 To-Do List Web App with CI/CD Pipeline

A simple, Dockerized Flask-based To-Do list application deployed on an AWS EC2 instance using a Jenkins-powered CI/CD pipeline.

---

## 🚀 Features

- 🧠 Built using **Flask** (Python)
- 🐳 Containerized using **Docker**
- 🔁 Automated deployments using **Jenkins CI/CD**
- ☁️ Hosted on **AWS EC2**
- 🗂️ Code managed with **Git & GitHub**

---

## 🛠 Tech Stack

- Python 3.x
- Flask
- Docker
- Jenkins
- GitHub
- AWS EC2 (Amazon Linux 2)


## 🧪 How to Run Locally

## 🧪 How to Run Locally

```bash
git clone https://github.com/Arunsaxena899255/todo-app.git
cd todo-app
pip install -r requirements.txt
python app.py
```


## 🔨 Build Docker Image
```
docker build -t todo-app 
```
## 🚀 Run Docker Container
 ```
docker run -d -p 5000:5000 --name todo-container todo-app
```
## 🌐 Live App
💡 Hosted on EC2: http://<your-ec2-public-ip>:5000

