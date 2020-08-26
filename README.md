# 💸 Desafio 005: NodeJs - Transações

## Conceito: 
  - API consiste em cadastrar e listar transações financeiras.

## Rotas da aplicação

- **```POST /transactions```**: A rota receber ```title```, ```value``` e ```type``` dentro do corpo da requisição, sendo ```type``` o tipo da transação, que deve ser ```income``` para entradas (depósitos) e ```outcome``` para saídas (retiradas).

- **```GET /transactions```**: retorna uma listagem com todas as transações cadastradas, junto com o valor de soma de entradas, retiradas e total de crédito.
