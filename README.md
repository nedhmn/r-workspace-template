# r-workspace-template

An R project template. Requires a minimum R version of 4.4.1.

## Installation

Create an `.Renviron` file based off [.Renviron.example](.Renviron.example).

Restore the lock file.

```
# Since there's an renv file, just need to snapshot the dependencies
renv::snapshot()
```
