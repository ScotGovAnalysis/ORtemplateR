This directory contains data used by your project. Not all data needs to be kept in the project itself, and in many cases it may be preferable to hold data elsewhere.
For example, if two projects both use the same data, it would make sense to keep the data separately and import it to each project, rather than duplicate the storage of the data.
This approach saves storage space, reduces the chance of conflicting results from different projects using different data versions, and simplifies the management of sensitive data.

(The reason this directory is called "extdata" rather than simply "data" is that data is a special folder in R packages that is specifically for R objects that are available to the package user.
To minimise disruption as and when converting a project to a package, it is preferable to start with extdata. https://r-pkgs.org/data.html has more info on data folders in packages.)

## Version control

Version controlling data held in spreadsheets or delimited formats isn't ideal. It's difficult to track changes, and it takes up a lot of space. It's preferable, where possible, 
to use a database. If you want to maintain this directory in local versions of the project without writing the contents to Git, add the following to the .gitignore:

extdata/*
!extdata/README
