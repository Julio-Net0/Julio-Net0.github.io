# Júlio Miranda | Portfolio & Tech Showcase

Bem-vindo ao repositório do meu portfólio pessoal e showcase técnico, hospedado via [GitHub Pages](https://Julio-Net0.github.io).

Este projeto é mais do que uma galeria de trabalhos; é uma experimentação prática de arquitetura front-end estática, manipulação avançada de DOM com Vanilla JavaScript e design modular orientado a Variáveis CSS (Custom Properties).

## 🏗️ Arquitetura do Projeto

Para garantir máxima performance e blindagem de escopo de estilos sem a necessidade de frameworks pesados, o portfólio adota uma arquitetura de "Monólitos HTML" com roteamento no lado do cliente:

* **Theme Switcher Dinâmico:** O arquivo `index.html` atua como um randomizador e roteador, distribuindo as visitas para diferentes abordagens de UI/UX (Neomorfismo, Neo-brutalismo, Glassmorphism).
* **Isolamento de Estilos:** Cada tema é um documento HTML independente, garantindo que as regras de CSS de um design (ex: sombras extrudadas do Neomorfismo) não interfiram na geometria de outro (ex: linhas finas do Bento Grid).
* **Componentes Imersivos:** Projetos de maior escala (Premium) possuem sessões visuais próprias e isoladas, alterando completamente o fluxo da página para combinar com a tecnologia utilizada.

## 🛠️ Tecnologias e Habilidades em Destaque

O portfólio documenta projetos que cobrem as quatro áreas principais da minha stack:

* **Full-Stack Web:** Migração e orquestração de APIs (FastAPI, Flask, Laravel), containers (Docker) e arquitetura de banco de dados.
* **Data Science & AI:** Pipelines de Visão Computacional (YOLO, TensorFlow) e integração com LLMs de alto desempenho (como o DeepSeek-V3).
* **Engenharia de Software (Baixo Nível):** Algoritmos avançados, gerenciamento de memória em C/C++ e desenvolvimento de engines (Raylib).
* **Linux Systems:** Administração de servidores (Ubuntu Server), clusters HPC, bash scripting e customização profunda de ambiente (Neovim/Lua, Arch Linux).

## 🚀 Projetos em Destaque

Alguns dos sistemas detalhados no portfólio incluem:

1. **Equinox System (Case Study):** Plataforma de monitoramento de energia construída com FastAPI e Docker, utilizando processamento de dados acelerado com DeepSeek-V3. (Apresentado via Dashboard Mockup por ser software proprietário).
2. **Projeto Torrefação IA:** Sistema de classificação de níveis de torra de grãos de café utilizando Visão Computacional (CNNs/YOLO) treinada com um dataset de mais de 40.000 imagens.
3. **Motor Voxel em C:** Clone de mecânicas de geração de mundo em C puro, focado em gerenciamento de chunks e otimização geométrica.
4. **Infraestrutura & Automação:** Projetos de automação física (Wake-on-LAN com ESP8266) e soluções completas web (Scalioni Engenharia).

## 👨‍💻 Sobre o Autor

**Júlio Ignácio Miranda Neto**
Estudante de Sistemas de Informação no CEFET-MG campus Varginha. Desenvolvedor apaixonado por descer ao baixo nível do hardware quando necessário e subir até a abstração de inteligência artificial para resolver problemas reais.

[LinkedIn](https://www.linkedin.com/in/júlio-neto-21990b2b4) | [GitHub](https://github.com/Julio-Net0)

---

### ⚙️ Como rodar localmente

Como o projeto é totalmente estático e não depende de build steps (Node.js/NPM), basta clonar o repositório e subir um servidor HTTP simples:

```bash
git clone https://github.com/Julio-Net0/Julio-Net0.github.io.git
cd Julio-Net0.github.io
# Usando Python 3
python -m http.server 8000