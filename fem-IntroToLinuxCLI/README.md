README

These are my notes on Brian Holt's course, Complete Intro to Linux and the Command-Line.
I feel like I have a decent ish understanding of using the CLI. 
Most of my notes will probably be things that I find interesting or didn't know before.

https://github.com/btholt/complete-intro-to-linux-and-the-cli
https://btholt.github.io/complete-intro-to-linux-and-the-cli/intro

Where I'm at right now: https://frontendmasters.com/courses/linux-command-line/cli-search/

Unix Philosophy: Make each program do one thing well.
Why Linux? 
    - Free
    - Well maintained
    - Runs almost anywhere

bash vs zsh
    - bash under GNU... all updates/improvements must be open source
    - as such, macOS uses zsh

cd, pwd, ls, echo
    - these (and all programs that we can run) can be foudn in the /bin directory
    - bin stands for binary

flags
    - one '-' character indicates to the program that you're going to be passing a bunch of single character flags (case sensitive)
    - two '-' characters (ie --help) indicates that the set of characters is to be used as the name for a flag
    - inconsistencies exist between different programs and how they approach flags, ordering, etc. 
        ~ remember that a lot of these were written in different decades