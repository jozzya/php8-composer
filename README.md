# Composer-gd-zip
Github action to run composer under a php image that uses gd and zip extensions, both extensions that I needed in some point to run composer install. 

## Example
```
steps:
  - name: Run composer
    uses: jozzya/php8-composer@main
    with:
      action: 'install'
```
