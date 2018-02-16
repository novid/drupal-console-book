# config:override
Override config value in active configuration.

**Usage:**
```
drupal config:override [arguments]
co
```

## Available arguments
Argument | Details
---------|-------------
name | Configuration name
key | Key
value | Value

## Examples
* Set the Contact module flood limit to 10.
```
drupal config:override contact.settings flood.limit 10
```
