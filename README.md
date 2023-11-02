# Swinburne PhD thesis template

A Typst template for Swinburne University PhD theses.

See `thesis.typ` for an example/skeleton template.

For convenience I have defined `citep` and `citet` functions in the template to aid in transitioning from LaTeX. Some examples on usage are included in the `thesis.typ` document.

As of writing (Typst v. 0.9.0) there are some big limitations to the native `table` function. I suggest including [tablex](https://github.com/PgBiel/typst-tablex) as follows and checking the documentation for more advanced table options:

```typst
#import "@preview/tablex:0.0.6": tablex, rowspanx, colspanx
```

For any bugs, requests and questions please open an issue!

There is a bug with indentation of the first paragraph under a heading, this will be fixed soon.
