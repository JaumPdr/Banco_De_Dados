# Banco_De_Dados
Atividade 1

Criar um banco de dados para uma agenda de contatos.

Criar uma agenda que permita ao usuário salvar os dados de seus contatos, os dados desejados são:

nome, email, telefone e grupo

O grupo é a indicação de onde conhece a pessoa, exemplos possíveis de grupos, são: trabalho, escola, família, amigo.

Inserir dados

Inserir diversos contatos (No mínimo 50).

Fazer buscas

Escrever algumas buscas com diferentes filtros

Atualizar registros

Atualizar algumas informações de alguns contatos (No mínimo 10)

Apagar contato

Remover alguns contatos.

Incluir a opção de favorito.

Incluir na tabela de contatos um campo para determinar se o contato em questão é ou não um contato favorito. 



// RESOLUÇÃO //



CREATE DATABASE agenda;
use agenda;
CREATE TABLE contatos (
	id INT PRIMARY KEY AUTO_INCREMENT,
	nome VARCHAR(150),
    email VARCHAR(150),
    telefone VARCHAR(150),
    grupo VARCHAR(150));

INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("João", "joao@email.com", "16998745632", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Matheus", "matheus@email.com", "1699874562", "familia");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Pedro", "pedro@email.com", "16987546823", "facebook");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Thiago", "thiago@email.com", "16998564231", "instagram");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Felipe", "felipe@email.com", "16998563215", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Julia", "julia@email.com", "16998546327", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Beatriz", "beatriz@email.com", "1698754632", "linkedin");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Carla", "carla@email.com", "1699563648", "familia");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Valeria", "valeria@email.com", "16998546723", "familia");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Romulo", "romulo@email.com", "16998658348", "familia");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Eduardo", "eduardo@email.com", "16989684756", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Vitor", "vitor@email.com", "16997845623", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Vinicius", "vinicius@email.com", "16998576423", "trabalho");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Vitoria", "vitoria@email.com", "16987546852", "trabalho");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Campitelli", "campitelli@email.com", "16998546215", "trabalho");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Douglas", "douglas@email.com", "16995468523", "trabalho");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Emily", "emily@email.com", "16996485723", "familia");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Marcus", "marcus@email.com", "16994685726", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Rafaela", "rafaela@email.com", "16998745632", "familia");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Luiz", "luiz@email.com", "16998888888", "facebook");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Jose", "jose@email.com", "16954875963", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Marcelo", "marcelo@email.com", "16985647598", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Rafael", "rafael@email.com", "16985647859", "instagram");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Joaquim", "joaquim@email.com", "16998745632", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Gabriel", "gabriel@email.com", "16998745632", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Marcio", "marcio@email.com", "16998745632", "instagram");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Ana", "ana@email.com", "16998745632", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Maria", "maria@email.com", "16998745632", "facebook");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Jacqueline", "jacqueline@email.com", "16998745632", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Rosimeire", "rosimeire@email.com", "16998745632", "instagram");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Oldimar", "oldimar@email.com", "16998745632", "familia");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Roberto", "roberto@email.com", "16998745632", "instagram");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Roberta", "roberta@email.com", "16998745632", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Rosa", "rosa@email.com", "16998745632", "facebook");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Thaline", "thaline@email.com", "16998745632", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Mayra", "mayra@email.com", "16998745632", "familia");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Mario", "mario@email.com", "16998745632", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Vitoria", "vitoria@email.com", "16998745632", "familia");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Ellen", "ellen@email.com", "16998745632", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Marta", "marta@email.com", "16998745632", "facebook");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Murilo", "murilo@email.com", "16998745632", "facebook");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Barbara", "barbara@email.com", "16998745632", "familia");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Juliano", "juliano@email.com", "16998745632", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Enzo", "enzo@email.com", "16998745632", "facebook");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Thomas", "thomas@email.com", "16998745632", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Kamila", "kamila@email.com", "16998745632", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Heitor", "heitor@email.com", "16998745632", "facebook");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Levi", "levi@email.com", "16998745632", "amigo");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Eloa", "eloa@email.com", "16998745632", "facebook");
INSERT INTO contatos (nome, email, telefone, grupo)
VALUES ("Eliana", "eliana@email.com", "16998745632", "familia");

SELECT * FROM contatos;

SELECT nome, telefone,email,grupo FROM contatos WHERE grupo = "amigo";
SELECT nome, id FROM contatos WHERE id = 37;
SELECT nome, telefone FROM contatos WHERE id = 14;
SELECT nome, email, telefone FROM contatos WHERE nome = "Maria";
SELECT nome, grupo, telefone FROM contatos WHERE id = 50;

UPDATE contatos set telefone = "16998457625" WHERE id = 45;
UPDATE contatos set email = "joaozin@email.com" WHERE id = 1;
UPDATE contatos set grupo = "facebook" WHERE nome = 36;
UPDATE contatos set telefone = "16998563232" WHERE id = 25;
UPDATE contatos set grupo = "instagram" WHERE id = 30;
UPDATE contatos set email = "pato@email.com" WHERE id = 3;
UPDATE contatos set grupo = "familia" WHERE id = 10;
UPDATE contatos set telefone = "16998745689" WHERE id = 38;
UPDATE contatos set email = "anonimo@email.com" WHERE id = 11;
UPDATE contatos set grupo = "amigo" WHERE id = 19;
UPDATE contatos set telefone = "16996548235" WHERE id = 22;

DELETE FROM contatos WHERE id = 32;
DELETE FROM contatos WHERE id = 45;
DELETE FROM contatos WHERE id = 4;
DELETE FROM contatos WHERE id = 12;

ALTER TABLE contatos ADD favoritos varchar(150);

UPDATE contatos set favoritos = "sim" WHERE id = 1;
UPDATE contatos set favoritos = "sim" WHERE id = 2;
UPDATE contatos set favoritos = "não" WHERE id = 3;
UPDATE contatos set favoritos = "sim" WHERE id = 4;
UPDATE contatos set favoritos = "sim" WHERE id = 5;
UPDATE contatos set favoritos = "não" WHERE id = 6;
UPDATE contatos set favoritos = "sim" WHERE id = 7;
UPDATE contatos set favoritos = "não" WHERE id = 8;
UPDATE contatos set favoritos = "sim" WHERE id = 9;
UPDATE contatos set favoritos = "sim" WHERE id = 10;
UPDATE contatos set favoritos = "não" WHERE id = 11;
UPDATE contatos set favoritos = "sim" WHERE id = 12;
UPDATE contatos set favoritos = "não" WHERE id = 13;
UPDATE contatos set favoritos = "sim" WHERE id = 14;
UPDATE contatos set favoritos = "sim" WHERE id = 15;
UPDATE contatos set favoritos = "sim" WHERE id = 16;
UPDATE contatos set favoritos = "sim" WHERE id = 17;
UPDATE contatos set favoritos = "sim" WHERE id = 18;
UPDATE contatos set favoritos = "sim" WHERE id = 19;
UPDATE contatos set favoritos = "sim" WHERE id = 20;
UPDATE contatos set favoritos = "sim" WHERE id = 21;
UPDATE contatos set favoritos = "sim" WHERE id = 22;
UPDATE contatos set favoritos = "não" WHERE id = 23;
UPDATE contatos set favoritos = "não" WHERE id = 24;
UPDATE contatos set favoritos = "não" WHERE id = 25;
UPDATE contatos set favoritos = "não" WHERE id = 26;
UPDATE contatos set favoritos = "sim" WHERE id = 27;
UPDATE contatos set favoritos = "não" WHERE id = 28;
UPDATE contatos set favoritos = "sim" WHERE id = 29;
UPDATE contatos set favoritos = "sim" WHERE id = 30;
UPDATE contatos set favoritos = "não" WHERE id = 31;
UPDATE contatos set favoritos = "sim" WHERE id = 32;
UPDATE contatos set favoritos = "não" WHERE id = 33;
UPDATE contatos set favoritos = "sim" WHERE id = 34;
UPDATE contatos set favoritos = "sim" WHERE id = 35;
UPDATE contatos set favoritos = "sim" WHERE id = 36;
UPDATE contatos set favoritos = "sim" WHERE id = 37;
UPDATE contatos set favoritos = "não" WHERE id = 38;
UPDATE contatos set favoritos = "sim" WHERE id = 39;
UPDATE contatos set favoritos = "sim" WHERE id = 40;
UPDATE contatos set favoritos = "sim" WHERE id = 41;
UPDATE contatos set favoritos = "sim" WHERE id = 42;
UPDATE contatos set favoritos = "não" WHERE id = 43;
UPDATE contatos set favoritos = "sim" WHERE id = 44;
UPDATE contatos set favoritos = "sim" WHERE id = 45;
UPDATE contatos set favoritos = "não" WHERE id = 46;
UPDATE contatos set favoritos = "sim" WHERE id = 47;
UPDATE contatos set favoritos = "sim" WHERE id = 48;
UPDATE contatos set favoritos = "sim" WHERE id = 49;
UPDATE contatos set favoritos = "não" WHERE id = 50;
