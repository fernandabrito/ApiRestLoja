# ApiRestLoja
Api Rest para minha loja


End Points:

Cadastrar categoria
 /categoria - Post - Body (String nome; private String descricao;)

Recuperar Categorias

/categorias - GET - lista todas as categorias

Cadastrar Produto

/categoria/{id-da-categoria} - POST - Body Produto (private String nome; private String descricao; private float preco; private int quantidadeEstoque; private String fotoUrl;)

recuperar produtos da categoria

/categoria/{id-da-categoria} GET - retorna uma lista de produtos


Testes automatizados - 

Teste para criar categoria / produtos e testar os retornos.
