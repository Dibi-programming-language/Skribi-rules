Soit une variable foo de type `Uiui`, pour créer cette variable il faut :
```skribi
foo:Uiui = valeur
```
Ou (déconseillé)
```skribi
foo = valeur
```

Il est possible de déclarer une variable à n'importe quel moment

Dans la seconde situation le type sera déduit par le programme avec le type de la valeur le plus haut dans l'héritage. (Comment traduire en anglais ?). Il faut donc faire attention, car si la variable est modifiée un conflit de type est possible.

# Null
Il est possible de faire une déclaration avec une valeur `null` ou de ne pas mettre `= valeur` (la valeur sera dans ce cas `null`) mais il faut dans ce cas indiquer le type obligatoirement

**Null n'est pas encore traduit**

