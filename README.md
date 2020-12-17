# GitHub

GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on
projects from anywhere. GitHub is home to more than 0 Million developers, You can work on GitHub for your personal
or public project from anywhere. GitHub works with version control system `git`. 

> ### What is `git`? 
> `Git` is an open-source version control system that was started by Linus Torvalds—the same person who created the Linux
kernel. Version control systems keep these revisions straight, storing the modifications in a central repository. 
This allows developers to easily collaborate, as they can download a new version of the software, make changes, and 
upload the newest revision. Every developer can see these new changes, download them, and contribute.

If you're new to GitHub and git you can find quick guide below to get started. The guide walks you through the basics
of using git and GitHub from installation and beyond.

If you know and used `git` and `GitHub` before you can find guides on specific topic from the table bellow.

## Getting Started

To get started using `GitHub` you need to create an account first, then you can follow along.

This tutorial teaches you GitHub essentials like repositories, branches, commits, and Pull Requests. You’ll create 
your own Hello World repository and learn GitHub’s Pull Request workflow, a popular way to create and review code.

### I - Installation

To start using `git` you have to first install it on your PC or Mac. see the following installation guides depending
on your platform.

* **Windows:** `git` does not come with windows installed thus you have to download and install it from 
[here](https://git-scm.com/download/win). download the architecture that fits your OS ( bit 64 or 32 bit).
After installing that your good to go.

* **MacOS:** There are several options for installing Git on macOS. recommended way is using `homebrew`. 
To install it using `homebrew` use:
```bash
 brew install git
 ```
 
* **Linux:** `Git` insallation on linux varies from distro to distro. Depending on your distro. <br>
For Ubuntu
```bash
sudo apt-get update
sudo apt install git
```

For CentOS, Fedora or related linux distros.
```bash
sudo dnf update
sudo dnf install git
```

### II - Git Configuration

After intalling `Git` on your OS there is one configuration you have to do before starting to use `Git`.
You need to configure `Git` to know who you are for credit. Configure it with you username and email.
```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@yourdomain.com"
```

Now that you have done that you're good to go.

### III - Create You're First Repo.
A repository (usually abbreviated to “repo”) is a location where all the files for a particular project are stored. 
Each project has its own repo, and you can access it with a unique URL. A repository is usually used to organize a 
single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets – anything 
your project needs.

#### To create a new repository
In the upper right corner, next to your avatar or identicon, click  and then select New repository.
1. Name your repository hello-world.
2. Write a short description.
3. Select Initialize this repository with a README.

![new-repo](https://guides.github.com/activities/hello-world/create-new-repo.png)

Click `Create repository`

> Great you have created your new repository.

### IV - Create a new branch

> Branching is the way to work on different versions of a repository at one time. Lets say that you have a software
and want add new feature you don't want add the source code of your new feature right into the main code base before
testing it for a bug. A way to do this safely is to create a branch where you can implement the new feature and test
it without breaking or disrupting the main code base. When the feature is fully implemented and you want to release
your new feature you merge it.

By default your repository has one branch named main which is considered to be the definitive branch. We use branches 
to experiment and make edits before committing them to main.

When you create a branch off the main branch, you’re making a copy, or snapshot, of main as it was at that point in time. 
If someone else made changes to the main branch while you were working on your branch, you could pull in those updates.

This diagram shows:
* The main branch
* A new branch called feature (because we’re doing ‘feature work’ on this branch)
* The journey that feature takes before it’s merged into main

![branches](https://guides.github.com/activities/hello-world/branching.png)

#### To create a new branch
Go to your new repository hello-world.
* Click the drop down at the top of the file list that says branch: main.
* Type a branch name, readme-edits, into the new branch text box.
* Select the blue Create branch box or hit “Enter” on your keyboard.

![new-branch](https://guides.github.com/activities/hello-world/readme-edits.gif)

Now you have two branches, and . They look exactly the same, but not for long! Next we’ll add our changes to the new branch.

### V - Make and commit changes
Bravo! Now, you’re on the code view for your branch, which is a copy of . Let’s make some edits.

On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining 
why a particular change was made. Commit messages capture the history of your changes, so other contributors can understand 
what you’ve done and why.

#### Make and commit changes
1. Click the README.md
2. Click the pencil icon in the upper right corner of the file view to edit.
3. In the editor, write a bit about yourself.
4. Write a commit message that describes your changes.
5. Click Commit changes button.

![commit](https://guides.github.com/activities/hello-world/commit.png)

Step 4. Open a Pull Request
Nice edits! Now that you have changes in a branch off of , you can open a pull request.main

Pull Requests are the heart of collaboration on GitHub. When you open a pull request, you’re proposing your changes and requesting that 
someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content 
from both branches. The changes, additions, and subtractions are shown in green and red.

As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.

By using GitHub’s @mention system in your pull request message, you can ask for feedback from specific people or teams, 
whether they’re down the hall or 10 time zones away.

You can even open pull requests in your own repository and merge them yourself. It’s a great way to learn the GitHub 
flow before working on larger projects.

#### Open a Pull Request for changes to the README
Click on the image for a larger version

| Setps  | Screenshot |
| ------------- | ------------- |
| Click the  `Pull Request` tab, then from the Pull Request page, click the green `New pull request` button.  | ![screenshot](https://guides.github.com/activities/hello-world/pr-tab.gif)  |
| In the Example Comparisons box, select the branch you made, `readme-edits`, to compare with main (the original). | ![screenshot](https://guides.github.com/activities/hello-world/pick-branch.png)  |
| Look over your changes in the diffs on the Compare page, make sure they’re what you want to submit. | ![screenshot](https://guides.github.com/activities/hello-world/diff.png)  |
| When you’re satisfied that these are the changes you want to submit, click the big green **Create Pull Request** button. | ![screenshot](https://guides.github.com/activities/hello-world/create-pr.png)  |
| Give your pull request a title and write a brief description of your changes. | ![screenshot](https://guides.github.com/activities/hello-world/pr-form.png)  |

> When you’re done with your message, click **Create pull request**!

### VI - Merge your Pull Request
In this final step, it’s time to bring your changes together – merging your readme-edits branch into the main branch.

1. Click the green Merge pull request button to merge the changes into main.
2. Click Confirm merge.
3. Go ahead and delete the branch, since its changes have been incorporated, with the Delete branch button in the purple box.

![merge](https://guides.github.com/activities/hello-world/merge-button.png)
![delete](https://guides.github.com/activities/hello-world/delete-button.png)

> Thats it you have successfully used some of the core features that GitHub offers. You have done all this without leaving the browser, Lets see how we can use `Git`
and `GitHub` in creating a mini website locally.



