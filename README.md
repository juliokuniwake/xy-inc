Banco de Dados

Foi usado na aplicação o banco de dados Mysql
Usuario: root
Senha: root
Porta: 3306

*****************************************************************************************
Segue o script de criação da base e tabela

create database xyinc;

use xyinc;

create table xy (

id int(10) not null auto_increment primary key,

nome varchar(50),

x int(10),

y int(10)
);

*****************************************************************************************
BackEnd

Foi criado uma classe Teste onde possivel efetuar os devidos teste da aplicação

*****************************************************************************************
FrontEnd

Criação do FrontEnd com o intuito de facilitar os teste da aplicação
Segue a url para acesso da pagina index.html

http://localhost:8080/xyinc/index.html

*****************************************************************************************
Outros

Caso queira testar usando o Postman
http://localhost:8080/xyinc/api/xy

