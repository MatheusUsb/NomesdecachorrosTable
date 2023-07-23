# NomesdecachorrosTable
# Este script criará uma tabela chamada "nome_dos_cachorros" 

-- Criação da tabela
CREATE TABLE nome_dos_cachorros (
    id INT PRIMARY KEY,
    nome VARCHAR(50) NOT NULL
);

-- Inserção dos dados
INSERT INTO nome_dos_cachorros (id, nome) VALUES
    (1, 'Thor'),
    (2, 'Mel'),
    (3, 'Bela'),
    (4, 'Max'),
    (5, 'Nina'),
    (6, 'Luke'),
    (7, 'Buddy'),
    (8, 'Luna'),
    (9, 'Bob'),
    (10, 'Spike');


