# cabinet

The {cabinet} package was made to show people how to create packages the easy way with {usethis} and {devtools}.

It was built in a [Cabinet Office Coffee & Coding session](https://co-analysis.github.io/co-coffee-and-coding/) on 1 November 2019.

[See the slides from that talk in your browser](https://matt-dray.github.io/r-pkg-slides/) and [read the accompanying blog post](https://www.rostrum.blog/2019/11/01/usethis/).

## Installation

You can install {cabinet} from GitHub using the {remotes} package:

```
install.packages("remotes")
remotes::install_github("cabinet")
```

## Example

The `cabinet_cat()` function tells you if the provided name belongs to a Cabinet Office cat. Try:

```
cabinet_cat("Ossie")
cabinet_cat("Larry")
cabinet_cat("Garfield")
```

## Code of conduct

Please note that the 'cabinet' project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By contributing to this project, you agree to abide by its terms.
