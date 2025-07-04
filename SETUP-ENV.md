# Sistema GENTE - Configuração de Ambiente

## 📋 Passos para Configurar os Arquivos .env

### Backend
```powershell
cd backend
copy config.example.env .env
```

### Frontend  
```powershell
cd frontend
copy config.example.env .env.local
```

## ⚙️ Configurações Necessárias

### Backend (.env)
- Configure as credenciais do PostgreSQL
- Defina um JWT_SECRET seguro
- Ajuste a porta se necessário (padrão: 3001)

### Frontend (.env.local)
- Configure a URL da API backend
- Ajuste outras configurações conforme necessário

## 🚀 Próximos Passos
1. Configure o banco PostgreSQL
2. Execute `npm run dev` no backend
3. Execute `npm run dev` no frontend
4. Acesse http://localhost:3000 para ver o sistema funcionando

## 📁 Estrutura do Projeto
```
Sistema-Gente/
├── backend/          # API REST com Node.js + Express + TypeScript
├── frontend/         # Interface com Next.js + TypeScript + Tailwind + ShadcnUI
└── SETUP-ENV.md     # Este arquivo
```
