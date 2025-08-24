# Insyd Notification POC (CRA frontend + Express backend + SQLite)

## Structure
- backend/ - Express server, SQLite DB (notifications.db), Socket.IO
- frontend/ - Create React App frontend (functional components)

## Run Backend
cd backend
npm install
npm start

Server runs on http://localhost:3001

## Run Frontend
cd frontend
npm install
npm start

Frontend runs on http://localhost:3000 (CRA dev server)

## Notes
- The backend ships with a pre-populated SQLite DB (`notifications.db`) with sample notifications for `user1`.
- Frontend proxy is configured to forward API/socket requests to the backend.
