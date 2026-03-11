# Set the paths to spreadsheet files (to be used with relative identifiers).

Set the paths to spreadsheet files (to be used with relative
identifiers).

## Usage

``` r
set_spreadsheet_paths(paths)
```

## Arguments

- paths:

  The folders containing the spreadsheet files Only used in relative
  addresses.

## Value

No output.

## Examples

``` r
set_spreadsheet_paths(system.file("extdata", package = "rjd3providers"))
#> Error in .jcall("jdplus/spreadsheet/base/r/SpreadSheets", "V", "setPaths",     .jarray(paths)): java.lang.UnsupportedClassVersionError: jdplus/text/base/api/XmlProvider has been compiled by a more recent version of the Java Runtime (class file version 65.0), this version of the Java Runtime only recognizes class file versions up to 61.0
```
