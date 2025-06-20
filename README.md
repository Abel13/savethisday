# 🎉 SaveThis.day — Crie eventos personalizados e inesquecíveis

**SaveThis.day** é uma plataforma white-label para criação de páginas de eventos como chás de bebê, aniversários, casamentos e confraternizações. Com uma experiência linda, responsiva e simples de usar, qualquer pessoa pode montar sua página, confirmar presenças e receber presentes online.

## 🌐 Acesse

[https://savethis.day](https://savethis.day) _(em breve)_

---

## ✨ Funcionalidades (MVP)

- Página pública do evento com URL personalizada
- Lista de presentes interativa
- Confirmação de presença
- Painel administrativo para criar e editar eventos
- Design adaptado para mobile e desktop
- Tema fofo e personalizável

---

## 📦 Stack

- **Next.js 14** com App Router
- **Tailwind CSS** com Radix UI / ShadCN
- **Supabase** (Auth, DB, Storage)
- **Zustand** para gerenciamento de estado
- **React Hook Form** + Yup para validações
- **Vercel** para deploy

---

## 🚀 Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/savethis-day.git

# Instale as dependências
cd savethis-day
npm install

# Copie o .env.example e configure suas variáveis
cp .env.example .env.local

# Rode o projeto
npm run dev
```

---

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

---

## 🗂️ Estrutura do Projeto

```
.
├── app/
│   ├── [eventSlug]/     # Página pública do evento
│   ├── admin/           # Painel administrativo
│   └── auth/            # Login/registro
├── components/
│   ├── ui/              # Botões, modais, inputs
│   ├── forms/           # Formulários com hook-form
├── utils/
├── store/
├── hooks/
├── public/
└── supabase/            # Tipos e serviços do Supabase
```

---

## 📌 Roadmap

- [x] MVP do evento (chá de bebê da Olívia)
- [ ] Área admin protegida
- [ ] Customização de temas
- [ ] Integração de pagamentos (Pix ou Stripe)
- [ ] Analytics para eventos
- [ ] Sistema de planos (Free/Premium)

---

## 👨‍💻 Contribuindo

1. Fork este repositório
2. Crie uma branch: `feat/nova-feature`
3. Commit suas alterações
4. Envie um PR 🚀

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

Feito com 💜 por [Abel] e colaboradores ✨
