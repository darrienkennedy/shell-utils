# `quotes`

ref: `bash pocket reference 2nd edition - page: 14`

## OVERVIEW

Quotes in bash have a specific purpose and there is a clear functional difference between the different types of quotes: single, double, backtick.

## BREAKDOWN

* single quotes (`'some string'`): Content is taken literally. Env vars will not be expanded
* double quotes (`"some $VAR"`): Env vars will be expanded or command substitition can occur
* backticks (`` `pwd` ``): Command substitution occurs (similar to `$(pwd)`)

## KNOWN GOTCHAS

N/A
