# `variables`

ref: `bash pocket reference 2nd edition - page: 25`

## OVERVIEW

Variable names consist of any number of lower case, upper case, or digit characters. They may not begin with a digit like most programming languages.

Convention is to use all caps when you spell the var's name.

## SYNTAX

Variable assignment is done using the `=` operator and there CANNOT exist whitespace surrounding the operator.

Valid syntax:
```
THIS="that"
```

Invalid syntax:
```
THIS = "that"
```

Appending can be done using the `+=` operator.

## KNOWN GOTCHAS

The shell will treat variable's values as strings even if the contents only contain digits.
