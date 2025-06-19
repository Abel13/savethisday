# 🎉 SaveThis.day — Crie eventos personalizados e inesquecíveis

**SaveThis.day** é uma plataforma white-label para criação de páginas de eventos como chás de bebê, aniversários, casamentos e confraternizações. Com uma experiência linda, responsiva e simples de usar, qualquer pessoa pode montar sua página, confirmar presenças e receber presentes online.

## 🌐 Acesse
[https://savethis.day](https://savethis.day) *(em breve)*

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
