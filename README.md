# How to use this template

This template R project comprises several directories that you are
likely to make use of. Each directory contains its own README file to
explain what types of file should go in that directory. You can
repurpose these README files to explain the contents of the directory.

Each README offers guidance on how to handle version control, and what
to do with the directory if you want to convert your project to a
package. In many (possibly most) cases, it will be useful to format your
analysis project as a package for reproducibility and to aid
documentation.

## Making a local copy of the template

There are several options for using the template in your own project. We
recommend one of the following:

1.  Clone the directory with
    `git clone https://github.com/ScotGovAnalysis/ORtemplateR.git`
    a.  then delete the `.git` folder and the LICENCE file.
    b.  rename the .RProj file and the directory to the new name of your
        project
    c.  to use git version control, reinitialise the repository using
        `git init`
    d.  add suitable licence if making the repo public
2.  Download a zip file from GitHub using the green "Code" button, and
    select "Download Zip".
    a.  Unzip the folder.
    b.  rename the .RProj file and the directory to the new name of your
        project
    c.  to use git version control, reinitialise the repository using
        `git init`
    d.  add suitable licence if making the repo public

## Template folder structure

-   root/
    -   analysis/ used for R scripts and Rmarkdown files that run the
        analysis
    -   documentation/ documentation of purpose and ways of working
    -   data/ data used by your project
        -   processed/ for any files that are produced within the
            project
        -   raw/ for any files that are used as input data only
    -   outputs/ contains end products produced by the project
    -   R/ functions (and potentially classes) used in the project
    -   scratchpad/ for code that is rough work - not version controlled
    -   tests/ code that tests the R code in your R/ folder

## What to do with this README file

Use this file to detail the purpose of the project, basic installation
instructions, and examples of usage.

Consider including:

-   Short statement of intent
-   Longer description describing the problem that your project solves
    and how it solves it
-   Basic installation instructions or link to installation guide
-   Example usage
-   Links to other project guidance, for example methodological papers
    or document repositories (if not already in the /documentation
    directory)
-   Links to related projects

## Version control

The .gitignore file sits in this folder. Use it to control parts of the
project that you don't want to include in the version control, such as
data (particularly sensitive data). The template is set up to ignore
files in the extdata and outputs directory, except for the readme.



