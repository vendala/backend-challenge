# Teste vaga Venda.la - Criação de produtos KIT via API

Este teste visa conhecer um pouco mais da forma em que você programa e como você vai se organizar para montar um produto do tipo KIT.

`
O produto kit nada mais é do que um produto que é composto por outros produtos, por exemplo, "Play Station 4 + 2 Controles + Fifa 2019". Este produto é um produto kit que é composto por 1 produto "Play Station 4" + " + 2 produtos "Controle Play Station 4" + 1  produto "Jogo PS4 Fifa 2019"
`

### Resumo do teste

Você precisa criar uma API em Laravel que vai receber informações de um front-end desacoplado e cadastrar um produto no banco de dados.

### Front-end
##### Tela de Cadastro do produto
Tela em que será preenchido os dados do produto.

 - Nome do produto
 - Categoria (A categoria terá de ser exatamente alguma categoria final do Mercado Livre, ou seja, você precisará utilizar a API de categorias do Mercado Livre e navegar até o seu último nível.)
 - Descrição
 - Preço
 - Imagens
 - KIT

* Fica ao seu critério montar nessa estrutura uma configuração de produto KIT.

##### Tela de listagem dos produtos cadastrados
Tela em que será listado os produtos cadastrados com uma opção para excluir o produto.

### Back-end
Criar uma API que vai ter as seguintes rotinas abaixo:

- Verificação de token que o front-end irá passar via header.
- Listar (com paginação)
- Cadastrar
- Deletar


Ao finalizar o teste, subir em um repositório público e encaminhar o link para graziani@vendala.com.br.

Obs: criar um README.md com as orientações para instalação.

