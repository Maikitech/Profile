# 🎯 Portfólio Profissional - Guia de Customização

Um portfólio elegante, responsivo e completo para profissionais de T.I divulgarem suas habilidades no GitHub e LinkedIn.

## 📋 Conteúdo do Projeto

```
PERFIL/
├── index.html      (Estrutura HTML)
├── styles.css      (Estilos CSS3)
├── script.js       (Interatividade JavaScript)
└── README.md       (Este arquivo)
```

## 🎨 Características

✅ **Design Moderno e Profissional**
- Paleta de cores gradiente moderna (roxo → rosa)
- Tipografia elegante com fontes Google
- Efeitos visuais suaves e animações

✅ **Totalmente Responsivo**
- Funciona perfeitamente em desktop, tablet e mobile
- Menu hamburger automático em telas pequenas
- Layouts adaptativos

✅ **Seções Completas**
- Hero section impactante
- Sobre mim com estatísticas
- Habilidades técnicas com barras de progresso
- Portfólio de projetos
- Experiência profissional (timeline)
- Formulário de contato
- Links de redes sociais

✅ **Funcionalidades JavaScript**
- Navegação suave
- Menu mobile responsivo
- Animações ao scroll
- Formulário de contato com validação
- Botão scroll to top
- Scroll ativo na navegação

## 🔧 Como Customizar

### 1. Informações Pessoais

Abra `index.html` e procure por:

```html
<!-- Hero Section -->
<h1 class="hero-title">Olá, meu nome é <span class="highlight">Seu Nome</span></h1>
```

Substitua `Seu Nome` pelo seu nome completo.

### 2. Descrição Pessoal

Na seção "Sobre Mim", atualize o texto:

```html
<p>Sou um profissional dedicado...</p>
```

### 3. Habilidades

Customize as habilidades em cada categoria. Exemplo:

```html
<div class="skill-item">
    <div class="skill-name">HTML5 / CSS3</div>
    <div class="progress-bar">
        <div class="progress" style="width: 95%"></div>
    </div>
</div>
```

- **skill-name**: Nome da habilidade
- **width**: Porcentagem de proficiência (0-100%)

### 4. Projetos

Customize a seção de projetos. Exemplo:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-shopping-cart"></i>
    </div>
    <div class="project-content">
        <h3>Plataforma E-Commerce</h3>
        <p>Descrição do projeto...</p>
        <div class="project-tags">
            <span class="tag">Tecnologia 1</span>
            <span class="tag">Tecnologia 2</span>
        </div>
    </div>
</div>
```

- Mude o ícone (use [Font Awesome](https://fontawesome.com))
- Atualize título e descrição
- Adicione links ao projeto no `href`

### 5. Experiência Profissional

Customize a timeline:

```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <h3>Senior Developer</h3>
        <p class="company">Tech Company Inc. | 2021 - Presente</p>
        <p class="description">Descrição da experiência...</p>
    </div>
</div>
```

### 6. Contato e Redes Sociais

**Email:**
```html
<a href="mailto:seu-email@email.com">seu-email@email.com</a>
```

**Telefone:**
```html
<a href="tel:+5511999999999">(11) 99999-9999</a>
```

**LinkedIn:**
```html
<a href="https://linkedin.com/in/seu-perfil" target="_blank">linkedin.com/in/seu-perfil</a>
```

**GitHub:**
```html
<a href="https://github.com/seu-usuario" target="_blank"><i class="fab fa-github"></i></a>
```

**Twitter:**
```html
<a href="https://twitter.com/seu-usuario" target="_blank"><i class="fab fa-twitter"></i></a>
```

## 🎨 Customização de Cores

Edite as cores em `styles.css`, na seção `:root`:

```css
:root {
    --primary: #6366f1;           /* Azul principal */
    --secondary: #ec4899;         /* Rosa/Magenta */
    --accent: #f59e0b;            /* Âmbar */
    --dark: #1f2937;              /* Texto escuro */
    --gray: #6b7280;              /* Cinza */
    /* ... mais cores */
}
```

### Paletas Sugeridas:

**Profissional Azul:**
```css
--primary: #2563eb;
--secondary: #1e40af;
```

**Moderno Verde:**
```css
--primary: #10b981;
--secondary: #059669;
```

**Tech Roxo:**
```css
--primary: #7c3aed;
--secondary: #6d28d9;
```

## 🔤 Mudar Fontes

As fontes estão sendo carregadas do Google Fonts. Para mudá-las, edite em `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
```

E em `styles.css`, mude as famílias de fonte:

```css
body {
    font-family: 'Inter', sans-serif;
}

.section-title {
    font-family: 'Poppins', sans-serif;
}
```

## 📱 Ícones Font Awesome

O portfólio usa [Font Awesome 6.4.0](https://fontawesome.com). Alguns ícones úteis:

- `fas fa-code` - Código
- `fas fa-laptop-code` - Desenvolvimento
- `fas fa-paint-brush` - Design
- `fas fa-server` - Backend
- `fas fa-tools` - Ferramentas
- `fas fa-users` - Equipe
- `fas fa-github` - GitHub
- `fas fa-linkedin` - LinkedIn
- `fas fa-twitter` - Twitter
- `fas fa-envelope` - Email
- `fas fa-phone` - Telefone

## 🚀 Deploy no GitHub Pages

1. Crie um repositório no GitHub chamado `seu-usuario.github.io`
2. Coloque os arquivos do portfólio na raiz do repositório
3. Faça push para o GitHub
4. Seu portfólio estará disponível em: `https://seu-usuario.github.io`

### Alternativa: Repositório Específico

1. Crie um repositório chamado `portfolio`
2. Ative GitHub Pages nas configurações
3. Escolha a branch `main` ou `gh-pages`
4. O portfólio estará em: `https://seu-usuario.github.io/portfolio`

## 💡 Dicas de SEO

Para melhorar a indexação no Google:

1. **Meta Tags** (já incluídas):
```html
<meta name="description" content="Portfólio Profissional - Especialista em Tecnologia da Informação">
```

2. **Open Graph** (adicione em `<head>`):
```html
<meta property="og:title" content="Meu Portfólio">
<meta property="og:description" content="Conheça meus projetos e habilidades">
<meta property="og:image" content="imagem.jpg">
<meta property="og:url" content="seu-site.com">
```

3. **Sitemap e Robots** (para sites mais complexos)

## 📧 Formulário de Contato

O formulário é funcional localmente, mas para enviar emails realmente, você precisa:

### Opção 1: Formspree (Recomendado)
1. Vá para [formspree.io](https://formspree.io)
2. Registre-se com seu email
3. Crie um novo formulário
4. Substitua o `action` do formulário

### Opção 2: EmailJS
1. Vá para [emailjs.com](https://emailjs.com)
2. Configure seu email service
3. Use o script deles no `script.js`

### Opção 3: Backend Próprio
Crie um endpoint em seu servidor para receber os dados do formulário.

## 🎭 Modo Escuro (Dark Mode)

Para ativar o dark mode, descomente no `script.js` e adicione em `styles.css`:

```css
body.dark-mode {
    background: #1a1a2e;
    color: #ffffff;
}

body.dark-mode .navbar {
    background: rgba(26, 26, 46, 0.95);
}

/* ... mais estilos para dark mode */
```

## 📱 Testar Responsividade

Abra o portfólio e:
1. Pressione `F12` (Developer Tools)
2. Clique em "Toggle device toolbar" (Ctrl+Shift+M)
3. Teste em diferentes resoluções

## ⚡ Performance

O portfólio já está otimizado, mas você pode:

1. **Minificar CSS/JS** em produção
2. **Compactar imagens** com [TinyPNG](https://tinypng.com)
3. **Usar CDN** para recursos externos
4. **Lazy loading** de imagens (código já incluído)

## 🐛 Troubleshooting

**Problema:** Menu não abre no mobile
- Verifique se `script.js` está carregado

**Problema:** Cores não aparecem
- Limpe o cache do navegador (Ctrl+Shift+Delete)

**Problema:** Ícones não aparecem
- Verifique a conexão com Font Awesome

**Problema:** Formulário não funciona
- Configure um serviço como Formspree ou EmailJS

## 📚 Recursos Úteis

- [Font Awesome Icons](https://fontawesome.com/icons)
- [Google Fonts](https://fonts.google.com)
- [CSS Gradients](https://cssgradient.io)
- [Animation Generator](https://animista.net)
- [GitHub Pages Docs](https://pages.github.com)

## 📞 Suporte

Para dúvidas ou melhorias, consulte a documentação de cada serviço ou customize conforme sua necessidade.

---

**Desenvolvido com ❤️ para profissionais de T.I**

Boa sorte em sua jornada profissional! 🚀
