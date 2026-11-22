# João Victor (JV) — Landing Page Pessoal

Landing page pessoal responsiva desenvolvida com **HTML5 semântico** e **CSS3 moderno**, construída com uma estética *Dark Tech Minimalista*, alta fidelidade de design, acessibilidade e micro-interações elegantes.

🔗 **Acesse a página no ar:** [https://jota-rodrigues.github.io/Dev-Landing/](https://jota-rodrigues.github.io/Dev-Landing/)

---

## 📸 Preview

* **Tema:** Dark mode com paleta tecnológica (`#080b09`, `#111814`) e acentos em verde vibrante (`#2ee67a`).
* **Tipografia:** [Inter](https://fonts.google.com/specimen/Inter) (interface e corpo de texto) e [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (rótulos e detalhes técnicos).

---

## 🚀 Seções da Página

1. **Header (Sticky Navigation):** Cabeçalho fixo com efeito de desfoque (*backdrop blur*), logotipo monograma e âncoras para as seções com indicador de hover dinâmico.
2. **Hero:** Apresentação pessoal com animação contínua de gradiente (*name-shine*) no nome João Victor, tag de status e moldura com efeito de elevação na foto.
3. **Meus Gostos:** Grid estruturado apresentando os principais pilares: Tênis de mesa competitivo, Futebol & amizades, Tecnologia & Java e Animes.
4. **Onde já fui (Viagens):** Diário visual de viagens pelo Programa de Férias Germinare (Goiânia e Rio Grande do Sul) e campeonatos esportivos escolares (JEESP em Praia Grande), com tratamento panorâmico nativo sem cortes.
5. **Top 3: Japão:** Lista ordenada estilizada com numeração tecnológica (`01.`, `02.`, `03.`) detalhando destinos almejados (Akita, Aomori e Tóquio), com links externos informativos.
6. **Footer:** Rodapé minimalista com atalho para voltar suavemente ao topo da página.

---

## 🛠️ Tecnologias e Recursos de CSS Utilizados

- **HTML5 Semântico:** Utilização rigorosa de tags estruturais (`header`, `main`, `section`, `article`, `figure`, `figcaption`, `ol`, `nav`).
- **CSS Grid & Flexbox:** Composição de layouts responsivos nos grids de gostos e viagens, combinados com Flexbox em componentes de navegação, cards e botões.
- **Pseudo-classes Avançadas:**
  - `:hover` e `:active` para feedback tátil suave.
  - `:focus-visible` com anel verde neon para acessibilidade completa por navegação via teclado.
  - `:nth-child()` aplicado para destaque visual de módulos específicos (Tecnologia e ritmo alternado nos destinos).
  - `:target` para realçar sutilmente o título da seção quando atingida por âncora.
- **Pseudo-elementos:**
  - `::before` e `::after` para linhas de gradiente, sublinhado animado no menu e marcadores de lista automatizados com `counter()`.
  - Animação de pulso em ponto de status (*radar dot*).
- **Acessibilidade:**
  - Link de pulo rápido para o conteúdo (`.skip-link`).
  - Textos `alt` detalhados em todas as imagens.
  - Relação de contraste de cores em conformidade com as diretrizes WCAG (acima de 4.5:1).
  - Suporte completo à diretiva `@media (prefers-reduced-motion: reduce)`, desativando animações contínuas e transições para usuários com sensibilidade a movimento.
- **Responsividade Total:** Adaptado com `clamp()`, unidades relativas (`rem`, `em`, `%`, `vw`, `vh`) e breakpoints para Desktop, Tablet e Mobile.

---

## 📁 Estrutura de Arquivos

```text
Dev-Landing/
├── assets/
│   ├── icons/       # Ícones SVG otimizados
│   └── images/      # Imagens e fotografias da página
├── index.html       # Estrutura semântica principal
├── jv.css           # Estilos e design system
├── favicon.ico      # Ícone do navegador
└── README.md        # Documentação do projeto
```

---

Desenvolvido por **João Victor (JV)**.
