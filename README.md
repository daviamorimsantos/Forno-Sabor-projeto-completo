# Forno & Sabor 🍕

Catálogo demonstrativo de pizzaria com React + Vite. Funciona no front-end, sem banco de dados ou backend.

## Requisitos
- Node.js LTS (https://nodejs.org/)
- Git (opcional, para enviar pelo terminal)

## Rodar localmente
```bash
npm install
npm run dev
```
Abra o endereço exibido pelo Vite, normalmente http://localhost:5173.

## Personalização
Edite `src/data/store.js` para trocar nome, WhatsApp, endereço, horário, taxa de entrega e links.
Edite `src/data/products.js` para alterar produtos, preços e imagens.

Os preços, endereço, avaliações, tempo de entrega e número de WhatsApp são demonstrativos. Antes de usar com um negócio real, substitua os dados e teste o fluxo completo.

## Publicar no GitHub e Vercel
1. Crie um repositório vazio no GitHub.
2. Envie todos os arquivos deste projeto.
3. Entre em https://vercel.com/ e conecte sua conta GitHub.
4. Clique em **Add New → Project** e importe o repositório.
5. A Vercel detecta Vite automaticamente. Build command: `npm run build`; output directory: `dist`.
6. Clique em **Deploy** e abra o link gerado.

Cada `git push` na branch principal dispara um novo deploy automaticamente.