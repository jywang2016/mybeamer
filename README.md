
# mybeamer: a fork of youngmetro <img src="http://aaronbaggett.com/images/youngmetro_logo.png" align="right" />



> Way too many questions you must think I trust you  
> You searching for answers I do not know nothing

-----

## Note

Fork of [aaronbaggett/youngmetro](https://github.com/aaronbaggett/youngmetro)

## Purpose

For the weekly meeting, the `mybeamer` is developed.

## Installation

``` r
if (!require("devtools")) {
  install.packages("devtools", dependencies = TRUE) 
}
devtools::install_github("jywang2016/mybeamer")
```

you also need `tinytex` to compile your beamer.

```r
install.packages('tinytex')
```

## Differences 

- Modify the theme of `youngmetro` slightly.
- Add support of Chinese.

## Usage 

### RStudio

1) File > New File > R Markdown > From Template > mybeamer
2) modify the yaml according to your need
3) place logo.png (maybe the school badge) in the `figs` folder
4) Click `knitr`

You will get your presentation in PDF format.

