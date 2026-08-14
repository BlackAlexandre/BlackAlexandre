<!--
╔══════════════════════════════════════════════════════════════════════╗
║  BLACKALEXANDRE // GITHUB PROFILE README                            ║
║  Cyber interface personalizada para Alexandre Rocha.                ║
║  Dados públicos confirmados; contatos privados foram omitidos.      ║
╚══════════════════════════════════════════════════════════════════════╝

SNAKE ANIMATION
Crie o arquivo .github/workflows/snake.yml no repositório do perfil:

name: Generate contribution snake

on:
  schedule:
    - cron: "0 3 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10
    steps:
      - name: Generate SVGs
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg?color_snake=%230E7490&color_dots=%23EBEDF0,%2367E8F9,%2322D3EE,%238B5CF6,%236D28D9
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark&color_snake=%2322D3EE&color_dots=%23020617,%230E7490,%2322D3EE,%238B5CF6,%23C4B5FD

      - name: Publish SVGs to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          build_dir: dist
          target_branch: output
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
-->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:020617,50:0E7490,100:6D28D9&text=BLACKALEXANDRE&fontColor=E0F2FE&fontSize=46&fontAlignY=38&desc=ALEXANDRE%20ROCHA%20%E2%80%A2%20SYSTEMS%20%7C%20SUPPORT%20%7C%20CYBERSECURITY&descAlignY=59&descSize=15&animation=fadeIn" alt="Banner BlackAlexandre" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=2200&pause=650&color=22D3EE&center=true&vCenter=true&repeat=true&width=780&height=45&lines=%5BBOOT%5D+Inicializando+perfil...;%5BOK%5D+Carregando+Python%2C+C%2C+SQL+e+Web...;%5BOK%5D+Conectando+Sistemas%2C+Suporte+e+Cybersecurity...;%5BONLINE%5D+Aprendendo%2C+construindo+e+evoluindo." alt="Animação de inicialização do sistema" />

<br>

<img src="https://img.shields.io/badge/SYSTEM-ONLINE-22D3EE?style=for-the-badge&labelColor=020617" alt="System online" />
<img src="https://img.shields.io/badge/STATUS-LEARNING_IN_PUBLIC-A855F7?style=for-the-badge&labelColor=020617" alt="Learning in public" />
<img src="https://img.shields.io/badge/LOCATION-CURITIBA_%E2%80%A2_PR-10B981?style=for-the-badge&labelColor=020617" alt="Curitiba, Paraná" />

<br><br>

<samp>
  <a href="#sobre-mim">SOBRE</a> &nbsp;•&nbsp;
  <a href="#tech-stack">STACK</a> &nbsp;•&nbsp;
  <a href="#projetos-em-destaque">PROJETOS</a> &nbsp;•&nbsp;
  <a href="#telemetria-do-github">STATUS</a> &nbsp;•&nbsp;
  <a href="#conecte-se-comigo">CONTATO</a>
</samp>

</div>

<br>

## SOBRE MIM

```text
IDENTIDADE   : Alexandre Zampronne Zaccaron Rocha
FORMAÇÃO     : Sistemas de Informação — FESP
BASE TÉCNICA : Técnico em Análise e Desenvolvimento de Sistemas
PERFIL       : Sistemas • Suporte Técnico • Desenvolvimento em formação
LOCALIZAÇÃO  : Curitiba, Paraná, Brasil
FOCO         : Python • C • SQL • Web • Cibersegurança
PROTOCOLO    : Aprender → Construir → Documentar → Evoluir
```

Sou estudante de **Sistemas de Informação na FESP**, bolsista integral pelo ProUni, e técnico em **Análise e Desenvolvimento de Sistemas**. Gosto de entender o que acontece por trás da tecnologia — da lógica de programação e dos dados ao suporte de usuários e à segurança da informação.

Atualmente desenvolvo o **MWE Harmonize**, pratico **Python, C, SQL e desenvolvimento web**, exploro **Linux/Ubuntu** e construo uma base sólida em **cibersegurança**. Minha experiência com atendimento, organização de informações, planilhas e sistemas internos fortaleceu competências como comunicação, atenção aos detalhes e resolução de problemas.

> **Diretriz do sistema:** código limpo, aprendizado constante e soluções com propósito.

<br>

## TECH STACK

<div align="center">

### Linguagens & Web

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=c,python,html,css,js&theme=dark" alt="C, Python, HTML, CSS e JavaScript" />
</a>

<br><br>

<img src="https://img.shields.io/badge/C-FUNDAMENTOS-22D3EE?style=for-the-badge&logo=c&logoColor=white&labelColor=020617" alt="C" />
<img src="https://img.shields.io/badge/PYTHON-EM_EVOLU%C3%87%C3%83O-8B5CF6?style=for-the-badge&logo=python&logoColor=white&labelColor=020617" alt="Python" />
<img src="https://img.shields.io/badge/SQL-FUNDAMENTOS-0284C7?style=for-the-badge&logo=databricks&logoColor=white&labelColor=020617" alt="SQL" />
<img src="https://img.shields.io/badge/WEB-BUILDING-A855F7?style=for-the-badge&logo=html5&logoColor=white&labelColor=020617" alt="Web Development" />
<img src="https://img.shields.io/badge/CYBERSECURITY-EXPLORING-10B981?style=for-the-badge&logo=hackthebox&logoColor=white&labelColor=020617" alt="Cybersecurity" />

</div>

<br>

## FERRAMENTAS E AMBIENTES

<div align="center">

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=git,github,vscode,figma,linux,ubuntu,windows,bash&theme=dark" alt="Git, GitHub, VS Code, Figma, Linux, Ubuntu, Windows e Bash" />
</a>

<br><br>

<img src="https://img.shields.io/badge/EDITOR-VS_CODE-22D3EE?style=flat-square&logo=visualstudiocode&logoColor=white&labelColor=020617" alt="VS Code" />
<img src="https://img.shields.io/badge/VERSIONAMENTO-GIT-A855F7?style=flat-square&logo=git&logoColor=white&labelColor=020617" alt="Git" />
<img src="https://img.shields.io/badge/PROT%C3%93TIPOS-FIGMA-8B5CF6?style=flat-square&logo=figma&logoColor=white&labelColor=020617" alt="Figma" />
<img src="https://img.shields.io/badge/DADOS-POWER_BI-F2C811?style=flat-square&logo=powerbi&logoColor=020617&labelColor=020617" alt="Power BI" />
<img src="https://img.shields.io/badge/AUTOMA%C3%87%C3%83O-N8N-F97316?style=flat-square&logo=n8n&logoColor=white&labelColor=020617" alt="n8n" />
<img src="https://img.shields.io/badge/DADOS-BASEROW-10B981?style=flat-square&logo=baserow&logoColor=white&labelColor=020617" alt="Baserow" />
<img src="https://img.shields.io/badge/PLANILHAS-EXCEL-217346?style=flat-square&logo=microsoftexcel&logoColor=white&labelColor=020617" alt="Microsoft Excel" />
<img src="https://img.shields.io/badge/COMPILADOR-GCC-10B981?style=flat-square&logo=gnu&logoColor=white&labelColor=020617" alt="GCC" />
<img src="https://img.shields.io/badge/AMBIENTE-WINDOWS_11-0284C7?style=flat-square&logo=windows11&logoColor=white&labelColor=020617" alt="Windows 11" />
<img src="https://img.shields.io/badge/AMBIENTE-UBUNTU-F97316?style=flat-square&logo=ubuntu&logoColor=white&labelColor=020617" alt="Ubuntu" />

</div>

<br>

## PROJETOS EM DESTAQUE

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🐍 Sistema de Gestão de Eventos</h3>
      <div align="center">
        <img src="https://img.shields.io/badge/STATUS-PROJETO_ACAD%C3%8AMICO-8B5CF6?style=flat-square&labelColor=020617" alt="Projeto acadêmico" />
      </div>
      <br>
      <p>Sistema em Python para organizar contratantes, eventos e itens de custo, com cadastro, edição, remoção, persistência, relatórios, validações e testes.</p>
      <p><code>Python</code> <code>Listas</code> <code>Tuplas</code> <code>Persistência</code> <code>Testes</code></p>
      <p align="center">
        <a href="https://github.com/BlackAlexandre?tab=repositories">
          <img src="https://img.shields.io/badge/VER_REPOSIT%C3%93RIOS-020617?style=for-the-badge&logo=github&logoColor=A855F7" alt="Ver repositórios" />
        </a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🎼 MWE Harmonize</h3>
      <div align="center">
        <img src="https://img.shields.io/badge/STATUS-EM_DESENVOLVIMENTO-22D3EE?style=flat-square&labelColor=020617" alt="Em desenvolvimento" />
      </div>
      <br>
      <p>Plataforma web para centralizar agenda, clientes, propostas, repertório, equipe e financeiro de eventos musicais.</p>
      <p><code>HTML</code> <code>CSS</code> <code>JavaScript</code> <code>Figma</code></p>
      <p align="center">
        <a href="https://github.com/BlackAlexandre?tab=repositories">
          <img src="https://img.shields.io/badge/VER_REPOSIT%C3%93RIOS-020617?style=for-the-badge&logo=github&logoColor=22D3EE" alt="Ver repositórios" />
        </a>
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3 align="center">🛡️ Conscientização em Cybersecurity</h3>
      <div align="center">
        <img src="https://img.shields.io/badge/STATUS-PROJETO_EDUCACIONAL-10B981?style=flat-square&labelColor=020617" alt="Projeto educacional" />
      </div>
      <br>
      <p align="center">Projeto em equipe apresentado na Feira Cultural CIEE, com roteiro, materiais visuais e dinâmicas sobre segurança digital, atualizações de sistemas, comportamento seguro e fundamentos de engenharia social.</p>
      <p align="center"><code>Security Awareness</code> <code>Engenharia Social</code> <code>Comunicação</code> <code>Apresentação Técnica</code></p>
      <p align="center">
        <a href="https://github.com/BlackAlexandre?tab=repositories">
          <img src="https://img.shields.io/badge/VER_REPOSIT%C3%93RIOS-020617?style=for-the-badge&logo=github&logoColor=10B981" alt="Ver repositórios" />
        </a>
      </p>
    </td>
  </tr>
</table>

<br>

## OBJETIVOS ATUAIS

```console
blackalexandre@neural-core:~$ ./mission_control --status

[ ACTIVE ] Consolidar Python, C, SQL e fundamentos de desenvolvimento web
[ ACTIVE ] Evoluir o MWE Harmonize do protótipo para uma aplicação funcional
[ ACTIVE ] Publicar projetos com documentação clara e histórico no GitHub
[ ACTIVE ] Tornar Linux/Ubuntu parte natural do fluxo de desenvolvimento
[ TARGET ] Estágio ou posição júnior em TI, Sistemas, Suporte ou Cybersecurity
[ NEXT   ] Aprofundar redes, bancos de dados e segurança da informação

SYSTEM_MESSAGE: evolução consistente supera pressa.
blackalexandre@neural-core:~$ _
```

<br>

## TELEMETRIA DO GITHUB

<div align="center">

<img width="49%" src="https://github-stats-extended.vercel.app/api?username=BlackAlexandre&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=020617&title_color=22D3EE&text_color=C4B5FD&icon_color=A855F7&ring_color=22D3EE&locale=pt-br" alt="Estatísticas do GitHub" />
<img width="49%" src="https://github-stats-extended.vercel.app/api/top-langs/?username=BlackAlexandre&layout=compact&langs_count=8&hide_border=true&bg_color=020617&title_color=22D3EE&text_color=C4B5FD&icon_color=A855F7&locale=pt-br" alt="Linguagens mais utilizadas" />

<br><br>

<img width="70%" src="./streak.svg" alt="Sequência de contribuições" />

<br><br>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=BlackAlexandre&bg_color=020617&color=C4B5FD&line=22D3EE&point=A855F7&area=true&area_color=0E7490&hide_border=true&custom_title=ATIVIDADE%20DOS%20%C3%9ALTIMOS%2031%20DIAS" alt="Gráfico de atividade do GitHub" />

</div>

<br>

## GITHUB TROPHIES

<div align="center">

<img width="100%" src="./trophy.svg" alt="Troféus do GitHub" />
</div>

<br>

## CONTRIBUTION PROTOCOL

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/BlackAlexandre/BlackAlexandre/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/BlackAlexandre/BlackAlexandre/output/github-contribution-grid-snake.svg">
  <img width="100%" alt="Animação da cobrinha de contribuições" src="https://raw.githubusercontent.com/BlackAlexandre/BlackAlexandre/output/github-contribution-grid-snake.svg">
</picture>

</div>

<br>

## CONECTE-SE COMIGO

<div align="center">

<a href="https://github.com/BlackAlexandre">
  <img src="https://img.shields.io/badge/GITHUB-020617?style=for-the-badge&logo=github&logoColor=22D3EE" alt="GitHub" />
</a>
<a href="https://www.linkedin.com/in/alexandrezzrocha">
  <img src="https://img.shields.io/badge/LINKEDIN-020617?style=for-the-badge&logo=linkedin&logoColor=22D3EE" alt="LinkedIn" />
</a>
<a href="mailto:alexandrezzrocha20@gmail.com">
  <img src="https://img.shields.io/badge/EMAIL-020617?style=for-the-badge&logo=gmail&logoColor=A855F7" alt="E-mail" />
</a>
<a href="https://github.com/BlackAlexandre?tab=repositories">
  <img src="https://img.shields.io/badge/PROJETOS-020617?style=for-the-badge&logo=rocket&logoColor=10B981" alt="Projetos" />
</a>

<br><br>

<samp>
  &gt; Conexões abertas para aprendizado, colaboração e projetos que gerem impacto.
</samp>

</div>

<br>

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=140&section=footer&color=0:6D28D9,50:0E7490,100:020617&text=END%20OF%20TRANSMISSION&fontColor=E0F2FE&fontSize=18&fontAlignY=72&animation=fadeIn" alt="Fim da transmissão" />

<samp>CODE • LEARN • BUILD • EVOLVE</samp>

</div>

<!--
Componentes compatíveis com GitHub:
Markdown + HTML • Shields.io • GitHub Stats Extended • Readme Typing SVG
Activity Graph • GitHub Profile Trophy • Platane/snk • Skill Icons • Capsule Render
-->
