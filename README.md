# Hey, I'm Alex 👋

**Software Engineer | AI, Machine Learning & Full-Stack | Looking for remote/hybrid roles**

*Building production-grade intelligent systems — from local LLM pipelines (RAG) to end-to-end web & mobile applications.*

---

## 🚀 What I'm Building

### VoIP OTP — Authentication Microservice → [Repo](https://github.com/AlexPT2k22/voip-otp)
OTP authentication service with SMS and voice delivery, rate limiting, and full CI/CD.
- **Stack**: Python · FastAPI · Redis · Twilio · Docker · GitHub Actions
- Sliding window rate limiting with Redis sorted sets (3 req/5min per phone)
- HMAC-SHA256 OTP hashing with time-safe comparison
- Dual channel delivery: SMS + voice calls with text-to-speech
- Full test suite: unit + integration tests with fakeredis and pytest
- CI/CD pipeline: lint → typecheck → test → build → push to container registry

### Hybrid RAG+SQL Chatbot @ Geodouro *(Internship)* [Sanitezed Repo Version](https://github.com/AlexPT2k22/llm-rag-sql-chatbot)
An LLM-powered chatbot for SIGP, an agricultural management platform. Full ownership from architecture to deployment.
- **Stack:** Python · FastAPI · LangChain · LangGraph · ChromaDB · Ollama · PostgreSQL
- Built a production RAG + SQL Agent chatbot using a deterministic pipeline with ReAct agent fallback, BM25+MMR hybrid retrieval, dynamic few-shot prompting, and schema pruning over 3 PostgreSQL databases
- Improved SQL accuracy from 13% → 77% on a 30-question domain golden set (LLM-as-Judge) using a 7B local model, outperforming a 14B reference model at 10–30× lower latency
- Achieved 5.2s median response time with no external API dependencies; system maintains stable performance under sustained 5-user concurrent load
- Designed and deployed PostgreSQL materialized views eliminating query timeouts on aggregation-heavy analytical questions

### AI Smart Parking System → [Repo](https://github.com/AlexPT2k22/AI_SE2)
Intelligent parking management with computer vision and IoT hardware integration.
- **Stack:** Python · PyTorch · FastAPI · PostgreSQL · React · React Native · ESP32
- **CV:** Custom-trained CNN (ResNet) for real-time spot occupancy detection
- **ALPR:** Fast-ALPR for automatic license plate recognition at entry/exit gates
- **IoT:** ESP32 cameras integrated for gate automation, WebSocket real-time updates

### Mockly — AI Interview Platform → [Repo](https://github.com/AlexPT2k22/Mockly-AI-Interviews-for-companies) · [Live](https://mockly-alpha.vercel.app/showcase)
AI-powered mock interview platform for companies, combining voice synthesis with dynamic conversational logic.
- **Stack:** TypeScript · Node.js · React · Supabase
- **Voice:** ElevenLabs API for realistic interviewer voice synthesis
- **Features:** Adaptive question flows, speech recognition (Whisper), candidate scoring, real-time feedback

### Enterprise Training Platform → [Repo](https://github.com/AlexPT2k22/PINT-SoftSkills)
End-to-end platform (Web + Mobile + Backoffice) built for Softinsa, an IBM subsidiary.
- **Stack:** React · Node.js · Express · PostgreSQL · Flutter · JWT
- **Features:** Course management, quizzes, certificates, admin dashboards, file uploads
- **Feedback from Softinsa:** *"I would buy it right now."*

---

## 🧠 Tech Stack

**AI & ML** · LangChain · RAG · ChromaDB · Ollama · PyTorch · OpenCV · Fast-ALPR · Whisper

**Languages** · Python · TypeScript · JavaScript · SQL · C/C++

**Backend** · FastAPI · Node.js · REST APIs · JWT

**Frontend & Mobile** · React · Flutter · HTML/CSS

**Data** · PostgreSQL · Supabase · MongoDB

**Tools** · Docker · Git · Postman · Figma

---

## 🌍 About Me

- 📍 Germany
- 🎓 Computer Engineering Graduate @ ESTGV/IPV
- 💼 Open to full-time remote roles
- 🇩🇪 Learning German (A1)

📧 alexandre@alexandrefernandes.dev
🔗 [alexandrefernandes.dev](https://alexandrefernandes.dev) · [LinkedIn](https://linkedin.com/in/alexandrerodrifernandes)
