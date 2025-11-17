# 🚀 TechSolutions - Site Responsivo

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-green?style=for-the-badge)
![Accessibility](https://img.shields.io/badge/Accessibility-WCAG%20AA-blue?style=for-the-badge)

> Site moderno e responsivo desenvolvido com HTML5 e CSS3 puro, focado em acessibilidade e design contemporâneo.

---

## 🔗 Deploy

O site está publicado e disponível no Netlify:

[Acesse aqui!](https://techsolutionsoficial.netlify.app/)

---

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Como Usar](#-como-usar)
- [Responsividade](#-responsividade)
- [Acessibilidade](#-acessibilidade)
- [Navegadores Suportados](#-navegadores-suportados)
- [Autor](#-autor)
- [Licença](#-licença)

---

## 🎯 Sobre o Projeto

**TechSolutions** é um projeto de site institucional desenvolvido para demonstrar competências em desenvolvimento web front-end utilizando tecnologias fundamentais da web: HTML5 e CSS3.

O site apresenta uma empresa fictícia de soluções tecnológicas, com foco em:
- 🎨 Design moderno e atrativo
- 📱 Responsividade total
- ♿ Acessibilidade (WCAG AA)
- ⚡ Performance otimizada
- 🔧 Código limpo e semântico

---

## ✨ Funcionalidades

### 🏠 Hero Section
- Banner impactante com gradiente animado
- Call-to-action destacado
- Animações de entrada suaves

### 💼 Seção de Serviços
- Grid responsivo com 6 cards de serviços
- Efeitos hover sofisticados
- Ícones ilustrativos

### 👥 Sobre a Empresa
- Layout flexível texto + imagem
- Lista de diferenciais estilizada
- Design clean e profissional

### 📬 Formulário de Contato
- Validação HTML5 nativa
- Feedback visual em tempo real
- Design glassmorphism
- Campos:
  - Nome completo (obrigatório)
  - E-mail (obrigatório com validação)
  - Telefone (com pattern)
  - Serviço de interesse (select)
  - Mensagem (obrigatória)
  - Newsletter (checkbox)

### 🎯 Menu de Navegação
- Sticky header com efeito glassmorphism
- Menu hambúrguer responsivo para mobile
- Smooth scroll para seções
- Estados hover e focus visíveis

### 📱 Menu Mobile
- Toggle JavaScript puro
- Animação suave de abertura
- Backdrop blur
- Navegação vertical

---

## 🛠️ Tecnologias Utilizadas

### Core
- **HTML5** - Estrutura semântica
- **CSS3** - Estilização avançada
- **JavaScript (Vanilla)** - Interatividade básica

### Técnicas CSS
- ✅ Flexbox
- ✅ CSS Grid
- ✅ Custom Properties (CSS Variables)
- ✅ Gradientes lineares
- ✅ Animações e transições
- ✅ Glassmorphism (backdrop-filter)
- ✅ Media Queries
- ✅ Pseudo-elementos e pseudo-classes
- ✅ Transform e animações performáticas

### Características
- 🚫 **Zero dependências externas**
- 🚫 **Sem frameworks CSS**
- 🚫 **Sem bibliotecas JavaScript**
- ✅ **100% código nativo**

---

## 📁 Estrutura do Projeto

```
projeto-techsolutions/
│
├── index.html          # Estrutura HTML principal
├── styles.css           # Estilos CSS
├── README.md           # Este arquivo

```

### Estrutura HTML

```
index.html
├── <header>
│   ├── Logo
│   ├── Menu Toggle (mobile)
│   └── <nav> Navegação
│
├── <main>
│   ├── <section#inicio> Hero
│   ├── <section#servicos> Serviços
│   ├── <section#sobre> Sobre
│   └── <section#contato> Contato
│
└── <footer>
    ├── Informações da empresa
    ├── Links rápidos
    ├── Contato
    └── Redes sociais
```

---

## 🚀 Como Usar

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Editor de código (VS Code, Sublime, etc.) - opcional

### Instalação

1. **Clone o repositório** ou baixe os arquivos:
```bash
git clone https://github.com/franciellivalerio/projeto-techsolutions.git
```

2. **Navegue até a pasta**:
```bash
cd projeto-techsolutions
```

3. **Abra o arquivo index.html** em seu navegador:
```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

### Ou use um servidor local:

```bash
# Com Python 3
python -m http.server 8000

# Com Node.js (http-server)
npx http-server

# Com PHP
php -S localhost:8000
```

Acesse: `http://localhost:8000`

---

## 📱 Responsividade

O site é totalmente responsivo e adapta-se perfeitamente a diferentes tamanhos de tela:

### Breakpoints

| Dispositivo | Largura | Características |
|------------|---------|-----------------|
| 📱 Mobile | < 480px | Menu hambúrguer, 1 coluna, fontes reduzidas |
| 📱 Tablet | 481px - 768px | Menu adaptado, 2 colunas em grid |
| 💻 Desktop | 769px - 1024px | Menu horizontal, 3 colunas |
| 🖥️ Large Desktop | > 1024px | Layout completo, max-width 1200px |

### Técnicas de Responsividade

```css
/* Grid Responsivo */
grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));

/* Flexbox Adaptável */
display: flex;
flex-wrap: wrap;

/* Media Queries */
@media (max-width: 768px) {
    /* Estilos para tablet */
}

@media (max-width: 480px) {
    /* Estilos para mobile */
}
```

---

## ♿ Acessibilidade

O projeto segue as diretrizes **WCAG 2.1 nível AA**:

### ✅ Implementações

#### Semântica HTML
- Tags semânticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- Hierarquia de headings correta (H1 > H2 > H3)
- Landmarks ARIA implícitos

#### Navegação por Teclado
- Estados `:focus` visíveis
- Tab order lógico
- Outline personalizado
- Menu navegável por teclado

#### Contraste de Cores
- Texto principal: contraste 16:1
- Texto secundário: contraste 7:1
- Links e botões: contraste mínimo 4.5:1

#### Formulários
- Labels associados a inputs (`for` + `id`)
- Atributos `aria-required` em campos obrigatórios
- Validação visual (cores + bordas)
- Placeholders não substituem labels

#### Imagens
- Atributo `alt` descritivo em todas as imagens
- Imagens decorativas com `alt=""` ou em CSS

#### ARIA
```html
<button aria-label="Abrir menu de navegação">
<nav aria-label="Navegação principal">
<input aria-required="true">
```

### Testes Recomendados

- ✅ [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/)
- ✅ [axe DevTools](https://www.deque.com/axe/devtools/)
- ✅ Lighthouse (Chrome DevTools)
- ✅ Navegação apenas por teclado (Tab, Enter, Esc)
- ✅ Leitores de tela (NVDA, JAWS, VoiceOver)

---

## 🌐 Navegadores Suportados

| Navegador | Versão Mínima |
|-----------|---------------|
| Chrome | 90+ |
| Firefox | 88+ |
| Safari | 14+ |
| Edge | 90+ |
| Opera | 76+ |

### Recursos que podem necessitar polyfills em navegadores antigos:
- CSS Grid
- Flexbox
- CSS Variables (Custom Properties)
- backdrop-filter
- smooth scroll behavior

---

## 🎨 Paleta de Cores

```css
/* Cores Principais */
--primary-color: #6368f1;  /* Índigo / Roxo-azulado */  
--secondary-color: #e52326;  /* Vermelho */
--accent-color: #f59e0b;     /* Laranja */
--accent-pink: #ec4899;      /* Rosa */

/* Cores Neutras */
--text-color: #1f2937;       /* Cinza escuro */
--gray: #64748b;             /* Cinza médio */
--light-bg: #f8fafc;         /* Cinza claro */
--white: #ffffff;            /* Branco */
```

---

## 📊 Performance

### Otimizações Implementadas

✅ **CSS**
- Uso de `transform` e `opacity` para animações (GPU-accelerated)
- Transições curtas (300-400ms)
- Seletores eficientes
- Minificação recomendada para produção

✅ **HTML**
- Estrutura semântica reduz tamanho
- SVG inline para evitar requisições HTTP
- Sem dependências externas

✅ **JavaScript**
- Código mínimo e otimizado
- Event delegation quando possível
- Smooth scroll nativo

### Lighthouse Score (Esperado)

| Categoria | Score |
|-----------|-------|
| Performance | 95+ |
| Accessibility | 100 |
| Best Practices | 100 |
| SEO | 100 |

---

## 🔧 Personalização

### Alterar Cores

Edite as variáveis CSS em `style.css`:

```css
:root {
    --primary-color: #sua-cor;
    --secondary-color: #sua-cor;
    /* ... */
}
```

### Adicionar Nova Seção

1. Adicione o HTML no `index.html`:
```html
<section id="nova-secao" class="nova-secao">
    <div class="container">
        <h2>Título</h2>
        <!-- Conteúdo -->
    </div>
</section>
```

2. Adicione estilos no `style.css`:
```css
.nova-secao {
    padding: 5rem 2rem;
    /* Seus estilos */
}
```

3. Adicione link na navegação:
```html
<nav>
    <!-- ... -->
    <a href="#nova-secao">Nova Seção</a>
</nav>
```

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/NovaFuncionalidade`)
5. Abra um Pull Request

### Guidelines

- Mantenha o código semântico e acessível
- Teste em múltiplos navegadores
- Documente mudanças significativas
- Siga os padrões de código existentes

- Documente mudanças significativas
- Siga os padrões de código existentes

---

## 📚 Recursos de Aprendizado

- [MDN Web Docs - HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
- [CSS Tricks](https://css-tricks.com/)
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Web Accessibility Initiative (WAI)](https://www.w3.org/WAI/)

---

## 👨‍💻 Autora

**Francielli Valerio**

- GitHub: [@franciellivalerio](https://github.com/franciellivalerio)
- LinkedIn: [Francielli Valerio](https://linkedin.com/in/franciellivalerio)

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

```
MIT License

Copyright (c) 2024 Francielli Valerio

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

<div align="center">

**⭐ Se este projeto foi útil para você, considere dar uma estrela!**

Feito com ❤️ e muito ☕

[⬆ Voltar ao topo](#-techsolutions---site-responsivo)

</div>