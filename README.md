# Flask + Nginx Docker Compose Project

## 📦 Описание

Този проект демонстрира как се използва Docker Compose за стартиране на две отделни услуги:
- Flask приложение (уеб сървър)
- Nginx (обратен прокси)

Проектът е напълно контейнеризиран и може да се стартира с една команда.

---

## ▶️ Стартиране на проекта

```bash
docker-compose up --build
flask-nginx-compose/
├── app/
│   ├── app.py
│   └── requirements.txt
├── nginx/
│   └── default.conf
├── Dockerfile
├── docker-compose.yml
└── README.md

</details>

---

## 🪜 СТЪПКА 2: Запази файла

В nano:
- натисни `Ctrl + O` (за да запишеш)
- натисни `Enter` (потвърждение)
- натисни `Ctrl + X` (за изход)

---

## 🪜 СТЪПКА 3: Направи commit и push

```bash
git add README.md
git commit -m "Добавен README.md с инструкции"
git push
