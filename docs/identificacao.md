# Identificação do Projeto

|Projeto | Requisitante | Gerente de Projetos|
| -------| ------------ | -------------------|
|  StormTech | Cleber Araujo | ArchStom |

# Brainstorming 
- Explique e coloque imagens de todas as reuniões do grupo, incluindo explicação de como ocorreu, datas, colaboraçoes, o que foi excluido e acatado na reuinão.  Esta apresentação deve incluir todos os esboços iniciais, ideias e as contribuições de cada membro do grupo, além da lista de frequência e votação.

# Técnicas de Elicatação de Requisitos
- Os requesitos levantados por nossa equipe foram retirados de uma entrevista semiestruturada realizada presencialmente com o nosso cliente e pela análise do contexto do sofrware requerido.
# Requisitos Funcionais 

|Código |Identificação |Classificação |Ator |Objetivo|
|------ |--------------|--------------|-----|--------|
|[RF01] | Melhor sistema |Importante    |Sistema| O sistema deve ser rival e melhor que a Amazon |
|[RF02] |Efetuar Login/Cadastro |Importante    |Usuário| O usuário deve conseguir realizar login/cadastro |
|[RF03] | Dois fatores |Importante    |Sistema| O sistema deve requesitar ao usuário uma confirmação de email |
|[RF04] | Idioma | Não importante |Usuário| O sistema pode permitir o usuário alterar o idoma |
|[RF05] | Redifinir senha |Importante    |Usuário| O sistema deve permitir que o usuário consiga redefinir sua senha pelo e-mail |
|[RF06] | Gerenciar Dados  |Importante    |Usuário| O sistema deve permitir que o usuário altere/adicione seu dados como endereço, métodos de pagamento e dados pessoais |
|[RF07] | Ver catálogo  |Importante    |Usuário| O sistema deve permitir que o usuário veja o catálogo com produtos sugeridos |
|[RF08] | Pesquisa  |Importante    |Usuário| O sistema deve permitir que o usuário consiga pesquisar por produtos específicos |
|[RF09] | Filtros de pesquisa  |Importante    |Usuário| O sistema deve permitir que o usuário configure filtros em suas pesquisas como: avaliações; classificações; mais vendidos; com descontos; entre outros filtros. |
|[RF10] | Detalhes do produto  |Importante    |Usuário| O sistema deve permitir que o usuário consiga ver uma descrição mais específica do produto como ficha técnica, fotos, vídeos e avaliações. |
|[RF11] | Adicionar ao carrinho  |Importante    |Usuário| O sistema deve permitir que o usuário consiga adicionar um ou mais produtos em seu carrinho de compras |
|[RF12] |Remover do carrinho  |Importante    |Usuário| O sistema deve permitir que o usuário consiga remover itens de seu carrinho de compras |
|[RF13] | Calcular preço |Importante    |Usuário| O sistema deve calcular o valor total do carrinho e informar ao cliente |
|[RF14] | Mêtodos de pagamentos  |Importante    |Usuário| O sistema deve permitir que o usuário consiga realizar seus pagamentos por diferentes meios de pagamentos: Pix; Cartão de crédito; Boleto; Cartão de Débitos; PayPal; entre outros; |
|[RF15] | Rastreio  |Importante    |Usuário| O sistema deve disponibilizar ao usuário um código de rastreio para o cliente acompanhar o produto após a compra ser realizada. |
|[RF16] | Confirmar entrega  |Importante    | Usuário| O sistema deve permitir que o usuário consiga confirmar a chegada do produto. |
|[RF17] | Avaliação  | Não importante  |Usuário| O sistema deve permitir que o usuário consiga avaliar o produto com uma nota (1 a 5 estrelas), um descrição da avaliação e anexar fotos/vídeos (não obrigatório). |
|[RF18] | Restrição de links  |Importante    |Sistema| O sistema não deve permitir o uso de links em suas avaliações. |
|[RF19] | Suporte  |Importante    |Usuário| O sistema deve permitir que o usuário consiga entrar em contato com o suporte da empresa. |
|[RF20] | Perguntas frequentes  |Importante    |Usuário| O sistema deve permitir que o usuário visualize as perguntas mais frequentes e suas respostas |
|[RF21] | Compartilhar produtos |Importante    |Usuário| O sistema deve permitir que o usuário visualize as perguntas mais frequentes e suas respostas |
|[RF22] | Cadastrar produto  |Importante    | Vendedor | O sistema deve permitir que os vendedores cadastrem novos produtos no catálogo |
|[RF23] | Empresas de terceiros |Importante    | sistema | O sistema deve permitir que outras empresas consigam cadastrar produtos em seu site. |
|[RF24] | Anexar arquivos  |Importante    | Vendedor | O sistema deve permitir que os vendedores consigam adicionar descrições e anexas arquivos de mídia junto ao cadastro do produto. |
|[RF25] | Respondendo clientes  |Importante    | Vendedor | O sistema deve permitir que os vendedores recebam e consigam responder às dúvidas dos clientes |
|[RF26] | Gerar cumpons  |Importante    | Vendedor | O sistema deve permitir que os vendedores consigam gerar cupons de desconto para seus produtos |
|[RF27] | Descontos  |Importante    | Vendedor | O sistema deve permitir que os vendedores adicione descontos aos seus produtos |
|[RF28] | Gerenciar estoque  |Importante    | Vendedor | O sistema deve permitir que os vendedores controlem a quantidade de estoque dos produtos |
|[RF29] | Confirmar pagamento  |Importante    | Vendedor | O sistema deve permitir que os vendedores confirmem o pagamento dos produtos comprados |
|[RF30] | Adicionar Cod. rastreio  |Importante    | Vendedor | O sistema deve permitir que os vendedores adicione o código de rastreio aos produtos comprados |
|[RF31] | Dados bancários  |Importante    | Vendedor | O sistema deve permitir que os vendedores informem seus dados bancários para receber os pagamentos. |
|[RF32] | Gerar relatórios  |Importante    | Vendedor | O sistema deve permitir que os vendedores gerem relatórios de suas vendas |
|[RF33] | Garantia  |Importante    | Vendedor | O sistema deve permitir que o vendedor adicione garantia aos seus produtos. |

# Requisitos Não Funcionais 
    
|Código |Identificação |Classificação |Ator |Objetivo|
|------ |--------------|--------------|-----|--------|
|[RNF01] | Intuitivo |Importante    |Sistema| O sistema deve ser intuitivo ao usuário|
|[RNF02] | Rápida resposta |Importante    |Sistema| O sistema deve ter o minimo de tempo de resposta |
|[RNF03] | Picos de acessos |Importante    |Sistema| O sistema deve suportar uma grande quantidade de usuários simultâneos |
|[RNF04] | Converção de moedas |Importante    |Sistema| O sistema deve integrar outros sistema para a converção de moedas |
|[RNF05] | Sempre ativo |Importante    |Sistema| O sistema deve sempre está ativo 24/7 |
|[RNF06] | Escalável |Importante    |Sistema| O sistema deve ser escálavel a manunteções  |
|[RNF07] | Segurança |Importante    |Sistema| O sistema deve implementar protocolos de segurança |
|[RNF08] | Ocultar produtos |Importante    |Sistema| O sistema deve ocultar produtos com restrições legais (de acordo com o país) |
|[RNF09] | Recomendações |Importante    |Sistema| O sistema deve integrar outros sistemas de recomendações com os interesses do usuário  |
|[RNF10] | Acessibilidade |Importante    |Sistema| O sistema deve ter suporte para PCD (Pessoa Com Deficiência) |
|[RNF11] | Criptográfia |Importante    |Sistema| O sistema deve transportar os dados com criptrográfia |
|[RNF12] | Fidelidade |Importante    |Sistema| O sistema deve implementar um sistema de fidelidade de usuários |
|[RNF13] | Foco na empresa |Importante    |Sistema| O sistema deve, na parte de sugestões, deve priorizar os produtos da empresa |



<!--
Requisitos funcionais:
Requisitos para usuários
O sistema tem que ser rival e melhor que Amazon; xx
O sistema deve permitir que os usuários façam login/cadastro; xx 
O sistema deve solicitar ao cliente a autenticação de dois fatores por e-mail; xx
O sistema deve permitir que o usuário altere a linguagem do site; xx
O sistema deve permitir que o usuário consiga redefinir sua senha pelo e-mail; xx
O sistema deve permitir que o usuário altere/adicione seu dados como endereço, métodos de pagamento e dados pessoais;
O sistema deve permitir que o usuário veja o catálogo com produtos sugeridos;
O sistema deve permitir que o usuário consiga pesquisar por produtos específicos;
O sistema deve permitir que o usuário configure filtros em suas pesquisas como: avaliações; classificações; mais vendidos; com descontos; entre outros filtros;
O sistema deve permitir que o usuário consiga ver uma descrição mais específica do produto como ficha técnica, fotos, vídeos e avaliações;
O sistema deve permitir que o usuário consiga adicionar um ou mais produtos em seu carrinho de compras ;
O sistema deve permitir que o usuário consiga remover itens de seu carrinho de compras;
O sistema deve calcular o valor total do carrinho e informar ao cliente;
O sistema deve permitir que o usuário consiga realizar seus pagamentos por diferentes meios de pagamentos: Pix; Cartão de crédito; Boleto; Cartão de Débitos; PayPal; entre outros;
O sistema deve disponibilizar ao usuário um código de rastreio para o cliente acompanhar o produto após a compra ser realizada;
O sistema deve permitir que o usuário consiga confirmar a chegada do produto;
O sistema deve permitir que o usuário consiga avaliar o produto com uma nota (1 a 5 estrelas), um descrição da avaliação e anexar fotos/vídeos (não obrigatório);
O sistema não deve permitir o uso de links em suas avaliações;
O sistema deve permitir que o usuário consiga entrar em contato com o suporte da empresa;
O sistema deve permitir que o usuário visualize as perguntas mais frequentes e suas respostas;
O sistema pode permitir que os usuários consigam compartilhar os produtos em rede sociais.



Requisitos para vendedores
O sistema deve permitir que os vendedores cadastrem novos produtos no catálogo;
O sistema deve permitir que outras empresas consigam cadastrar produtos em seu site;
O sistema deve permitir que os vendedores consigam adicionar descrições e anexas arquivos de mídia junto ao cadastro do produto;
O sistema deve permitir que os vendedores recebam e consigam responder às dúvidas dos clientes;
O sistema deve permitir que os vendedores consigam gerar cupons de desconto para seus produtos;
O sistema deve permitir que os vendedores adicione descontos aos seus produtos;
O sistema deve permitir que os vendedores controlem a quantidade de estoque dos produtos;
O sistema deve permitir que os vendedores confirmem o pagamento dos produtos comprados;
O sistema deve permitir que os vendedores adicione o código de rastreio aos produtos comprados;
O sistema deve permitir que os vendedores informem seus dados bancários para receber os pagamentos;
O sistema deve permitir que os vendedores gerem relatórios de suas vendas;
O sistema deve permitir que o vendedor adicione garantia aos seus produtos.



Não funcionais
O sistema deve ser responsivo; xxx
O sistema deve ter o mínimo possível de tempo de resposta; xxx
O sistema deve suportar picos de acesso simultâneos de usuários; xxx
O sistema deve ter integração com meios de pagamentos distintos; xxx
O sistema deve ter integração com outros sistema de cotações de moedas para que o usuário visualize o produto já com a conversão da moeda; xxx
O sistema deve esta disponível 24/7; xxx
O sistema deve ser escalável para futuras manutenções e atualizações; xxx
O sistema deve realizar backups automáticos e armazená los em nuvem; xxx
O sistema deve seguir protocolos para a segurança dos dados dos clientes e vendedores; xxx
O sistema deve ocultar produtos que possuam alguma restrição legal em países específicos ; xxx
O sistema deve integrar algum sistema que informe os interesses do usuário para que o sistema consiga recomendar produtos que o usuário deseja; xxx
O sistema deve ter de acessibilidade para deficientes; xxx
O dados dos usuários devem ser transportados com criptografia; xxx
O sistema deve ter um sistema de fidelidade que garanta o usuários descontos automáticos baseados em sua quantidade de compras na plataforma; xxx
O sistema, na parte de sugestão de produtos, deve focar mais em produtos da própria empresa.
-->