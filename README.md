# Linear algebra library for Futhark

A small collection of linear algebra operations written in Futhark.
There's not a lot here yet; please open an issue if you need something
that's missing.

## Installation

```
$ futhark-pkg add github.com/diku-dk/sorts
$ futhark-pkg sync
```

## Usage

```
> import "lib/github.com/diku-dk/linalg/linalg"
> module linalg_f32 = mk_linalg f32
> linalg_f32.matmul [[1,2],[3,4]] [[5,6],[7,8]]
[[19.0f32, 22.0f32],
 [43.0f32, 50.0f32]]
```

## See also

* https://github.com/athas/distance
* https://github.com/athas/vector
