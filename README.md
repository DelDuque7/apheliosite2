# Aphelio Lab — Landing Page (Vite + React)

## Rodar localmente
```bash
npm install
npm run dev
```

## Publicar
```bash
npm run build
npm run preview
```

## Ajustes obrigatórios (placeholders)
- `src/config.js`
  - `whatsappNumber` (somente números, ex.: 5535999999999)
  - `city`
  - `instagramUrl`, `linktreeUrl`
  - `og:url` em `index.html`

## Imagens (placeholders)
- Logo: `public/images/logo.png` (já incluído)
- Foto do Vinícius (sem fundo): `public/images/vinicius-duque.png` (já incluído)
- OG image: `public/images/og.jpg` (placeholder)
- Outros: `public/images/hero.jpg`, `before-after-1.jpg`, `logo-1.png` etc (placeholders)

## Observações
- A landing é 1 página (`/`) + thank you page (`/obrigado`).
- O formulário salva os dados no `localStorage` e redireciona para `/obrigado`.
- O botão do WhatsApp é gerado com mensagem pré-preenchida.

