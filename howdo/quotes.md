# `quotes`

ref: `bash pocket reference 2nd edition - page: 14`

## OVERVIEW

Quotes in bash have a specific purpose and there is a clear functional difference between the different types of quotes: single, double, back-tick.

## BREAKDOWN

* single quotes (`'some string'`): Content is taken literally. Environment vars will not be expanded
* double quotes (`"some $VAR"`): Environment vars will be expanded or command substitution can occur
* back-ticks (`` `pwd` ``): Command substitution occurs (similar to `$(pwd)`)

## KNOWN GOTCHAS

N/A
