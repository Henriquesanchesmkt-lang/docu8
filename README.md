
# Docu8 – MVP (Backend + Frontend)

Este pacote contém um MVP funcional do Docu8:
- Backend (Express + Prisma + PDFKit + JWT OTP)
- Frontend (React + Vite) com login por OTP e geração/baixa de contrato em PDF

## Como usar localmente
### Backend
1. `cd backend`
2. `cp .env.example .env` e ajuste o `DATABASE_URL` para o seu Postgres
3. `npm install`
4. `npm run prisma:generate`
5. `npm run prisma:migrate`
6. `npm start`

### Frontend
1. `cd frontend`
2. `cp .env.example .env` e aponte `VITE_API_BASE_URL` para `http://localhost:4000/api`
3. `npm install`
4. `npm run dev`

## Deploy no VPS
- Siga as instruções que o assistente já entregou (Node 20 + PM2 + Nginx).
