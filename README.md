# recipe-hexagonal-maker-bundle
Symfony recipe pour le bundle hexagonal-maker.

## Commande pour générer une clé pour la valeur "ref"
```php
<?= bin2hex(random_bytes(20)); ?>
```
**Chaque modification de la recette doit entrainer une modification de la valeur du ref** 
