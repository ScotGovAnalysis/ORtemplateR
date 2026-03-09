This directory contains any files that are produced within the project and that 
are readable by R (if they aren't produced by the project, then they go in 
/extdata/raw and if they aren't readable by R they go in /outputs). 

## What to do with this README file

If you follow the advice below to have git ignore the contents of the /processed 
directory, then it is useful to keep this README file, so that the directory 
itself will still remain in the cloned file structure.

It is also useful to use this file to describe files that are written to this 
folder and what they are for.

## Version control

You shouldn't generally need to commit processed data to Git because all users
should be able to create the data using the project. If you want to maintain 
this directory in local versions of the project without writing the contents to 
Git, add the following to the .gitignore:

extdata/processed/*
!extdata/processed/README.md
