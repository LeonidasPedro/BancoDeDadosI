# Banco de dados
Sistema de banco de dados como o conjunto de quatro conponentes básicos: dados, hardware software e usuários. O sistema de banco de dados pode ser considerado uma sala de arquivos eletrônica.


#### Importância do projeto

* Projetar o banco de dados tem grande importãncia pela performance e eficácia das buscas. 

#### O que é Banco de Dados?

* Coleção de dados inter-relacionados, representando informações sobre um dominio específico. Agrupamento de informações que se relacionam e tratam do mesmo assunto.

####  Sistema de gerenciamento do banco de dados 

* Software pra manipular o banco != banco em si
* postgres, mysql

(pesquisar como funciona o sequelize ou outra ORM qualquer)
"C Compiler" e "C++ Compiler" com as seguintes informações:
### Transação

#### ACID
* Atomicidade
* Consistencia
* Isolamento
* Durabilidade

[👆Vídeo do akita que eu lembro ter mencionado isso aqui e não entendi nadakkkk](https://youtu.be/_7nISfpofec)


### Sql é a linguagem de manipulação de dados nas SGBD:

~~~sql
SELECT studentID, FullName, sat_score
FROM student
ORDER BY FullName DESC;

+-----------+------------------------+-----------+
| studentID | FullName               | sat_score |
+-----------+------------------------+-----------+
|         2 | Teri Gutierrez         |       800 |
|         3 | Spencer Pautier        |      1000 |
|         6 | Sophie Freeman         |      1200 |
|         9 | Raymond F. Boyce       |      2400 |
|         1 | Monique Davis          |       400 |
|         4 | Louis Ramsey           |      1200 |
|         7 | Edgar Frank "Ted" Codd |      2400 |
|         8 | Donald D. Chamberlin   |      2400 |
|         5 | Alvin Greene           |      1200 |
+-----------+------------------------+-----------+
9 rows in set (0.00 sec)



