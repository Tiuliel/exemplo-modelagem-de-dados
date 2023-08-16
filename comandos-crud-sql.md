# Comandos para operações no Banco de Dados

## Resumo

- C -> CREATE (unserir dados, usando comando `INSERT`)
- R -> READ (ler dados usando comando `SELECT`)
- U -> UPDATE (atualizar dados usando comando `UPDATE`)
- D -> DELETE (excluir dados usando comando `DELETE`)

## INSERT

### Fabricantes
```sql
INSERT INTO fabricantes (nome) VALUES('Asus');

INSERT INTO fabricantes (nome) VALUES('Dell');
INSERT INTO fabricantes (nome) VALUES('Apple');

INSERT INTO fabricantes (nome) 
VALUES('LG'), ('Samsung'), ('Brastemp');

INSERT INTO fabricantes (nome) 
VALUES('Positivo'), ('Microsoft');
```

### Produtos

```sql
INSERT INTO produtos(
    nome, preco, descricao, quantidade, fabricante_id)
VALUES(
    'Ultrabook',
    3500,
    'Equipamento de última geração cheio de recursos, com
    processador intel core i9',
    7,
    2 -- id do fabricante DELL

);

INSERT INTO produtos(
    nome, preco, descricao, quantidade, fabricante_id)
VALUES(
    'Tablet Android',
    1500.99,
    'Tablet com a versão 14 do sistema operacional android,
    possui tela de 10 polegadas e armazenamento de 128 GB, e 64 GB de RAM ',
    5,
    5
);

INSERT INTO produtos(
    nome, preco, descricao, quantidade, fabricante_id)
VALUES(
    'Geladeira',
    5000,
    'geladeira que gela',
    12,
    6
), 
(
    'Iphone 18 pro Max',
    12666.66, 
    'Smartphone apple pra rico',
    3,
    3
), 
(
    'Ipad',
    10000.01,
    'Tablet apple com canela'
    5,
    3
);

```