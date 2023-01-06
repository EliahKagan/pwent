<!-- SPDX-License-Identifier: 0BSD -->

# pwent - reading /etc/passwd entries in Perl

This is a demonstration of two ways to read `/etc/passwd` entries using Perl
scripts.

- [`pwent-ext`](pwent-ext) uses the external command `getent` (a system
  command) and parses the result with regular expressions.

- [`pwent-int`](pwent-int) uses Perl's `getpwent`, `getpwuid`, and `getpwnam`
  builtin functions.

This can be useful for system administration, learning how files like
`/etc/passwd` work, or learning how regular expressions and the `getpw*` Perl
functions work.

## License

[0BSD](https://spdx.org/licenses/0BSD.html). See [**`LICENSE`**](LICENSE).

## History

This was originally made as a demonstration of Perl regular expressions,
consisting solely of the script now called `pwent-ext`. Then it grew a bit from
there, including the second script that doesn't need regular expressions.

It was first presented in [this old
gist](https://gist.github.com/EliahKagan/bcab9d925a87ead59ce651e288a052c5),
which this repository supersedes..
