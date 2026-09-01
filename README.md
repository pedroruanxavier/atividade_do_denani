## 🛠️ Como Aplicar no Projeto (CSS Variables)

Você pode declarar essas variáveis diretamente no seu arquivo global de estilos (`styles.css` ou `variables.css`):

```css
:root {
  /* --- Cores Primárias --- */
  --color-primary-light: #FF8133;
  --color-primary: #FF6200;
  --color-primary-dark: #CC4E00;

  /* --- Cores Secundárias --- */
  --color-secondary-light: #539AE9;
  --color-secondary: #1866BE;
  --color-secondary-dark: #267FE3;

  /* --- Tons Dark --- */
  --color-dark-deep: #0B0A0A;
  --color-dark-main: #262323;
  --color-dark-subtle: #403B3B;

  /* --- Tons Light --- */
  --color-light-border: #D3DDE4;
  --color-light-bg: #F2F5F7;
  --color-light-white: #FFFFFF;

  /* --- Cores de Status --- */
  --color-success-light: #2FC63E;
  --color-success: #52D65F;
  --color-success-dark: #7BE085;

  --color-danger-dark: #9E1500;
  --color-danger: #D11C00;
  --color-danger-light: #FF2705;

  /* --- Tipografia --- */
  --font-family-main: 'Poppins', sans-serif;
  --font-size-h1: 40px;
  --font-size-h2: 34px;
  --font-size-h3: 28px;
  --font-size-h4: 24px;
  --font-size-h5: 18px;
  --font-size-body: 16px;
  --font-size-small: 14px;
}
```

---

## 📂 Estrutura Sugerida do Projeto

```text
├── assets/
│   ├── fonts/
│   │   └── Poppins/
│   └── images/
├── css/
│   ├── variables.css      # Declaração das CSS Variables
│   ├── typography.css     # Regras de escala tipográfica (H1-H5, Body, Small)
│   ├── colors.css         # Utilitários de cores e contraste
│   └── style.css          # Estilos gerais e layout/centralização
├── README.md              # Documentação oficial do Design System
└── index.html             # Página de demonstração dos componentes
```

---

## 📜 Licença e Créditos

Desenvolvido como parte do trabalho prático sobre **Fundamentos Visuais de UI/UX**, englobando:
- Base Tipográfica com a fonte *Poppins*
- Teoria e Harmonia das Cores
- Avaliação de Contraste e Acessibilidade (WCAG)
- Princípios de Centralização e Grid Layout