# 🎨 Paleta de Cores - Tema Rústico

## Cores Utilizadas

A paleta foi atualizada para um tema rústico e masculino com cores mais elegantes e profissionais:

### Cores Principais

| Cor | Código | Uso |
|-----|--------|-----|
| **Marrom Principal** | `#8B6F47` | Botões, destaques, links |
| **Marrom Escuro** | `#6B5637` | Hover dos botões |
| **Marrom Claro** | `#A0835C` | Variações e alternativas |
| **Azul Escuro** | `#1F3A5F` | Complemento secundário |
| **Azul Médio** | `#2C5282` | Elementos interativos |
| **Preto Profundo** | `#1a1a1a` | Texto e footer |
| **Cinza Escuro** | `#2d2d2d` | Elementos secundários |

### Cores de Fundo

| Cor | Código | Uso |
|-----|--------|-----|
| **Bege Claro** | `#f5f2ed` | Background principal |
| **Bege Médio** | `#ede9e0` | Seções alternadas |
| **Cinza Claro** | `#e8e4dd` | Elementos secundários |
| **Branco** | `#ffffff` | Cards e elementos destacados |

### Cores de Estado

| Cor | Código | Uso |
|-----|--------|-----|
| **Sucesso** | `#2d5016` | Mensagens positivas |
| **Erro/Perigo** | `#7a2e2e` | Avisos e erros |
| **Aviso** | `#8B6F47` | Atenção |

## Gradientes Utilizados

### Gradiente Principal (Marrom → Azul)
```css
background: linear-gradient(135deg, #8B6F47 0%, #1F3A5F 100%);
```
Usado em:
- Títulos das seções
- Botões primários
- Cards com hover
- Barras de progresso
- Botão scroll-to-top

### Gradiente Secundário (Azul)
```css
background: linear-gradient(135deg, #1F3A5F 0%, #2C5282 100%);
```
Usado em:
- Cards de projeto
- Card flutuante do hero
- Elementos decorativos

### Gradiente Timeline
```css
background: linear-gradient(180deg, #8B6F47 0%, #1F3A5F 100%);
```
Usado na:
- Linha da timeline de experiência

## Sombras

### Sombra Padrão
```css
box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
```

### Sombra Grande (hover)
```css
box-shadow: 0 20px 50px rgba(0, 0, 0, 0.3);
```

### Sombra de Botão
```css
box-shadow: 0 10px 25px rgba(139, 111, 71, 0.3);
```

## Paleta Visual Completa

```
┌─────────────────────────────────────────────────┐
│                  MARROM - #8B6F47                │
│        Cor primária, botões, destaques           │
└─────────────────────────────────────────────────┘
        ↓                           ↓
   ┌─────────────┐          ┌──────────────┐
   │   Escuro    │          │    Claro     │
   │ #6B5637     │          │  #A0835C     │
   └─────────────┘          └──────────────┘

┌─────────────────────────────────────────────────┐
│              AZUL - #1F3A5F / #2C5282           │
│         Complemento, cards, elementos            │
└─────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────┐
│               NEUTROS - Bege/Cinza              │
│   Backgrounds, espaços em branco, suportes       │
└─────────────────────────────────────────────────┘
```

## Harmonia das Cores

A paleta segue os princípios de design rústico:

1. **Marrom como âncora** - Transmite profissionalismo, confiança e experiência
2. **Azul como complemento** - Adiciona frescor, modernidade e credibilidade
3. **Neutros como suporte** - Bege e cinza mantêm a elegância e clareza
4. **Preto para contraste** - Garante legibilidade e hierarquia visual

## Como Customizar as Cores

Se desejar alterar as cores, edite o arquivo `styles.css` na seção `:root`:

```css
:root {
    --primary: #8B6F47;           /* Marrom principal */
    --primary-dark: #6B5637;      /* Marrom escuro */
    --primary-light: #A0835C;     /* Marrom claro */
    --secondary: #1F3A5F;         /* Azul escuro */
    --accent: #2C5282;            /* Azul médio */
    /* ... mais cores */
}
```

Depois atualize os gradientes específicos nos componentes necessários.

## Sugestões de Paletas Alternativas

### Opção 1: Mais Escuro (Premium)
```css
--primary: #6B5637;       /* Marrom escuro */
--secondary: #0F1F2E;     /* Azul muito escuro */
```

### Opção 2: Mais Quente (Terroso)
```css
--primary: #9B7563;       /* Marrom terroso */
--secondary: #8B4513;     /* Marrom avermelhado */
```

### Opção 3: Mais Frio (Tech Moderno)
```css
--primary: #2C5282;       /* Azul principal */
--secondary: #1F3A5F;     /* Azul escuro */
--accent: #8B6F47;        /* Marrom como suporte */
```

---

**Atualizado:** Dezembro 2025
**Tema:** Rústico Profissional Masculino
