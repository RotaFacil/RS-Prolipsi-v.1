# Guia de Deploy - RS Prólipsi

## Arquivos de Produção

Os arquivos prontos para deploy estão na pasta **`dist/`**:
- `index.html` - Página principal
- `assets/` - Arquivos JavaScript e CSS otimizados

## Tamanho Total
- HTML: 8.86 kB (gzip: 2.15 kB)
- JavaScript: 825.54 kB (gzip: 200.05 kB)
- **Total comprimido: ~202 kB**

## Opções de Deploy

### 1. Vercel (Recomendado)
```bash
npm install -g vercel
vercel
```

### 2. Netlify
```bash
npm install -g netlify-cli
netlify deploy --prod --dir=dist
```

### 3. GitHub Pages
1. Push para repositório GitHub
2. Configure GitHub Pages para servir a pasta `dist/`

### 4. Cloudflare Pages
1. Conecte seu repositório Git
2. Configure build command: `npm run build`
3. Configure output directory: `dist/`

## Variáveis de Ambiente

Certifique-se de configurar no seu serviço de deploy:
```
GEMINI_API_KEY=sua_chave_da_api_google_gemini
```

## Verificação Pré-Deploy

```bash
# Build
npm run build

# Verificar arquivos
ls -la dist/
```

## Após o Deploy

1. Teste todas as funcionalidades principais:
   - Navegação do site
   - Carrinho de compras
   - Chatbot com IA
   - Painel administrativo (acesso local)

2. Verifique o console do navegador para erros

3. Teste em diferentes dispositivos (mobile, tablet, desktop)
