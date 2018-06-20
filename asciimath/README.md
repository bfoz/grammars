# ASCII Math

- Website: http://asciimath.org/
- Wikipedia: https://en.wikipedia.org/wiki/AsciiMath

The website gives the BNF equivalent as:
```
# v ::= [A-Za-z] | greek letters | numbers | other constant symbols
# u ::= sqrt | text | bb | other unary symbols for font commands
# b ::= frac | root | stackrel | other binary symbols
# l ::= ( | [ | { | (: | {: | other left brackets
# r ::= ) | ] | } | :) | :} | other right brackets
# S ::= v | lEr | uS | bSS             Simple expression
# I ::= S_S | S^S | S_S^S | S          Intermediate expression
# E ::= IE | I/I                       Expression
```

At first glance that seems reasonable, despite being rather obtuse and not quite valid BNF. However, the rule for `E` doesn't terminate on any input that isn't a fraction.