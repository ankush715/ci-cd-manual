# 🚀 AWS CI/CD Project (Node.js App)

## 📌 Project Overview

This is a simple Node.js application deployed using a manual CI/CD pipeline on AWS.

The project demonstrates how to:

* Push code to GitHub
* Build using AWS CodeBuild
* Deploy manually to an EC2 instance

---

## 🏗️ Tech Stack

* Node.js
* AWS EC2
* AWS CodeBuild
* Git & GitHub

---

## ⚙️ Project Structure

```
my-project/
│── app.js
│── package.json
│── buildspec.yml (optional)
```

---

## ▶️ How to Run Locally

```bash
npm install
npm start
```

Open in browser:

```
http://localhost:3000
```

---

## ☁️ AWS Deployment Steps

### 1. Launch EC2 Instance

* Install Node.js
* Clone repository

### 2. Setup AWS CodeBuild

* Connect GitHub repo
* Add buildspec.yml

### 3. Manual Deployment

```bash
git pull origin main
npm install
pm2 restart app
```

---

## 🔄 CI/CD Flow

```
GitHub → CodeBuild → Manual Deploy (EC2)
```

---

## 📸 Output

```
Hello from AWS CI/CD Project 🚀
```

---

## 🎯 Key Learnings

* CI/CD basics
* AWS services integration
* Deployment process on EC2

---

## 👨‍💻 Author

Ankush

---

## ⭐ Note

This project is created for learning and practice purposes.
