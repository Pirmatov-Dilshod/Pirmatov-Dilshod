from pathlib import Path

readme_content = """
# 👋 Привет! Меня зовут Пирматов Дилшод

💻 Я — backend-разработчик на Python (Junior)  
🎓 Студент 2 курса, направление: "Разработка программного обеспечения"  
📍 Мне 19 лет, и у меня уже есть 1 год опыта

---

## 💼 Чем я занимаюсь

- Разрабатываю веб-приложения и REST API на Django и Django REST Framework  
- Работаю с PostgreSQL, SQLite, Redis  
- Пишу автотесты с Pytest  
- Настраиваю CI/CD процессы, использую Docker  
- Работаю с GitHub, GitLab, Linux (Ubuntu)

---

## 🛠️ Мой стек технологий

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=fff)
![Django](https://img.shields.io/badge/-Django-092E20?logo=django&logoColor=fff)
![DRF](https://img.shields.io/badge/-DRF-red?logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?logo=postgresql&logoColor=fff)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black)
![CI/CD](https://img.shields.io/badge/-CI/CD-blue)
![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github)
![GitLab](https://img.shields.io/badge/-GitLab-FC6D26?logo=gitlab&logoColor=white)
![HTML](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white)
![Pytest](https://img.shields.io/badge/-Pytest-0A9EDC?logo=python&logoColor=white)

---

## 🔭 Сейчас работаю над

- 📚 Django-библиотекой с короткими и длинными ссылками
- 🔗 API-сервисом для генерации коротких URL
- 🧪 Тестами и Swagger-документацией для REST API

---

## 📫 Контакты

- 💬 Telegram: [@Moneybossf](https://t.me/Moneybossf)
- 🌐 GitHub: [github.com/Pirmatov-Dilshod](https://github.com/Pirmatov-Dilshod)

---

## ⚡ Немного обо мне

- Люблю backend, REST и чистую архитектуру
- Учу DevOps: деплой, docker, auto-tests, workflows
- Постоянно расту через pet-проекты
"""

# Save the content to a README.md file
readme_path = Path("/mnt/data/README.md")
readme_path.write_text(readme_content.strip())

readme_path.name
