# Plano de Desenvolvimento - Landing Page para Larissa (Copywriter)

## Informações do Projeto
- **Profissional:** Larissa - Especialista em Copywriting
- **Objetivo:** Converter visitantes em leads/clientes através de uma copy persuasiva e design moderno
- **Arquivos disponíveis:** 
  - `images/foto1.png`
  - `images/foto2.jpg`
  - `images/foto3.jpg`

## Estrutura HTML Semântica

### 1. Header (`<header>`)
- Logotipo: "Larissa Copy" ou marca pessoal
- Menu de navegação: Início, Portfólio, Serviços, Contato
- Mobile: menu hambúrguer com CSS puro

### 2. Hero Section (`<section class="hero">`)
- **Título (h1):** "Palavras que Convertem | Copywriting Estratégico"
- **Subtítulo:** "Transforme visitantes em clientes com textos persuasivos que vendem seu produto ou serviço"
- **Call-to-action:** "Quero Vender Mais" (botão para formulário)
- **Imagem de destaque:** `foto1.png` - Foto profissional da Larissa (lado direito no desktop, abaixo no mobile)
- **Diferencial:** selo com "+100 clientes atendidos" ou similar

### 3. Seção "Quem é Larissa" (`<section class="about">`)
- **Título (h2):** "A Copywriter que dá voz ao seu negócio"
- **Texto persuasivo:** 
  - Formação/experiência
  - Cases de sucesso
  - Metodologia própria
- **Imagem:** `foto2.jpg` - Larissa trabalhando ou foto estilizada (posicionamento alternado com texto)
- **Grid:** 2 colunas (texto | imagem)

### 4. Seção "Como Posso Ajudar" (`<section class="services">`)
**3 serviços principais (cards):**
- **Card 1:** Copy para Landing Pages
- **Card 2:** E-mails de Marketing
- **Card 3:** Copy para Redes Sociais
- **Bônus:** Cada card com ícone, descrição e "Saiba mais"
- **Layout:** Grid responsivo (1x3 → 2x2 → 1x1)

### 5. Portfólio/Resultados (`<section class="portfolio">`)
- **Título (h2):** "Resultados que Falam por Si Mesmos"
- **Diferenciais numéricos:**
  - +245% de conversão em média
  - +50 clientes satisfeitos
  - 98% de recomendação
- **Imagem de prova social:** `foto3.jpg` - Print de resultado ou foto com clientes
- **Depoimentos:** 2-3 clientes com nome, empresa e resultado

### 6. Seção "Convite para Ação" (`<section class="cta">`)
- **Texto:** "Pronta para decolar suas vendas?"
- **Subtítulo:** "Vamos conversar sobre como a copy certa pode transformar seu negócio"
- **Botão principal:** "Agendar Consultoria Gratuita"
- **Botão secundário:** "Ver Portfólio"

### 7. Contato/Newsletter (`<section class="contact">`)
- **Título:** "Receba Dicas de Copy Poderosas"
- **Lead magnet:** "Inscreva-se e ganhe um eBook com '10 Gatilhos Mentais que Vendem'"
- **Formulário:** Nome, E-mail, botão "Quero Aprender"

### 8. Footer (`<footer>`)
- Links rápidos (Home, Serviços, Contato)
- Redes sociais: Instagram, LinkedIn, E-mail
- Copyright: "© 2024 Larissa Copy - Todos os direitos reservados"
- Selo de garantia ou destaque profissional

## Técnicas CSS Modernas

### Reset e Variáveis
```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

:root {
  --primary: #d946ef;    /* Rosa vibrante (marca pessoal) */
  --secondary: #8b5cf6;  /* Roxo */
  --dark: #18181b;       /* Dark elegante */
  --light: #faf5ff;      /* Roxo claro */
  --gray: #71717a;
  --text: #3f3f46;
  --white: #ffffff;
}

body {
  font-family: 'Inter', system-ui, -apple-system, sans-serif;
  line-height: 1.6;
  color: var(--text);
  scroll-behavior: smooth;
}