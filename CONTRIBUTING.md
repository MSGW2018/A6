# How to contribute to this repository

This is the repository where we will be creating the content for Assignment 6. This document explains exactly where and how you need to modify the example content to add your own and thus complete A6 [as described in ALUD](https://alud.deusto.es/mod/assign/view.php?id=15863). 

This assignment will be carried out in three different stages:

1. Stage 1: content creation. Each group will create the content regarding the specific topic they need to work on in their own branch in this repository.
2. Stage 2: revision. Each student will be assigned a number of pages from a different group, and will need to revise and contribute to those documents.
3. Stage 3: final merge. Each group will finish the editing on their own pages, and we will merge all branches into the `master` branch.

The following sections explain the step-by-step for each of these stages.

## Previous steps

First, you need to create an account on GitHub and follow the [101 Introduction to GitHub](https://services.github.com/on-demand/intro-to-github/) tutorial. We did this in class, so make sure you do it on your own if you didn't. It will get you to the basics of how GitHub works, which will be necessary for you in this assignment.

Then you need to be part of the [MSGW2018 organization on GitHub](https://github.com/MSGW2018). All of you got an invite to join the organization, either directly through your GitHub account if you have one, or through email if you still don't. Let me know if you didn't get an invite or otherwise have problems joining the organization. I will then add all organization members as collaborators to the Assignment 6 repository (this repository). 

All this is necessary to go on with the following steps.

## Stage 1: content creation

Each group will create their content in their own branch in this repository. To do this, first designate **one member of the group** to carry out this first setup tasks: creating a branch for your group's additions. To do this:

1. Click the `Branch: master` button to the top-left on the repository page
2. Write a name for the new branch. It has to be descriptive of the topic you will be working on, so if your topic title is, for example, _Sample topic_, you could name the branch `sample-topic`.
3. A blue button should appear in the dropdown (you are not correctly set as a collaborator to the repository if it doesn't, let me know), with the text _<i class="fa fa-code-branch"></i> Create branch: sample-topic (from 'master')_. Click that.

<!-- FORK VERSION
1. Fork [the _central_ repository of the assignment](https://github.com/MSGW2018/A6) to your personal account. To do this:
   1. Click the [<i class="fa fa-code-branch"></i> Fork](https://github.com/MSGW2018/A6#fork-destination-box) button to the top-right on the repository page 
   2. Choose your profile picture on the `Where should we fork this repository?` pop-up window
   3. It will take you to your forked repository, with an URL in the form of 
`https://github.com/YOUR-USERNAME/A6`
2. Change the name of the repository to include your group number. To do this:
   1. Click the `Settings` tab 
   2. In the `Repository name` field, change the name to `A6-group0`, where `0` must be your group number. If you were Group 9, for example, your repository should be named `A6-group9`
   3. Click the `Rename` button
3. Add your teammates as collaborators to the repository. To do this:
   1. Click the `Settings` tab if you are not already in the Settings
   2. Select `Collaborators` from the menu on the left
   3. Search your teammates by username and add them

Now all the group members have permission to edit the repository. The following steps will describe the contents present in the repository you forked, and where you need to add your contents and editions. 
-->

You have created a branch where you and the rest of your group members will be creating the content for this assignment. 

Now each of you need to `clone` (create a copy in your own computer) the repository to work on it. You will find more detailed instructions for his in the official  [GitHub Desktop User Guides](https://help.github.com/desktop/guides/). For the purposes of this assignment, follow these steps:

1. Install [GitHub Desktop](https://desktop.github.com/) (download and setup)
3. Clone this repository to your computer (see the [official documentation](https://help.github.com/desktop/guides/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop/))
	1. Go to the [repository front page](https://github.com/MSGW2018/A6) and click the `Clone or download` green button to the right of the page
	2. Click the `Open in Desktop` button. This will open GitHub Desktop in the repository clone setup window
	5. In `Local path`, select where you want to store the repository folder in your hard drive
	6. Click the `Clone` button. The repository files are now in your computer
3. Change to _your_ branch, the branch your group will be generating content into. In GitHub Desktop, click the _<i class="fa fa-code-branch"></i> Current branch **master**_ button and select your branch from the dropdown

You would now go on and add content to the files in your computer, create new files, etc. Compared to editing files through the GitHub.com interface (which is what you did in the GitHub 101 tutorial), using GitHub Desktop will allow for more complex work, such as committing more than one modification at once, for example.

See the 'sample-topic' folder as an example. Each topic will have its own folder, so coordinate with the rest of your group and create the folder where you will be adding your files. Also, you may begin to write the _front page_ of your topic, or decide how many and which pages you will have in your folder and create them. 

Once you have a significant (in the sense of _with a unique meaning_, not necessarily _big_) set of modifications, you should [commit them through GitHub Desktop](https://help.github.com/desktop/guides/contributing-to-projects/committing-and-reviewing-changes-to-your-project/). This will save the _new versions_ of the project that you have been creating in your computer. The next step, at least when you finish your work session (but more often if you want to), would be to push your commits to the remote repository by clicking the `Push origin` button in GitHub Desktop (always make sure **your branch** is selected). This will update your branch on the shared repository in GitHub, _in the cloud_.

The next time you want to start working on the assignment, it is important to note that your teammates may have been making changes to the shared repository in the cloud in the meantime. If this has happened, you will see a small number with a downward arrow in the `Pull origin` button of GitHub Desktop. Click that, and your copy (the copy in your computer) of the repository will be updated to match the shared one in the cloud. This should always be your first step when you plan to start editing your files for this assignment, as merge conflicts may occurr otherwise which are more difficult to solve. 

One final point to have in mind for this content creation stage is that we will be using Markdown to format the content in our files. The specifics of what Markdown is and how it can be used are explained in detail in the following section.

### Markdown

We are going to use Markdown to format our content in this project. [From Wikipedia](https://en.wikipedia.org/wiki/Markdown):

> **Markdown** is a lightweight markup language with plain text formatting syntax.
> 
> (...)
> 
> The key design goal is _readability_ – that the lan guage be readable as-is, without looking like it has been marked up with tags or formatting instructions, unlike text formatted with a markup language, such as (...) HTML, which have obvious tags and formatting instructions. 

You will find the [basics about its syntax in the GitHub Help](https://help.github.com/articles/basic-writing-and-formatting-syntax/) which you can use as reference or through the [Mastering Markdown GitHub Guide](https://guides.github.com/features/mastering-markdown/). Additionally, you can also follow this [simple Markdown tutorial](https://www.markdowntutorial.com/
) if you need a more guided solution, or even the [more thorough Codecademy course](https://www.codecademy.com/courses/web-intermediate-en-Bw3bg/0/1
).

### Pull requests during class time

We will be doing at least one pull request per week during class time, so as to merge the content you have been creating into the `master` branch of the repository. To do this (required to do only once per group):

1. Navigate to the repository front page and make sure your working branch is selected (for example https://github.com/MSGW2018/A6/tree/sample-topic)
2. Just below the branch selection dropdown, you will see a message that says `This branch is XX commits ahead of master.`, and `Compare` and `Pull request` buttons to its right. Click on `Pull request`
3. In the `pull request` creation page:
   - Describe your pull request. Add a descriptive title, and explain your main modifications in all the commits that will go with this pull request (you can see a summary below the form). 
   - In the `Reviewers` area to the right, add me (@mberasategi) as a reviewer
   - In the `Milestone` area to the right, select the _Content creation stage_ from the dropdown
   - Click `Create pull request`

Once the pull request is created, we will use that page to discuss your modifications and make further changes if needed. Once they are approved, we will merge them into the master branch. 


## Stage 2: revision

For the revision stage, each of you have been assigned between 2 and 3 pages by other groups to revise. Check [the `Issues` tab](https://github.com/MSGW2018/A6/issues) and search for `Everything assigned to you` in the `Filters` dropdown in the search box to easily access the issue with your list of assignations. 

Remember that the revision stage is an individual activity. As you have in [the assignment description](https://alud.deusto.es/mod/assign/view.php?id=15863), it is an individual responsibility to assess and contribute to some of your classmates' pages. As such, your individual task will be to review and edit them. 

Contributions should include:

- Substantive textual additions or editing (e.g. reorganizing/revising text, adding sections, etc.).
- Thorough and accurate copyediting/proofreading (e.g. grammar, spelling, fact-checking, documentation).
- Adding internal and external links and tags.
- Adding other media (e.g. adding an appropriate YouTube video).

Also remember that, to document your individual work, you must do so using your personal account. The individual evaluation will be carried out only on what is found through your recorded activity in this repository.

There are two ways in which you can carry out revisions on your assigned pages: by actually editing them, or by discussing your suggestions for edition in your issue. 

### Actually editing the files

The most usual would be that you actually edit the files that you a reviewing to add your contributions and modifications to the page. To do so:

- Create a branch named `yourusername-rev`
- Using GitHub Desktop, switch to that branch 
- Always pull first, because there are other classmates reviewing the same content and they may have pushed modifications since the last time you pulled
- Modify the files that you are reviewing, commit changes (remember to add descriptive commit messages, which is still more important now that you are editing content by someone else), and push when necessary
- When you have finished your modifications and contributions to one file, check it in your issue
- When you have finished your modifications to all your assigned files, open a pull request to merge your branch to the `master` branch: `base:master` :arrow_backward: `compare:yourusername-rev`. Remember to:
   + Give a general description of your contributions to the content
   + Mention your issue (you mention an issue by giving its number like this: `#00` )
   + Mention the group that created the content (you mention all members in a group like this: `@MSGW2016/Group0`)
   + Add me as a reviewer (in the righthand side of the `Open a pull request` screen)
   + Set the Milestone to `Revision stage`

### Discussing suggestions 

It may happen that you consider major revisions are necessary but beyond your responsibility as a reviewer. In that case, you could add a comment to your issue mentioning the group responsible for the pages (you mention all members in a group like this: `@MSGW2016/Group0`), describing your suggestion as thoroughly as possible.

### Doing additional reviews

The ones you have in your assigned issue are the **compulsory and minimum reviews** you need to make for this assignment. Feel free to **make as many additional reviews as you like**, as they will contribute to improve your final grade and also the overall quality of the document.

Make sure you add them as task-list elements to a comment in your issue to make it easier for me to track. The syntax to create a task list element is as follows:

```
- [ ] [Page title](page-url.md)
```

## Stage 3: final merge

---

**WORK IN PROGRESS**

## Further references

[GitHub Flow](https://guides.github.com/introduction/flow/)