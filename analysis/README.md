This directory contains R scripts and Rmarkdown files for individual pieces of analysis. (Rmarkdown files should be set up to write to the outputs directory).

Consider Duck Book guidance on modular code (https://best-practice-and-impact.github.io/qa-of-code-guidance/modular_code.html):
* Write independent pieces of logic as functions, to minimise repetition and to make it easier to separate the project into modules

Consider Duck Book guidance on readable code (https://best-practice-and-impact.github.io/qa-of-code-guidance/readable_code.html):
* Make the code easy for yourself and others to understand by:
** Using informative and concise variable names
** Using a self-consistent code style (https://style.tidyverse.org/ is an example, but what style you use is less important than being self-consistent)
** When writing functions (and classes), describe the purpose, inputs and outputs
** Use comments to describe why code is written in a particular way

Functions and classes should generally speaking go in the R directory, so that they can be used by different pieces of analysis.

## Version control

Every R script and Rmarkdown in this folder should be subject to version control, e.g. through Git.
