# AI-Based Adaptive Learning Platform for Children with Mental & Learning Disabilities

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Architecture](#architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview
This project is an **AI-Based Adaptive Learning Platform** designed to support children with mental and learning disabilities. The platform delivers **personalized learning experiences** by adapting the difficulty, content, and teaching style based on each child’s learning pace and interaction patterns.  

It provides a **safe, accessible, and engaging environment** for children to learn while giving parents and educators insights into progress.

---

## Features
- **Personalized Learning:** Adaptive content powered by **Gemini LLM (Vertex AI)**  
- **Child-Friendly Interface:** Built with **Angular** for a responsive, accessible, and visual experience  
- **Secure Authentication:** Login via **Google Identity Services**  
- **Access Control:** Managed using **GCP IAM** for secure permissions  
- **Progress Tracking:** Monitor performance and adjust learning strategies  

---

## Tech Stack
- **Frontend:** Angular, Angular Material  
- **AI / Machine Learning:** Gemini LLM via Vertex AI (GCP)  
- **Authentication:** Google Identity Services  
- **Cloud & Security:** Google Cloud Platform (GCP IAM)  

---

## Architecture
```text
          ┌─────────────────────────┐
          │  Angular Frontend       │
          │  - Responsive UI        │
          │  - Child-friendly       │
          └─────────┬──────────────┘
                    │
        Google Identity Services (Auth)
                    │
          ┌─────────▼──────────────┐
          │  Backend / API Layer    │
          │  (Optional Cloud Run)  │
          └─────────┬──────────────┘
                    │
          ┌─────────▼──────────────┐
          │  Gemini LLM (Vertex AI)│
          │  - Adaptive Learning    │
          │  - Content Personalization │
          └─────────┬──────────────┘
                    │
               GCP IAM / Database
```

## Installation
Prerequisites
Node.js & npm
Angular CLI
Git
Google Cloud account with Vertex AI enabled
Steps
## 1.Clone the repository:
git clone https://github.com/Shreyash-03-codes/Adaptive-learning-AI.git
cd Adaptive-learning-AI

## 2.Install dependencies:
npm install

## 3.Configure Google Authentication:
Add your OAuth client ID in the Angular environment configuration

## 4.Configure Vertex AI:
Provide API keys and model endpoint for Gemini LLM

## 5.Run the application:
ng serve
Open http://localhost:4200 in your browser.


## Usage
Parents and educators can register and log in using Google accounts.
Children can access interactive lessons that adapt in real-time.
The AI evaluates responses, adjusts difficulty, and provides suggestions for improvement.
Admins can monitor learning analytics via the backend dashboard.


## Contributing
Fork the repository
Create a new branch (git checkout -b feature/your-feature)
Commit your changes (git commit -m "Add feature")
Push to branch (git push origin feature/your-feature)
Open a Pull Request

## License
This project is licensed under the MIT License. See the LICENSE file for details.

Empowering children with learning disabilities through personalized AI-driven education.


I can also create a **more visually appealing GitHub README** with **badges, GIF demo placeholders, and AI architecture diagram** if you want your repo to **look professional and portfolio-ready**.  

Do you want me to do that next?
