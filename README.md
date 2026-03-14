# hey 👋
 
I'm Jakub, backend/AI dev from Łódź, Poland. Recently finished my BSc in Computer Science at Łódź University of Technology, now doing my Master's in Software Engineering & Machine Learning.
 
I like building things that actually work — most of my projects start from some problem I had or something I wanted to learn. Recently I've been deep into local LLM inference, RAG pipelines, and trying to make AI features that run without burning $200/month on API calls.
 
---
 
### stuff I've built
 
**[CalorieTracker AI](https://github.com/Ceendi/CalorieTracker)** — the project I'm most proud of. I was tired of manually logging every meal, so I built an app where you just talk or take a photo. Voice goes through Whisper → Bielik 4.5B SLM (running locally via llama-cpp) → hybrid search with pgvector + pg_trgm. Photo recognition uses Gemini Flash. There's also a RAG meal planner that pulls recipes matching your macros. Backend is a DDD modular monolith in FastAPI, frontend in React Native. CI pipeline with GitHub Actions (ruff + Alembic migrations + pytest for backend, Expo lint + Jest for frontend on every push/PR), everything Dockerized with GPU passthrough.
 
**[GymApp](https://github.com/stejzy/GymApp)** — microservices fitness backend built with 3 friends. 6 Spring Cloud services (auth, users, schedules, workout generation, gateway, config server), OpenAI integration for workout plans, the whole Eureka + Config Server setup. We went a bit overboard with the architecture for a uni project but learned a ton about distributed systems.
 
**[Flashlingo](https://github.com/stejzy/LanguageCOMmunication)** — language learning app where I led a 4-person team. I handled auth (OAuth2 + JWT) and flashcards. The cool part was integrating 5 AWS services (Textract, Translate, Polly, Transcribe, Comprehend) — OCR, speech synthesis, the works. We shipped 2 actual releases.
 
**[Video-Sent](https://github.com/Ceendi/CompetencyProject)** — paste a YouTube link, get aspect-level sentiment analysis of a phone review. Transcribes audio, runs it through BERT, shows results on a React dashboard. FastAPI + SQLAlchemy backend.
 
**[Moon Poro Bot](https://github.com/Ceendi/Moon-Poro-Bot)** — Discord bot I built and maintained for a League of Legends community. Verification via Riot API, auto-updating rank roles, warn system, tickets. 130 commits, my first "real" project.
 
---
 
### what I work with
 
Python (FastAPI, Django, SQLAlchemy) · Java (Spring Boot, Spring Cloud) · TypeScript · React Native · React · Vue  
PostgreSQL (pgvector, pg_trgm) · Docker · GCP · AWS · GitHub Actions · Git · Linux  
Whisper · llama-cpp · E5 embeddings · RAG · BERT · SpaCy · Gemini · OpenAI API  
pytest · JUnit · Cypress · Cucumber · Maestro
 
---
 
📫 **ceendek@gmail.com** · [LinkedIn](https://www.linkedin.com/in/jakub-cendalski-b720642b0/)
 
