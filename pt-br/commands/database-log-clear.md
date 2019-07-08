# database:log:clear
Remove eventos da tabela DBLog, filtros disponíveis

**Utilização:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
event-id | DBLog event ID

## Exemplos
* Clear the database log from DBLog table
```
drupal database:log:clear \
  <database>
```
* Clear the database log from DBLog table using filters
```
drupal database:log:clear \
  <database> \
  --type=TYPE \
  --severity=SEVERITY
```
