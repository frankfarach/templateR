# Welcome to templateR!

templateR is a repository that allows you to quickly deploy a templated,
version-controlled directory structure and an RStudio project for a new
R project. templateR is the result of creating a bare-bones
[ProjectTemplate](http://projecttemplate.net/) project and adding an
[RStudio](http://rstudio.com) project configuration file. 

This isn't an R package or anything fancy like that; I'm just making
available something I created to save myself time. I wanted the
simplicity of being able to just clone a repo and automatically have, in
a version-controlled directory, the default structure and RStudio
project that I always work with when I start a new analysis project in
R.

You must have the ProjectTemplate R package
[installed](http://projecttemplate.net/installing.html) and, optionally,
a copy of RStudio
[installed](http://www.rstudio.com/ide/download/desktop).

To use this repository, do the following:

1. [Fork](https://help.github.com/articles/fork-a-repo) this repo. You
   only need to do this the first time.
2. From now on, whenever you want to create a version-controlled default
   project structure, just clone your copy of the repo to your local directory:  

    ```
    git clone https://github.com/$USER/templateR.git $REPO
    ```   

    **Note:** Replace `$USER` with your own GitHub user name, and `$REPO` with whatever you want
to name your local repository.

3. If you don't plan to use RStudio, change the working directory to
   your local repo path in R and skip to Step 6. 
4. If you wish, rename the RStudio project file by renaming the file `NewProject.Rproj`:    

    ```
    cd $REPO
    mv NewProject.Rproj $NAME   
    ```

    where you should replace `$REPO` with the path to your local
repository and `$NAME` with the name of your RStudio project.

5. Open the project in RStudio. Click on the `Project`
button in the upper-right-hand side of the window, then select `Open
Project...`. Select the folder you just created above when you cloned the repository from GitHub.

6. Issue the following commands at the R console:

    ```
    library(ProjectTemplate)
    load.project()
    ```

7. Watch this [video](http://www.youtube.com/watch?v=I9YNIi-QmR0) on
   using R, ProjectTemplate, RStudio, and GitHub to learn more. Happy
analyzing and committing!
