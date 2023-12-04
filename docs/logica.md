# Visão Lógica

## Subsistema: Gestão de Produtos

### Pacote: Produto
- **Classes:**
- `Produto`: Representa um produto na loja.

## Subsistema: Gestão de Pedidos

### Pacote: Pedido
- **Classes:**
- `Pedido`: Representa um pedido feito por um cliente.
- `Produto`: Descreve um item ou mais itens específico em um pedido.
- `Carrinho`: Gerencia os itens no carrinho de compras para transferilas a classe `Pedido`.

## Subsistema: Gestão de Pedidos

### Pacote: Pedido
- **Classes:**
- `Pedido`: Representa um pedido feito por um cliente.
- `Produto`: Descreve um item ou mais itens específico em um pedido.
- `Carrinho`: Gerencia os itens no carrinho de compras.

## Subsistema: Processamento de Pagamento

### Pacote: Pagamento
- **Classes:**
- `Carrinho`: Responsável pela lógica de calcular o preço total.
- `Pagamento`: Define um interface para os meios de pagamento implementados.

## Subsistema: Autenticação e Conta do Cliente

### Pacote: Cliente
- **Classes:**
- `Cliente`: Representa um cliente registrado na loja.

## Subsistema: Gestão de Usuários

### Pacote: Usuário
- **Classes:**
- `Administrador`: Representa um administrador do sistema.
- `Cliente`: Estende a classe de cliente e adiciona funcionalidades específicas para clientes registrados.

## Subsistema: Integração com Logística

### Pacote: Logística
- **Classes:**
- `Pedido`: Armazena o status de envio do pedido e rastreamento.

## Relacionamentos e Atributos

- `Cliente` herda a interface `Pessoa`
- `Funcionario` herda a interface `Pessoa`
- `Pergunta` possue uma associação com `Cliente`
- `Pergunta` possue uma associação com `Empresa`
- `Empresa` possue uma associação com `Funcionario`
- `Produto` possue uma associação com `Empresa`
- `Produto` possue uma associação com `Avalicao`
- `Cliente` possue uma associação com `Carrinho`
- `Carrinho` possue uma associação com `Produto`
- `Carrinho` possue uma associação com `Pagamento`
- `Cliente` possue uma associação com `Pedido`
- `Pedido` possue uma associação com `Produto`  

## Operações Importantes

- `ProcessarPedido` na classe `Cliente`.
- `AdicionarItem` e `RemoverItem` na classe `Carrinho`.
- `AdicionarProduto`,`RemoverProduto`, `AdicionarFuncionario` e `RemoverFuncionario` na classe `Empresa`
- `ResponderSuporte` na classe `Funcionario`
- `CancelarPedido` e `ConfirmarEntrega` na classe `Pedido`