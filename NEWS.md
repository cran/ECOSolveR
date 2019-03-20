
# ECOSolveR 0.5

* ECOS update: Synced underlying library to version 2.0.7.

* Removed import of `Matrix` package, added `slam` interface,
  contributions from [Florian
  Schwendinger](https://github.com/FlorianSchwendinger/ECOSolveR/).

* Tests: Added a number of unit tests based on base C library.

# ECOSolveR 0.4

* `ECOS_csolve` assumes `A` and `G` as `NULL` if any dimension is 0
* The dims list is now coerced to integer immediately upon entry to
  `ECOS_csolve`
* ECOS library sources updated to version 2.0.5.

# ECOSolveR 0.3-[1-3]

* Updated Readme
* Allowed empty vector `c`, per Anqi’s request

# ECOSolveR 0.3

* Registered `.Call` entries
* Changed Anqi’s email

# ECOSolveR 0.2

* Added system requirement of GNU makefile
* Improved the description of the package
* Checked more carefully on Linux, MacOS, and Windows

# ECOSolveR 0.1-1

* First version, thought I had it right for all platforms, but quite
  wrong. 
