<h2>Testes unitários para validar uma API REST de gerenciamento de estoques de cerveja.</h2>

Este API foi desenvolvido em aula proporcionada pela Digital Innovation One, através do desenvolvedor Rodrigo Peleais.

------------------

Em relação ao projeto desenvolvido em aula, fiz os seguintes acréscimos:

* Incluído no controller, quando da criação do produto (beer), no caso de ser informada quantidade inicial maior que a quantidade máxima, uma instrução para igualar a quantidade máxima (estoque) a quantidade inicialmente informada;

* Incluída a opção de busca por marca (retorna lista);

* Inclusão do teste abaixo, para o método acrescentado:

  ```
  void whenGETListWithBrandsIsCalledThenOkStatusIsReturned()
  ```

Com isso, foi necessário tratar a quase totalidade das classes e funcionalidades desenvolvidas na API.

Para acessar a API:

http://localhost:8080/api/v1/beers/

Via Swager:

http://localhost:8080/swagger-ui.html

-----------------

Requisitos para a execução do projeto:

- SDK15 para funcionamento das anotações do Lombok (no momento do desenvolvimento do projeto, o Lombok não estava funcionando na versão 16.

* Maven 3.6.3 ou versões superiores.
* Intellj IDEA Community Edition ou outra IDE.



