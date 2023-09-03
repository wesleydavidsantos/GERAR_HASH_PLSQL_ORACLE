# GERAR_HASH_PLSQL_ORACLE

Gerar HASH de CLOB ou VARCHAR - PL/SQL - Oracle

Em alguns momentos precisamos gerar um HASH sobre VARCHAR ou CLOB para facilitar a realização de consultas ou gerar esses HASH para tratar um valor muito extenso como único.

Suponha que você precise tratar um VARCHAR(4000) como único, seu SELECT vai ficar muito pesado ao realizar uma consulta, desta forma você pode criar um HASH de 32 caracteres e usar ele como filtro garantindo assim que aquele valor é único. Agora suponha que seja um CLOB, ai complicou.

Esse era um problema que eu estava enfrentando, então criei essa Function que descomplica esse problema.

Você pode usar ela direto em uma query SQL ou em PLSQL, lembrando, para query SQL você só consegue com textos até 4000 caracteres, para textos maiores você vai ter que chamar a Function dentro de um PLSQL.

Faça bom aproveito.
