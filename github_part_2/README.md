# GitHub (Part 2)

## Assignment Format
One goal of these GitHub tutorials will be getting you used to looking at documentation.  You will likely do this quite often when working with a programming language, whether you've been working with it for 12 days or 12 years!  

With that said, **I still want to help you with these assignments**.  So, if you have questions about how to do this, please do not be afraid to post on Piazza, as either I or another classmate will be there to answer and/or help to the best of our abilities.  Feel free to collaborate with other students on this as well -- just make sure that you are *collaborating*, not *copying*.

## Recent Git Updates
  * If you have Git 2.23.0 or newer, you can use [git switch](https://salferrarello.com/git-switch/) to switch to a branch.  Otherwise, keep using `git checkout branch_name` to start making changes to an existing branch or `git checkout -b branch_name` to make a branch and start making changes to it.

## Assignment Motivation
  As you get more into coding big projects with other people, you will notice that it's difficult to all work on the same set of code without having to keep some convoluted method of updating each other's versions -- that is what GitHub is designed to help with.  
  You may even want to add a specific feature that will take a long time (e.g. a new character in fighting game) or test something (e.g. a different menu design in a piece of software) without messing up the "good" version of your code, i.e. the `main` branch.  This is what branching allows you to do; you can work on a very specific task on a separate copy of the repo and then merge it into the `main` branch when it's finished, or you can delete it if it ends up not working out correctly.  Branching lets you do very specific task without committing all the in-between steps to `main`, which helps keep your repo better-organized.

## Assignment Outline
1. **Make a branch of your cs 191 repo called `part_2`.**  
    * Here is [A Short Guide to Branching/Merging on GitHub](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging), and you should only need the first few lines.
    * I recommend immediately pushing your branch (with no changes) to GitHub to make sure that it was created successfully.  If you create and switch to your branch with the command `git checkout -b part_2`, you can immediately push it to remote with the command `git push origin part_2`.  Note that you're choosing `part_2` instead of `main` (previously called `master`) as the 2nd argument, since you are now pushing to the `part_2` branch of the repo.  If you do this correctly, you'll be able to select that branch on the repo's page in addition to seeing that your repo now has `2 branches` at the top of the page.

1. **Solve the *Crazy Cut* puzzle.**
    * Given the shape below, draw one line on it that divides it into two identical parts.  This line does not have to be straight (so it can change directions) as long as it's a single line.  I recommend opening it up in an image editor like Paint and simply drawing the line and saving the image.

    ![Crazy Cut Puzzle](images/crazy_cut_puzzle.png)

1. **Upload your solution to the *Crazy Cut* puzzle to your `part_2` branch.**  
    * **IMPORTANT**: Make sure that you are making changes to the `part_2` branch!  You can check your current branch with the command `git branch`, and it should look something like this:
          git branch
          * part_2
            main
    * Add a folder called `part_2/`.  All of your for this homework should take place in this folder.
    * Add a README.md to `part_2/` (so `part_2/README.md`).
    * Using Git Markdown, cleanly present your solution in the `/part_2/README.md` file.  You are required to at least add an image of your proposed line to your repository and reference it using Git Markdown, and feel free to add any additional explanation above/below it.  As a reminder, here's a [Guide to Mastering Markdown](https://guides.github.com/features/mastering-markdown/) that presents 2 different ways of adding images to Markdown.  You can either make an `images/` folder in part_2 (resulting in `part_2/images/`) or just add your image to the `part_2/` folder.  It's usually better organization to make a dedicated folder for images/figures.  You can check that the reference to the image works if it shows up on the page!  Don't worry if you have to make a quick push immediately after realizing the image doesn't load -- this happens all the time.  

1. **Merge your branch into `main` by creating a pull request.**
    * Before merging, you need to create the pull request.  Here's a [Guide to Creating a Pull Request](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).  While it's doable using the command line, I've always found it to be easier to create pull requests using the web interface.  If you're interested in doing it through the command line, here is [the documentation for `git request-pull`](https://git-scm.com/docs/git-request-pull).
    * In general, you'll want your title and description to be somewhat informative, in this case it's not important but in a real-world scenario it's very helpful.  Here is [a helpful article about writing the description and title of a pull request](https://github.blog/2015-01-21-how-to-write-the-perfect-pull-request/).
    * After successfully creating a pull request, you need to approve and merge it into `main`.  Here's a [Guide to Merging Pull Requests](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/merging-a-pull-request).
    * Although it seems silly to make a pull request on your own repo and immediately merge it, many companies do this!  It's an easy way to keep track of changes, and since branches often add new/unusual features, it's helpful to make a pull request to note that you're merging a branch.  In a larger company, making a request would also other flag other developers to review your changes before fully merging into `main`.

1. **Make a fork of the [`cs-191-fys-f21` repository](https://github.com/zwhile/cs-191-fys-f21)**.
    * Here is a [Guide to Forking a Repo](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo).
    * Make sure to [clone the repository](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository) to your local machine so that you can make edits to it.
    * One often forks a repository if they want a copy of the repo to add their own features/changes, and sometimes this results in making a pull request at the original repo so that they can consider adding your features/changes.  The fork also keeps track of changes made in the original repo.
    * When it comes to committing/pushing, treat a fork as you would any other code in your own repo -- the only difference is that the code starts out as someone else's.  
    * With that said, be aware that the fork will always identify itself as such, and you should never fork someone else's repo and then claim the entirety of it as your own.  It is often good manners to acknowledge that a repo is a fork somewhere in its README as a respectful nod/citation to the original creator.  GitHub will always remember anyway, though.

1. **Make a branch on your fork; the only change will be that you must add your GitHub username onto this task list below my name:**
    - [X] zwhile
    - [X] JonahOsborne
    - [X] Jiexyy
    - [X] CalebTeeter
    - [X] noamgans
    - [X] amotupalli7
    - [X] Mutter-Liam
    * Even though you are making a fork of *my* repository, **please make a branch on your fork where the branch's name is your username**.  So if I were doing this, my branch on my fork would be `zwhile`, since that is my GitHub username.
    * The only change you need to make is adding your username and a checkbox, like my username has now.  You should be able to see the required change/format in a text editor.
    * Make sure to push your changes to **your branch** on **your fork**!  Like above, you can check which branch you're working on by using the command `git branch`.  Once you've cloned the repo, pushing to a fork is the same as pushing to a normal repo (and the same goes for branches of a fork).

1. **Make a pull request <u>on my repo</u> for me to merge your fork's changes into my repository.**
    * The steps to do this should be very similar to the previous pull request you made, this time it's just on *my* repository.
    * Here's a [Guide to Creating a Pull Request from a Fork](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork).
    * Be aware that I will comment on and/or deny the pull request if anything is incorrect (such as the branch name and/or the changes you made) since accepting your pull request visibly changes the repo.  The comments will just let you know what changes need to be made before resubmitting your pull request.

1. **Submit a link to your repo as the homework submission on Moodle.**
 
1. **OPTIONAL:** If you see any spelling errors (or other errors in general) on this repo, open an issue!
    * Here's a [Guide to Opening Issues on GitHub](https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/creating-an-issue).
    * This won't count for extra credit, but it's good practice for opening issues on GitHub!
