Zuki-AI-assistant
Features

Voice Assistant
- Understands voice input for task setting
- Recognizes interval-based commands (e.g., "every 10 minutes")
- Provides voice responses using `pyttsx3`

Reminders System
- Stores task and time intervals in a PostgreSQL database
- Tracks last triggered time for each task
- Can be extended for notification alerts

Intelligent Backend
- PostgreSQL integration using `psycopg2`
- `reminders` table with:
  - ID
  - Task
  - Interval (minutes)
  - Last Triggered timestamp
- Smart error handling (e.g., permission, duplication)

Upcoming Features
- Desktop GUI to view/edit reminders
- Background notifications and reminders
- Google Calendar sync
- Task progress visualization
- Voice command customization
