<div align="center">

<img src="assets/hero-window.svg" width="100%" alt="Gustavo Izidoro, desenvolvedor de software em formação"/>

<br>

![Status](https://img.shields.io/badge/status-aberto_a_est%C3%A1gio_e_j%C3%BAnior-43E97B?style=flat-square&labelColor=3F7DC4)
![Local](https://img.shields.io/badge/Uberl%C3%A2ndia_MG-presencial_ou_remoto-4FACFE?style=flat-square&labelColor=3F7DC4)
![Formação](https://img.shields.io/badge/ADS-4%C2%BA_per%C3%ADodo-00C9FF?style=flat-square&labelColor=3F7DC4)

</div>

<br>

<!-- ===================== SOBRE MIM ===================== -->
<img src="assets/titlebar-sobre.svg" width="100%" alt="Sobre mim"/>

<br>

Estudante de **Análise e Desenvolvimento de Sistemas** na UniPac Uberlândia (4º período, conclusão prevista para julho de 2027), em busca da primeira experiência profissional em desenvolvimento de software.

Trabalho **definindo escopo e especificações antes de implementar** e uso IA (Claude e GitHub Copilot) como ferramenta de implementação, com revisão e testes feitos por mim. Tenho base em Python/Django, React e Git/GitHub, e estou desenvolvendo um app para um **cliente real**, do levantamento de requisitos ao APK.

| | |
|:--|:--|
| 🎓 **Formação** | Análise e Desenvolvimento de Sistemas, curso noturno |
| 🎯 **Foco** | Back-end com Python/Django, front-end com React e apps mobile |
| 🧭 **Metodologia** | Spec-Driven Development: spec primeiro, código depois |
| 🔎 **Procuro** | Estágio ou vaga júnior em desenvolvimento (presencial em Uberlândia ou remoto) |

<br>

<img src="assets/bottom-edge.svg" width="100%" alt=""/>

<br>

<!-- ===================== PROJETOS ===================== -->
<img src="assets/titlebar-projetos.svg" width="100%" alt="Projetos em destaque"/>

<br>

<!-- ---------- STUDIO GE ---------- -->
<img src="assets/titlebar-studio-ge.svg" width="100%" alt="Studio-GE: app Android para cliente real"/>

<p align="center">
  <img src="https://raw.githubusercontent.com/Gustavo-izidoro2006/Studio-GE/main/docs/screenshots/banner.png" width="100%" alt="Studio GE: alunos, treinos e financeiro em um só lugar"/>
</p>

### Studio GE

App Android de gestão para o **Studio Geração Energia**, feito para o dono e instrutor do studio. Nasceu no Projeto de Extensão do curso e, depois de uma **entrevista com o cliente**, deixou de ser um app para o aluno e virou uma ferramenta de trabalho do instrutor: alunos, avaliações físicas, evolução, treinos e financeiro em um só lugar.

<table>
  <tr>
    <td align="center" width="25%"><img src="https://raw.githubusercontent.com/Gustavo-izidoro2006/Studio-GE/main/docs/screenshots/alunos.png" alt="Lista de alunos" width="200"><br><sub><b>Alunos</b></sub></td>
    <td align="center" width="25%"><img src="https://raw.githubusercontent.com/Gustavo-izidoro2006/Studio-GE/main/docs/screenshots/aluno-evolucao.png" alt="Gráfico de evolução do aluno" width="200"><br><sub><b>Evolução</b></sub></td>
    <td align="center" width="25%"><img src="https://raw.githubusercontent.com/Gustavo-izidoro2006/Studio-GE/main/docs/screenshots/treino-detalhe.png" alt="Detalhe do treino" width="200"><br><sub><b>Treino</b></sub></td>
    <td align="center" width="25%"><img src="https://raw.githubusercontent.com/Gustavo-izidoro2006/Studio-GE/main/docs/screenshots/financeiro.png" alt="Resumo financeiro" width="200"><br><sub><b>Financeiro</b></sub></td>
  </tr>
</table>

> As telas usam dados fictícios gerados por um comando de seed; nenhum dado real de aluno está no repositório.

**O que o app faz**

- 📏 **Avaliações e evolução:** 12 métricas por avaliação, IMC calculado automaticamente, gráfico por métrica e tabela comparativa entre avaliações
- 🏋️ **Treinos:** catálogo de exercícios por grupo muscular, séries, repetições, carga e adaptações por aluno
- 💰 **Financeiro:** mensalidades geradas por mês, pagamento em um toque, despesas, saldo, inadimplência e gráfico de 6 meses
- 🗂️ **Perfis de trabalho:** Academia, Personal e Pessoal, cada um com seus próprios dados

**Engenharia por trás**

- API REST em **Django REST Framework** com regras de negócio no back-end (IMC, status de pagamento e saldo são calculados, nunca digitados) e testes automatizados
- App em **React Native + Expo (TypeScript)**, distribuído como **APK** via EAS Build, com o back-end publicado na nuvem
- **22 specs** em `specs/` guiando cada funcionalidade e um `CLAUDE.md` com as convenções do projeto (por exemplo, dinheiro sempre em `DecimalField`)
- Pensado para quem não é da área de tecnologia: poucos passos por tela, áreas de toque de 44px e nenhum estado indicado só por cor

![Python](https://img.shields.io/badge/Python-3F7DC4?style=flat-square&logo=python&logoColor=white)
![Django REST](https://img.shields.io/badge/Django_REST-092E20?style=flat-square&logo=django&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-00C9FF?style=flat-square&logo=react&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3F7DC4?style=flat-square&logo=typescript&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-2CC6B8?style=flat-square&logo=sqlite&logoColor=white)

[![Ver repositório](https://img.shields.io/badge/Ver_reposit%C3%B3rio-Studio--GE-3F7DC4?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Gustavo-izidoro2006/Studio-GE)

<br>

<!-- ---------- TAREFAS EXPRESS ---------- -->
<img src="assets/titlebar-tarefas.svg" width="100%" alt="TarefasExpress: gestão colaborativa de tarefas"/>

### TarefasExpress

Aplicação para **organizar tarefas em grupos** (casa, trabalho, escola), com convite de membros, responsáveis, prioridade, prazo e comunicação dentro do próprio grupo. É a base do meu TCC.

- 👥 **Grupos e convites:** cada grupo tem seus membros, cargos e tarefas
- ✅ **Tarefas completas:** prioridade, prazo, responsáveis, categorias, comentários e anexos
- 💬 **Comunicação:** chat do grupo e notificações
- 📊 **Relatórios:** visão do andamento das tarefas

```mermaid
flowchart LR
    A["🖥️ Front-end<br/>React 18 · React Router · Axios"] -- "HTTP + JSON" --> B["⚙️ API REST<br/>ASP.NET Core · Controllers e Services"]
    B -- "Entity Framework Core" --> C[("🗄️ MySQL 8")]
    D["🐳 Docker Compose"] -. "sobe API + banco" .-> B
    D -.-> C
```

![React](https://img.shields.io/badge/React-00C9FF?style=flat-square&logo=react&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-4FACFE?style=flat-square&logo=javascript&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-3F7DC4?style=flat-square&logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity_Framework_Core-3F7DC4?style=flat-square&logo=dotnet&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-2CC6B8?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CC6B8?style=flat-square&logo=docker&logoColor=white)

[![Ver repositório](https://img.shields.io/badge/Ver_reposit%C3%B3rio-TarefasExpress-3F7DC4?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Gustavo-izidoro2006/TarefasExpress)

<br>

<img src="assets/bottom-edge.svg" width="100%" alt=""/>

<br>

<!-- ===================== STACK E FERRAMENTAS ===================== -->
<img src="assets/titlebar-stack.svg" width="100%" alt="Stack e ferramentas"/>

<br>

| | |
|:--|:--|
| **Uso no dia a dia** | ![Python](https://img.shields.io/badge/Python-3F7DC4?style=flat-square&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-4FACFE?style=flat-square&logo=javascript&logoColor=white) ![React](https://img.shields.io/badge/React-00C9FF?style=flat-square&logo=react&logoColor=white) ![HTML](https://img.shields.io/badge/HTML-2CC6B8?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-2CC6B8?style=flat-square&logo=css3&logoColor=white) ![Git](https://img.shields.io/badge/Git-43E97B?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-43E97B?style=flat-square&logo=github&logoColor=white) |
| **Já usei em projetos** | ![TypeScript](https://img.shields.io/badge/TypeScript-3F7DC4?style=flat-square&logo=typescript&logoColor=white) ![React Native](https://img.shields.io/badge/React_Native-00C9FF?style=flat-square&logo=react&logoColor=white) ![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white) ![Django REST](https://img.shields.io/badge/Django_REST-092E20?style=flat-square&logo=django&logoColor=white) ![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-3F7DC4?style=flat-square&logo=dotnet&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-2CC6B8?style=flat-square&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-2CC6B8?style=flat-square&logo=sqlite&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2CC6B8?style=flat-square&logo=docker&logoColor=white) |
| **IA e fluxo de trabalho** | ![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white) ![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-24292F?style=flat-square&logo=githubcopilot&logoColor=white) ![SDD](https://img.shields.io/badge/Spec--Driven_Development-3F7DC4?style=flat-square) ![VS Code](https://img.shields.io/badge/VS_Code-3F7DC4?style=flat-square) |

<sub>Também estudo Java Web (Servlet, JSP, JDBC) e SQL na faculdade.</sub>

<br>

<!-- ===================== COMO EU TRABALHO ===================== -->
<img src="assets/titlebar-fluxo.svg" width="100%" alt="Como eu trabalho"/>

<br>

Uso **Spec-Driven Development (SDD)**: primeiro eu decido *o quê* o software precisa fazer, depois a IA ajuda no *como*. Aprendo e pratico o método com [BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD), [spec-kit](https://github.com/github/spec-kit) e [tech-leads-club/agent-skills](https://github.com/tech-leads-club/agent-skills).

```mermaid
flowchart LR
    A["🗣️ Entrevista<br/>e escopo"] --> B["📝 Spec<br/>o QUÊ + critérios<br/>de aceite"]
    B --> C["🤖 Implementação<br/>com Claude e Copilot<br/>em camadas"]
    C --> D["🔍 Revisão<br/>e testes"]
    D --> E["📦 APK<br/>e deploy"]
    D -. "ajusta a spec" .-> B
```

- **Spec antes do código:** nenhuma funcionalidade começa sem uma spec com critérios de aceite
- **Contexto para a IA:** cada projeto tem um `CLAUDE.md` com convenções e regras, para a IA seguir o mesmo padrão sempre
- **Mudanças pequenas:** uma funcionalidade por vez, em camadas (model, migration, API, tela)
- **A revisão é minha:** leio o que a IA gerou, rodo os testes e valido com o uso real

<br>

<img src="assets/bottom-edge.svg" width="100%" alt=""/>

<br>

<!-- ===================== CONTATO ===================== -->
<img src="assets/titlebar-contato.svg" width="100%" alt="Contato"/>

<br>

<div align="center">

Estou buscando **estágio ou vaga júnior** em desenvolvimento de software. Fique à vontade para olhar os projetos acima e entrar em contato.

<br>

[![GitHub](https://img.shields.io/badge/GitHub-Gustavo--izidoro2006-3F7DC4?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Gustavo-izidoro2006)
<!-- Descomente e preencha para adicionar mais formas de contato:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-seu--perfil-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/SEU-PERFIL/)
[![E-mail](https://img.shields.io/badge/E--mail-seu@email.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:seu@email.com)
-->

<br><br>

<sub>Feito com código e um toque de nostalgia Aero</sub>

</div>
