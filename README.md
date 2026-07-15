# Valura — site institucional

Site one-page da Valura (saúde baseada em valor), na identidade **Cálice Solar**.
Estático, sem dependências (HTML/CSS/JS inline, SVG). Pronto para GitHub Pages.

## Arquivos
- `index.html` — o site (documento completo, autossuficiente).
- `favicon.svg` — a marca (Cálice Solar) para a aba/atalho.
- `.nojekyll` — desliga o Jekyll no GitHub Pages (servimos HTML puro).

## Publicar no GitHub Pages
1. Criar repositório (ex.: `valura-site`) e enviar estes arquivos ao branch `main`.
2. Settings → Pages → Source: `Deploy from a branch` → `main` / `/ (root)`.
3. Em ~1 min o site fica em `https://<usuario>.github.io/valura-site/`.

## Domínio próprio (opcional)
- Comprar `valura.health` (ou similar).
- Settings → Pages → Custom domain: `valura.health`.
- No DNS do domínio, apontar `CNAME`/`A` para o GitHub Pages.

## Notas
- Site público desde 2026-07-15: `noindex` e selo "Versão preliminar" removidos (aprovação do Dr. Igor). O Academy (`/academy`) segue com `noindex` + "Versão preliminar" até a Fase 2.
- Contato `contato@valura.health` é placeholder até registrar o domínio/e-mail.
