Welcome to templateR!

templateR is a repository that will quickly get you set up with a templated,
version-controlled directory structure and an RStudio project for a new R
project. templateR is the result of creating a bare-bones
[ProjectTemplate](http://projecttemplate.net/) project and adding an
[RStudio](http://rstudio.com) project configuration file.

You must have the ProjectTemplate R package installed and, optionally, a copy
of RStudio installed.

To use this repository, do the following:

1. [Fork](https://help.github.com/articles/fork-a-repo) this repo.
2. Clone your copy of the repo to your local directory:  
```
git clone https://github.com/$USER/templateR.git $REPO
```  
NB: Replace `$USER` with your own GitHub user name, and `$REPO` with whatever you want
to name your local repository.
3. If you use RStudio and want to open the project, click on the `Project`
button in the upper-right-hand side of the window, then select `Open
Project...`. Select the folder you just created above when you cloned the repository from GitHub.
4. Load the project in RStudio (optional):

```
library(ProjectTemplate)
load.project()
```
