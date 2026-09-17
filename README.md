<p align="center">
  <img src="Capa_Readme.jpg" alt="Capa do perfil de Gabriel Martorelli" />
</p>

<h1 align="center">👋 Olá! Eu sou o Gabriel Martorelli</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=Desenvolvedor+Full+Stack+Jr+na+PROVER;.NET+10+%2B+C%23+no+backend;React+%2F+Next.js+%2B+TypeScript+no+frontend;Aprendendo+e+construindo+todos+os+dias+%F0%9F%9A%80&font=Fira+Code&center=true&width=600&height=45&duration=3000&pause=1000&color=58A6FF&vCenter=true" alt="Typing SVG" />
</p>

<p align="center">
  💼 <strong>Desenvolvedor Full Stack Jr</strong> na <strong>PROVER Soluções em TI e Software House</strong><br />
  🎓 Estudante de <strong>Sistemas de Informação</strong><br />
  🛠️ Construindo aplicações reais com <strong>.NET, C#, React, Next.js e TypeScript</strong>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/gabrielmartorelli/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://www.martodev.online/" target="_blank">
    <img src="https://img.shields.io/badge/Portfólio-121011?style=for-the-badge&logo=github&logoColor=white" alt="Portfólio" />
  </a>
  <a href="https://martoxm.github.io/marto-devcard/" target="_blank">
    <img src="https://img.shields.io/badge/Link%20in%20Bio-0A66C2?style=for-the-badge&logo=linktree&logoColor=white" alt="Link in Bio" />
  </a>
  <a href="mailto:gabriel.martorelli@hotmail.com">
    <img src="https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail" />
  </a>
</p>

<p align="center">
  <a href="https://crypto-monitor-fullstack.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/🔴%20Live%20em%20produção-Crypto%20Monitor-success?style=for-the-badge" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=martoxm&style=for-the-badge&color=blueviolet&label=Visitas+ao+perfil" alt="Visitas ao perfil" />
</p>

---

## 👨‍💻 Sobre mim

Atualmente atuo como **Desenvolvedor Full Stack Jr na PROVER Soluções em TI e Software House**, aplicando no dia a dia o que venho estudando em desenvolvimento web e arquitetura de software.

Gosto de construir aplicações organizadas, funcionais e fáceis de manter, aplicando boas práticas como **DDD**, **CQRS**, **SOLID**, separação de responsabilidades e documentação de APIs. No backend trabalho com **C#/.NET**, e no frontend com **React**, **Next.js** e **TypeScript**.

> 🌱 Atualmente estudando: **Clean Architecture, CQRS com MediatR, Entity Framework Core, testes unitários com xUnit e Tailwind CSS.**

---

## ⭐ Projetos em destaque

---

### 🍽️ [Restaurante Estoque — Sistema de Controle de Estoque Full Stack](https://github.com/martoxm/restaurante-estoque)

> Projeto desenvolvido na PROVER: sistema de controle de estoque para restaurante, construído do zero — domínio, CQRS, autenticação, regras de estoque e CRUD completo.

| Camada          | Tecnologias                                                                                             |
| :-------------- | :------------------------------------------------------------------------------------------------------ |
| **Backend**     | .NET 10 · C# · Minimal API · CQRS com MediatR · Entity Framework Core · SQL Server · JWT + BCrypt       |
| **Frontend**    | Next.js (App Router) · TypeScript · Tailwind CSS · shadcn/ui · Axios · TanStack Query                   |
| **Arquitetura** | Clean Architecture (Domain → Application → Infrastructure → Api → Contracts) · DDD · Repository Pattern |

**Destaques técnicos:**

- 🧱 DDD com entidades ricas — regras de negócio na própria entidade, não em serviços externos
- 🔐 Autenticação JWT com hash de senha via BCrypt
- 📦 CRUD completo de Produtos, Categorias e Fornecedores + movimentação de estoque com validação de saldo
- 📊 Dashboard com indicadores simples (estoque baixo, totais) e listagens paginadas/ordenáveis
- 🔗 API versionada (`/api/v1`)

---

### 🔐 [Crypto Monitor — Ecossistema Fullstack em Produção 24/7](https://github.com/martoxm/crypto-monitor-fullstack)

> Sistema autônomo de monitoramento de criptoativos rodando em produção real, com infraestrutura cloud completa.

| Camada              | Tecnologias                                                    |
| :------------------ | :------------------------------------------------------------- |
| **Backend**         | .NET 10 · C# · ASP.NET Core · Entity Framework Core · SQLite   |
| **Automação / ETL** | n8n (Docker) · Pipeline de ingestão agendado · CoinGecko API   |
| **Infraestrutura**  | Oracle Cloud VPS · Docker · Nginx (Proxy Reverso) · Systemd    |
| **Segurança**       | TLS/SSL via Certbot (Let's Encrypt) · HTTPS ponta a ponta      |
| **Frontend**        | HTML5 · CSS · JavaScript (Fetch API / CORS) · Deploy na Vercel |
| **Arquitetura**     | DDD · SOLID · Microsserviços desacoplados                      |

**Destaques técnicos:**

- 🌐 Disponível 24/7 em: [crypto-monitor-fullstack.vercel.app](https://crypto-monitor-fullstack.vercel.app/)
- ⚙️ Pipeline ETL automatizado com n8n em container Docker
- 🔒 Infraestrutura segura com SSL, Nginx reverse proxy e Systemd service
- ☁️ Hospedagem em VM Ubuntu na Oracle Cloud com SWAP de 2GB otimizado

---

### 💸 [Controle de Gastos Residenciais — Desafio Técnico Fullstack](https://github.com/martoxm/ControleGastos)

> Sistema web fullstack desenvolvido como teste técnico, do backend ao frontend, do zero.

| Camada          | Tecnologias                                                                    |
| :-------------- | :----------------------------------------------------------------------------- |
| **Backend**     | .NET 10 · C# · ASP.NET Core Web API · Entity Framework Core · SQLite · Swagger |
| **Frontend**    | React 19 · TypeScript · Vite · React Router DOM · Axios                        |
| **Arquitetura** | DDD · SOLID · Separação em camadas                                             |

**Funcionalidades entregues:**

- Cadastro, listagem e remoção de pessoas (exclusão em cascata de transações)
- Regra de negócio: menores de 18 anos só podem registrar despesas
- Relatório financeiro com totais por pessoa e consolidado geral
- Persistência com SQLite · Documentação com Swagger/OpenAPI

---

<details>
<summary>🛠️ <strong>Tecnologias</strong> (clique para expandir)</summary>

### Backend

<p>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET Core" />
  <img src="https://img.shields.io/badge/Entity_Framework_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="Entity Framework Core" />
  <img src="https://img.shields.io/badge/MediatR-5C2D91?style=for-the-badge" alt="MediatR" />
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT" />
</p>

### Frontend

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white" alt="shadcn/ui" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

### Ferramentas e práticas

<p>
  <img src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" alt="Swagger" />
</p>

**Arquitetura e qualidade:** DDD · CQRS · SOLID · Clean Architecture · Clean Code · APIs REST · Testes unitários com xUnit

**Bibliotecas e ferramentas:** Entity Framework Core · MediatR · Swagger/OpenAPI · FluentValidation · AutoMapper · Axios · TanStack Query

</details>

---

## 📊 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.shion.dev/api/top-langs/?username=martoxm&layout=compact&theme=tokyonight&hide_border=true" />
  <img height="180em" src="https://github-readme-stats.shion.dev/api?username=martoxm&show_icons=true&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=martoxm&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

---

## 📫 Vamos conversar?

- **E-mail:** [gabriel.martorelli@hotmail.com](mailto:gabriel.martorelli@hotmail.com)
- **LinkedIn:** [linkedin.com/in/gabrielmartorelli](https://www.linkedin.com/in/gabrielmartorelli/)
- **Portfólio:** [https://www.martodev.online/](https://www.martodev.online/)

<p align="center">
  Obrigado por visitar meu perfil! 🚀
</p>
