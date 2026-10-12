<div align="center">

# 🏛️ Bruno Lima — Portfólio Executivo

### Desenvolvedor Full Stack & Especialista em Soluções Corporativas
**Magiccomp** • Osasco, São Paulo, Brasil

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Bruno%20Lima-0077b5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bruno-lima-20b099325/)
[![GitHub](https://img.shields.io/badge/GitHub-Bruno--LimaHG-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Bruno-LimaHG)
[![Email](https://img.shields.io/badge/Email-brudeflima%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:brudeflima@gmail.com)
[![Status](https://img.shields.io/badge/Status-Disponível%20para%20Projetos-10b981?style=for-the-badge)](#contato)

<br/>

<img src="https://capsules-render.vercel.app/api?type=waving&color=0f172a&height=180&section=header&text=Bruno%20Lima&fontSize=42&fontAlignY=38&desc=Full%20Stack%20Engineer%20%7C%20Cloud%20%26%20Cybersecurity&descAlignY=58&descAlign=50&theme=dark" alt="Header Bruno Lima" width="100%" />

</div>

---

## 💼 Sobre Mim

Desenvolvedor de software focado na construção de sistemas web robustos, escaláveis e de alta confiabilidade corporativa. Atualmente desenvolvendo soluções na **Magiccomp**, com ênfase em arquiteturas modernas full stack (**Node.js, Express, MongoDB, Vue.js**), processamento assíncrono em segundo plano (**BullMQ & Redis**), armazenamento seguro em nuvem (**AWS S3**) e estrita conformidade com a **LGPD (Lei Geral de Proteção de Dados)**.

Certificado oficialmente em segurança cibernética pela **Fortinet (NSE 1 & NSE 2)** e em governança e continuidade de dados pela **N-able (Cove Data Protection Advanced - Class of 2026)**.

---

## ⭐ Projeto Destaque: SIGACRC

> **Sistema Integrado de Gestão de Atendimento de Cartório de Registro Civil**  
> 🔗 **Repositório Oficial:** [github.com/Bruno-LimaHG/SIGACRC](https://github.com/Bruno-LimaHG/SIGACRC)

<div align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/AWS%20S3-FF9900?style=flat-square&logo=amazons3&logoColor=white" alt="AWS S3" />
  <img src="https://img.shields.io/badge/Redis%20%26%20BullMQ-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.io" />
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT" />
  <img src="https://img.shields.io/badge/Jest%20%26%20Supertest-C21325?style=flat-square&logo=jest&logoColor=white" alt="Jest" />
  <img src="https://img.shields.io/badge/LGPD%20Compliance-0284c7?style=flat-square&logo=shield&logoColor=white" alt="LGPD" />
</div>

<br/>

### 🎯 O Desafio de Negócio
O processo tradicional de habilitação e celebração de casamento civil em cartórios de registro civil frequentemente envolve filas presenciais exaustivas, risco de extravio de certidões físicas e tempo elevado de resposta. O **SIGACRC** transforma essa dinâmica através de uma plataforma digital unificada e segura.

### 🛡️ Destaques de Arquitetura & Segurança
* 🔒 **Autenticação Stateless JWT**: Autenticação resiliente através do cabeçalho `Authorization: Bearer <token>`, eliminando fallbacks legados e reforçando a integridade da sessão.
* ☁️ **Segurança de Documentos via AWS S3 Pre-Signed URLs**: Anexos civis e certidões são protegidos em bucket privado na AWS S3. O backend emite URLs temporárias pré-assinadas sob demanda, impedindo qualquer acesso não autorizado aos dados pessoais dos noivos.
* ⚡ **Processamento Assíncrono com BullMQ & Redis**: Filas dedicadas em segundo plano para envio de notificações por e-mail e manipulação de anexos, garantindo tempo de resposta quase instantâneo na API principal.
* 💬 **Comunicação em Tempo Real (WebSocket / Socket.io)**: Atendimento direto e interativo entre escreventes e requerentes dentro da própria plataforma.
* 🚦 **Defesa Contra Ameaças**: Limitação de taxa de requisições (`express-rate-limit`) para mitigação de força bruta/DDoS e cabeçalhos de segurança via `Helmet`.
* 📊 **Logging Estruturado Forense**: Integração de **Winston** e **Morgan** para rastreabilidade de requisições, diagnósticos de erros e auditoria de ações.
* ⚖️ **Governança & LGPD**: Arquitetura construída sob os preceitos de privacidade por padrão (Privacy by Design) e documentação de política de proteção de dados.
* 🧪 **Confiabilidade Contínua**: Cobertura de testes automatizados com **Jest** e **Supertest**, além de scripts autônomos de backup MongoDB (`npm run backup`).

---

## 🏆 Certificações Oficiais

| Emissor | Certificação | Foco & Domínio |
| :--- | :--- | :--- |
| **Fortinet** | **NSE 1 — Certified in Cybersecurity** | Conscientização de ameaças, segurança da informação e vetores cibernéticos |
| **Fortinet** | **NSE 2 — Certified in Cybersecurity** | Evolução da cibersegurança, ZTNA, SASE e arquitetura defensiva moderna |
| **N-able Academy** | **Cove Data Protection — Advanced Certification** | Continuidade de negócios, backup em nuvem, retenção imutável e DRaaS (2026) |
| **Pearson** | **Pearson English Certificate of Achievement** | Avaliação Global Scale of English (GSE 33–52 / CEFR A2-B1+) |

---

## 🛠️ Stack Tecnológica & Competências

```
├── Backend & APIs      : Node.js, Express.js, REST APIs, WebSocket (Socket.io), Winston, Morgan
├── Cloud & Mensageria  : AWS S3 (Pre-Signed URLs), BullMQ, Redis Queue, Background Workers
├── Bancos de Dados     : MongoDB, Mongoose ODM, Redis Cache, Scripts Automatizados de Backup
├── Segurança & LGPD    : Fortinet NSE 1 & 2, JWT Stateless, Helmet, Rate Limiting, LGPD Compliance
├── Frontend Web        : JavaScript (ES6+), Vue.js, HTML5 Semântico, CSS3 Moderno, Flexbox/Grid
└── Qualidade & Dados   : Jest, Supertest, Git/GitHub, CI/CD, Power BI, Dashboards Executivos
```

---

## 📂 Outros Repositórios em Destaque

* 📊 **[MONITORAMENTO-ESCOLAR](https://github.com/Bruno-LimaHG/MONITORAMENTO-ESCOLAR)** — Sistema web de acompanhamento e monitoramento de métricas educacionais.
* 🔄 **[LISTA-TAREFA-REDUX](https://github.com/Bruno-LimaHG/LISTA-TAREFA-REDUX)** — Implementação de fluxo de gerenciamento de estado global com Redux e dados reativos.
* ♿ **[PRODUTO-ACESSIVEL](https://github.com/Bruno-LimaHG/PRODUTO-ACESSIVEL)** — Aplicação desenvolvida com foco estrito em acessibilidade digital (WCAG/a11y).
* ⛅ **[CLIMA-TEMPERATURA](https://github.com/Bruno-LimaHG/CLIMA-TEMPERATURA)** — Aplicação de consulta meteorológica em tempo real via consumo de API REST.
* 🚀 **[TESTES-CI-CD](https://github.com/Bruno-LimaHG/TESTES-CI-CD)** — Laboratório de testes e pipelines automatizados de Integração e Entrega Contínua.

---

## 🌐 Publicação do Portfólio Web (GitHub Pages)

Este repositório acompanha a versão web interativa completa em **`index.html`**, pronta para publicação gratuita via GitHub Pages:

1. Suba este repositório para o seu GitHub (por exemplo, com o nome `portfolio` ou `Bruno-LimaHG.github.io`).
2. No seu repositório no GitHub, acesse:  
   **Settings** ➔ **Pages** (no menu lateral esquerdo).
3. Na seção **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: selecione `main` e a pasta `/ (root)`.
4. Clique em **Save**. Em instantes seu portfólio executivo estará no ar no link:
   ```
   https://bruno-limahg.github.io/portfolio/
   ```

---

## 📬 Contato Executivo

<div align="center">

<a href="https://www.linkedin.com/in/bruno-lima-20b099325/">
  <img src="https://img.shields.io/badge/LinkedIn-Conectar%20com%20Bruno%20Lima-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<br/><br/>

✉️ **E-mail Corporativo:** [brudeflima@gmail.com](mailto:brudeflima@gmail.com)  
🐙 **GitHub:** [github.com/Bruno-LimaHG](https://github.com/Bruno-LimaHG)  
📍 **Localização:** Osasco / São Paulo — Brasil

</div>

---

<div align="center">
  <sub>© 2026 Bruno Lima. Desenvolvido com padrão executivo de excelência e segurança.</sub>
</div>
