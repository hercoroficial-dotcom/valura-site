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
- `<meta name="robots" content="noindex">` está ativo: o site é compartilhável por link, mas não é indexado por buscadores. Remover quando quiser torná-lo público de fato.
- Rodapé marcado como "Versão preliminar" — remover na aprovação.
- Contato `contato@valura.health` é placeholder até registrar o domínio/e-mail.
