# Componentes
O sistema StormTech é composto por quatro principais componentes, cada um desempenhando um papel crucial na funcionalidade global da plataforma:

1. **Módulo de Interface:**
    - Responsável pela apresentação e interação do usuário com o sistema.
    - Inclui a interface gráfica do usuário (GUI) e elementos de navegação.
    - Integra-se aos módulos de Usuários, Produtos e Transações.

2. **Módulo de Usuários:**
    - Representa todos os usuários que interagem com a plataforma StormTech.
    - Inclui clientes que realizam compras e lojas parceiras que cadastram e vendem produtos.
    - Autenticação segura e controle de acesso são implementados para garantir a segurança da plataforma.

3. **Módulo de Produtos:**
    - Compreende o catálogo de produtos disponíveis na plataforma.
    - Inclui informações detalhadas sobre cada produto, como descrição, preço e disponibilidade.
    - Relaciona-se diretamente com os usuários para facilitar a busca, seleção e compra de produtos.

4. **Módulo de Transações:**
    - Gerencia o processo de compra e venda entre usuários e lojas parceiras.
    - Inclui funcionalidades de carrinho de compras, métodos de pagamento e confirmações de transações.
    - Integra-se ao módulo de Produtos para atualização de inventário e informações de transações.

Esses componentes interagem harmoniosamente para fornecer uma experiência completa de compras e vendas online no StormTech. O Módulo de Interface facilita a interação do usuário com os Produtos e as Transações, enquanto o Módulo de Usuários desempenham papéis distintos na dinâmica do sistema. Essa arquitetura modular promove eficiência e escalabilidade na plataforma.

# Protocolos e APIs
1. **AwesomeAPI - Economia:**
    - **Descrição:** Uma API especializada em fornecer serviços de conversão de moedas.
    - **Utilização no StormTech:** Integrada para possibilitar a exibição de preços em diferentes moedas, proporcionando uma experiência internacional aos usuários.

2. **API Mercado Pago:**
    - **Descrição:** Plataforma de pagamento online utilizada para processar transações financeiras de forma segura.
    - **Utilização no StormTech:** Integração vital para facilitar métodos de pagamento diversos, como cartão de crédito, boleto, entre outros, oferecendo opções variadas aos usuários.

3. **HTTPS:**
    - **Descrição:** Protocolo de Transferência de Hipertexto Seguro, garantindo a comunicação segura entre o navegador do usuário e o servidor.
    - **Utilização no StormTech:** Assegura a integridade e confidencialidade das informações transmitidas durante todas as interações, incluindo transações financeiras.

4. **Criptografia TLS:**
    - **Descrição:** Protocolo de Segurança de Transporte utilizado para criptografar dados transmitidos pela internet.
    - **Utilização no StormTech:** Implementado em conjunto com o HTTPS para garantir a segurança das informações durante a comunicação online, prevenindo a interceptação não autorizada.

5. **API Interna do Backend:**
    - **Descrição:** Interface de programação de aplicativos para comunicação interna entre os componentes do backend do StormTech.
    - **Utilização no StormTech:** Facilita a integração e a troca de dados entre os diversos módulos, como Usuários, Produtos e Transações, assegurando a coesão e eficiência do sistema.