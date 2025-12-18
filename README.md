# RS Prólipsi - Sistema de Criação de Sites

Sistema desenvolvido por Roberto Camargo que integra criação de sites, e-commerce, chatbot com IA, e gerenciamento de conteúdo.

## Recursos Principais

- Sistema de page builder completo com editor visual
- E-commerce com carrinho de compras e checkout
- Chatbot integrado com Google Gemini AI
- Painel administrativo completo
- Sistema de temas e personalização
- Suporte multi-idioma
- Sistema de banners e publicidade
- Gerenciamento de produtos e ofertas
- Sistema de pedidos e carrinho abandonado

## Instalação

1. Instalar dependências:
   ```bash
   npm install
   ```

2. Configurar a chave da API do Google Gemini no arquivo `.env.local`:
   ```
   GEMINI_API_KEY=sua_chave_aqui
   ```

3. Executar em modo de desenvolvimento:
   ```bash
   npm run dev
   ```

4. Fazer build para produção:
   ```bash
   npm run build
   ```

## Deploy

O projeto está pronto para deploy. Os arquivos de build estão na pasta `dist/`.

Para fazer deploy, você pode usar qualquer serviço de hospedagem estática como:
- Vercel
- Netlify
- GitHub Pages
- Cloudflare Pages

## Tecnologias

- React 19
- TypeScript
- Vite
- Google Gemini AI
- TailwindCSS (via classes customizadas)
