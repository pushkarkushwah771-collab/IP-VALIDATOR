" />
# IP-VALIDATOR
An IP Validator is a tool that checks whether an IP address is valid and correctly formatted for IPv4 or IPv6 standards. It helps detect invalid addresses, prevents configuration errors, and improves network security in applications, servers, and networking systems.
IP Validator
A modern Flask-based IP Validator web app with a cyber-style UI.

Features
Validate IPv4, IPv6, and CIDR

Detect public IP using backend API route

Live IP lookup using Python backend

Responsive UI with dark/light theme toggle

Flask backend with JSON API routes
Project Structure
text
ip-validator-flask/

├── app.py

├── requirements.txt

├── README.md

├── .gitignore

├── templates/

│   └── ip-validator.html

└── static/
    ├── style.css
    └── app.js
Installation
bash
pip install -r requirements.txt
Run
bash
python app.py
Open in browser:

text

http://127.0.0.1:5000/
API Routes

/api/validate?ip=VALUE

/api/detect-ip
<img width="829" height="547" alt="Screenshot 2026-05-21 202217" src="https://github.com/user-attachments/assets/cd36b3bc-2a47-463b-b259-1f884f582a77" />

/api/lookup?ip=VALUE




