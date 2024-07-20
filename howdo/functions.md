# `functions`

ref: `bash pocket reference 2nd edition - page: 23`

## OVERVIEW

Functions are grouping of commands within a script.

Parameters are accessed via `$1`,`$2`, and so forth.

Functions may contain `return` statements for exit status codes.

## SYNTAX

The syntax is as follows

```
name () {
  code
} [redirections]
```

or


```
function name [()] {
  code
} [redirections]
```

Parenthesis are optional when using the `function` keyword for declaration.

## KNOWN GOTCHAS

Any redirection given within function definition are evaluated during execution and not during definition.
