# How to use this template

This template R project comprises several directories that you are
likely to make use of. Each directory contains its own README file to
explain what types of file should go in that directory. You can
repurpose these README files to explain the contents of the directory.

Each README offers guidance on how to handle version control.

This template is organised as an R Project. Further details of the benefits of
R projects can be found [here](https://scotsconnect.sharepoint.com/sites/StatisticsGroup-Org-SG/SitePages/Coding-Good-Practice.aspx#use-rstudio-projects)

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

Version control is the practice of tracking and managing changes to files. 
We recommend using [Git](https://git-scm.com/) for version control, and this 
template is set up accordingly. Guidance for using Git in Scottish Government 
and Git training resources can be found [here](https://scotsconnect.sharepoint.com/sites/StatisticsGroup-Org-SG/SitePages/Version-Control.aspx)

The .gitignore file sits in this root folder. Use it to control parts of the
project that you don't want to include in Git version control, such as
data (particularly sensitive data). The template is set up to ignore
files in the data and outputs directory, except for the readme.

## Project settings

Rstudio projects can be set to automatically save your environment (variables, 
functions, etc.) at the end of your session, and/or reload it at the start of
the next session. This is generally bad practice because it hinders 
reproducibility: you can end up with code that only works if the workspace is
available, and it may be impossible to trace how that workspace was created.

This template has set the project to not save or reload the workspace, even if
your global RStudio options are set to do so. If you wish to change this, then
you can change the project settings in RStudio or edit the .Rproj file, but do
so at your own risk.

## Quality Assurance

Analysis projects should be quality assured. The assurance should be 
proportionate to the potential effect it will have and the size and complexity 
of the analysis. The level of assurance should be guided by a structured 
assessment of the business risks.

[The Aqua Book](https://www.gov.uk/guidance/the-aqua-book) explains the
Quality Assurance process and how to tailor it to the complexity and 
importance of your project.

[The Duck Book](https://best-practice-and-impact.github.io/qa-of-code-guidance/intro.html)
gives more specific guidance on Quality Assuring code.

Quality Assurance should be logged. More information is provided in the 
/documentation/Readme.md file.
