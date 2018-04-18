# Lab 02 - Scope Exercise
## Wyatt Pefley
## Example code:
*Code From https://gist.github.com/sjschmidt44/556d31146a2b1ff3be84820e5fc06959*
`'use strict'`

`var foo = 'bar';`

`function bar() {`
  `var foo = 'baz';`

  `function baz(foo) {`

   `foo = 'bam';`
    `bam = 'yay';`
 `}`
  `baz();`
`}`

`bar();`
`foo;`
`bam;`
`baz();`