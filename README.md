
<p align="center" width="100%">
<img src="https://pbs.twimg.com/profile_images/1567906020831150081/oJ7mKaaj_400x400.jpg" width="300">

# <p align="center">[Contribute To This Project](https://ayush-dixit-15.github.io/Reponsive-webpage/)</p>



</p>

# How to contribute:

This project aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.



<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

#### If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).

## Step 1 :- Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Step 2 :- Clone the repository

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/this-is-you/first-contributions.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Step 3 :- Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-contributions
```

Now create a branch using the `git switch` command:

```
git switch -c your-new-branch-name
```

For example:

```
git switch -c add-alonzo-church
```

## Step 4 :- Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add your-name to Contributors list"
```

replacing `your-name` with your name.

## Step 5 :- Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin -u your-branch-name
```

replacing `your-branch-name` with the name of the branch you created earlier.

<details>
<summary> <strong>If you get any errors while pushing, click here:</strong> </summary>

- ### Authentication Error
     <pre>remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
  remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
  fatal: Authentication failed for 'https://github.com/<your-username>/first-contributions.git/'</pre>
  Go to [GitHub's tutorial](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) on generating and configuring an SSH key to your account.

</details>

## Step 6:- Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

## Step 7:- Now submit the pull request.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the main branch of this project. You will get a notification email once the changes have been merged.
<br><br><br>
     

## <strong> Rules </strong>

<p id= "guide">
1. For PRs to be counted into your participation in Hacktoberfest, they must be merged between October 1st and October 31st.<br>
2. Contributions must be made to public repositories.<br>
3. If a PR has a label that contains the word spam in it, the PR will not be counted. Also, if a participant has 2 or more spam PRs, they'll be disqualified from Hacktoberfest.<br>
4. If a PR has a label that contains the word invalid, it will not be counted. The exception for this is if the PR also has the label hacktoberfest-accepted.<br>
<br><br><br>


#### **Read the official hacktoberfest guidelines:**👇🏻👇🏻👇🏻

[https://hacktoberfest.com/participation/#pr-mr-details](https://hacktoberfest.com/participation/#pr-mr-details)<br>
[https://hacktoberfest.com/participation/#spam](https://hacktoberfest.com/participation/#spam)
