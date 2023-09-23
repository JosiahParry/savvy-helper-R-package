# savvy (R package)

This is a simple wrapper R package around `savvy-cli` command.

## Installation

You can install this package from R-universe.

``` r
install.packages("savvy"", repos = c("https://yutannihilation.r-universe.dev", "https://cloud.r-project.org"))
```

## Usage

``` r
# Run savvy_init() to do the initial setup for using savvy framework
savvy::savvy_init()

# Run savvy_update() to re-generate the C and R wrapper files from the Rust files.
savvy::savvy_update()

# To update savvy, please Run this command to overwrite the existing savvy-cli binary.
savvy::download_savvy_cli()
```

