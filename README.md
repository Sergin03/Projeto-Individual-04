# Projeto-Individual-04
create table curso(
id varchar(20) primary key,
nome varchar(50),
carga_horaria int ,
matricula varchar(50)
professor varchar(10));


create table turma(
id varchar(20) primary key,
turno varchar(10),
carga_horaria int,
matricula varchar(20)
professor varchar(10));

create table aluno(
id varchar(20) primary key,
idade int,
email varchar(30),
cpf int)
turno varchar(20));
