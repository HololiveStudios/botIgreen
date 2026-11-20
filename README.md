# botIgreen - Automação e Painel iGreen

## 1. Objetivo e Finalidade
Sistema de automação com bot e painel de controle voltado à operação comercial de assinaturas de energia limpa iGreen Energy.

## 2. Tecnologias Utilizadas
- Node.js, TypeScript, Vite, React, Express, WhatsApp Automation

## 3. Arquitetura e Estrutura de Diretórios
Arquitetura desacoplada cliente-servidor:
- `backend/`: Servidor Node.js para fluxo de atendimento e automação.
- `frontend/`: Dashboard em React/Vite/TypeScript para visualização e métricas.

## 4. Principais Arquivos e Responsabilidades
- `backend/package.json`: Dependências do motor do bot.
- `frontend/src/`: Componentes visuais do painel de monitoramento.
- `frontend/vite.config.ts`: Configuração do frontend.

## 5. Funcionalidades Identificadas
- Dashboard de acompanhamento de leads e clientes iGreen
- Fluxos automatizados para captação de clientes de energia solar
- Separação clara entre backend de automação e interface gráfica

## 6. Como Compilar ou Executar
```bash
# Frontend
cd frontend && npm install && npm run dev
# Backend
cd backend && npm install && npm run dev
```

## 7. Estado Atual do Projeto
**Completo**

## 8. Pendências e Limitações Identificadas
Conexão com gateway oficial de WhatsApp (Evolution API / Baileys).
