# Welcome to templateR!

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

    **Note:** Replace `$USER` with your own GitHub user name, and `$REPO` with whatever you want
to name your local repository.

3. If you don't plan to use RStudio, you're all done. Simply use
   ProjectTemplate as you normally would by navigating to the root
folder of your repo within R and issuing the following commands:   

    ```
    library(ProjectTemplate)  
    load.project()
    ```

    If you're using RStudio, read on.

4. Rename the RStudio project file by renaming the file `NewProject.Rproj`:    

    ```
    mv NewProject.Rproj $NAME   
    ```

    where you should replace `$NAME` with the new name of the RStudio
project.

5. Open the project in RStudio. Click on the `Project`
button in the upper-right-hand side of the window, then select `Open
Project...`. Select the folder you just created above when you cloned the repository from GitHub.
6. Do step 3 above to get started. Head over to the [ProjectTemplate](http://projecttemplate.net) website to learn more.  Happy analyzing and committing!
