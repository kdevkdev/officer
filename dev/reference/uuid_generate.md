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
#> [1] "f2c8788a-405f-4b63-9fa3-764a6186f891"
#> [2] "9308e1b3-8e74-4795-9829-df901c3b0d3b"
#> [3] "d399b489-7e23-4931-9bc4-d616d3a7ffad"
#> [4] "469242c3-2c4b-40ad-8d31-a93de91f87dc"
#> [5] "6a30df60-5056-4590-967f-d9df2a90c9af"
```
