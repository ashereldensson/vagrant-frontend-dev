# Vagrant box for front-end development
This is a simple vagrant box I use for front-end development. It come with:

  * Ubuntu 14.04 x64.
  * The latest version of Git.
  * Node.js 6.x LTS version.
  * The latest version of npm.
  * The latest version of Gulp (gulp-cli) and Bower installed globally.

# How to use it?
Assuming you have the latest version of [vagrant](https://www.vagrantup.com/) and [virtualbox](https://www.virtualbox.org/) installed:

  * Clone this repository and `cd` into it.

    > Note: If you are on Windows OS, use something like [Git Bash](https://git-scm.com/downloads) or [Cygwin](https://www.cygwin.com/).


  * Create a directory and name it `Code`. This directory will serve as the `synced_folder`, and you can place your projects inside it.
  * Run `vagrant up`.
  * And `vagrant ssh`.
  * Done.
