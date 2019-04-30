Julia v1.3 Release Notes
========================

New language features
---------------------


Language changes
----------------


Multi-threading changes
-----------------------


Build system changes
--------------------


New library functions
---------------------

* New `findall(pattern, string)` method where `pattern` is a string or regex ([#31834](https://github.com/JuliaLang/julia/issues/31834)).

Standard library changes
------------------------

* `Regex` can now be multiplied (`*`) and exponentiated (`^`), like strings ([#23422](https://github.com/JuliaLang/julia/issues/23422)).

#### LinearAlgebra

* `diagm` and `spdiagm` now accept optional `m,n` initial arguments to specify a size ([#31654](https://github.com/JuliaLang/julia/issues/31654)).

#### SparseArrays


#### Dates


#### Statistics

* `mean` now accepts both a function argument and a `dims` keyword ([#31576](https://github.com/JuliaLang/julia/issues/31576)).

#### Miscellaneous



External dependencies
---------------------


