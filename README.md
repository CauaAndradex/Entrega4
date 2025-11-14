🌱 ONGConnect — Plataforma de Conexão entre ONGs, Voluntários e Doadores
📖 Descrição do Projeto

O ONGConnect é uma plataforma web desenvolvida como atividade acadêmica, simulando um sistema real de apoio a ONGs, voluntários e doadores.
O projeto utiliza HTML5, CSS3, JavaScript (ES Modules) e inclui um SPA básico, além das versões HTML tradicionais para cumprir todos os requisitos do trabalho.

A aplicação conta com:

🏠 Página Inicial (index) — apresentação da plataforma.

🧩 Página de Projetos (projetos) — lista de ONGs, sistema de doações e interação.

📝 Página de Cadastro (cadastro) — formulário completo com validações e máscaras.

⚡ SPA (Single Page Application) para navegação dinâmica.

O objetivo é demonstrar domínio de:
✔ estrutura HTML5 semântica
✔ responsividade
✔ acessibilidade (WCAG 2.1 nível AA)
✔ manipulação do DOM
✔ modularização JS
✔ máscaras de input
✔ UX moderna com grids, modais e toasts

🧩 Estrutura do Projeto
ONGConnect/
│
├── index.html              # Página Home (HTML independente + versão SPA)
├── projetos.html           # Listagem das ONGs + Doações
├── cadastro.html           # Formulário completo HTML5
│
├── css/
│   └── style.css           # Design System + Grid + Componentes + Modais
│
├── js/
│   ├── app.js              # Controlador SPA
│   ├── templates.js        # Páginas do SPA (home, projetos, cadastro)
│   ├── form.js             # Máscaras, validações e lógica dos formulários
│   └── masks.js            # Máscaras de CPF, telefone e CEP
│
└── assets/
    ├── logo.png            # Logo oficial ONGConnect
    ├── exemplo1.jpg        # Imagens de exemplo para ONGs
    └── (outros arquivos)

🎨 Design System

O projeto utiliza um sistema de design completo, incluindo:

🎨 Paleta de cores (8+ tons)

Verdes (primárias): #2b6b3a, #46a067, #a8e0b1

Destaques: âmbar e azul

Tons neutros: #0b0b0b → #ededed

Background suave: #fbfdfb

🔤 Tipografia

Hierarquia com 5 níveis (fs-900 → fs-500)

📐 Sistema de espaçamento

Escala modular (8px → 64px)

🔲 Layout Responsivo

CSS Grid de 12 colunas

Flexbox para componentes

5 breakpoints:

480px (xs)
640px (sm)
768px (md)
1024px (lg)
1280px (xl)

⚙️ Funcionalidades JavaScript
🖥 SPA (Single Page Application)

Navegação via data-route

Sem reload

Conteúdo injetado no <main id="app">

🧾 Formulário com validação avançada

Nome completo

Email obrigatório com formato válido

CPF com máscara automática

Telefone com máscara automática

CEP com máscara automática

Data de nascimento

Endereço completo (logradouro, cidade, estado)

Validações:
✔ obrigatoriedade
✔ limites de caracteres
✔ validação HTML5
✔ highlight verde/vermelho automático
✔ alerta visual e toast de sucesso

🎭 Máscaras (JavaScript Nativo)

CPF → 000.000.000-00

Telefone → (00) 00000-0000

CEP → 00000-000

🎁 Simulação de Doações

3 ONGs ativas

Cada ONG possui um botão "Doar"

Abre modal de doação via :target

Campo de valor

Feedback visual com toast de sucesso

⚙️ Outros Recursos JS

Atualização automática do menu ativo

Sistema modular (import/export)

Validação do formulário dentro do SPA

♿ Acessibilidade (WCAG 2.1 AA)

O projeto segue boas práticas como:

Navegação por teclado (TAB)

Labels conectados aos inputs

Contraste mínimo de 4.5:1

Texto alternativo em todas as imagens

Estrutura semântica completa:

<header>

<main>

<section>

<article>

<footer>

<nav>

Foco visível em botões e inputs

Modais acessíveis

Navegação mobile com hambúrguer acessível (aria-label)

🚀 Desempenho

Minificação recomendada

Estrutura otimizada

Toasts e modais leves

Carregamento rápido

Código modular

🔐 Segurança

Validações no front-end

Inputs higienizados

Boas práticas de formulário

🧠 Metodologias e Versionamento

Commits Semânticos

GitFlow

Organização modular

Pastas padronizadas

🧰 Tecnologias Utilizadas

HTML5

CSS3 (Grid + Flexbox + Design System)

JavaScript ES Modules

Git & GitHub

VS Code + Live Server

💡 Como Executar
git clone https://github.com/CauaAndradeX/ONGConnect.git
cd ONGConnect

# Abrir no VS Code
code .

# Rodar com Live Server:
Clique com o botão direito no index.html
→ "Open With Live Server"

👨‍💻 Autores

Cauã de Andrade Silva
Nicollas Santana de Sousa

Desenvolvedores Front-End | Criadores do ONGConnect

📝 Licença

MIT — uso livre para estudos.

“Conectar, apoiar e transformar — esse é o poder do código.”
