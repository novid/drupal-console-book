# config:export
Exportar la configuració actual de l'aplicació

**Ús:**
```
drupal config:export [options]
ce
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--directory | Define the export directory to save the configuration output.
--tar | If set, the configuration will be exported to an archive file.
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## Exemples
* Optional you can add the path to export
```
drupal config:export  \
  --directory="path/to/export"
```
* If export will be in a compressed file and/or if uuid and config hashes will be removed.
```
drupal config:export  \
  --directory="path/to/export" \
  --tar \
  --remove-uuid \
  --remove-config-hash
```
