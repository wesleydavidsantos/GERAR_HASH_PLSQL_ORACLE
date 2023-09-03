# GERAR_HASH_PLSQL_ORACLE

Gerar HASH de CLOB ou VARCHAR - PL/SQL - Oracle

Em alguns momentos precisamos gerar um HASH sobre VARCHAR ou CLOB para facilitar a realização de consultas ou gerar esses HASH para tratar um valor muito extenso como único.

Suponha que você precise tratar um VARCHAR(4000) como único, seu SELECT vai ficar muito pesado ao realizar uma consulta, desta forma você pode criar um HASH de 32 caracteres e usar ele como filtro garantindo assim que aquele valor é único. Agora suponha que seja um CLOB, ai complicou.

Esse era um problema que eu estava enfrentando, então criei essa Function que descomplica esse problema.

Você pode usar ela direto em uma query SQL ou em PLSQL, lembrando, para query SQL você só consegue com textos até 4000 caracteres, para textos maiores você vai ter que chamar a Function dentro de um PLSQL.

Faça bom aproveito.

---

Generate HASH for CLOB or VARCHAR - PL/SQL - Oracle

At times, we need to generate a HASH on VARCHAR or CLOB to facilitate queries or generate these HASH values to treat a very extensive value as unique.

Suppose you need to treat a VARCHAR(4000) as unique, your SELECT query will become very heavy when executing a search. In this way, you can create a HASH that encrypts it into 32 characters and use it as a filter, ensuring that the value is unique. Now, suppose it's a CLOB, that's where it gets complicated.

This was a problem I was facing, so I created this Function to simplify the issue.

You can use it directly in an SQL query or in PLSQL. Please note that for SQL queries, it only works with texts up to 4000 characters, for larger texts, you'll need to call the Function within PLSQL.

In summary, with this Function, you can encrypt any value within an Oracle database.

Enjoy using it.

#PLSQL #Oracle #HashEmOracle #HashPLSQL #HashCLOB #HashBLOB #HashVARCHAR #CriptografiaOracle #CriptografiaPLSQL #DBA
