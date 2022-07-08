WORK IN PROGRESS
===

Don't use this yet.


bufbuild.nvim
===

`bufbuild.nvim` is a neovim plugin for [buf][2], written in [Yuescript][1].

This is a work-in-progress, I sketched it out in a day and am still wiring
things up.


Functionality
===

`bufbuild.nvim` provides a few easy-to-use functions that you can set up mappings for:

### `buf.ls()`

Uses `buf ls` to list all proto files in your project - using telescope - giving a
quick preview of said files and the ability to jump into them.

### `buf.format()`

Uses `buf format` to format a proto file.
This can be automatically run if the `autoformat` option is set to true during setup.

### `buf.lint()`

Provides lint-based diagnostics for the current proto file.


Contributing
===

- don't be an ass
- use [yue][1]
- write decent commit messages
- ???


[1]: https://github.com/pigpigyyy/Yuescript
[2]: https://buf.build
