# Avaliacao-PRS
Avaliação prática para desenvolvedor.

Imagine um cenário onde um determinado cliente precisa apenas gerenciar seus produtos e suas vendas.
Desenvolva um sistemas web para atender as necessidades desse cliente.

# Nomes das tabelas: Usuario, Produto, Venda, ProdutoVenda.
# Rotas de back-end: Autenticação, Produto, Venda.
# Telas do front-end: Login, Home, Produto, Venda.

Tabela Usuario:
- id
- usuario
- senha

Tabela Produto:
- id
- nome
- quantidade
- valor

Tabela Venda:
- id

Tabela ProdutoVenda:
- id
- idProduto
- idVenda

Observações:
- As operações de Produto e Venda, precisam ser operações CRUD (create, update e delete).
- Operação de login, apenas uma autenticação simples de usuário.
- Preferência para back-end: API feita em .NET Core com EF. Core.
- Preferência para front-end: Angular.
