
<h1 align="center">🤖 AI Resume Generator (Full Stack)</h1>

<p align="center">
An AI-powered web application that generates professional, ATS-friendly resumes using a Spring Boot backend and React frontend.
</p>

<hr>

<h2>🚀 Features</h2>
<ul>
  <li>🧠 AI-generated resumes using structured prompts</li>
  <li>📄 Clean and ATS-friendly resume output</li>
  <li>⚡ Real-time resume generation</li>
  <li>🌐 Full-stack architecture (React + Spring Boot)</li>
  <li>🎨 Modern UI with Tailwind CSS</li>
  <li>🔌 REST API integration</li>
</ul>

<hr>

<h2>🏗️ Architecture</h2>
<pre>
User Input → React Frontend → REST API → Spring Boot Backend → AI Processing → Resume Output
</pre>

<hr>

<h2>🛠️ Tech Stack</h2>

<h3>Frontend</h3>
<ul>
  <li>React (Vite)</li>
  <li>Tailwind CSS</li>
  <li>JavaScript (ES6+)</li>
</ul>

<h3>Backend</h3>
<ul>
  <li>Java</li>
  <li>Spring Boot</li>
  <li>Maven</li>
</ul>

<h3>AI Integration</h3>
<ul>
  <li>Prompt-based generation</li>
  <li>Custom <code>resume_prompt.txt</code></li>
</ul>

<hr>

<h2>📂 Project Structure</h2>

<pre>
ai_based_resume_generator_main/
│
├── resume-ai-backend/
│   ├── controller/
│   ├── service/
│   ├── ResumeRequest.java
│   └── resume_prompt.txt
│
├── resume_frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── vite.config.js
</pre>

<hr>

<h2>⚙️ Setup Instructions</h2>

<h3>🔧 Backend</h3>
<pre>
cd resume-ai-backend
mvnw.cmd spring-boot:run
</pre>

<p>Runs on: <code>http://localhost:8080</code></p>

<h3>💻 Frontend</h3>
<pre>
cd resume_frontend
npm install
npm run dev
</pre>

<p>Runs on: <code>http://localhost:5173</code></p>

<hr>

<h2>🔗 API Endpoint</h2>

<h3>Generate Resume</h3>
<pre>
POST /api/resume/generate
</pre>

<h3>Example Request</h3>
<pre>
{
  "name": "John Doe",
  "skills": ["Java", "React"],
  "experience": "2 years in development"
}
</pre>

<hr>

<h2>💡 How It Works</h2>
<ol>
  <li>User enters details in frontend</li>
  <li>Data sent to backend API</li>
  <li>Backend formats prompt</li>
  <li>AI generates resume</li>
  <li>Result displayed to user</li>
</ol>

<hr>

<h2>🎯 Future Improvements</h2>
<ul>
  <li>📄 Multiple templates</li>
  <li>📥 PDF export</li>
  <li>🔐 Authentication</li>
  <li>🌍 Multi-language support</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>
<p><b>Yash Raj</b></p>
<p>GitHub: <a href="https://github.com/YashRaj-37">YashRaj-37</a></p>

<hr>

<h2>⭐ Support</h2>
<p>If you like this project, give it a ⭐ on GitHub!</p>
