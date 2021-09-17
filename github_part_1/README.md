# GitHub (Part 1)

## Assignment Format
One goal of these GitHub tutorials will be getting you used to looking at documentation.  You will likely do this quite often when working with a programming language, whether you've been working with it for 12 days or 12 years!  

With that said, **I still want to help you with these assignments**.  So, if you have questions about how to do this, please do not be afraid to post on Piazza, as either I or another classmate will be there to answer and/or help to the best of our abilities.  Feel free to collaborate with other students on this as well -- just make sure that you are *collaborating*, not *copying*.

## Assignment Outline
1. **Create a GitHub account**, if you haven't already.  You will probably use this in other courses and possibly as an online "resume" of sorts, so I recommend using a more professional username and picture.
1. **Install [Git](https://git-scm.com/downloads) on your computer.**  If you're on Windows, installing with all the default options should give you everything you need.  If you're not sure about something relating to the installation, feel free to post on Piazza.  On Windows, you should be all set to go if you can open the program "Git Bash"; on Linux/Unix/MacOS, you should be able to just type `git` into the command line without getting a "this program is not installed" error.
1. **Create your own GitHub repo for this course**.  We will be either using my repo or your own repos for these assignments (which will be clearly stated on the assignment), and you only have to make 1 repo for all of these assignments.  Here is [a link to a GitHub guide detailing one way to do it](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/create-a-repo) and make sure to add a README file!
    * You can make it public or private, up to you.
    * If you want more private repos (among other benefits), consider signing up for the [student developer pack](https://docs.github.com/en/free-pro-team@latest/github/teaching-and-learning-with-github-education/applying-for-a-student-developer-pack#applying-for-a-github-student-developer-pack). This is not required but there are general benefits for you now and later as at student.
    * Adding a description for your repo is optional.
1. **Clone the repo to your computer.** Here is [a helpful guide on how to do this using the command line](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository).
    * I recommend doing it with the command line, if possible; there are other ways to do it, but most people eventually converge to using git through the command line.
    * Once the repo is cloned (downloaded as a folder) to your computer, you can add files/folders to it like any other folder.
    * I recommend making a folder called `github_part_1/` for storing everything for this assignment, that way you can add more folders for other assignments and keep everything organized.
1. **Edit the repository's main README.md**. Keep in mind, ultimately the README.md is ultimately just a text file, and as such, I recommend using a text editor and/or an IDE to do this.  [This page](https://github.com/mundimark/awesome-markdown-editors) has a list of several online/local text editors for markdown, which will let you preview how it looks before uploading back to GitHub.  I recommend avoiding the web interface, mostly because you won't get as much out of the learning experience; you will normally be working with files that you can't easily edit online, so it's better to get used to working with a local version.  At the very least, it must have the sections below.  In order to format sections, check out this guide on [GitHub Markdown Formatting](https://guides.github.com/features/mastering-markdown/).
    1. **Assignment Info**, providing below it the course name, your name, and your section (either the number or the day of the week).
    1. **What is a Math Puzzle in CICS?**, a short description of what you think of when you think about "math puzzles in CICS" or "math puzzles in computing in general".  The [GitHub Markdown Formatting](https://guides.github.com/features/mastering-markdown/) will show you how to nicely add URLs and/or images if needed.
    1. **A Puzzle I Like**, a short summary or a link to the prompt of an out-of-class puzzle that you enjoy -- could be from a board game, a video game, a TV show, a book, really anything works for this.  If nothing comes to mind, feel free to just google something and find something that looks fun.  Again, the [GitHub Markdown Formatting](https://guides.github.com/features/mastering-markdown/) will show you how to nicely add URLs and/or images if needed.
1. **Push your changes back to GitHub**. To see what has changed in your repo, go to the main folder of the repo and type the command ``git status`` to see what has been modified.  If everything is working correctly, it should look something like the output below.  Once you're good to go, here is a [useful guide to adding and committing a file to your GitHub repo](https://docs.github.com/en/free-pro-team@latest/github/managing-files-in-a-repository/adding-a-file-to-a-repository-using-the-command-line). When it comes to the `git commit -m "message"` command, usually you want to add something short but descriptive regarding what changes you made to your repo as the `"message"`.  You can check that your add, commit, and push are successful if you go to your repo's webpage and the README has changed!  You will also see your commit message (`Add existing file` in the example) at the top of your repo.

        git status
        On branch main
        Your branch is up to date with 'origin/main'.

        Changes not staged for commit:
          (use "git add <file>..." to update what will be committed)
          (use "git checkout -- <file>..." to discard changes in working directory)

                modified:   README.md

        no changes added to commit (use "git add" and/or "git commit -a")

    * If you want to make changes after pushing, just change them locally and repeat the add/commit/push steps that you just did. As long as your local (downloaded) version is up to date, you don't have to keep cloning/downloading it from GitHub.
1. **Submit a link to your GitHub repo on Moodle, or invite me to your repo if the repo is private. If you invited me to your repo, just say "private repo" on the HW3 submission page.** Specifically on Moodle, submit it under whichever assignment you are completing (Homework 2, 3, or 4). This [guide to inviting collaborators](https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-your-github-user-account/inviting-collaborators-to-a-personal-repository) will show you how to add a collaborator to a private repo.  My username on GitHub is zwhile, the account that this repo is hosted on.  
