This directory contains files produced by the project.

Examples of files to include:
* Image files with charts
* Spreadsheet or delimited files with formatted data
* R objects

## Version control

If the project is built to be reproducible, it should be possible to exactly recreate the outputs, and therefore they do not need to be included in version control.
It should be clear from the output (e.g. metadata, naming conventions) how to reproduce it. If you want to maintain this directory in local versions of the project without writing
the contents to Git, add the following to the .gitignore:

outputs/*
!outputs/README
