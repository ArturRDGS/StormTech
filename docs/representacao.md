# Representação Arquitetural

## 1. Visão de Casos de Uso:

- **Elementos de Modelo:**
    - **Ator:** Cliente, Vendendor, Funcionario, Administrador
    - **Caso de Uso:** "Realizando compra", "Contas" , "Pesquisando produtos", "Suporte", "Acompanhamento do produto".

## 2. Visão Lógica:

- **Elementos de Modelo:**
    - **Classe:** Cliente, Pedido, Funcionario, Empresa, Carrinho, Produto, Pedido, Avaliacao e Pergunta.
    - **Relacionamentos:**   <br/>
        - `Cliente` herda a interface `Pessoa` <br/>
        - `Funcionario` herda a interface `Pessoa`  <br/>
        - `Pergunta` possue uma associação com `Cliente`  <br/>
        - `Pergunta` possue uma associação com `Empresa`  <br/>
        - `Empresa` possue uma associação com `Funcionario` <br/>
        - `Produto` possue uma associação com `Empresa`  <br/>
        - `Produto` possue uma associação com `Avalicao`  <br/>
        - `Cliente` possue uma associação com `Carrinho` <br/>
        - `Carrinho` possue uma associação com `Produto` <br/>
        - `Carrinho` possue uma associação com `Pagamento` <br/>
        - `Cliente` possue uma associação com `Pedido` <br/>
        - `Pedido` possue uma associação com `Produto`  <br/>

## 3. Visão de Processos:

- **Elementos de Modelo:**
    - **Diagrama de Sequência:** Representação de interações entre objetos ao longo do tempo.
    - **Diagrama de Atividades:** Avaliação, Cadastrar produto, Comprando produto e Suporte.
