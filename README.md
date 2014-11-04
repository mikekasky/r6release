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
    
    Naming convention
    com.flext.release.xxx
    
    
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
    
