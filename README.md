git-gradle-multi-idea
=====================

A Template IntelliJ IDEA Git multi-root project with Gradle build support

Description
-----------

Git Gradle Multi Idea simplifies the setup of new IntelliJ multi-root Git projects.  The repository is shared so
that others can create/fork similar project structures with ease.  

A simple IntelliJ import from VCS command should be all that's needed to download, initialize and beging working with
all of the Git modules contained the complete layout.

Consider sharing/adapting the template for your own projects that use this powerful feature of IntelliJ.

Project Layout
--------------
This template is made up of the following nested directory structure.  Each IntelliJ project/module is encapsulated in it's own
Git repository.

*[git-gradle-multi-idea](https://github.com/afarentino/git-gradle-multi-idea) - Parent Git repository containing top-level .idea files and build scripts
  *gradle/ -> directory of parent repository containing the Gradle wrapper files
  *libs/ -> directory containing the [git-gradle-multi-libs](https://github.com/afarentino/git-gradle-multi-libs) IntelliJ module.
  *web/ -> directory containing the [git-gradle-multi-web](https://github.com/afarentino/git-gradle-multi-web) IntelliJ module.
  *core/ -> directory containing the [git-gradle-multi-core](https://github.com/afarentino/git-gradle-multi-core) IntelliJ module.
