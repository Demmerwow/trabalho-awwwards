# 🦇 Instituto Arkham do Saber (IAS) - Edição Premium

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

Este é o repositório do **Trabalho 2** da disciplina de Desenvolvimento Web. O projeto consiste na estilização e aplicação de responsividade ao site institucional fictício **Instituto Arkham do Saber (IAS)**, inspirado na estética *Dark Premium* do portal [Awwwards](https://www.awwwards.com/).

---

## 👤 Autor
* **Nome:** [Seu Nome Completo Aqui]
* **Curso:** [Seu Curso Aqui]
* **Instituição:** [Sua Instituição Aqui]

---

## 🎯 Objetivos Alcançados (Trabalho 2)
- [x] **Design Visual Premium:** Estética inspirada em sites premiados (Awwwards), com uso de fundo escuro, tipografia gigante e minimalismo.
- [x] **Paleta de Cores:** Alto contraste (WCAG AA) utilizando Preto Profundo (`#0a0a0a`), Branco Off-white (`#f4f4f4`) e Vermelho Vibrante (`#e63946`) como cor de destaque.
- [x] **Tipografia:** Uso da fonte *Montserrat* para títulos (impacto visual) e *Inter* para textos de leitura (legibilidade), via Google Fonts.
- [x] **Responsividade Total (Mobile First):** Adaptação para Celular (< 768px), Tablet e Desktop (>= 1024px) com Media Queries.
- [x] **Layout com Flexbox e Grid:** 
  - Grid para organizar os cards de cursos e professores.
  - Flexbox para alinhar o cabeçalho (Header), formulário e rodapé.
- [x] **Componentes Especiais:** 
  - Formulário com design *line-bottom* (bordas apenas embaixo) e validações HTML5.
  - Tabela comparativa minimalista.
  - Menu Hambúrguer animado para dispositivos móveis.
- [x] **Micro-interações (Bônus):** Imagens que ganham cor ao passar o mouse (transição de *grayscale* para colorido) e botões com efeito de elevação.

---

## 📁 Estrutura do Projeto

```text
trabalho-awwwards/
│
├── index.html          # Página Inicial (Hero, Filosofia, Destaques)
├── sobre.html          # Sobre Nós (História, Corpo Docente, Infraestrutura)
├── cursos.html         # Cursos e Programas (Cards e Tabela Comparativa)
├── contato.html        # Contato (Formulário e Mapa customizado)
├── README.md           # Documentação do projeto
│
├── css/
│   └── style.css       # Todo o estilo do site (Variáveis, Grid, Flexbox, Media Queries)
│
└── images/             # Imagens do projeto (Professores, Cursos, Logo, etc.)