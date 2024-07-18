# `redirect`

ref: `bash pocket reference 2nd edition - page: 17`

## OVERVIEW

There are various redirection forms to the streams:
* 0: `stdin`
* 1: `stdout`
* 2: `stderr`

## SYNTAX

* `>` overwrite a file
* `>>` append to a file
* `<` take input from a file
* `<<` [here doc](https://en.wikipedia.org/wiki/Here_document) input
* `2>` overwrite a file with `stderr`
* `2>>` append to a file with `stderr`

## KNOWN GOTCHAS

The redirection operators are not comparison operators. Instead use `-lt` or `-gt`.
