# notification-service

Parte do projeto **Tigrinho Trader** (disciplina Projeto de Software).

## Finalidade

Servico opcional (4o servico). Consome eventos de ordem executada e saldo atualizado para gerar notificacao, ranking e historico de atividade do usuario.

## Como interage com os outros servicos

- Consome (assincrono, via fila): eventos `ordem.executada` (do trading-service) e eventos de saldo (do wallet-service).
- Exposto (sincrono, via API Gateway): leitura de notificacoes/ranking pro frontend.

## Repositorios do projeto

- [trading-service](https://github.com/tigrinho-trader/trading-service)
- [wallet-service](https://github.com/tigrinho-trader/wallet-service)
- [market-data-service](https://github.com/tigrinho-trader/market-data-service)
- [api-gateway](https://github.com/tigrinho-trader/api-gateway)
- [frontend](https://github.com/tigrinho-trader/frontend)
- [docs-arquitetura](https://github.com/tigrinho-trader/docs-arquitetura)
