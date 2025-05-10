<!-- HEADER BADGES -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-j-422b5620b)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/pedroso._.oficial/)
[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=PedrosoY&show_icons=true&theme=transparent)](https://github.com/PedrosoY)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=PedrosoY&layout=compact)](https://github.com/PedrosoY/github-readme-stats)
[![Trophies](https://github-profile-trophy.vercel.app/?username=PedrosoY&theme=flat)](https://github.com/PedrosoY/github-profile-trophy)

---

## 👋 Olá, eu sou o Pedro Paulo

Estudante de Engenharia da Computação apaixonado por desenvolvimento de software, arquitetura de sistemas e automação. Em busca de oportunidades para colaborar em projetos de código aberto e começar minha carreira como desenvolvedor.

---

## 📑 Sumário

- [Sobre Mim](#sobre-mim)  
- [🏷️ Tecnologias](#️-tecnologias)  
- [🚀 Projetos em Destaque](#-projetos-em-destaque)  
- [🤝 Contribuições Open-Source](#-contribuições-open-source)  
- [⚙️ GitHub Actions & Automação](#️-github-actions--automação)  
- [📫 Contato](#️-contato)

---

## 🧑‍💻 Sobre Mim

- 🎓 Cursando Engenharia da Computação  
- 💡 Foco em back-end (Java, Python), simuladores e estruturas de dados  
- 🌱 Aprendendo desenvolvimento front-end e DevOps  
- ⚡ Gosto de desafios algorítmicos e arquitetura limpa

---

## 🏷️ Tecnologias

<div style="display: inline_block">
  <img align="center" alt="html5"     src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img align="center" alt="css3"      src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img align="center" alt="javascript"src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img align="center" alt="php"       src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
  <img align="center" alt="java"      src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" />
  <img align="center" alt="python"    src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white" />
  <img align="center" alt="c++"       src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
</div>

---

## 🚀 Projetos em Destaque

### 📘 MIPS Simulator
**Tecnologias:** Java, JUnit, Maven  
Simulador completo da arquitetura MIPS com leitura de instruções (R, I, J), controle de registradores, memória, contagem de ciclos e logs detalhados.  
🔗 [Repositório](https://github.com/PedrosoY/mips-simulator) · ⭐ 60

### 💼 Portfolio Pessoal
**Tecnologias:** HTML, CSS, JavaScript  
Site responsivo com tema claro/escuro, seções de projetos, blog integrado via RSS e animações CSS.  
🔗 [Repositório](https://github.com/PedrosoY/portfolio) · ⭐ 35 · 🚀 [Página ao Vivo](https://pedrosoy.github.io/portfolio)

### 📊 Gerador de Relatórios SEO
**Tecnologias:** Python, Google Analytics API, Google Search Console API  
Script unificado que coleta métricas de SEO essenciais, gera gráficos e exporta relatórios em PDF.  
🔗 [Repositório](https://github.com/PedrosoY/seo-reports) · ⭐ 25

---

## 🤝 Contribuições Open-Source

- 📦 Issue em [spring-projects/spring-framework](https://github.com/spring-projects/spring-framework) melhorando validações de configuração  
- 🔧 Pull Request em [tensorflow/tensorflow](https://github.com/tensorflow/tensorflow) corrigindo bug na função de pré-processamento de imagens  
- 📝 Documentação atualizada em [microsoft/vscode](https://github.com/microsoft/vscode) para extensão de Java

---

## ⚙️ GitHub Actions & Automação

- 🤖 CI/CD: testes automatizados com Maven e GitHub Actions  
- 🔄 Atualização diária de badges de métricas via workflow  
- 📥 Release Notes: publicação automática de releases com changelog gerado

```yaml
name: CI/CD Pipeline
on: [push, pull_request]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Set up JDK
        uses: actions/setup-java@v3
        with:
          java-version: '17'
      - name: Build with Maven
        run: mvn clean verify
