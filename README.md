<div align="center">
  <h1>Olá, eu sou Tharcio Santos</h1>
  <p><strong>Desenvolvedor Full Stack Júnior · Estágio em Desenvolvimento</strong></p>
  <p>TypeScript · React · Next.js · Node.js · PostgreSQL</p>

  <p>
    De manutenção de equipamentos e suporte de TI para aplicações full stack.<br/>
    Aprendi a diagnosticar problemas, documentar processos e conversar com quem usa o sistema no dia a dia.<br/>
    Hoje construo produtos completos: interface, API, banco relacional e controle de acesso (RBAC/RLS), com regra de negócio coberta por testes automatizados, do banco ao deploy.
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

### [ManutFlow](https://github.com/tharciosantos/manutflow) · Gestão de manutenção e ordens de serviço
Sistema full stack para controle de equipamentos, ordens de serviço e SLAs. Substitui planilhas por visibilidade operacional em tempo real do que está parado, em andamento ou atrasado — com dashboard, prazos e histórico auditável.

- Isolamento de dados em 3 camadas: Proxy SSR, validação na API e PostgreSQL RLS + triggers contra IDOR
- Atualização transacional via RPC (`SELECT ... FOR UPDATE`), bucket privado com proxy autenticado e login demo em 1 clique
- **207 testes automatizados em 19 suítes** (Vitest + Testing Library) com CI no GitHub Actions

`Next.js` · `TypeScript` · `Tailwind CSS` · `Supabase` · `PostgreSQL` · `Vitest`

[Demo](https://manutflow.vercel.app) · [Estudo de Caso](https://tharcio-portfolio.vercel.app/projetos/manutflow) · [Repositório](https://github.com/tharciosantos/manutflow)

---

### [HelpFlow](https://github.com/tharciosantos/helpflow) · Service desk multi-empresa
Plataforma de chamados com arquitetura multi-tenant, garantindo no servidor que cada organização acesse exclusivamente seus próprios dados e tickets.

- Convite por código, perfis Cliente e Agente (RBAC fail-closed no servidor), revogação de sessão (`tokenVersion`), rate limiting e login demo em 1 clique
- Validação com Zod, **169 testes unitários no Vitest (14 suítes)** + **15 fluxos E2E no Cypress**
- Primeiro sistema completo que construí em JavaScript; no ManutFlow evoluí a arquitetura para TypeScript strict

`Next.js` · `JavaScript` · `Prisma` · `PostgreSQL` · `NextAuth.js` · `Zod` · `Vitest` · `Cypress`

[Demo](https://helpflow.vercel.app) · [Estudo de Caso](https://tharcio-portfolio.vercel.app/projetos/helpflow) · [Repositório](https://github.com/tharciosantos/helpflow)

---

### [DevLinks](https://github.com/tharciosantos/devlinks-web) · Agregador de links full stack
Frontend SPA e API RESTful em repositórios desacoplados, com perfil público de links, autenticação JWT e upload de avatar via Cloudinary.

- **API (`devlinks-api`):** Node.js, Express, MongoDB, JWT, ownership, validação Zod e **15 testes de integração** (Vitest + Supertest + MongoDB Memory Server)
- **Frontend (`devlinks-web`):** React, Vite, cache e sincronização via TanStack Query + testes E2E com Cypress no GitHub Actions

`React` · `Vite` · `Node.js` · `Express` · `MongoDB` · `TanStack Query` · `Cloudinary` · `Cypress`

[Demo](https://devlinks-web-api.vercel.app/) · [Repositório Web](https://github.com/tharciosantos/devlinks-web) · [Repositório API](https://github.com/tharciosantos/devlinks-api)

<details>
<summary><strong>Outros projetos publicados</strong></summary>
<br/>

- **[Lista de Mercado PWA](https://lista-mercado-sage.vercel.app/)**: lista de compras offline-first (Service Worker) com auto-categorização de 220 itens e exportação para WhatsApp. `React` · `Vite` · `PWA` · `Tailwind CSS` · [Repositório](https://github.com/tharciosantos/lista-mercado)
- **[Crypto Dashboard](https://crypto-dashboard-five-sandy.vercel.app/)**: painel financeiro consumindo a API CoinGecko com fallback resiliente contra rate limit. `Next.js` · `React` · `Tailwind CSS` · [Repositório](https://github.com/tharciosantos/crypto-dashboard)
</details>

---

## Tecnologias e ferramentas

| Categoria               | Tecnologias                                                              |
|-------------------------|--------------------------------------------------------------------------|
| **Frontend**            | React, Next.js (App Router), TypeScript, JavaScript (ES6+), Vite, Tailwind CSS |
| **Backend e APIs**      | Node.js, Express, Next.js Route Handlers, NextAuth.js, JWT, Zod          |
| **Bancos e ORM**        | PostgreSQL, SQL, Supabase (RLS), Prisma ORM, MongoDB                     |
| **Mídia e estado**      | TanStack Query, Cloudinary                                               |
| **Testes e qualidade**  | Vitest, React Testing Library, Cypress (E2E), Supertest, ESLint, Prettier|
| **Ferramentas e deploy**| Git, GitHub, GitHub Actions (CI/CD), Vercel                              |

### Atualmente estudando
`Java e JVM` (POO e estruturas de dados) · `Arquitetura de software` (SOLID, Clean Architecture) · `DevOps` (Docker e containers)

---

## Sobre mim

- Cursando **Análise e Desenvolvimento de Sistemas** na Anhanguera (**4º semestre** · previsão de conclusão: jul/2027)
- Experiência prévia em manutenção de equipamentos, rotina administrativa e suporte de TI autônomo — bagagem que uso para diagnosticar causas raiz e modelar regras de negócio reais
- Caeté / Região Metropolitana de Belo Horizonte (MG) · **Aberto a estágio ou júnior (presencial, híbrido ou remoto)**
