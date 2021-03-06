# playing_with_ast

Example code for manipulating Python "AST"

## Useful Lings

- [Green Tree Snakes tutorial][1] on Python AST
- [List of AST nodes][7] form "Green Tree Snakes" tutorial
- [`ast` module][8] official docs
- [The AST and Me][9] talk by Emily Morehouse-Valcarcel

## TOC

- [x] [Green Tree Snakes tutorial](green_tree_snakes/sample.ipynb)
- [x] [The AST and Me](ast_and_me/sample.ipynb)

## TODO

- [ ] [Hacking Python AST: checking methods declaration][10]
- [ ] AST manipulating libraries
    - [ ] [astor][2]
    - [ ] [Meta][3]
    - [ ] [uncompyle6][4]
- [ ] [AST manipulating commands][5]
- [ ] [ASTsearch][6] library


[1]: https://greentreesnakes.readthedocs.io/en/latest/
[2]: https://github.com/berkerpeksag/astor
[3]: https://github.com/srossross/Meta
[4]: https://github.com/rocky/python-uncompyle6/
[5]: https://greentreesnakes.readthedocs.io/en/latest/tofrom.html#fixing-locations
[6]: https://astsearch.readthedocs.io/en/latest/
[7]: https://greentreesnakes.readthedocs.io/en/latest/nodes.html
[8]: https://docs.python.org/3/library/ast.html
[9]: https://youtu.be/XhWvz4dK4ng
[10]: https://julien.danjou.info/python-ast-checking-method-declaration/