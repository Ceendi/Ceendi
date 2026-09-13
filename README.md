# hey 👋

I'm Jakub, a backend developer from Łódź, Poland. I recently finished my BSc in Applied Computer Science at Łódź University of Technology and I'm now doing my Master's in Software Engineering & Machine Learning.

I mostly work with Java/Spring and Python/FastAPI. I like building backend systems and figuring out how things work in practice — authentication, async processing, databases, testing, deployment and all the small things that usually break outside the happy path.

I'm also interested in AI/ML, especially local LLMs, RAG and building useful features around them.

---

### stuff I've built

**[Deepfake Detector](https://github.com/Ceendi/Deepfake-Detector)** — university team project for detecting manipulated audio and video. I was responsible for the backend and infrastructure: Spring Boot API Gateway, orchestrator and file service, RabbitMQ for asynchronous processing, Redis, Keycloak, PostgreSQL, Docker Compose, CI and monitoring. The ML detection services were built by other team members.

**[GymApp](https://github.com/stejzy/GymApp)** — microservices fitness app built with 3 friends. I worked mostly on authentication, user service, API Gateway, Spring Security + JWT, Eureka and Config Server. We definitely went a bit overboard with the architecture for a university project, but it was a good way to learn how Spring Cloud services work together.

**[Moon Poro Bot](https://github.com/Ceendi/Moon-Poro-Bot)** — Discord bot I built and still maintain for the largest Polish League of Legends Discord community with 68k+ members. More than 3,300 users have gone through its Riot account verification flow. It's built with Python, discord.py, PostgreSQL, SQLAlchemy/Alembic and Riot Sign On, and runs 24/7 on GCP with Caddy, systemd and GitHub Actions.

**[CalorieTracker AI](https://github.com/Ceendi/CalorieTracker)** — probably the project I'm most proud of. I got tired of manually logging meals, so I built an app where you can just talk or take a photo. Voice input goes through Whisper → local Bielik 4.5B SLM → hybrid search with pgvector + pg_trgm. Photo recognition uses Gemini Flash, and there's also a RAG meal planner that matches recipes to macro targets. The backend is a DDD modular monolith in FastAPI, with a React Native frontend, automated tests and GitHub Actions CI.

**[Flashlingo](https://github.com/stejzy/LanguageCOMmunication)** — language learning app built by a 4-person university team. I worked mainly on the Spring Boot backend, authentication with OAuth2 + JWT, user and flashcard functionality, and AWS deployment. We ended up shipping two working releases.

**[Video-Sent](https://github.com/Ceendi/CompetencyProject)** — app for aspect-level sentiment analysis of video reviews. It downloads and transcribes video content, runs it through BERT and shows the results in a React dashboard. Backend is built with FastAPI, SQLAlchemy and Alembic.

---

### what I work with

**Backend:** Java · Spring Boot · Spring Cloud · Spring Security · Python · FastAPI · Django  
**Data:** PostgreSQL · JPA/Hibernate · SQLAlchemy · Redis · pgvector · pg_trgm  
**Infrastructure:** Docker · GCP · AWS · GitHub Actions · Linux  
**Testing:** JUnit · Mockito · pytest · Testcontainers · Cucumber · Cypress  
**AI / ML:** RAG · Whisper · local LLM inference · embeddings · BERT · Gemini · OpenAI API

---

📫 **ceendek@gmail.com** · [LinkedIn](https://www.linkedin.com/in/jakub-cendalski-b720642b0/)
