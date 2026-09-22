👋 Hi, I'm Dmitrii!

💻 I'm a Python backend developer. Before switching to software, I spent 8 years as a process engineer in machine-building (aviation & energy industries) — that background shapes how I think about reliability and systems design today.

📢 Open to opportunities: Middle / Middle+
📬 Contact: d.nikolaev1994@gmail.com · [LinkedIn](https://www.linkedin.com/in/dmitrii-nikolaev-202007435/) · Telegram: [@my_UUID](https://t.me/my_UUID)

## 🧰 Skills & Tech

| Category | Stack |
|---|---|
| **Languages & Frameworks** | <img height="28" src="https://skillicons.dev/icons?i=python,fastapi,django,flask" /> <img height="28" src="https://img.shields.io/badge/DRF-A30000?style=flat-square&logo=django&logoColor=white" /> <img height="28" src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" /><br/>Python, FastAPI, Django, Django REST Framework, Flask, Pydantic |
| **Databases & ORM** | <img height="28" src="https://skillicons.dev/icons?i=postgres,sqlite,redis" /> <img height="28" src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" /> <img height="28" src="https://img.shields.io/badge/Alembic-6BA81E?style=flat-square&logoColor=white" /><br/>PostgreSQL, SQLite, Redis, SQLAlchemy, Alembic |
| **Tools & Libraries** | <img height="28" src="https://skillicons.dev/icons?i=docker,git" /> <img height="28" src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" /> <img height="28" src="https://img.shields.io/badge/uv-DE5FE9?style=flat-square&logoColor=white" /> <img height="28" src="https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black" /> <img height="28" src="https://img.shields.io/badge/pre--commit-FAB040?style=flat-square&logo=precommit&logoColor=black" /><br/>Docker, Docker Compose, Git, Jupyter Notebook, uv, Ruff, pre-commit |
| **Testing** | <img height="28" src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" /><br/>pytest, unit testing |
| **DevOps** | <img height="28" src="https://skillicons.dev/icons?i=githubactions,nginx" /> <img height="28" src="https://img.shields.io/badge/Gunicorn-499848?style=flat-square&logoColor=white" /> <img height="28" src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" /><br/>GitHub Actions (CI/CD), Nginx, Gunicorn, Celery |

*Also worked with: httpx, mypy, JWT (PyJWT / python-jose), Loguru*

**What I can do:**
- Design and build REST APIs (DRF, FastAPI)
- Set up asynchronous task processing (Celery)
- Implement authentication & authorization (JWT, Djoser)
- Containerize and deploy applications (Docker, Docker Compose, Gunicorn, Nginx)
- Set up CI/CD pipelines (GitHub Actions)
- Work in a team following Agile/Scrum and GitFlow


## 📐 Case Study: corex — Internal Backend Framework

**Context:** At my current job, the backend team was rebuilding the same plumbing — routing, authentication, database access, response's models usable utils, — for every new service. This slowed delivery and introduced inconsistent, hard-to-track bugs.

**What I built:** I designed and developed my own internal framework on top of FastAPI, which the company came to call corex. It standardizes these cross-cutting concerns into reusable layers, so new services and endpoints follow a consistent pattern instead of being rebuilt from scratch each time.

**Impact:** Reduced code duplication and the class of bugs caused by ad-hoc auth/routing implementations, and let the team focus on business logic instead of infrastructure boilerplate. It's now the standard used across the team's services.

*Implementation details and source code are proprietary to my employer and aren't shared publicly — happy to walk through the design decisions in an interview.*

## 🚀 Projects

### ⚔️ Legends of Wuno
A commercial RPG game — volunteer (pro bono) backend contribution, working within a development team.
**My contribution:**
- Built the in-game shop module: product catalog, checkout endpoint, order-confirmation emails, inventory deduction on purchase
- Built character-creation endpoints: location, character, and nickname selection
- Configured Django/Celery entrypoints in Docker

Stack: Python 3.12, Django, DRF, PostgreSQL, Docker, Celery, Ruff, pre-commit
→ [My commits in this project](https://github.com/Kesh113/Legends-of-Wuno/commits/develop/?author=MrFR0D0)

### 🥗 Foodgram
A recipe publishing and management service.
**My contribution:**
- Full backend: authentication, subscriptions, shopping lists, favorites
- Docker build, deployment with Gunicorn and Nginx
- PostgreSQL, CI/CD via GitHub Actions

Stack: Python, Django, DRF, Docker, PostgreSQL, Nginx, Gunicorn, GitHub Actions

### 📚 YaMDb
A ratings & review platform for cultural content (films, books, music) — team project.
**My contribution:**
- API development
- Team collaboration following GitFlow
- 90% test coverage (pytest); acted as team lead — broke down tasks, assigned work, coordinated the team

Stack: Python, Django, DRF, pytest

### ✅ Taski-docker
A simple task tracker.
**My contribution:**
- API on Django REST Framework
- Docker and CI/CD setup
- Server deployment

Stack: Python, DRF, Docker, Gunicorn, Nginx, GitHub Actions

### 🤖 Telegram Status-Check Bot
A bot that tracks project status changes via an external API.
**My contribution:**
- Request logic, logging, Telegram API integration

Stack: Python, Telebot, requests, dotenv


## 📊 GitHub Stats

<p align="left">
  <img height="180" src="https://github-readme-stats-hobby-49d2.vercel.app/api?username=MrFR0D0&show_icons=true&theme=default&hide_border=true" />
  <img height="180" src="https://github-readme-stats-hobby-49d2.vercel.app/api/top-langs/?username=MrFR0D0&layout=compact&hide_border=true" />
</p>
