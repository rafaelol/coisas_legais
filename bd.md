
## Banco de Dados

### Teoria

* [How does a relational database work](http://coding-geek.com/how-databases-work/)

### Modelagem e implementações

* [You might as well timestamp it](https://changelog.com/posts/you-might-as-well-timestamp-it)

Alguns argumentos para substituir flags booleanas de estado por timestamps.

* [Soft Deletion Probably Isn't Worth It](https://brandur.org/soft-deletion)

Alguns argumentos contra o uso de "soft deletion" de linhas de tabela, apresentando uma alternativa para manter o log de deleção.

### Mysql

* [Using EXPLAIN to Write Better MySQL Queries](https://www.sitepoint.com/using-explain-to-write-better-mysql-queries/)
* [What is the meaning of filtered in MySQL explain?](https://dba.stackexchange.com/questions/164251/what-is-the-meaning-of-filtered-in-mysql-explain)
* [StackOverflow - Match/Against and transactions](https://stackoverflow.com/questions/37199082/match-against-and-transactions)

Sempre que for fazer uma query com índice inverso, é necessário que o dado esteja commitado no banco.

* [Is 20M of rows still a valid soft limit of MySQL table in 2023?](https://yishenggong.com/2023/05/22/is-20m-of-rows-still-a-valid-soft-limit-of-mysql-table-in-2023)

Uma análise sobre uma "regra informal" antiga sobre evitar ter tabelas com mais de 20 milhões de linhas. Explica a razão desta regra e uma análise se ela ainda é válida hoje.

### Postgres

* [The Unexpected Find That Freed 20GB of Unused Index Space](https://hakibenita.com/postgresql-unused-index-size)
* [Postgres 15 improves UNIQUE and NULL](https://blog.rustprooflabs.com/2022/07/postgres-15-unique-improvement-with-null)

Postgres 15 vai permitir que indexe valor NULL como único.

### Nuvem

* [How to enable slow query log on Google Cloud SQL for MySQL](https://www.eversql.com/slow-query-log-on-google-cloud-sql-mysql/)

Como adicionar logs para queries e outras coisas no Mysql da GCP.

### Histórias de vida

* [Why Uber Engineering Switched from Postgres to MySQL](https://eng.uber.com/postgres-to-mysql-migration/)
