# Set the paths to xml files (to be used with relative identifiers).

Set the paths to xml files (to be used with relative identifiers).

## Usage

``` r
set_xml_paths(paths)
```

## Arguments

- paths:

  The folders containing the xml files. Only used in relative addresses.

## Value

No output.

## Examples

``` r
set_xml_paths(system.file("extdata", package = "rjd3providers"))
#> Error in .jcall("jdplus/text/base/r/XmlFiles", "V", "setPaths", .jarray(paths)): java.lang.UnsupportedClassVersionError: jdplus/text/base/r/TxtFiles has been compiled by a more recent version of the Java Runtime (class file version 65.0), this version of the Java Runtime only recognizes class file versions up to 61.0
```
