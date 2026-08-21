# Banco-de-Dados-
### Anotações: 
Guia de Comandos SSH e MySQL

#### Conexão e Acesso:

Conexão SSH:
* Conecta remotamente ao servidor usando o usuário e IP especificados.
* ssh nome.Ultimosobrenome@10.111.9.113

Acesso ao MySQL:
* Abre o terminal interativo do MySQL solicitando a senha.
* mysql -u usuario -p

#### Comandos SQL:

##### CREATE:
Usado para criar novas bases de dados ou tabelas na estrutura do banco.
* CREATE DATABASE db_nome;
* CREATE TABLE tabela (id INT PRIMARY KEY AUTO_INCREMENT, nome VARCHAR(100));

##### DROP:
Usado para apagar permanentemente tabelas ou bancos de dados do sistema.
* DROP TABLE tabela;
* DROP DATABASE db_nome;

##### INSERT:
* Usado para inserir novos registros de dados em uma tabela existente.
* INSERT INTO tabela (nome) VALUES ('Exemplo'); INT

##### SELECT:
* Usado para consultar e recuperar dados salvos em uma ou mais tabelas.
* SELECT * FROM tabela;

##### UPDATE:
* Usado para atualizar ou alterar dados que já existem em uma tabela.
* UPDATE tabela SET nome = 'Novo Nome' WHERE id = 1;

##### DELETE:
* Usado para remover registros específicos de uma tabela com base em condições.
* DELETE FROM tabela WHERE id = 1;
