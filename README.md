Organization for Introduction to Nonlinear Dynamics, fall 2016.

Ideally, this will be a place to work together on homework, share modules, tips, etc.

The title of this file is a bit misleading—something like `SKIM-ME-FOR-THE-INFORMATION-YOU-NEED.md` 
  might be more appropriate, but GitHub dosen't show files of that name by default.

## New to Git/GitHub?

First, you will want to [install git](https://git-scm.com/download).

Then, you'll probably want to [learn the basics of Git and GitHub](http://blog.udacity.com/2015/06/a-beginners-git-github-tutorial.html).

If you have questions, Rachael (r.steiner@uconn.edu) should be able to help
  (others with git experience, please feel free to add yourselves).

### Proposed structure

This repository could serve as the "hub" for more general discussions, resources, etc.
  For example, check out the [`matlab-help/`](https://github.com/NLDFall2016/nldfall2016/tree/master/matlab-help)
  folder. Then everyone who chooses to can make a repo for their own assignments and things.

### Asking for help

If you want to request help, you would probably want to open
  an issue. To open an issue, go to the repository in question, and click the
  "Issues" tab, next to the "Code" tab and under the repo's name.

If it is a general question directed at anyone, you may want to open the issue on
  this repository. If you have a question for a specific person, such as asking
  for help with a script they wrote, you can open an issue in their repository.

### Offering help

The simplest way to offer help is to leave a comment on an issue. But sometimes,
  you'll want to edit code directly. For that, you will want to make a pull request.

A **pull request** is when you make changes to files in a repository and propose
  to the repository's owner, so that they can "pull" them in if they approve of
  the changes.

First, you'll need to **fork** the repository by clicking the "Fork" button in the
  upper right corner. Then, clone it to your computer with

```sh
git clone https://github.com/NLDFall2016/[repo-name].git
```

Make a new **branch** for your changes: 

```sh
git checkout -B [new-branch-name]
```

Make your changes, commit and push them to your branch, and open a pull request (find the "Pull Requests" tab) in the original repository, explaining what you did. If the repository owner is satisfied with the changes, they will **merge** them into their repo. Otherwise, they might ask for more clarification or ask you to expand on it (of course, doing so is your choice).

## Intellectual property

**This may seem unnecessary, but it's actually important for protecting your work as well as avoiding copyright infringement.**

Everything you post here is public. This has several important implications:

1. Do not post anything that you do not want the world to see.
2. You will want to license your work so that others may adapt it on your terms.
3. Respect others' intellectual property; do not publish anything that you did
    not create unless you *know* you have the right to do so.

By default, **everything you create is copyrighted to you**, with all rights
  reserved. This means that no one can use, modify, or distribute it without
  your express permission. That's not really ideal for collaboration.

You have the right (and are encouraged) to license your work, which is a way of
  making explicit what you permit--or do not permit--others to do with your work.
  I know it sounds like a hassle, but it's a lot simpler than you'd expect. You
  can find accessible information about licenses on [choosealicense.com](http://choosealicense.com/).

To make things even simpler, it might be best if we have a standard license that
  everyone is encouraged to use (**but you do have the right to choose not to**).
  That way, everyone is on the same page about what is and is not okay to do, and
  you can know that your license is compatible with any scripts, etc. that you
  are using. I tentatively propose the [MIT license](http://choosealicense.com/licenses/mit/), which is summarized as:

1. You can use, modify, and distribute the work as long as the original copyright
  holder is properly acknowledged.
2. No warranty is provided.

Regardless of what license you choose, please be cognizant of others' choices (that is, don't incorporate a [GPL-licensed](http://choosealicense.com/licenses/gpl-3.0/) file into an
  MIT-licensed project). A license is good for both the copyright holder and the user, because it creates a clear set of terms so that there will be no legal surprises.
