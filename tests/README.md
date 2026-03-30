This directory contains anything that tests the R code in your /R directory or 
anything in your analysis directory. Regularly testing code reduces errors.

Whenever you test that a piece of code is doing what you think it's doing, save 
it here. You might need it again in future!

You can include cross-software tests, such as R code that checks a piece of
analysis in Excel, or and Excel spreadsheet that compares the results of R 
analysis with the expected value. However, for reproducibility, it's best to 
work towards doing all R code testing in R.

Refer to https://r-pkgs.org/testing-basics.html for guidance on organising 
testing as you increase the number of tests that you've saved.
It's recommended that you make use of the testthat package.

## What to do with this README file

Leave this file as it is to inform any future users of the project.

## Version control

Everything in this folder should be subject to version control, e.g. through Git.
