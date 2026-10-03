# Chrono X Pulse Titanium — Landing Page de Alta Conversão

Landing page institucional e de vendas de alta performance para o smartwatch executivo **Chrono X Pulse Titanium**, desenvolvida com foco em design moderno (*Titanium Precision*), acessibilidade, SEO, animações fluidas e tempos de resposta rápidos.

---

## 🚀 Demonstração & Visão Geral

- **Design System**: Tema *Titanium Precision*, estética aeroespacial com paleta slate/sky/emerald.
- **Tipografia**: Google Fonts (*Sora*, *Inter*, *JetBrains Mono*) e *Material Symbols Outlined*.
- **Performance**: Lazy loading inteligente de imagens com `IntersectionObserver` e `loading="lazy"`, transição suave com fade-in e blur.
- **Interatividade**: Contador regressivo de escassez em tempo real, animações de entrada (*scroll reveal*) sincronizadas com a rolagem e header dinâmico com backdrop-blur.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico**: Estrutura acessível com tags semânticas (`<header>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`), atributos ARIA e tags Open Graph para SEO.
- **CSS3 Moderno (`style.css`)**:
  - Arquitetura de design tokens (variáveis CSS customizadas);
  - Classes modulares para cards, botões de conversão e badges;
  - Animações otimizadas para hardware (`transform`, `opacity`, `will-change`);
  - Suporte completo a acessibilidade (`prefers-reduced-motion` e `:focus-visible`).
- **Tailwind CSS CDN**: Utilitários complementares de layout e espaçamento responsivo.
- **Vanilla JavaScript**: Scripts leves e modulares sem dependência de bibliotecas externas pesadas.

---

## 📁 Estrutura do Projeto

```text
├── index.html         # Página principal da landing page
├── style.css          # Estilos desacoplados e design tokens (Titanium Precision)
├── .gitignore         # Regras de exclusão do Git
├── README.md          # Documentação do projeto
├── old/               # Arquivos originais de referência (backup da refatoração)
│   ├── code.html
│   ├── DESIGN.md
│   └── screen.png
├── stitch/            # Template base gerado via Google Stitch
│   ├── code.html
│   ├── DESIGN.md
│   └── screen.png
└── .docs/             # Documentação e especificações de engenharia
    ├── prompt_github.md
    └── SPEC.md
```

---

## 💻 Como Executar o Projeto

Como o projeto é puramente estático (Vanilla HTML5, CSS3 e JS), não há necessidade de compilação ou instalação de dependências pesadas.

### Opção 1: Abrir diretamente no navegador
Basta dar dois cliques no arquivo `index.html` ou abri-lo em qualquer navegador moderno (Chrome, Edge, Firefox, Safari).

### Opção 2: Servidor estático local (Recomendado)
Para uma experiência idêntica à de produção (com suporte correto a fetch e cache local):

Com **Python**:
```bash
# Python 3
python -m http.server 3000
```
Acesse no navegador: `http://localhost:3000`

Com **Node.js (npx)**:
```bash
npx serve .
# ou
npx live-server
```

Com a extensão **Live Server** do VS Code:
- Clique com o botão direito em `index.html` e selecione **Open with Live Server**.

---

## 🧪 Validação e Qualidade

- **Validação HTML5**: Código indentado, fechamento adequado de tags, sem erros de sintaxe.
- **Acessibilidade (a11y)**:
  - Contrastes conforme padrões WCAG;
  - Textos alternativos (`alt`) descritivos em todas as imagens;
  - Atributos `aria-label`, `aria-hidden` e `role` em componentes visuais e decorativos;
  - Respeito à preferência do sistema operacional para redução de movimento (`prefers-reduced-motion: reduce`).
- **SEO & Social Sharing**: Meta tags de descrição, Open Graph para compartilhamento em redes sociais e cabeçalhos em hierarquia correta (`h1` único, seguido de `h2` e `h3`).

---

## 📄 Licença

Este projeto é desenvolvido para fins comerciais e demonstrativos. Todos os direitos reservados.
