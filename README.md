# selenium-login-automation
Python Selenium script that automates the login process for SauceDemo as an example of UI automation testing.
# Selenium Login Automation — SauceDemo

This repository contains a simple Python Selenium automation script that logs into **https://www.saucedemo.com/**.  
It is intended for beginners learning browser automation, QA testing, and Selenium WebDriver.

---

## 🔧 Features
- Automates browser launch using Selenium
- Opens SauceDemo login page
- Enters username and password
- Clicks the login button
- Prints page titles before and after login

---

## 📁 Project Structure


selenium-login/
│-- login.py
│-- requirements.txt
│-- .gitignore
└-- README.md



---

## 🛠️ Requirements
- Python 3.8+
- Google Chrome browser
- pip (Python package manager)

---

## 📦 Install Dependencies
Create a virtual environment (optional but recommended):

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate


Install required packages:

pip install -r requirements.txt

▶️ Run the Script

python login.py

🔐 Security Notice

Do NOT hardcode real usernames or passwords inside the script.
If needed, store credentials in a .env file and load them using python-dotenv.

Example .env file (DO NOT upload this to GitHub):
SAUCE_USER=standard_user
SAUCE_PASS=secret_sauce

📄 requirements.txt

This project uses the following Python libraries:

selenium
webdriver-manager
python-dotenv   # optional

🗂️ .gitignore (recommended)

__pycache__/
venv/
.env
.env.*
*.pyc
.DS_Store

🧩 Troubleshooting

If ChromeDriver version mismatch occurs, reinstall:
pip uninstall webdriver-manager -y
pip install webdriver-manager

Ensure your internet is working because webdriver-manager downloads drivers online.

