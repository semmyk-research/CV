
# Data Driven CV

## What

This CV is created using the **`R`** Package [`vitae`](https://github.com/mitchelloharawild/vitae)  
It is based on [Bryan Jenks 'tallhuyjenks' repo](https://github.com/tallguyjenks/CV)

---

> _**Curriculum Vitae**_
>
> a short account of one's career and qualifications prepared typically by an applicant for a position
> --- Merriam Webster's Dictionary
>
> It is a Latin phrase meaning "course of life"

---


## Why

Extends @tallguyjenks pipe with R native pipe |>

## How

This document utilizes **RMarkdown** and is compiled through pandoc.

Uses various other packages with `vitae` such as `here`, `tibble`, `glue`, and `R` native pipe _`|>`_)

With RStudio, read in _tribbles_ contained in the `data.r` script containing all (CV) data, then using the `vitae` functions and `glue` string literals, creates the document itself.

Data exists in the `data.r` file in the `r/` directory and is added to the CV when the script is sourced by the `RMarkdown` document in the main directory.

The header portion of the document is comprised in the `YAML` portion of the `RMarkdown` document.
