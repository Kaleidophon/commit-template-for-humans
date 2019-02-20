# A commit message template for humans :family:

## What is this about? :interrobang:

Are you weary :weary: of shitty commit messages like

---
Bugfix. 

--- 
Refactor stuff.

--- 
Delete old code.

---
    
Behold! Here is a simple solution. Use the `.gitmessage` template provided in this repository to nudge your colleagues 
(and yourself) into writing better commit messages like 

---
:bug: Fix bug in data loader causing an IndexError.

---
:recycle: Refactor database integration.

---
:scissors: Removed old routing logic.

---

## How do I use this? :computer:

If you want to set this commit template **globally**, clone the repo or download the `.gitmessage` file and run 

    git config commit.template /absolute/path/to/file
    
If you want to set this commit template **for a single repository**, run 

    git config commit.template relative-path-from-repository-root
    
When working on your project, just call the usual

    git commit 
    
and the template pops up. Don't worry, every line starting with `#` is a comment and will not be visible.

## Credit where credit is due :clap:

This particular template was created in collaboration with @dieuwkehupkes and @jumelet on [this](https://github.com/dieuwkehupkes/diagnosing_lms)
project. 

The emoji system is loosely adapted from @dannfritz's system, which can be found [here](https://github.com/dannyfritz/commit-message-emoji).

Instructions on how to set the template was found on [this](https://stackoverflow.com/questions/21998728/how-to-specify-a-git-commit-message-template-for-a-repository-in-a-file-at-a-rel)
StackOverflow question. 

A complete list of emojis that are supported by GitHub can be found [here](https://gist.github.com/rxaviers/7360908).