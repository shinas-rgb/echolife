# echolife
│
├── app.py                     # Main flask app

├── requirements.txt           # Libraries list
├── config.py                  # Keys, DB connection, cloud creds
│
├── static/                    # Frontend assets
│   ├── css/
│   ├── js/
│   └── uploads/               # Temporary local media before cloud upload
│
├── templates/                 # HTML pages (Jinja2)
│   ├── index.html
│   ├── dashboard.html
│   ├── login.html
│   ├── register.html
│   ├── journal_record.html
│   ├── todos.html
│   └── settings.html
│
├── models/                    # DB models
│   ├── user_model.py
│   ├── journal_model.py
│   └── todo_model.py
│
├── routes/                    # All route files
│   ├── auth_routes.py
│   ├── journal_routes.py
│   ├── todo_routes.py
│   └── reminder_routes.py
│
├── services/                  # Background task, cloud, email, reminder
│   ├── cloud_service.py       # Firebase / AWS upload functions
│   ├── reminder_service.py    # Cron/mail/WhatsApp notification logic
│   └── speech_to_text.py      # (optional)
│
└── database/
    └── schema.sql             # Table creation script
