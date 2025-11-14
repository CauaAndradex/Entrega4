# 🌱 ONGConnect — Plataforma de Conexão entre ONGs, Voluntários e Doadores

## 📖 Descrição do Projeto
O **ONGConnect** é uma plataforma web criada como atividade acadêmica, simulando um sistema completo de apoio a ONGs, voluntários e doadores.  
O projeto foi desenvolvido utilizando **HTML5, CSS3 e JavaScript (ES Modules)**, incluindo:

- ✔ Uma **SPA (Single Page Application)** funcional  
- ✔ Páginas HTML independentes (index, projetos e cadastro)  
- ✔ Formulário completo com máscaras e validações  
- ✔ Sistema de doações com modais  
- ✔ Toasts, alerts e interação moderna  
- ✔ Design system + grid de 12 colunas + responsividade  
- ✔ Padrões de acessibilidade WCAG 2.1 AA  

---

```

## 🧩 Estrutura do Projeto

ONGConnect/
│
├── index.html # Página Home (SPA + versão HTML)
├── projetos.html # Listagem das ONGs
├── cadastro.html # Formulário completo
│
├── css/
│ └── style.css # Design system, grid, componentes e modais
│
├── js/
│ ├── app.js # SPA Controller
│ ├── templates.js # Telas da SPA
│ ├── form.js # Validação e máscaras
│ └── masks.js # Máscaras de CPF, telefone, CEP
│
└── assets/
├── logo.png
```

---

## 🎨 Sistema de Design

### 🎨 Paleta de Cores
- **Verde primário:** `#2b6b3a`, `#46a067`, `#a8e0b1`
- **Destaques:** âmbar (`#ffd166`), azul (`#2a9d8f`)
- **Neutras:** `#0b0b0b` → `#ededed`
- **Background:** `#fbfdfb`

### 🔤 Tipografia
5 níveis hierárquicos:
- fs-900  
- fs-800  
- fs-700  
- fs-600  
- fs-500  

### 📐 Sistema de grid e espaçamento
- Grid **12 colunas**
- 5 breakpoints:
  - 480px  
  - 640px  
  - 768px  
  - 1024px  
  - 1280px  
- Escala modular (8 → 64px)

---

## ⚙️ Funcionalidades JavaScript

### 🖥 SPA Completa
- Navegação dinâmica usando `data-route`
- Conteúdo injetado no `<main id="app">`
- Atualização automática do menu ativo

### 🧾 Formulário com validações avançadas
Inputs utilizados:
- Nome completo  
- E-mail  
- CPF  
- Telefone  
- Data de nascimento  
- Endereço completo  
- CEP  
- Cidade  
- Estado  

Validações:
- HTML5 (`required`, `type`, `pattern`, `minlength`, `maxlength`)
- Mensagens de erro
- Bordas coloridas via CSS (`valid` / `invalid`)
- Máscaras dinâmicas em:
  - CPF
  - Telefone
  - CEP

### 🎁 Sistema de Doações
- 3 ONGs cadastradas
- Abertura de modal via `:target`
- Campo de valor obrigatório
- Toast de sucesso após doação

### 🧱 Componentes criados
- Botões (com hover/focus/active)
- Cards responsivos
- Badges & tags
- Alertas
- Toasts animados
- Modais acessíveis

---

## ♿ Acessibilidade (WCAG 2.1 AA)

Implementações:
- Navegação completa por teclado  
- Foco visível em elementos interativos  
- Contraste dentro do mínimo recomendado  
- Estrutura HTML semântica  
- Texto alternativo em todas as imagens  
- Labels associados aos inputs  
- Menu mobile com `aria-label`

---

## 🚀 Desempenho
- Código modular  
- CSS otimizado  
- Estrutura leve  
- Carregamento rápido  

---

## 🔐 Segurança
- Validação nativa + JS  
- Campos higienizados  
- Regex para inputs críticos  

---

## 🧠 Metodologias e Versionamento
- Padrão **GitFlow**  
- **Commits Semânticos**  
- Organização lógica de pastas  
- SPA + HTML estático  

---

## 🧰 Tecnologias Utilizadas
- **HTML5**  
- **CSS3**  
- **JavaScript (ES Modules)**  
- **Flexbox**  
- **CSS Grid**  
- **Git + GitHub**  

---




## 👨‍💻 Autores
Cauã de Andrade Silva
Nicollas Santana de Sousa

Desenvolvedores Front-End | Criadores da ONGConnect

---

## 📝 Licença
Licença MIT — livre para fins acadêmicos e educacionais.

“Conectar, apoiar e transformar — esse é o poder do código.”


