# Medicine Reminder (React)

Manage medicine schedules: name, dosage, times of day, start/end date.
All data is stored in the browser's **localStorage** – no backend or database needed.

## Features
- No login required
- Add, view, edit and delete medicines (CRUD)
- Multiple dose times per medicine
- "Today's schedule" with Mark taken / Undo
- Reminders: in-app alert + optional browser notification when a dose time arrives (keep the tab open)

## Run
Requires Node.js 18+.
```bash
npm install
npm run dev      # http://localhost:5173
```
Production build: `npm run build`

## Notes
- Data stays in the browser you use (and is lost if you clear site data).
- Storage code lives in `src/storage.js`.
