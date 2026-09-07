# Style
## 1. Organização da Arquitetura CSS

```text
css/
├── base/          # Fundações globais (variáveis, tokens e normalização de reset)
├── layout/        # Áreas estruturais da página (cabeçalho, rodapé e menus laterais)
├── components/    # Blocos reutilizáveis independentes (botões, cards, tabelas, etc.)
└── feedback/      # Estados de resposta assíncrona (alertas, diálogos e telas vazias)
```

## 2. Estrutura interna das Pastas

```text
├── css/
│   ├── variables.css          # Variáveis globais (cores, tipografia, espaçamentos, raios)
│   ├── reset.css              # Reset de box-sizing e margens padrão
│   │
│   │  /* Componentes Estruturais e Globais */
│   ├── navigation.css         # .header-nav, .header-nav--public, .header-nav--admin
│   ├── footer.css             # .footer, .footer__tags, .footer__copyright
│   ├── sidebar.css            # .sidebar-nav, .sidebar-nav__link--active
│   │
│   │  /* Componentes de Conteúdo e Apresentação */
│   ├── hero-banner.css        # .hero-banner, .hero-banner__title, .hero-banner__actions
│   ├── heading.css            # .section-heading, .section-heading--query
│   ├── card.css               # .card, .card--grid, .card--list, .card--featured
│   ├── stat-card.css          # .stat-card, .stat-card__metric, .admin-stats-grid
│   │
│   │  /* Elementos de Formulário e Ações */
│   ├── button.css             # .button, .button--primary, .button--secondary, .button--action
│   ├── form.css               # .form, .form--login, .form--register, .form--post-editor
│   ├── input.css              # .form-field, .form-field__input, .form-field__textarea
│   │
│   │  /* Componentes de Apoio e Moderação */
│   ├── tag-chip.css           # .tag-chip, .tag-chip--card, .tag-chip--filter
│   ├── table.css              # .data-table, .data-table__row, .data-table__actions
│   ├── badge.css              # .badge-status, .badge-status--active, .badge-status--pending
│   ├── avatar.css             # .user-avatar, .user-avatar--large
│   │
│   │  /* Estados Dinâmicos e Overlays */
│   ├── alert.css              # .alert, .alert--success, .alert--error
│   ├── modal.css              # .modal, .modal--confirm-delete, .modal--confirm-action
│   ├── pagination.css         # .pagination, .pagination__load-more
│   └── empty-state.css        # .empty-state, .empty-state__description
```