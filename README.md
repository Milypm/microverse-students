# Microverse Students Fork & Pull Practice Project
A project for Microverse Students to practice GitHub fork and pull requests.

[Visit live page here](https://brenoxav.github.io/microverse-students/)

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

Now clone the forked repository to your machine. Remember this is the repository associated with your account.

```
git clone url:<your-github-username>/microverse-students
```

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd microverse-students
```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b add-breno-xavier
```

## Make necessary changes and commit those changes

Now open `index.html` file in a text editor, copy the 'article' element with the class 'student-card', paste it after the last 'student-card' in the file and update the required elements with you own personal info. Now, save the file.



Add those changes to the branch you just created using the `git add` command:

```
git add index.html
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> Student Card"
```

replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

Now submit the pull request.

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.