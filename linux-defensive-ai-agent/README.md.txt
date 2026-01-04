# 🛡️ Linux Defensive AI Agent with Telegram Alerts

A defensive cybersecurity AI agent that monitors Linux authentication logs,
detects suspicious SSH brute-force behavior using machine learning,
and sends real-time alerts to Telegram.

## 🚀 Features
- SSH log monitoring
- AI-based anomaly detection (Isolation Forest)
- Telegram alerts
- Lightweight & SOC-style
- Beginner friendly

## 🧠 How It Works
1. Reads `/var/log/auth.log`
2. Detects abnormal failed login behavior
3. Uses ML to identify anomalies
4. Sends alert to Telegram

## ⚙️ Installation
```bash
git clone https://github.com/yourusername/linux-defensive-ai-agent.git
cd linux-defensive-ai-agent
pip install -r requirements.txt
copy config.example.py config.py
notepad config.py
sudo python defender_agent.py
