# 💼 Vitor Sales - Portfolio & Technical Blog

[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-181717?logo=github)](https://tvitor.github.io/)
[![Jekyll](https://img.shields.io/badge/Built%20with-Jekyll-CC0000?logo=jekyll)](https://jekyllrb.com/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> **Senior Software Engineer** especializado em **HealthTech & Radiology Information Systems (RIS)**  
> 5+ anos construindo sistemas críticos para a Rede D'Or São Luiz

🔗 **Live Site:** [tvitor.github.io](https://tvitor.github.io/)  
🔗 **LinkedIn:** [linkedin.com/in/vitor-sales89](https://linkedin.com/in/vitor-sales89)

---

## 📚 Sobre o Projeto

Este repositório contém meu **portfolio profissional** e **blog técnico**, desenvolvido como um site estático usando **Jekyll** e hospedado gratuitamente no **GitHub Pages**..

O objetivo é compartilhar conhecimento sobre:
- 🏥 **HealthTech:** Desenvolvimento de sistemas RIS/PACS/HIS
- ⚙️ **Engenharia de Software:** Arquitetura, performance, compliance regulatório
- 🚀 **Metodologias Ágeis:** SAFe, Scrum, TDD, DevOps
- 💻 **Stack Moderna:** TypeScript, NestJS, Angular, PostgreSQL, AWS, Kubernetes

---

## 🛠️ Stack Tecnológica

### **Core Framework**
- **Jekyll 3.x** - Gerador de site estático (Ruby)
- **GitHub Pages** - Hospedagem gratuita com deploy automático
- **Liquid** - Template engine (sintaxe `{% %}`)

### **Frontend**
- **HTML5** - Estrutura semântica
- **SCSS/Sass** - Estilização modular e componentizada
- **Markdown** - Conteúdo dos artigos (`_posts/`)
- **Google Fonts** - Tipografia (Quicksand, Open Sans)

### **Design System**
- **Custom CSS Framework** inspirado em Material Design
- **Componentes:** Cards com z-depth, buttons, grid responsivo
- **Responsividade:** Media queries mobile-first

### **Versionamento**
- **Git/GitHub** - Controle de versão e "CMS" para conteúdo
- **GitHub Actions** - CI/CD automático (build + deploy)

---

## 📂 Arquitetura do Projeto

```
tvitor.github.io/
│
├── _config.yml              # Configurações globais do site
├── index.html               # Página inicial (HTML + Liquid)
├── about.md                 # Página "Sobre" (Markdown)
│
├── _layouts/                # Templates HTML reutilizáveis
│   ├── default.html         # Layout base (header, footer, nav)
│   ├── post.html            # Layout de artigo individual
│   └── page.html            # Layout de páginas estáticas
│
├── _includes/               # Componentes parciais
│   ├── header.html          # Cabeçalho do site
│   ├── footer.html          # Rodapé com links sociais
│   └── head.html            # Meta tags, CSS, fonts
│
├── _posts/                  # Artigos do blog (Markdown)
│   ├── 2018-07-02-as-etapas-do-desenvolvimento-de-software.markdown
│   ├── 2025-05-01-construindo-sistemas-ris-criticos.markdown
│   └── 2025-11-11-Agil.markdown
│
├── _sass/                   # Arquivos SCSS modulares
│   ├── _base.scss           # Reset CSS, tipografia base
│   ├── _layout.scss         # Grid, containers, sections
│   ├── _buttons.scss        # Estilos de botões
│   ├── _cards.scss          # Componente de cards
│   └── _syntax-highlighting.scss  # Código com highlight
│
├── css/
│   └── main.scss            # Arquivo principal que importa todos os _sass/
│
├── assets/                  # Recursos estáticos
│   ├── headshot.jpg         # Foto de perfil
│   └── *.PNG                # Imagens dos artigos
│
├── _site/                   # Site compilado (gerado automaticamente)
│   └── (não versionado)
│
└── README.md                # Este arquivo
```

---

## 🔄 Fluxo de Funcionamento

### **1. Desenvolvimento Local**

```bash
# Instalar Jekyll e dependências (requer Ruby 2.5+)
gem install bundler jekyll

# Clonar o repositório
git clone https://github.com/Tvitor/tvitor.github.io.git
cd tvitor.github.io

# Instalar dependências do projeto
bundle install

# Servir localmente com live reload
bundle exec jekyll serve --livereload

# Acessar em http://localhost:4000
```

### **2. Como Jekyll Funciona**

1. **Compilação:** Jekyll lê arquivos `.md` e `.html` com front matter (metadados YAML)
2. **Processamento:** Aplica templates Liquid (`_layouts/`) e inclui componentes (`_includes/`)
3. **Build:** Gera HTML estático na pasta `_site/`
4. **Deploy:** GitHub Pages detecta push na branch `master` e republica automaticamente

### **3. Estrutura de um Post**

````markdown
---
layout: post                          # Usa [post.html](http://_vscodecontentref_/0)
title: "Título do Artigo"
date: 2025-11-22 10:00:00            # Data/hora de publicação
categories: HealthTech Engineering    # Tags/categorias
---

## Conteúdo em Markdown

Texto, **negrito**, *itálico*, links

```typescript
// Código com syntax highlighting
const exemplo = "funciona automaticamente";
```

!Imagem