# OPERA WMS V19 — pacote mobile e computador

Protótipo evoluído do V18 para celular e computador. O pacote tenta migrar o estado local `opera_v18_state` para `opera_v19_state` no mesmo navegador; **faça backup antes de publicar**.

## Publicação pelo iPhone
1. No V18, entre em Admin e exporte o backup JSON, se disponível.
2. Baixe e descompacte este ZIP no app Arquivos.
3. No Safari, abra o repositório existente `opera-wms-v17` e escolha Add file → Upload files.
4. Substitua todos os arquivos e mantenha os caminhos, incluindo `index.html`, `manifest.webmanifest`, `sw.js` e `icons/`. Não basta substituir só o HTML.
5. Se o iPhone não permitir selecionar pastas ou preservar os caminhos, não faça commit parcial. Tente modo computador ou use computador autorizado para concluir.
6. Faça commit na branch `main` com mensagem `Atualiza OPERA WMS V19`.
7. Abra `https://joaovitor-art30.github.io/opera-wms-v17/` no Safari, recarregue e confirme o título V19.
8. Preserve o backup do V18 até validar os registros.

Usuários de demonstração: `joao`, `ana`, `maria`, `admin`; senha `1234`.

## Limites
Dados são locais ao navegador; não há sincronização entre dispositivos nem backend corporativo. O WMS continua sendo o estoque oficial e não está conectado. Integração exige interface oficial e homologação. Fotos reais, mapa 3D produtivo, leitor validado, relatórios corporativos e autenticação corporativa ainda exigem desenvolvimento.
