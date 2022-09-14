select nomeProduto as Produto, nomeCategoria as Categoria from produtos
inner join categorias on categorias.id_categoria = produtos.fk_categoria
inner join carrinho on idproduto = produtos.idprodutos where idusuario = 3

aqui será feita a busca pelo usuário número 3, retornando quais produtos que ele adquiriu e a categoria de cada um.
