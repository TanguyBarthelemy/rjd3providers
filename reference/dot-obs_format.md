# Generates the Java object for data formats

Generates the Java object for data formats

## Usage

``` r
.obs_format(
  locale = NULL,
  dateFmt = NULL,
  numberFmt = NULL,
  ignoreNumberGrouping = TRUE
)
```

## Arguments

- locale:

  Locale language. Null to use the default

- dateFmt:

  Format of the date. Null to use the default of the locale

- numberFmt:

  Format of the number. Null to use the default of the locale

- ignoreNumberGrouping:

  Ignore number grouping

## Value

An internal Java object.

## Examples

``` r
.obs_format(locale = "french-be")
#> Error in .jcall(obj = "jdplus/text/base/r/Utility", returnSig = "Ljdplus/toolkit/base/tsp/util/ObsFormat;",     method = "obsFormat", as.character(locale), as.character(dateFmt),     as.character(numberFmt), as.logical(ignoreNumberGrouping)): RcallMethod: cannot determine object class
```
