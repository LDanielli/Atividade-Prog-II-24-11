BibliotecaORM
Atividade da Aula 11 de Programação II, curso de Ciência da Computação da UNOESC. Professor: Leandro Otavio Cordova Vieira Aluna: Luiza Terezinha Danielli

Mini-ORM didático em PHP com PDO e MySQL, usando o padrão Data Mapper, para cadastrar livros e autores de uma biblioteca.

Tecnologias
PHP 8
PDO
MySQL 8
Conceitos aplicados
Encapsulamento, herança e polimorfismo
Interface e classe abstrata
Associação N:N entre livro e autor
CRUD com consultas preparadas
Transações (commit e rollback)
Estrutura
sql/schema.sql           banco de dados
src/Domain/              entidades Livro e Autor
src/Infrastructure/      repositórios e conexão
tests/smoke.php          testes
exemplo.php              exemplo de uso
