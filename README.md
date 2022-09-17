# desafio-dio-e-commerce

## Desafio
O desafio consiste em refinar o diagrama *Entidade-Relacionamento* criado em aula, adicionando como atributo de uma tabela existente<br/>
ou como entidade, os tipos de cliente(PF ou PJ), as formas de pagamento e a entrega.

### Produto
- Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros).
- Cada produto possui um fornecedor
- Um ou mais produtos podem compor um pedido

### Cliente
- O cliente pode se cadastrar no site com seu CPF ou CNPJ
- O Endereço do cliente irá determinar o valor do frete
- Um cliente pode comprar mais de um pedido. Este tem um período
de carência para devolução do produto

### Pedido
- Os pedidos são criados por clientes e possuem informações de
compra, endereço e status da entrega
- Um produto ou mais compõem o pedido
- O pedido pode ser cancelado

### Refinando
- Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não
pode ter as duas informações
- Pagamento – Pode ter cadastrado mais de uma forma de
pagamento
- Entrega – Possui status e código de rastreio
