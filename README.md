## Evolving SQL

Despite SQL's enduring success,
it is widely accepted that there are serious flaws in the language and
a number of authors argue that SQL should be replaced in its entirety.
Among many such works, here are some noteworthy arguments:

* [A Critique of the SQL Database Language](https://dl.acm.org/doi/pdf/10.1145/984549.984551)
a 1983 paper by
[C.J. Date](https://en.wikipedia.org/wiki/Christopher_J._Date),
* [Against SQL](https://www.scattered-thoughts.net/writing/against-sql/)
by [Jamie Brandon](https://www.scattered-thoughts.net/),
* [A Critique of Modern SQL And A Proposal Towards A Simple and Expressive
Query Language](https://www.cidrdb.org/cidr2024/papers/p48-neumann.pdf)
by [Neumann](https://db.in.tum.de/~neumann/)
and [Leis](https://www.cs.cit.tum.de/dis/team/prof-dr-viktor-leis/).

Armed with both sum and product types, super-structured data provides a 
comprehensive algebraic type system that can represent any
[JSON value as a concrete type](https://www.researchgate.net/publication/221325979_Union_Types_for_Semistructured_Data).
And since relations are simply product types 
as originally envisioned by Codd, any relational table can be represented
also as a super-structured product type.  Thus, JSON and relational tables
are cleanly unified with an algebraic type system.
