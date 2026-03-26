This directory contains functions (and potentially classes) used in the project, that should be loaded at the start of any session.

Consider 
  <a href="https://best-practice-and-impact.github.io/qa-of-code-guidance/modular_code.html"
  target="_blank" rel="noopener noreferrer">
Duck Book guidance on modular code</a>:

* Write independent pieces of logic as functions, to minimise repetition and to make it easier to separate the project into modules

Consider
  <a href="https://best-practice-and-impact.github.io/qa-of-code-guidance/readable_code.html"
  target="_blank" rel="noopener noreferrer">
Duck Book guidance on readable code</a>:

* Make the code easy for yourself and others to understand by:
    * Using informative and concise variable names
    * Using a self-consistent code style (Scottish Government recommends the 
      <a href="https://style.tidyverse.org/" target="_blank" rel="noopener noreferrer">
  tidyverse</a> style, but what style you use is
  less important than being self-consistent)
    * When writing functions (and classes), describe the purpose, inputs and outputs (consider using Roxygen2 formatting)
    * Use comments to describe why code is written in a particular way. See 
      <a href="https://best-practice-and-impact.github.io/qa-of-code-guidance/code_documentation.html#comments"
      target="_blank" rel="noopener noreferrer">
  here</a> for guidance on commenting code.

## Version control

Everything in this folder should be subject to version control, e.g. through Git.
