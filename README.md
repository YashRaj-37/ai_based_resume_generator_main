🤖 AI Resume Generator (Full Stack)

An AI-powered full-stack web application that generates professional, ATS-friendly resumes based on user input. The system uses a Spring Boot backend integrated with AI prompt engineering and a modern React frontend for a seamless user experience.

🚀 Live Features
🧠 AI-generated resumes using structured prompts
📄 Clean, professional, ATS-friendly output
⚡ Real-time resume generation
🌐 Full-stack architecture (Frontend + Backend)
🎨 Modern UI with Tailwind CSS
🔌 REST API integration between frontend & backend
🏗️ Architecture Overview
User Input → React Frontend → REST API → Spring Boot Backend → AI Prompt Processing → Generated Resume
🛠️ Tech Stack
🔹 Frontend
React (Vite)
Tailwind CSS
JavaScript (ES6+)
🔹 Backend
Java + Spring Boot
REST APIs
Maven
🔹 AI Integration
Prompt-based resume generation (resume_prompt.txt)
Structured input → formatted output pipeline
📂 Project Structure
ai_based_resume_generator-main/
│
├── resume-ai-backend/        # Spring Boot backend
│   ├── controller/           # API endpoints
│   ├── service/              # Business logic
│   ├── ResumeRequest.java    # Request model
│   └── resume_prompt.txt     # AI prompt template
│
├── resume_frontend/          # React frontend
│   ├── src/
│   │   ├── components/       # UI components
│   │   ├── pages/            # Pages (Home, Generate, etc.)
│   │   ├── api/              # API calls
│   │   └── main.jsx
│   └── vite.config.js
⚙️ Setup Instructions
🔧 Backend Setup (Spring Boot)
cd resume-ai-backend
./mvnw spring-boot:run

Or (Windows):

mvnw.cmd spring-boot:run

Backend runs on:

http://localhost:8080
💻 Frontend Setup (React)
cd resume_frontend
npm install
npm run dev

Frontend runs on:

http://localhost:5173
🔗 API Endpoint
Generate Resume
POST /api/resume/generate
Request Body Example:
{
  "name": "John Doe",
  "skills": ["Java", "React"],
  "experience": "2 years in web development"
}
💡 How It Works
User fills in details via frontend
Data is sent to backend via REST API
Backend formats input using resume_prompt.txt
AI generates structured resume content
Response is sent back and displayed
📸 Screens (Add Yours Here)
Landing Page
Resume Generator Page
Output Resume View
🎯 Key Highlights (For Recruiters)
Full-stack project (React + Spring Boot)
Clean separation of concerns (Controller → Service → API)
Real-world AI integration using prompt engineering
Scalable architecture for adding templates or features
Production-style project structure
🔮 Future Improvements
📄 Multiple resume templates
📥 Export as PDF/DOCX
🔐 User authentication
🌍 Multi-language support
🔗 LinkedIn/GitHub auto-fetch
🤝 Contributing

Feel free to fork and improve the project. PRs are welcome!

👨‍💻 Author

Yash Raj

GitHub: https://github.com/YashRaj-37
⭐ Support

If you found this useful, give it a ⭐ on GitHub!
