# easy-random

A Motoko library that allows to compute Random features easily

## Installation

You need to add this repo as an entry to your package-set.dhall, in the additions List:

```
let additions =
    [
      {
        name = "easy-random",
        repo = "https://github.com/neokree/easy-random",
        version = "v0.1.0",
        dependencies = [ "base" ]
      }
    ] : List Package
  
```

And add it as a dependency for your project, in vessel.dhall:

```
{
  dependencies = [ "base", "easy-random" ],
  compiler = None Text
}
```

## API Documentation

API documentation for this library can be found at https://neokree.github.io/easy-random

## License

easy-random is distributed under the terms of the Apache License (Version 2.0).

See LICENSE for details.
