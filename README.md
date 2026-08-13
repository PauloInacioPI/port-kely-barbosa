# Portfólio — Kely Barbosa

Site de página única da Kely Barbosa, especialista em coloração em
Santo Antônio de Pádua (RJ).

## Estrutura

```
docs/
├─ index.html          # marcação da página
├─ css/
│  └─ style.css        # todo o estilo (variáveis, layout, responsivo)
└─ assets/
   └─ img/
      ├─ kely-hero.webp
      ├─ kely-sobre.webp
      └─ portfolio-01..06.webp
```

O site é estático: não há build, dependências nem JavaScript. As animações de
entrada usam apenas CSS (`animation-timeline: view()`, com degradação suave em
navegadores sem suporte) e respeitam `prefers-reduced-motion`.

## Rodando localmente

Abra `docs/index.html` no navegador, ou sirva a pasta:

```bash
npx serve docs
```

## Publicação

Publicado pelo GitHub Pages a partir da branch `main`, pasta `/docs`
(Settings → Pages → Source: Deploy from a branch).
