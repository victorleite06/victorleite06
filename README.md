<div align="center">

# Victor Leite de Andrade

### Desenvolvedor Full Stack Pleno · Java · Spring Boot · Angular

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victor-leite-de-andrade-5b7083192)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:victor.leite2001@gmail.com)
[![Location](https://img.shields.io/badge/Belo_Horizonte,_MG-4B5563?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

## 👨‍💻 Sobre mim

Desenvolvedor Full Stack com **mais de 3 anos de experiência** em Java e Angular, construindo toda a trajetória dentro da mesma empresa — de **Jovem Aprendiz até Pleno**. Atuo com domínio completo da stack: desde SPAs responsivas em Angular/TypeScript até back-ends robustos com Spring Boot, processamento assíncrono com Kafka e integrações com ERP TOTVS RM.

Foco em **clean code**, **SOLID**, **arquitetura de microsserviços** e soluções que entregam valor de ponta a ponta. Mentoreio juniores e tenho visão sistêmica que une front-end, back-end e infra em decisões de arquitetura.

---

## 🚀 Stack principal

### Back-end
![Java](https://img.shields.io/badge/Java_8%2F11%2F17%2F21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

### Front-end & Desktop
![Angular](https://img.shields.io/badge/Angular_12+-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=flat-square&logo=reactivex&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

### Banco de Dados
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_DB-F80000?style=flat-square&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

### DevOps & Ferramentas
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

---

## 🌟 Projetos

### 💰 finApp — Gestão Financeira Desktop

> Aplicativo desktop completo de gestão financeira pessoal, combinando Angular + Electron no front com Java Spring Boot no back. Projeto full stack autoral, com CI/CD e banco embarcado.

<table>
  <tr>
    <td align="center" width="50%">
      <strong>🖥️ <a href="https://github.com/victorleite06/finApp-desktop">finApp-desktop</a></strong><br/><br/>
      Interface desktop construída com Angular + Electron.<br/>Compila para app nativo multiplataforma.<br/><br/>
      <img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white"/>
      <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
    </td>
    <td align="center" width="50%">
      <strong>⚙️ <a href="https://github.com/victorleite06/api-finApp">api-finApp</a></strong><br/><br/>
      API REST em Java + Spring Boot com SQLite embutido.<br/>Pipeline CI/CD configurado via GitHub Actions.<br/><br/>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
      <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white"/>
    </td>
  </tr>
</table>

- 🖥️ App desktop nativo empacotado com `electron-builder` — roda sem servidor externo
- 🔗 Angular consome a API REST Spring Boot localmente via HTTP
- 💾 SQLite embutido — zero dependência de banco de dados externo
- ⚙️ CI/CD com GitHub Actions no back-end

---

### 🔗 Ecossistema de Microsserviços: mini-crm + mini-sign

> Dois microsserviços Spring Boot que se comunicam via **OpenFeign**, cobrindo o fluxo completo de proposta comercial → geração de contrato em PDF → assinatura digital. Cada serviço tem responsabilidade única, banco próprio e documentação via Swagger.

```
┌─────────────────────────────┐        OpenFeign        ┌──────────────────────────────┐
│         mini-crm            │ ──────────────────────► │         mini-sign            │
│  Gestão de Propostas        │                          │  Geração e Assinatura de     │
│  Comerciais · :8080         │ ◄────────────────────── │  Contratos em PDF · :8081    │
└─────────────────────────────┘      callback status     └──────────────────────────────┘
         │                                                          │
    MySQL · Swagger UI                                     MySQL · Swagger UI
```

#### 📋 [mini-crm](https://github.com/victorleite06/mini-crm) — CRM de Propostas Comerciais

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![OpenFeign](https://img.shields.io/badge/OpenFeign-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

Gerencia o ciclo de vida completo de propostas: criação, consulta de status, envio para assinatura e recebimento de callback do mini-sign.

| Método | Rota | Descrição |
|--------|------|-----------|
| `POST` | `/api/proposta/salvar` | Cria nova proposta com cliente e itens |
| `GET` | `/api/proposta/consultar-status/{id}` | Retorna status (`RASCUNHO`, `ASSINADO`) |
| `GET` | `/api/proposta/enviar-proposta/{id}` | Aciona geração do contrato PDF no mini-sign |
| `GET` | `/api/proposta/buscar-proposta/{id}` | Retorna todos os detalhes da proposta |
| `GET` | `/api/proposta/marcar-assinada/{uuid}` | Callback: atualiza proposta para assinada |

#### ✍️ [mini-sign](https://github.com/victorleite06/mini-sign) — Microserviço de Contratos

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![OpenFeign](https://img.shields.io/badge/OpenFeign-6DB33F?style=flat-square&logo=spring&logoColor=white)
![PDF](https://img.shields.io/badge/PDF_Generation-EC1C24?style=flat-square&logo=adobeacrobatreader&logoColor=white)

Gera contratos em PDF, gerencia o status de assinatura e notifica o mini-crm após a confirmação.

| Método | Rota | Descrição |
|--------|------|-----------|
| `POST` | `/api/contrato/enviar-assinatura` | Recebe proposta e gera PDF do contrato |
| `GET` | `/api/contrato/assinar-contrato/{id}` | Simula assinatura e notifica o CRM |
| `GET` | `/api/contrato/consultar-status/{id}` | Retorna status (`AGUARDANDO_ASSINATURA`, `ASSINADO`) |

---

### 🧵 [simulador-multithreading](https://github.com/victorleite06/simulador-multithreading) ⭐

> Simulador de arquiteturas de concorrência em Java puro — threads, sincronização e processamento paralelo. Conceitos que aplico diretamente em produção com Apache Kafka.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
`Threads` `Concorrência` `Arquiteturas`


---

## 🏢 Trajetória profissional

```
Grupo SFA · Belo Horizonte, MG
─────────────────────────────────────────────────────────
Fev 2022 → Ago 2022   Jovem Aprendiz – Assistente Administrativo
Set 2022 → Mar 2025   Estagiário – Desenvolvedor Full Stack
Abr 2025 → Atual      Desenvolvedor Full Stack Pleno
─────────────────────────────────────────────────────────
```

> Do zero ao Pleno dentro da mesma empresa — 3 anos de crescimento contínuo com impacto real em produção.

---

## 🎓 Formação

- **Ciência da Computação** — UNA EaD *(7º período · Conclusão: jul/2027)*
- **Ciência da Computação** — PUC Minas *(1º ao 6º período cursados)*

---

## 🌐 Idiomas

- 🇧🇷 Português — Nativo
- 🇺🇸 Inglês — Intermediário *(leitura técnica de documentações e APIs)*

---

<div align="center">

*"Trajetória que começa do zero e cresce de forma consistente é a mais sólida que existe."*

</div>
