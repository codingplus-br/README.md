<div align="center">

<img src="./codingplus-banner.svg" alt="CodingPlus" width="100%" />

### Construímos software que fica no bastidor do trabalho de outras pessoas —
### e faz esse trabalho ficar mais simples.

<br />

![Status](https://img.shields.io/badge/status-em%20constru%C3%A7%C3%A3o-16A66A?style=for-the-badge)
![Made in Brazil](https://img.shields.io/badge/feito%20no-Brasil-16A66A?style=for-the-badge)
![Open Source Friendly](https://img.shields.io/badge/open%20source-friendly-16A66A?style=for-the-badge)

</div>

<br />

## 👋 Quem somos

A **CodingPlus** é uma software house criada para dar apoio técnico a produtos
digitais do dia a dia — sistemas que precisam ser confiáveis, simples de usar
e feitos para durar, não só para o lançamento.

Em vez de ser uma consultoria genérica, atuamos como um **time de tecnologia
dedicado** a um portfólio pequeno de produtos próprios, cuidando de arquitetura,
segurança, infraestrutura e evolução contínua de cada um deles.

<br />

## 🚀 Produtos que apoiamos

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🩺 Fawlife</h3>
      <p>
        Plataforma de gestão para profissionais e clínicas da área da saúde —
        agenda, cadastro de pacientes, cobrança e financeiro em um só lugar,
        multi-tenant desde o primeiro dia.
      </p>
      <p>
        <img src="https://img.shields.io/badge/status-em%20desenvolvimento-16A66A?style=flat-square" />
      </p>
      <ul>
        <li>Arquitetura de microsserviços (API Gateway + serviços por domínio)</li>
        <li>Autenticação e onboarding completo (perfil profissional + loja/clínica)</li>
        <li>Agenda, disponibilidade e agendamento de consultas</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🛒 Tivvo</h3>
      <p>
        Sistema de gestão de caixas (PDV) para supermercados — pensado para o
        dia a dia do operador de caixa, com o mínimo de fricção possível.
      </p>
      <p>
        <img src="https://img.shields.io/badge/status-planejamento-6B7771?style=flat-square" />
      </p>
      <ul>
        <li>Frente de caixa (PDV) rápida e confiável</li>
        <li>Controle de vendas e fechamento de caixa</li>
        <li>Integração com o fluxo de estoque do supermercado</li>
      </ul>
    </td>
  </tr>
</table>

<br />

## 🛠️ Como construímos

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

Cada produto é dividido em **microsserviços independentes**, um repositório
por serviço, com um API Gateway cuidando da porta de entrada. Isso deixa cada
time (ou cada dev) livre para evoluir uma parte do sistema sem travar as
outras — e permite escalar só o que realmente precisa escalar.

Alguns princípios que seguimos em todos os projetos:

- **Segurança não é etapa final.** Toda mudança passa por revisão de
  segurança (com apoio de IA) antes de chegar em produção.
- **Testes automatizados de verdade.** Unitários e de integração rodando em
  CI a cada push, não só "quando dá tempo".
- **Infraestrutura como produto.** Ambientes reproduzíveis (Docker), deploy
  documentado e observável, sem "só funciona na minha máquina".
- **Git com fluxo claro.** Uma branch pessoal por dev → integração →
  produção, sempre via *pull request* revisado.

<br />

## 📂 Como nossos repositórios são organizados

Não usamos monorepo. Cada serviço/produto vive no seu próprio repositório,
com seu próprio ciclo de deploy e versionamento — a documentação de
arquitetura de cada produto explica o motivo dessa escolha e como os serviços
conversam entre si.

<br />

<div align="center">

**CodingPlus** — construindo com cuidado, um produto de cada vez. 💚

</div>
<img width="1280" height="320" alt="codingplus-banner" src="https://github.com/user-attachments/assets/3cb0b364-bb1b-4d49-aa6f-678fd1ebb155" />
