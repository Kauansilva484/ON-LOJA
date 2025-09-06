# OnZap - Agentes de IA para WhatsApp

Landing page SaaS para plataforma de agentes de IA integrados ao WhatsApp Business.

## Estrutura do Projeto

```
SAAS-main/
├── frontend/          # Aplicação React + TypeScript + Vite
│   ├── src/          # Código fonte da landing page
│   ├── dist/         # Build de produção
│   ├── package.json  # Dependências do frontend
│   └── ...
├── backend/          # API e serviços backend (futuro)
│   └── README.md     # Guia para desenvolvimento backend
├── node-portable/    # Node.js portável
└── README.md         # Este arquivo
```

## Frontend

- **Framework**: React 18 + TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Animações**: GSAP + ScrollTrigger
- **Deploy**: Netlify

### Comandos Frontend

```bash
cd frontend
npm install          # Instalar dependências
npm run dev         # Servidor de desenvolvimento
npm run build       # Build de produção
```

## Backend

Estrutura preparada para desenvolvimento futuro de APIs e integração com WhatsApp Business.

## Deploy

O projeto está configurado para deploy no Netlify via `netlify.toml`.
