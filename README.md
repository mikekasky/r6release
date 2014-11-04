release
=======

    A quick project overview.

    Provide a short description of the project's goals and a bit of background. Any links that you frequently access are also good to include up at the top as well, for easy access. Everyone loves easy access.

    Information about the directory structure.

    Typically we have more than just Drupal in our repository root, so it's helpful to have a brief description of what is in there. We typically have a drush folder for aliases and commands, as well as a patches directory with its own README.

    How to get started developing.

    Tell the developers what the best way to jump into the project might be. Things like, "clone this repository, create a feature branch, run the installer, download a copy of the database, etc.. Whomever reviews the pull request should also do things like remove the remote branch from the repository once it is merged."

    Code promotion workflow.

    It's a good idea to outline your development process, as it may change from project to project. Do you want people to fork your repository and send pull requests; create feature branches and send pull requests; or just go ahead and commit to master? Let the developers know up-front, so there's no confusion.

    Environments.

    Outline information for your dev, staging and live environments, if you have them. Also, outline the process for getting things to the various places. How do I make sure my code is on staging? What is the best way to grab a database dump? We like to setup drush aliases for each environment ahead of time as a means of outlining this information and giving developers a good starting point. This document contains some example commands for doing some typical operations. Here's an example.

    Links to where to find more information.

    Typically this is our wiki, where we keep more detailed documentation and notes on things; project details like the original proposal's SOW, credentials to environments, Scrum Notes, Pre-launch checklists, etc.
    
    Building a Development Matrix
    A streamlined tool for tracking website construction
    https://www.lullabot.com/blog/article/building-development-matrix

---
    
    Naming convention
    com.flext.release.xxx

---    
    
    GitHub issues
    With new GitHub issues 2.0 1 [2] you can use these synonyms to reference an issue and close it (in your commit message):

    fix #xxx   fixes #xxx   fixed #xxx   close #xxx   closes #xxx   closed #xxx   resolve #xxx   resolves #xxx   resolved #xxx
    
    Just include #xxx [issue no.] in your commit message to reference an issue. You can also substitute #xxx with gh-xxx. Referencing and closing issues across repos also works: fixes user/repo#xxx
    
    Managing Projects with GitHub
    https://www.lullabot.com/blog/article/managing-projects-github
    
    Referencing and Association
    Issues can be associated with each other by simply throwing an #issue-number (ex: #3) within the body of another issue. 
    
    Issue Labels
    Tags are a simple and effective way to add metadata to your issues. [custom tags for this project must only be recognized HTML, CSS, or jQuery tags (no new terms and poetry please)]
    
    Attach Code to an Existing Issue
    We've found the in-line commenting with pull requests to be immensely useful since they keep everyone in the project in the loop with changes that are happening ... There's a bit of overhead in that it may take a little longer for some new piece of code to be merged in, so plan accordingly. But this also means we find bugs sooner, typically before they're actually introduced into the master branch of the code ... through a nice command-line tool called Hub [https://github.com/github/hub], we've found there's a way to turn issues into pull requests! Very handy for keeping your discussions and code all in one place and not having to deal with multiple issues about the same thing.
    
    Milestones
    We tend to only plan one sprint ahead, but there is a milestone created for each iteration up until the end of the project. We grab these tickets from the Backlog, which is essentially just any ticket that is NOT in a Sprint.
    
    Huboard
    GitHub's issue tracking system lacks a mechanism for prioritizing your issues ... With Huboard, we now have a means of seeing what the priority tasks are for the week and it gives developers an easy way to see what they should work on next.

---

    GitHub Secrets
    https://github.com/blog/967-github-secrets
    
    Cross-Repository Issue References
    You can reference issues between repositories by mentioning user/repository#number in an issue. Once we see something like that — say, github/enterprise#59 — we'll make sure to update issue #59 in github's enterprise repository and let you know where it was referenced from. You can include "fixes user/repo#45" in your commit message, and it will close the referenced issue, provided you have the permission to push to that repository.
    
    Hot Branch on Branch Pull Request Action
    Did you know you can use Pull Requests between branches, on the same repository? You don't need to fork repositories to use Pull Requests.
    
    Navigate quickly
    On your repository's home page, type w to quickly bring up a quick filter panel for your branches. Inside of your repository, type t to jump into a quick file selector. Select your file, hit enter, and you're gold. There's also a slew of other shortcut keys you can use, depending on the page- just hit ? to see them.
    
    Filter Notifications
    Email notifications for Issues, Pull Requests, and Gists can easily be filtered by the List-ID header. Look for this header value to sort your notifications, or even forward them to a more appropriate email account. You can filter on *.org.github.com to filter out emails by organization, or repo.org.github.com to filter out emails from a specific repo.
    
