# OPERA WMS V17 — Pacote de Publicação

Pacote pronto para hospedar como PWA estático.

### Conteúdo principal
- `index.html` — aplicação
- `manifest.webmanifest` — configuração PWA
- `sw.js` — cache/offline
- `icons/` — ícones PWA/iPhone
- `.github/workflows/deploy.yml` — publicação automática no GitHub Pages
- `.nojekyll` — publicação estática
- `PUBLICACAO_GITHUB_PAGES.md` — passo a passo

### Limitação atual
A V17 continua standalone: os dados ficam no dispositivo. Não há servidor remoto nem integração real com WMS nesta versão.
