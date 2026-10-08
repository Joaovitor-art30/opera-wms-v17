# OPERA WMS V17 — Publicação

## Objetivo
Este pacote está preparado para publicação como PWA estático em HTTPS.

## GitHub Pages
1. Crie um repositório no GitHub, por exemplo `opera-wms-v17`.
2. Envie todo o conteúdo desta pasta para a branch `main`.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment → Source**, selecione **GitHub Actions**.
5. Aguarde a execução do workflow `Publicar OPERA V17`.
6. Abra a URL informada pelo GitHub Pages.

O GitHub Pages publica arquivos estáticos diretamente do repositório. A URL de um projeto normalmente segue o formato `https://SEU_USUARIO.github.io/SEU_REPOSITORIO/`.

## iPhone
Abra a URL publicada no Safari:
**Compartilhar → Adicionar à Tela de Início → ativar “Abrir como App da Web” → Adicionar.**

## Importante
Esta V17 é independente para operação local no aparelho, usando IndexedDB.
A fila de sincronização ainda é local; ela não envia dados para um servidor WMS real.
A integração oficial com WMS continua sendo uma etapa posterior.
