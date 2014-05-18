# Postfix Calculator

This is an exercise to write an RPN (reverse polish notation)
calculator. It serves as a base program for learning new languages
against. The interface is simple, it reads from `STDIN` until `EOF` or
`=` and then prints the result on `STDOUT`.

    $ calc 1 1 +
      2

    $ cat - > sum
    > 1 2 3
    > +
    > 4 5 6
    > -
    > 7 8 9
    > *
    $ calc sum
      -3027

There are namespaced branches for every language and implementation, eg.
`ruby/functional-core` or `perl/v1`.
