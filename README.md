# ATV6_Data_Base

# EX 1
- Engenheiro
- Projeto
- Atuação

# EX 2
Produto (CodProd (chave primária), Nome)
Cidade (CodCid (chave primária), Nome)
Distribuidor (CodDistr (chave primária), Nome)
Distribuição (CodProd, CodCid, CodDistr (chave primária composta), Nome)
  - CodProd ref. Produto
  - CodCidade ref. Cidade
  - CodDistr ref. Distribuidor

# EX 3
Exercício: Sistema de Biblioteca
Descrição: Uma biblioteca deseja armazenar informações sobre livros, autores e usuários que realizam
empréstimos.
Requisitos:
•Cada livro tem um código, título e ano de publicação.
•Cada livro pode ter um ou mais autores, e cada autor pode ter escrito vários livros.
•Cada usuário pode pegar vários livros emprestados, mas um livro só pode ser emprestado para um usuário por vez.

Desafio:
1.Construa o Modelo Lógico com tabelas e relacionamentos.
2.Defina chaves primárias e estrangeiras.
