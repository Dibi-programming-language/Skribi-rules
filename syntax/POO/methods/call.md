# Français

Soit une variable `bar` contenant un objet. `foo` est une méthode non static appartenant à la class de cet objet.
Pour utiliser cette méthode :
```skribi
foo:bar()
```

Si `foo` prend des arguments, il suffit de les ajouter
```skribi
foo:bar(arg1, arg2, arg3)
```

Dans le cas d'une méthode `foo` static appartenant à la class `Bar` c'est exactement la même chose :
```skribi
foo:Bar()
```

## Pourquoi ?

Le dibi utilise une syntaxe vso (verbe-sujet-objet), la méthode se place donc au début.
