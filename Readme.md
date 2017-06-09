# How To Github

1. [Create a new repository](https://help.github.com/articles/creating-a-new-repository/) on Github by the **_New Repository_** button or the **_+_** button next to profile picture.  On new page, only need to fill out *Repository name*. No need to worry about any other fields. After the repository has been created, you'll be able to see the URL that will be used to link the repo to the project on your computer.

2. Navigate to your project folder in terminal. You can open terminal from VS Code by clicking on **>_** at bottom blue panel. 

3. Initialize the project as a Git repo by running `git init`. Will only need to do this the first time you set up project.

4. To connect your project to GitHub, run `git remote add origin URL`. The URL is what you get at the end of first step. Also only need to do one time.

5. Add the files to the staging area with `git add .`
    - if you want to see what is in ur staging area that you'll be committing, you can run `git status`

6. Commit the files in your staging area with `git commit -m "commit message"`. Your *commit message* is basically what changes you are making.

7. Then you'll want to push your changes to Github with `git push -u origin master`.