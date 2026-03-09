This optional directory contains end products produced by the project.

Examples of files to include:
* Image files with charts
* Spreadsheet or delimited files with tables formatted for publication or
for customers
* Knitted html or Word documents

It may be useful to divide this directory into sub-directories, e.g. plots,
reports, tables.

It may be preferable to write outputs to a directory outwith the project, in 
which case this directory can be deleted.

## What to do with this README file

If you follow the advice below to have git ignore the contents of the outputs 
directory, then it is useful to keep this README file, so that the directory 
itself will still remain in the cloned file structure.

It is also useful to use this file to describe files that are written to this 
folder, what they are for, and to whom (if anyone) they ought to be sent.

## Version control

If the project is built to be reproducible, it should be possible to exactly 
recreate the outputs, and therefore they do not need to be included in version 
control.
It should be clear from the output (e.g. metadata, naming conventions) how to 
reproduce it. If you want to maintain this directory in local versions of the 
project without writing the contents to Git, add the following to the 
.gitignore:

outputs/*
!outputs/README.md
