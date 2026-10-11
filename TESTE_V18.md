# Roteiro de teste V18

## Teste 1 — Check 360
Usuário: ana / 1234
- P00140
- Origem: Extrema
- Transportadora: Transportadora Demo
- Quantidade: 1
- Resultado: OK
- Registrar
Esperado: Check registrado por Ana + demanda OPEN criada.

## Teste 2 — Guarda
Sair e entrar como joao / 1234.
- Operação
- Usar demanda P00140
- Confirmar guarda
Esperado: Guarda confirmada por João, endereço A03-02-05, evento GUARD_CONFIRMADA.

## Teste 3 — Bloqueio de função
Com joao tente abrir Check 360.
Esperado: acesso restrito.

## Teste 4 — Rastreabilidade
Dados → pesquisar P00140.
Esperado: histórico com Ana no Check 360 e João na Guarda.

## Teste 5 — Exceção
ana → P00126 → RETRABALHO.
Depois joao → Operação → tentar guardar P00126.
Esperado: bloqueio por falta de demanda/liberação.
