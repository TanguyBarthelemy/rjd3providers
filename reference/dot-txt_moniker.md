# Generates a java moniker for the corresponding id.

Generates a java moniker for the corresponding id.

## Usage

``` r
.txt_moniker(id)
```

## Arguments

- id:

  Identifier of the requested information.

## Value

An internal java moniker.

## Examples

``` r
.txt_moniker("toy_id")
#> Error in .jcall(obj = "jdplus/toolkit/base/api/timeseries/TsMoniker",     returnSig = "Ljdplus/toolkit/base/api/timeseries/TsMoniker;",     method = "of", txt_name(), id): java.lang.UnsupportedClassVersionError: jdplus/spreadsheet/base/api/SpreadSheetProvider has been compiled by a more recent version of the Java Runtime (class file version 65.0), this version of the Java Runtime only recognizes class file versions up to 61.0
```
