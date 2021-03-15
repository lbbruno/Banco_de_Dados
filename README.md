# Banco de Dados ![db_logo](db.png)
 Exercícios e Projetos de Banco de Dados

 _*OBS: Os Modelos conceituais no diretório exercícios são somente para exempplo e prática de abstrção*_

## Modelo conceitual Biblioteca
* Exercício de abstração de um banco de dados para de acervos das bibliotecas das univercidades.

**Regras do Negócio:** O acervo de uma biblioteca é composto por exemplares de livros. Existe uma biblioteca em cada campus da universidade. Cada biblioteca possui um CNPJ próprio e um nome, que é o nome do primeiro diretor do campus em que se localiza a biblioteca. A biblioteca mantém um conjunto de livros, sendo que para cada um dos livros é associada uma categoria. Conforme a sua categoria, o livro é disposto em uma estante apropriada. Um livro tem vários exemplares na biblioteca. Na biblioteca trabalham várias bibliotecárias. Cada bibliotecária é responsável por organizar periodicamente sempre o mesmo conjunto de estantes e realizar empréstimos de exemplares para clientes. Empréstimos cadastrados no BD devem conter a data da devolução e o valor diário da multa, permanecendo no BD até o cliente entregar o exemplar. A bibliotecária que realizou o empréstimo também é relevante de ser mantido no BD. Algumas bibliotecárias são estagiárias. Uma bibliotecária estagiária está sempre sob a responsabilidade de uma bibliotecária efetiva.
Cada livro é caracterizado por um ou mais autores, um título, uma editora, local de edição, um código ISBN e um conjunto de palavras-chave.  Cada Autor, além do nome, possui um código para identificá-lo. A editora possui um CNPJ, um nome e local de edição, que constam a rua, cidade e a UF do local. Para cada empréstimo, é registrada a data em que este foi realizado. Cada cliente  possui um código, nome e endereço.


<img src="/Exercícios/Modelo_Conceitual/Biblioteca_B.png">

*Exercícios/Dicionário_de_Dados/[Dicionario_de Dados_Biblioteca.xlsx](https://github.com/lbbruno/Banco_de_Dados/tree/main/Exerc%C3%ADcios/Dicion%C3%A1rio_de_Dados)

## Modelo conceitual Aeroporto
* Exercício de abstração de um banco de dados para controle de voos e reservas.
<img src="/Exercícios/Modelo_Conceitual/Aeroporto_A.png">

## Modelo conceitual Academia
* Exercício de abstração de um banco de dados para uma Academia.
<img src="/Exercícios/Modelo_Conceitual/Academia_A.png">

## Modelo conceitual Locadora de DVD's
* Exercício de abstração de um banco de dados para uma locadora.
<img src="/Exercícios/Modelo_Conceitual/Locadora_A.png">