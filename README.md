Ссылка на проект @PinkEpil_Bot 

[Скриншот](https://github.com/Khorneluk/Ai_Assistent-/blob/main/photo_2025-05-28_22-57-56.jpg?raw=true)



🧠 ИИ Ассистент для студии лазерной эпиляции
Этот проект представляет собой интеллектуального ассистента на основе искусственного интеллекта, разработанного специально для студии лазерной эпиляции. Он помогает автоматизировать общение с клиентами, отвечать на часто задаваемые вопросы и записывать клиентов на прием через календарь Google.

📌 Основные функции
Осмысленное ведение диалога
Ассистент поддерживает естественный диалог с клиентом благодаря использованию нейросетевой модели.
Ответы по базе знаний
Предоставляет точные ответы на вопросы клиентов, опираясь на заранее подготовленную базу знаний о процедурах, ценах, противопоказаниях и других важных аспектах.
Запись клиента на услугу
Автоматически бронирует удобное время для клиента в календаре Google Calendar.
Интеграция с внешними сервисами
Qwen : используется для создания системного промпта и наполнения базы знаний.
Suvvy AI : платформа, на которой реализован ИИ-ассистент (https://app.suvvy.ai/ ).
🔧 Архитектура решения
1. Создание базы знаний
База знаний формировалась с помощью LLM-модели Qwen , которая помогла структурировать информацию, создать FAQ и сгенерировать системный промпт для работы ассистента.

2. Разработка ИИ-ассистента
Для создания самого ассистента использовалась платформа Suvvy AI :

Настройка чат-бота
Интеграция базы знаний
Обучение модели на типовых вопросах клиентов
🔗 Suvvy AI — платформа, позволяющая создавать ИИ-ассистентов без необходимости глубокого программирования.

3. Интеграция с Google Calendar
После того как клиент выбирает услугу и удобное время, ассистент взаимодействует с API Google Calendar для записи клиента. Это позволяет автоматизировать процесс записи и исключить дублирование.

🛠️ Технологии и инструменты
Qwen
Генерация промптов и базы знаний
Suvvy AI
Платформа для создания ИИ-ассистента
Google Calendar API
Запись клиентов на прием
JavaScript
Взаимодействие с API и обработка данных

📁 Структура проекта (пример)


1
2
3
4
5
6
7
/laser-epilation-assistant
│
├── /knowledge-base     # Файлы с информацией о студии, услугах, FAQ
├── /scripts            # Скрипты для интеграции с Google Calendar
├── /prompts            # Промпты, используемые в Suvvy AI
├── README.md           # Описание проекта
└── config.js           # Конфигурационные файлы (ключи API и т.д.)
📈 Возможности развития
Добавление интеграции с CRM-системой
Поддержка нескольких языков
Анализ обращений клиентов и улучшение базы знаний
Отправка напоминаний клиентам через WhatsApp или SMS
📬 Контакты
Если у вас есть идеи по улучшению проекта или предложения по сотрудничеству — свяжитесь с нами:
