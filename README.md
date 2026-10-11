# CRMS Frontend

React and Vite client for the Campus Recruitment Management System.

## Run locally

```powershell
Copy-Item .env.example .env
npm install
npm run dev
```

The development server runs at `http://localhost:5173`. Set
`VITE_API_BASE_URL` in `.env` to the backend API base URL, normally
`http://localhost:8080/api`.

## Build

```powershell
npm run build
npm run preview
```

This directory can be pushed as its own GitHub repository. Commit
`package-lock.json` and `.env.example`; do not commit `.env` or `node_modules`.
