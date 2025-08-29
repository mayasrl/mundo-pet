# Mundo Pet

Um **sistema de agendamento para petshop** interativo e responsivo, criado durante o curso da **Rocketseat**.  
Permite agendar, visualizar e cancelar horários de atendimento para pets, organizados por períodos do dia (manhã, tarde e noite) com interface moderna e intuitiva.

---
 
## Visão Geral

- **HTML5**: marcação semântica com `<header>`, `<main>`, `<section>`, `<form>`, `<fieldset>` e elementos de lista.  
- **CSS3**: variáveis (Custom Properties), Flexbox & CSS Grid, transições suaves, design responsivo e tema escuro.  
- **JavaScript ES6+**: módulos, manipulação do DOM, validação de formulários, integração com API e formatação de datas com Day.js.  
- **Webpack**: bundling de módulos, desenvolvimento com hot reload e build otimizado para produção.  
- **JSON Server**: API REST simulada para persistência de dados dos agendamentos.

---

## Estrutura do Projeto

- **`index.html`**: página principal com interface de agendamentos e formulário.  
- **`global.css`**: estilos globais com variáveis, reset, layout e responsividade.  
- **`main.css`**: estilos específicos para a lista de agendamentos e períodos do dia.  
- **`form.css`**: estilos do formulário de agendamento com validações visuais.  
- **`src/modules/`**: módulos JavaScript organizados por funcionalidade.  
- **`assets/`**: ícones SVG e recursos visuais do projeto.

---

## Principais Funcionalidades

- **Agendamento de Horários** – formulário completo com validação de dados e horários.  
- **Visualização por Períodos** – organização automática em manhã, tarde e noite.  
- **Cancelamento de Agendamentos** – remoção rápida com confirmação.  
- **Filtro por Data** – visualização de agendamentos de dias específicos.  
- **Validação Inteligente** – impede agendamentos em horários passados.  
- **Interface Responsiva** – adaptação perfeita para desktop e mobile.  
- **Tema Escuro** – design moderno com paleta de cores profissional.

---

## Como Executar

```bash
# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm run dev

# Iniciar API (em outro terminal)
npm run server

# Build para produção
npm run build
```

---

## Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript ES6+
- **Build Tool**: Webpack 5
- **Bundling**: Babel, CSS Loader, Style Loader
- **API**: JSON Server
- **Formatação de Datas**: Day.js
- **Design**: Mobile First, CSS Grid, Flexbox

---

<img width="1919" height="869" alt="mundo-pet" src="https://github.com/user-attachments/assets/d17a3721-8201-4a51-bb92-fd197602f677" />

---

<p align="center">
  Desenvolvido durante o curso da <strong>Rocketseat</strong> com <img src="src/assets/heart.svg" width="14" alt="coração"/> por <strong>@mayasrl</strong>.
</p>
