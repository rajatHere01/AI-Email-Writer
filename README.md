📧 AI Email Writer

An AI-powered email writing assistant built with Spring Boot, React, and a custom Chrome Extension, designed to generate intelligent email replies with personalized tones.

**🚀 Features**

✨ AI-Powered Drafting – Automates up to 70% of repetitive email writing.

🎭 Tone Customization – Generates replies with different tones (formal, friendly, persuasive, etc.) for improved personalization.

🔗 Google API Integration – Uses Google APIs for authentication and seamless email interaction.

🌐 Full-Stack Architecture – Backend in Spring Boot, frontend in React, and Chrome Extension for real-time use.

🐳 Containerized Deployment – Backend containerized with Docker, hosted on Render, frontend deployed on Vercel.

**🛠️ Tech Stack**

Frontend: React, Material-UI, Vercel

Backend: Spring Boot, REST APIs, Docker, Render

Extension: Custom Chrome Extension (JavaScript/React)

APIs: Google APIs for email and authentication

DevOps: GitHub, CI/CD, Docker





***⚙️ Installation & Setup**

1️⃣ Clone the repository

git clone https://github.com/rajatHere01/AI-Email-Writer.git

cd AI-Email-Writer

2️⃣ Backend (Spring Boot)

cd email-writer-sb/email-writer-sb

./mvnw spring-boot:run

Or run with Docker:

docker build -t email-writer-backend .

docker run -p 8080:8080 email-writer-backend

Add env variables in your IDE, 1.GEMINI_API_URL = _google api url_, 2. GEMINI_API_KEY = _Your api key_ (refer google API documentation)


3️⃣ Frontend (React)

cd email-writer-frontend

npm install

npm start

4️⃣ Chrome Extension

Navigate to chrome://extensions/ in your browser.

Enable Developer Mode → Click Load Unpacked.

Select the Email-Writer-Ext/ folder.



🌍 **Deployment**

Frontend: Vercel → Live Demo (https://ai-email-writer-zeta.vercel.app/)

Backend: Render (Dockerized Spring Boot service)

Extension: Chrome Developer Mode
