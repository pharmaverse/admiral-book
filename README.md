# admiral-book

> A teaching book for creating ADaM datasets using the
> [`{admiral}`](https://pharmaverse.github.io/admiral/) R package.

## Overview

This repository contains the source files for **The admiral Book** — an
online, open-source book that accompanies the `{admiral}` R package.

The book follows a similar structure to the
[ggplot2 book](https://ggplot2-book.org/) and is built with
[Quarto](https://quarto.org/).

### Why this book?

The `{admiral}` package has grown large with vignettes and examples. This
book provides a home for the full set of worked examples and vignettes,
allowing the package itself to be kept lean while offering richer teaching
material here.

## Contents

| Part | Description |
|---|---|
| Getting Started | Introduction to `{admiral}` and programming concepts |
| ADaM Data Structures | Step-by-step guides to ADSL, OCCDS, BDS Findings, BDS Exposure, BDS TTE |
| Special Topics | Imputation, visits, lab grading, Hy's Law, estimands, higher order functions, questionnaires, queries |
| Advanced Topics | PK NCA (ADNCA), antibody data (ADAB), FAQ |

## Building the Book

### Prerequisites

Install R and the following packages:

```r
install.packages(c(
  "quarto",
  "admiral",
  "pharmaversesdtm",
  "dplyr",
  "lubridate",
  "stringr",
  "tibble"
))
```

Install [Quarto](https://quarto.org/docs/get-started/).

### Render

```bash
quarto render
```

The rendered book will be output to the `_book/` directory.

## Contributing

Contributions are welcome! Please open an issue or pull request in this
repository.

-   Book issues: <https://github.com/pharmaverse/admiral-book/issues>
-   Package issues: <https://github.com/pharmaverse/admiral/issues>

## Licence

This book is licensed under the
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) licence.
