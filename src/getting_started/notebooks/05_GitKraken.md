# Git and GitKraken

---

## Purpose

`GitKraken` is a graphical user interface tool for tracking git repos. It 
provides graphs and visual representations of branches to make it easier to 
track who is working on what when. Also, the application provides easy to user 
interfaces to perform all the major local git functions that you would add the 
command line (push, pull, branch, merge, etc). GitKraken is an **optional** 
tool within this team but it may make understanding git easier. This tutorial 
will provide a brief introduction to GitKraken but if you would like more 
information got to [this](https://help.gitkraken.com/gitkraken-client/how-to-install/) 
link to read all of GitKraken's documentation.

## Installing GitKraken

To install GitKraken follow [this](https://www.gitkraken.com) link here. Click 
"Download GitKraken Client Free" and select the version for you OS. Perform the 
normal downloading steps that you would to install any other application and 
then open GitKraken. Sign into your github account upon opening GitKraken to 
get started. For more specific install instructions follow [this] https://help.gitkraken.com/gitkraken-client/how-to-install/tutorial here.

## Opening a Repo

When you first open GitKraken you should be greeted with a screen that looks 
like the one below:

<img src="/images/git/GitKraken/GitKrakenHomeScreen.png" width="50%" style="margin-left: auto; margin-right: auto; display: block;" />

click the "Open a repo" button and then click Open a Repository near the top of 
the pop up window. Using your file explorer navigate to where you cloned the 
git repo you are trying to open, select it, and then click open. When you do 
this GitKraken should bring you to a screen similar to the one below:

<img src="/images/git/GitKraken/RepoHomeScreen.png" width="50%" style="margin-left: auto; margin-right: auto; display: block;" />

## Checking Out and Creating Branches

To check out a branch just double click on the branch name within in the tree 
and watch the a checkmark appear next to the branch name. To create a new branch 
right click on the branch that you would like to branch off of and click 
"Create branch here". Enter your branch name in the box that pops up and then 
click enter.

## Committing File Changes.

When you have file changes waiting to be committed a dotted bubble will appear 
at the top of your git tree. Click on the "// WIP" text box to see the files 
that you can commit on a screen that pops up on the right side. You can 
selectively add files that you want to include in your next commit by hovering 
over the changed files and selecting stage file, or you can commit all changed 
files by clicking the stage all changes button above the changed files. Feal 
free to click on any of the changed files for GitKraken to show you what 
changed in those files. Once you have staged the files you want to commit, write 
a commit message in the text box below the staged files and then click the 
commit changes to 1 file button. 

## Pushing and Pulling

When you are ready to push your changes from a branch, switch to that branch and
click the push button at the top of your screen. If the branch was just created 
it might ask if you want to create an origin for that branch and just click yes.
To pull down the most recent changes to a repository press the pull button at 
the top of the screen. It may default to fetch, but if you press the dropdown 
arrow you can switch to "Pull (fast-forward if possible)".

## Merging

When you want to merge two branches together switch to the branch that you want 
to merge another branch into. Then right click on the other branch and click: 
"Merge 'Other branch name' into 'Current branch name'". If there are merge 
conflicts Gitkraken will guide you through solving them, or you can solve them 
on your own in your own IDE or merge resolution tool. Don't forget to commit and 
push your merge after successfully debugging any merge conflicts.