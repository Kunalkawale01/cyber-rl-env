# 🛡️ Cyber RL Defense System (Simulation)

## Overview

Cyber RL Defense System is an AI-powered cybersecurity simulation platform that uses **Reinforcement Learning (PyTorch)** to detect and respond to cyber attacks in real time.

It simulates attacker-defender scenarios using a custom environment and trains an RL agent to optimize defense strategies.

---

## Key Features

* 🔥 Reinforcement Learning-based cyber defense
* 🧪 Simulated attack environment (honeypot)
* 📊 Real-time attack visualization dashboard
* 🤖 AI decision-making using PyTorch
* 🐳 Dockerized deployment
* 🌐 Frontend + Backend architecture

---

## Tech Stack

* **AI/ML:** PyTorch
* **Backend:** Python (FastAPI/Flask)
* **Frontend:** HTML, CSS, JavaScript
* **Deployment:** Docker, Hugging Face
* **Logging:** Custom attack logs

---

## How It Works

1. Environment simulates cyber attacks
2. RL Agent observes state
3. Agent takes action (block, allow, monitor)
4. Rewards are assigned based on defense success
5. Model improves over time

---

## Run Locally

```bash
Download Zip file
cd cyber-rl-insane

pip install -r requirements.txt
uvicorn backend.app:app --reload
```
Runs at:
```
http://127.0.0.1:8000
```
Just open:
```
frontend/index.html

Double Click To index.html
```
---

## Run with Docker

```
docker build -t cyber-rl .
docker run -p 5000:5000 cyber-rl
```

---

## Screenshots

<img width="1874" height="913" alt="Screenshot 2026-04-03 171547" src="https://github.com/user-attachments/assets/8e3e160c-a2d7-49ca-9e46-0e9c05c60871" />
<img width="926" height="318" alt="Screenshot 2026-04-03 171552" src="https://github.com/user-attachments/assets/27df830d-e546-430d-bbce-e79e723384e8" />
<img width="916" height="308" alt="image" src="https://github.com/user-attachments/assets/3c562269-a799-4ae0-89e1-d2a06e5eee04" />
<img width="923" height="292" alt="image" src="https://github.com/user-attachments/assets/b74c266a-a0ee-466f-8913-06021ded7baf" />
<img width="901" height="290" alt="image" src="https://github.com/user-attachments/assets/5f70d939-7748-4625-882d-54c59bbc64e0" />
<img width="917" height="254" alt="image" src="https://github.com/user-attachments/assets/4c3d0efc-14b1-4df6-8e37-6f1a43d3c840" />
<img width="768" height="235" alt="image" src="https://github.com/user-attachments/assets/52750094-aa50-4dbf-8504-082393692bd1" />

---

## Use Case

* Cybersecurity research
* AI-based intrusion detection
* Ethical hacking simulation
* Autonomous defense systems

---

## Hackathon Submission

This project is built for **Meta x PyTorch Hackathon** and demonstrates real-world application of reinforcement learning in cybersecurity.

---
## 📜 License

MIT License

## Folder Structure
```
cyber-rl-insane/
│── app.py
├── 📁 backend/
│   ├── rl_agent.py
│   ├── environment.py
│   ├── utils.py
│   └── requirements.txt
│
├── 📁 frontend/
│   ├── index.html
│   ├── app.js
│   ├── styles.css
│   └── assets/
│
├── 📁 models/
│   └── trained_model.pt
│
├── 📁 logs/
│   └── attacks.log
│
├── 📁 screenshots/
│   ├── dashboard.png
│   ├── training.png
│   └── results.png
│
├── 📁 docs/
│   ├── architecture.md
│   └── api.md
│
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
├── .gitignore
├── LICENSE
├── README.md
└── run.sh
```
