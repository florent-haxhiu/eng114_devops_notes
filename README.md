# Eng144-DevOps

## Links

### [Basic Terminal Commands](#basic-terminal-commands)

### [Create Git Repo](#create-git-repo-and-change-master-to-main)

### [Git Commands](#git-commands)

### [Object Oriented Programming](#object)

## Notes

- ### Basic Terminal Commands

  - pwd (print working directory)
  - ls (list directory items)
  - cat (copies file items and prints it in terminal)
  - rm -r (deletes whole directories, -r means recursively)
  - rmdir (also deletes whole directories)
  - vim (brings up terminal editor)
  - nano (brings up nano editor)
  - cd (change directory)
  - rm (removes items)
  - echo (prints it to terminal)
  - --version (shows version, universal)
  - touch (creates any types of files)
  - touch {itemOne,itemTwo}.extensionType (Creates multiple files with the same file type)

- ### Create git repo and change master to main

  - Create git repo by going into an empty dir
  - git init (initializes a git repo)
  - git branch -m master main (changes master to main)

- ### Git Commands

  - git status (Shows what's been commited, added or pushed)
  - git add . (Adds all the files into a queue to be pushed)
  - git commit -m (Commits the files that have been added with a message)
  - git push (Pushes it into the git repo on github)
  - git log (Shows git logs so who changed what and etc.)
  - git checkout -d <insertNameHere> (Creates a branch with that name)
  - git checkout <branchName> (Goes to the branch name, it has to first exist)
  - git diff (shows the changes to the file)
  - git clone <repoSSH/repoHTTPS> (Clones the existing repo)

- ### Object Oriented Programming (OOP) {#object}
  - Four pillars for OOP
  - APIE
    - **Abstraction**
    - **Polymorphism**
    - **Inheritance**
    - **Encapsulation**
  - Based on the concepts of objects
    - Can contain **data** in the form of **attributes** or **properties**
    - Can contain **actions** in the form of **functions** or **methods**
  - **Abstraction**
    - Abstraction is getting rid of unnecessary information for the user. We should only care about calling the method and the not underlying implementation.
  - **Polymorphism**
    -
  - **Inheritance**
    -
  - **Encapsulation**
    - Fundamental concept in OOP. It is the idea of bundling data and methods that work on that data within one unit. This is usually used to hide internal representaion, or state of an object from the outside. This is called ==information hiding.==
