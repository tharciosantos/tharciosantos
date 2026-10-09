<div align="center">
  <h1>Olá, eu sou Tharcio Santos</h1>
  <p><strong>Desenvolvedor Full Stack Júnior</strong></p>
  <p>TypeScript · React · Next.js · Node.js · PostgreSQL</p>

  <p>
    De manutenção de equipamentos e suporte de TI para aplicações full stack.<br/>
    Aprendi a diagnosticar problemas, documentar processos e conversar com quem usa o sistema no dia a dia.<br/>
    Hoje construo produtos completos: interface, API, banco relacional e controle de acesso (RBAC/RLS), com regra de negócio coberta por teste, do banco ao deploy.
  </p>

  <p>
    <a href="https://tharcio-portfolio.vercel.app" target="_blank"><img src="https://img.shields.io/badge/Portfólio-B91C1C?style=flat-square&logo=vercel&logoColor=white" alt="Portfólio" /></a>
    <a href="https://www.linkedin.com/in/tharcio-santos-dev/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://tharcio-portfolio.vercel.app/curriculo-tharcio-santos.pdf" target="_blank"><img src="https://img.shields.io/badge/Currículo_PDF-57534E?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Currículo" /></a>
    <a href="mailto:tharciosantos09@gmail.com"><img src="https://img.shields.io/badge/E--mail-57534E?style=flat-square&logo=gmail&logoColor=white" alt="E-mail" /></a>
  </p>
</div>

---

## Projetos em destaque

### [ManutFlow](https://github.com/tharciosantos/manutflow) · Gestão de manutenção industrial
Sistema full stack para equipamentos, ordens de serviço e SLAs. Sai da planilha e entrega visibilidade real do que está parado, em andamento ou atrasado — com dashboard, prazos e histórico.

<p align="center">
  <img src="https://raw.githubusercontent.com/tharciosantos/manutflow/main/public/previews/preview-dashboard.png" alt="Dashboard do ManutFlow" width="100%" />
</p>

- Isolamento de dados por `user_id` (RLS), sessão com Supabase SSR e validação de payload nas APIs
- Dashboard operacional + landing com simulador e acesso de demonstração em 1 clique
- 169 testes automatizados em 17 suítes (Vitest + Testing Library)

`Next.js` · `TypeScript` · `Tailwind CSS` · `Supabase` · `PostgreSQL` · `Vitest`

[Demo](https://manutflow.vercel.app) · [Repositório](https://github.com/tharciosantos/manutflow)

---

### [HelpFlow](https://github.com/tharciosantos/helpflow) · Service desk multi-empresa
Sistema de chamados com arquitetura multi-tenant. Cada organização fica isolada: o chamado de uma empresa não aparece para outra.

<p align="center">
  <img src="https://raw.githubusercontent.com/tharciosantos/helpflow/main/docs/screenshots/04-dashboard-empresa-ti.png" alt="Dashboard do HelpFlow" width="100%" />
</p>

- Convite por código, perfis Cliente e Agente (RBAC no servidor), rate limiting e login demo em 1 clique
- Validação com Zod, 82 testes Vitest + 15 fluxos E2E no Cypress
- Foi o primeiro sistema completo que montei em JavaScript. No ManutFlow a stack migrou para TypeScript strict

`Next.js` · `JavaScript` · `Prisma` · `PostgreSQL` · `NextAuth` · `Vitest` · `Cypress`

[Demo](https://helpflow.vercel.app) · [Repositório](https://github.com/tharciosantos/helpflow)

---

### [DevLinks](https://github.com/tharciosantos/devlinks-web) · Agregador de links full-stack
Frontend e API em repositórios separados: perfil público de links, autenticação JWT e upload de avatar via Cloudinary.

<p align="center">
  <img src="https://raw.githubusercontent.com/tharciosantos/devlinks-web/main/docs/tela-dashboard.PNG" alt="Dashboard do DevLinks" width="100%" />
</p>

- API Express com JWT, ownership, MongoDB e upload no Cloudinary + testes de integração (Vitest + Supertest)
- Frontend React + Vite com cache via TanStack Query + E2E com Cypress no fluxo de login e links

`React` · `Vite` · `Express` · `MongoDB` · `TanStack Query` · `Cloudinary` · `Cypress`

[Demo](https://devlinks-web-api.vercel.app/) · [Frontend](https://github.com/tharciosantos/devlinks-web) · [API](https://github.com/tharciosantos/devlinks-api)

<details>
<summary><strong>Outros projetos</strong></summary>
<br/>

- **[Lista de Mercado PWA](https://lista-mercado-sage.vercel.app/)**: lista de compras offline (Service Worker) com base de 220 itens. `React` · `Vite` · `PWA` · `Tailwind` · [Repositório](https://github.com/tharciosantos/lista-mercado)
- **[Crypto Dashboard](https://crypto-dashboard-five-sandy.vercel.app/)**: cotações em tempo real via CoinGecko API. `Next.js` · `React` · `Tailwind` · [Repositório](https://github.com/tharciosantos/crypto-dashboard)
</details>

---

## Tecnologias e ferramentas

| Categoria              | Tecnologias                                                              |
|------------------------|--------------------------------------------------------------------------|
| **Frontend**           | React, Next.js (App Router), TypeScript, JavaScript, Tailwind CSS        |
| **Backend e APIs**     | Node.js, Express, Next.js API Routes, NextAuth.js, JWT, Zod              |
| **Bancos e ORM**       | PostgreSQL, Supabase (RLS), Prisma, MongoDB                              |
| **Mídia e cache**      | Cloudinary, TanStack Query                                               |
| **Testes e qualidade** | Vitest, React Testing Library, Cypress, Supertest, ESLint, Prettier      |
| **Ferramentas e deploy**| Git, GitHub, GitHub Actions, Vercel                                     |

### Atualmente estudando
`Java e JVM` (POO e estruturas de dados) · `Arquitetura de software` (SOLID, Clean Architecture) · `DevOps` (Docker e containers)

---

## Sobre mim

- Cursando **Análise e Desenvolvimento de Sistemas** na Anhanguera (previsão de conclusão: jul/2027)
- Experiência prévia em manutenção de equipamentos, rotina administrativa e suporte de TI autônomo
- Essa bagagem me ajuda a entender o lado do usuário e a construir sistemas que realmente resolvem problemas do dia a dia
- Moro em Caeté, região metropolitana de Belo Horizonte (MG) · Presencial, híbrido ou remoto

---

<div align="center">
  <p><strong>Aberto a oportunidades de estágio ou júnior.</strong><br/>Vamos conversar?</p>
  <p>
    <a href="https://tharcio-portfolio.vercel.app" target="_blank"><img src="https://img.shields.io/badge/Portfólio-B91C1C?style=flat-square&logo=vercel&logoColor=white" alt="Portfólio" /></a>
    <a href="https://www.linkedin.com/in/tharcio-santos-dev/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:tharciosantos09@gmail.com"><img src="https://img.shields.io/badge/E--mail-57534E?style=flat-square&logo=gmail&logoColor=white" alt="E-mail" /></a>
  </p>
</div>
