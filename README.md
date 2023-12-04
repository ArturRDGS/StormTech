# Stormtech
**Nome do Grupo:** ArchStorm <br/>
**Disciplina:** Engenharia de Software III <br/>
**Professor:** Cléber Araujo


## Alunos
| Matrícula   | Aluno             |
|-------------|-------------------|
| 2022123TADS0012   | Artur Rodrigues Severo  |
| 2022123TADS0039   | Fabrício Andrade Sousa  |
| 2022123TADS0292   | Henrique Ferreira Alves |
| 2022132TADS0284   | Iago da Silva Amorim    |
| 2022123TADS0390   | Maria Milleny Teixeira Mesquita |

## Sobre
O projeto StormTech é uma plataforma de comércio eletrônico projetada para facilitar a interação entre consumidores e lojas parceiras. Essa aplicação web oferece uma experiência de compra intuitiva e eficiente, conectando usuários a uma variedade de produtos oferecidos por diferentes lojas.

- **Objetivos Principais:**
    - Facilitar Compras Online: Proporcionar aos usuários uma plataforma amigável e intuitiva para explorar e comprar produtos de diversas categorias.

    - Suporte a Lojas Parceiras: Permitir que lojas parceiras cadastrem e gerenciem seus produtos, ampliando sua presença online e alcançando um público mais amplo.

    - Segurança e Confiabilidade: Garantir transações seguras, protegendo informações sensíveis dos usuários e mantendo a confiabilidade em todas as interações.

- **Principais Recursos:**
    - Navegação Intuitiva: Interface de usuário projetada para facilitar a navegação, pesquisa e compra de produtos.

    - Gestão de Lojas: Painel administrativo para lojas parceiras gerenciarem seu catálogo de produtos, pedidos e informações.

    - Carrinho de Compras: Funcionalidade para adicionar e revisar produtos antes de concluir a compra.

    - Autenticação Segura: Sistema de autenticação robusto para proteger informações do usuário e permitir transações seguras.

### Tecnologias Utilizadas:
O StormTech é construído utilizando uma arquitetura MVC, adotando tecnologias modernas para garantir desempenho, segurança e escalabilidade. Bancos de dados relacionais, APIs de pagamento e protocolos seguros estão entre os elementos-chave para o sucesso desta aplicação.

## Screenshots
![Screenshot 1](URL_da_Imagem_1)
![Screenshot 2](URL_da_Imagem_2)
![Screenshot 3](URL_da_Imagem_3)

## Instalação
- **Tecnologias:** MKDocs

Para rodar o projeto do MKDocs em seu computador, o MKDocs necessita de algumas dependências para rodar normalmente, algumas extensões.

 1. Instalando MKDocs
```bash
pip install mkdocs
```

2. Instalando dependências do MKdocs
```bash
pip install pymdown-extensions --force
```


## Uso
Abra a pasta do projeto e inicie o servidor do projeto
```bash
mkdocs serve
```
Caso esteja rodando em sistema Windows este é o comando:
```bash
python -m mkdocs serve
```



## Vídeo
Adicione 1 ou mais vídeos demonstrando a execução do projeto final.

## Principal(is) Metodologia(s) Adotada(s)
- Scrum: Metodologia ágil amplamente utilizada para o gerenciamento de projetos. Baseado em iterações curtas chamadas "sprints", o Scrum promove a colaboração e a entrega incremental, enfocando a adaptabilidade e a eficiência na execução de projetos.

## Principais Linguagens Utilizadas e/ou Pretendidas
- JavaScript
- TypeScript
- **Frameworks:**
    - React
    - Nest

## Principais Tecnologias Utilizadas e/ou Pretendidas
- React
- Nest
- PostgreSQL

## Principal(is) Estilo(s) Arquitetural(is) Adotado(s)
- MVC: Arquitetura Model-View-Controller

## O Projeto está rodando?
( ) SIM (x) NÃO


## Introdução

Este repositório é dedicado ao projeto StormTech, uma plataforma de comércio eletrônico. Aqui, você encontrará recursos relacionados ao desenvolvimento e manutenção do projeto. Explore os elementos estruturais, documentação e recursos utilizados na aplicação. Este espaço visa facilitar a colaboração e contribuições para aprimorar continuamente o StormTech. Utilize-o para explorar, relatar problemas ou propor alterações. Agradecemos pela sua participação no desenvolvimento do StormTech.

## Tecnologia

A geração do site estático é realizada utilizando o [MkDocs](https://www.mkdocs.org/).

> "MkDocs is a fast, simple and downright gorgeous static site generator that's geared towards building project documentation."

### Instalando o MkDocs

Para instalar o MkDocs, você pode executar o comando:

```shell
pip install mkdocs
```

Para mais detalhes, consulte o [Guia de Instalação](#).

# Criando um Novo Projeto

Começar é super fácil. Para criar um novo projeto, execute o seguinte comando a partir da linha de comando:

```shell
mkdocs new meu-projeto
cd meu-projeto
```

Dê um momento para revisar o projeto inicial que foi criado para você.

## Estrutura Inicial do MkDocs

Existe um único arquivo de configuração chamado `mkdocs.yml` e uma pasta chamada `docs`, que conterá os arquivos de origem da sua documentação (o valor padrão para a configuração `docs_dir` é `docs`). No momento, a pasta `docs` contém apenas uma página de documentação, chamada `index.md`.

O MkDocs vem com um servidor de desenvolvimento integrado que permite visualizar sua documentação enquanto você trabalha nela. Certifique-se de estar no mesmo diretório do arquivo de configuração `mkdocs.yml` e, em seguida, inicie o servidor executando o comando `mkdocs serve`:

```shell
$ mkdocs serve
```

```shell
INFO    -  Construindo documentação...
INFO    -  Limpando o diretório do site
INFO    -  Documentação construída em 0.22 segundos
INFO    -  [15:50:43] Observando alterações nos caminhos: 'docs', 'mkdocs.yml'
INFO    -  [15:50:43] Servindo em http://127.0.0.1:8000/
```

Abra [http://127.0.0.1:8000/](http://127.0.0.1:8000/) no seu navegador, e você verá a página inicial padrão sendo exibida:

![O servidor MkDocs ao vivo](http://127.0.0.1:8000/)

O servidor de desenvolvimento também suporta recarregamento automático e reconstruirá sua documentação sempre que algo no arquivo de configuração, diretório de documentação ou diretório do tema for alterado.

Abra o documento `docs/index.md` no seu editor de texto preferido, altere o título inicial para "MkLorum" e salve suas alterações. Seu navegador recarregará automaticamente e você verá sua documentação atualizada imediatamente.

Agora tente editar o arquivo de configuração: `mkdocs.yml`. Altere a configuração `site_name` para "MkLorum" e salve o arquivo.

```yaml
site_name: MkLorum
site_url: https://example.com/
```
