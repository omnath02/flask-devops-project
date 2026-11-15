Flask DevOps Project
Project Overview

This is a lightweight Python Flask web application created to practice real-time DevOps workflows.

The project will be used to understand application development, Git, GitHub, Docker, Jenkins CI/CD, and deployment on Linux servers.

Technology Stack
Technology	Purpose
Python 3.11	Programming language
Flask	Python web framework
pip	Dependency management
HTML	Frontend
CSS	Styling
Git	Version control
GitHub	Source code management
Docker	Containerization
Jenkins	CI/CD automation
Nginx	Reverse proxy
Project Structure
text
flask-devops-project/
│
├── app.py
├── requirements.txt
├── README.md
│
├── templates/
│   ├── index.html
│   └── about.html
│
└── static/
    └── style.css

Prerequisites
Python 3.11 or later
pip
Git
VS Code
Installation and Setup
1. Clone the repository
bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd flask-devops-project

2. Create a virtual environment
bash
python -m venv venv

3. Activate virtual environment

Windows:

powershell
.\venv\Scripts\Activate.ps1


Linux:

bash
source venv/bin/activate

4. Install dependencies
bash
pip install -r requirements.txt

5. Run the application
bash
python app.py


Open your browser:

http://127.0.0.1:5000

Application Features
Simple Flask homepage
About page
Lightweight HTML and CSS
Python backend
DevOps Implementation Roadmap
Flask application development
Local application testing
Git and GitHub integration
Dockerfile creation
Docker image build
Jenkins pipeline creation
Docker Hub integration
Linux server deployment
Nginx configuration
Author

DevOps Learning Project

Project Goal

To gain practical experience in building, containerizing, automating, and deploying Python applications using industry-standard DevOps tools.