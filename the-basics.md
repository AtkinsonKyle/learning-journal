<h1 align="center">The Fundamentals of Git</h1>

<p align="center">
  <img width="800" height="300" src="https://i.pinimg.com/600x315/2c/b6/70/2cb670b6ddd8922a1c1b2fee4f6f758c.jpg">
</p>
<hr>

## Words That Would Be Helpful to Know
- `Version Control`: A system that allows you to revisit versions of a file by recording changes.
- `Local VCS`: A database on your hard disk that stores changes to files.
- `Centralized Version Control System (CVCS)`: A server storing all changes and file versions, which can be accessed by clients.
- `Distributed Version Control Systems (DVCS)`: Allows clients to create mirrored repositories.

## What On Earth Is a Git?
Git is a distributed version control system that stores data in a file system made up of snapshots. It creates the snapshots and essentially saves them. Git primarily relies on the local side of the house because most important information comes from local resources which eliminates the need to return history information from a server and allows one to work on a project. Git is like a gatekeeper! Changes applied to any file or directory is tracked by it. 

## First Run Customizations
After installing Git, you should set your user name and email address, which will be used for every Git commit.
Type the following into the Command Line:
- git config --global user.name "Jane Smith"
- git config --global user.email "example@email.com"

To confirm that you have the correct settings, enter the following command:
- git config --global user.name (should return Jane Smith)
- git config --global user.email (should return example@email.com)

## 
### Importing
To import existing projects into Git, follow these steps using the command line:


[Download Git](http://git-scm.com/download/win) | [Download Github Desktop](http://windows.github.com/) | [GUI Clients](https://git-scm.com/downloads/guis)
