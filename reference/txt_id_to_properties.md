# Gets the list of the properties corresponding to the identifier of a moniker

Gets the list of the properties corresponding to the identifier of a
moniker

## Usage

``` r
txt_id_to_properties(id)
```

## Arguments

- id:

  Identifier of a series or of a collection of series.

## Value

Returns a list with the elements of the id: file \[, series\], format,
gathering, ...).

## Examples

``` r
# \donttest{
set_txt_paths(system.file("extdata", package = "rjd3providers"))
#> Error in .jcall("jdplus/text/base/r/TxtFiles", "V", "setPaths", .jarray(paths)): RcallMethod: cannot determine object class
txt_15 <- txt_series("ABS.csv", series = 15, delimiter = "COMMA")
#> Error in .jcall(obj = "jdplus/text/base/r/Utility", returnSig = "Ljdplus/toolkit/base/tsp/util/ObsFormat;",     method = "obsFormat", as.character(locale), as.character(dateFmt),     as.character(numberFmt), as.logical(ignoreNumberGrouping)): java.lang.UnsupportedClassVersionError: jdplus/text/base/r/TxtFiles has been compiled by a more recent version of the Java Runtime (class file version 65.0), this version of the Java Runtime only recognizes class file versions up to 61.0
id<-txt_15$moniker$id
#> Error: object 'txt_15' not found
print(txt_id_to_properties(id))
#> Error: object 'id' not found
# }
```
