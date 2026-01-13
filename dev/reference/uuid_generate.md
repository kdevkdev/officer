# generates unique identifiers

generates unique identifiers based on
[`uuid::UUIDgenerate()`](https://rdrr.io/pkg/uuid/man/UUIDgenerate.html).

## Usage

``` r
uuid_generate(n = 1, ...)
```

## Arguments

- n:

  integer, number of unique identifiers to generate.

- ...:

  arguments sent to
  [`uuid::UUIDgenerate()`](https://rdrr.io/pkg/uuid/man/UUIDgenerate.html)

## Examples

``` r
uuid_generate(n = 5)
#> [1] "568159b3-7bf6-4fe0-b23d-e804a8183b81"
#> [2] "aee40e40-f147-4d12-a0f3-86973b9208ea"
#> [3] "24c47f7d-4e34-45a5-8b5f-18271a00d7c2"
#> [4] "4c92b0e7-319b-4f09-8abe-0afe1afd8ab9"
#> [5] "4d8538c9-6f4e-49f2-a9e3-11458efc3ea4"
```
