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
Each project has its own repo, and you can access it with a unique URL.
