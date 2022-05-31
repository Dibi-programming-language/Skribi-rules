## Français
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

### Null
Il est possible de faire une déclaration avec une valeur `null` ou de ne pas mettre `= valeur` (la valeur sera dans ce cas `null`) mais il faut dans ce cas indiquer le type obligatoirement

**Null n'est pas encore traduit**

## English
Given a foo variable of `Uiui` type, to create this variable you must :
```skribi
foo:Uiui = value
```
Or
```skribi
foo = valeur
```

It is possible to declare a variable at any time.

### Null
It is possible to make a declaration with a `null` value or to not put `= value` (the value, in this case, will be `null`) but in this case you must give the type.


**Null is not in Dibi yet**

## Dibi

