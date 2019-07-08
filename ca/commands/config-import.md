# config:import
Importar la configuració a l'aplicació actual.

**Ús:**
```
drupal config:import [options]
ci
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--file | Path to an archive file of configuration to import.
--directory | Path to a directory of configuration to import.
--remove-files | Remove files after synchronization.
--skip-uuid | commands.config.import.options.skip-uuid

## Exemples
* Provide a configuration file
```
drupal config:import \
  --file=/path/to/config/file
```
* Provide a configuration directory
```
drupal config:import  \
  --directory=/path/to/config/dir
```
