# SQL

## Tipos de dados

* INTEGER
* SMALLINT
* NUMBER
  
    PRECISION - numero de digitos
    
    SCALE - numero de digitos depois do ponto
  
* DOUBLE PRECISION
* FLOAT
* REAL
* CHAR - tamanho fixo
* VARCHAR - tamanho variável
* BLOB - Binary Large Object
* DATE 
* TIME
* TIMESTAMP

## RESTRIÇOES DE COLUNAS
* NOT NULL
* DEFAULT valor
* CHECK (condição)

## RESTRIÇÕES DE TABELA
* PRIMARY KEY
* UNIQUE
* FOREIGN KEY
-> AÇÕES: ON DELETE & ON UPDATE
* CASCADE
* SET NULL
* SET DEFAULT
* CHECK

## EXERCICIO

CRIAR TABELAS PARA O SEGUINTE ESQUEA

ALUNO = NOME-, Nmatr, idade, dataNasc
prof = NOME-, nomeFunc, idade, titulacao
disciplina = siglaNome-, nCred, prof, livro
turma = sigla, numero, alunos
matricula = sigla, numero, aluno, ano, nota

#ALTER TABLE

Incluir/alterar/remover definições de colunas e restrições
* ALTER TABLE tabela <ação>;

Ações:
* ADD
* DROP
* ALTER
