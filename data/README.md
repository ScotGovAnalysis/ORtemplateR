This directory contains data used by your project. Not all data needs to be kept 
in the project itself, and in many cases it may be preferable to hold data 
elsewhere.
For example, if two projects both use the same data, it would make sense to keep 
the data separately and import it to each project, rather than duplicate the 
storage of the data.
This approach saves storage space, reduces the chance of conflicting results 
from different projects using different data versions, and simplifies the 
management of sensitive data.

The directory is divided into two sub-directories: /raw and /processed.

* /raw is for any files that are used as input data only and that aren't altered
by the project.
* /processed is for any files that are produced within the project and that are
readable by R (if they aren't produced by the project, then they go in 
/extdata/raw and if they aren't readable by R they go in /outputs)


## What to do with this README file

As long as you are not putting any files directly into the data folder, and
are instead using the /raw and /processed sub-directories, you can delete this
file.

## Version control

Version controlling data held in spreadsheets or delimited formats isn't ideal. 
It's difficult to track changes, and it takes up a lot of space. It's 
preferable, where possible, 
to use a database. If you want to maintain this directory in local versions of 
the project without writing the contents to Git, add the following to the 
.gitignore:

data/*

!data/README.md

!data/raw

!data/processed
