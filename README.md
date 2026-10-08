# OPERA WMS V17 — Mobile Standalone

Versão independente para testes diretamente no celular.

## Objetivo
A V17 remove a dependência de Docker/PostgreSQL/FastAPI para a operação básica no dispositivo.

A aplicação usa:
- PWA instalável
- IndexedDB para dados locais
- funcionamento offline
- fila de sincronização
- câmera para leitura de código quando o navegador suportar BarcodeDetector
- FEFO
- endereçamento
- Check 360
- demandas
- guarda
- evidências
- produtividade
- mapa
- exportação/importação JSON para backup local

## Instalação
### iPhone
1. Abra a aplicação hospedada em HTTPS no Safari.
2. Compartilhar → Adicionar à Tela de Início.
3. Abra o ícone OPERA.

### Android
1. Abra a aplicação em Chrome.
2. Menu → Instalar aplicativo / Adicionar à tela inicial.

> Para instalação PWA em iPhone/Android, a aplicação precisa estar publicada em HTTPS. Um ZIP não pode ser instalado diretamente como aplicativo.

## Dados de demonstração
- joao / 1234 — OPERADOR
- ana / 1234 — CHECK360
- maria / 1234 — SUPERVISOR
- admin / 1234 — ADMIN

Os dados da V17 ficam no aparelho. A sincronização com WMS real exige um servidor/API oficial posteriormente.
