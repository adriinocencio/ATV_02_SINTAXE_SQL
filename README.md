# ATV_02_SINTAXE_SQL

### Para filtrar e mostrar apenas os alunos com 16 anos, executamos o seguinte código:
```sql
SELECT * FROM `alunos` WHERE idade = 16; 
```

### Para filtrar e mostrar apenas os alunos com o sobrenome 'Santos', executamos o seguinte código:
```sql
SELECT * FROM `alunos` WHERE sobrenome = 'Santos'; 
```

### Para filtrar e mostrar apenas os alunos que no sobrenome tem a palavra 'Santos', executamos o seguinte código:
```sql
SELECT * FROM `alunos` WHERE sobrenome LIKE '%Santos%'; 
```

### Para filtrar e mostrar apenas os alunos que o sobrenome acaba com a palavra 'Santos', executamos o seguinte código:
```sql
SELECT * FROM `alunos` WHERE sobrenome LIKE '%Santos'; 
```

### Para filtrar e mostrar apenas os alunos que o sobrenome tem a palavra 'Silv', executamos o seguinte código:
```sql
SELECT * FROM `alunos` WHERE sobrenome LIKE '%Silv'; 
```
