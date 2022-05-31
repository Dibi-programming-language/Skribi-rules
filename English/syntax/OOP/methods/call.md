Consider a `bar` variable containing an object. `foo` is a non-static method belonging to it's class.
To use this method :
```skribi
foo:bar()
```

If `foo` takes arguments, just add them
```skribi
foo:bar(arg1, arg2, arg3)
```

In the case of a `foo` static method belonging to the class `Bar`, it's exactly the same thing :
```skribi
foo:Bar()
```

# Why ?

Dibi use a vso (verb-subject-object) syntax, the method is therefore placed at the beginning.

