# OPERA WMS V18 — Mobile Standalone

Evolução da V17 com foco em operação, rastreabilidade e visibilidade.

## Novidades V18
- Torre de Controle inicial com indicadores.
- Perfis e permissões visíveis; usuário não acessa função de outro perfil.
- Botão Sair/trocar usuário.
- Check 360 com quantidade, origem, transportadora, resultado, observação e registro de responsável.
- Estrutura para evidências/fotos.
- Operação com demandas de guarda, lote, quantidade, validade e filtro por mês.
- FEFO/slotting e validação de endereço.
- Guarda registra responsável, data/hora, endereço e evento de auditoria.
- Dados com indicadores, gráfico simples, pesquisa e rastreabilidade.
- Mapa 2D de posições e visualização 3D operacional preparada para estrutura real.
- Backup/importação JSON.
- PWA instalável no iPhone/Android quando publicado via HTTPS.

## Usuários de teste
- joao / 1234 — OPERADOR
- ana / 1234 — CHECK360
- maria / 1234 — SUPERVISOR
- admin / 1234 — ADMIN

## Processo completo recomendado
1. Entre como `ana`.
2. Check 360 → P00140 → OK → registrar.
3. Sair.
4. Entre como `joao`.
5. Operação → selecione demanda P00140 → usar demanda → confirmar guarda.
6. Sair.
7. Entre como `maria` e abra Dados.
8. Pesquise P00140 e confira responsável pelo Check e pela Guarda.

## Importante
Esta versão é standalone/local: os dados ficam no navegador do aparelho. Ela não é integração real com WMS. Para sincronização corporativa e integração WMS será necessário um backend/adapter oficial.
