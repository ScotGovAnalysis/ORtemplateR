This directory contains any files that are used as input data only and that 
aren't altered by the project. Not all data 
needs to be kept in the project itself, and in many cases it may be preferable 
to hold data elsewhere.
For example, if two projects both use the same data, it would make sense to keep 
the data separately and import it to each project, rather than duplicate the 
storage of the data.
This approach saves storage space, reduces the chance of conflicting results 
from different projects using different data versions, and simplifies the 
management of sensitive data.

## What to do with this README file

If you follow the advice below to have git ignore the contents of the /raw 
directory, then it is useful to keep this README file, so that the directory 
itself will still remain in the cloned file structure.

It is also useful to use this file to describe files that need to be in this
folder for the project to work, and where the data comes from.

## Version control

Version controlling data held in spreadsheets or delimited formats isn't ideal. 
It's difficult to track changes, and it takes up a lot of space. It's 
preferable, where possible, to use a database. If you want to maintain this 
directory in local versions of the project without writing the contents to Git, 
add the following to the .gitignore:

data/raw/*

!data/raw/README.md
