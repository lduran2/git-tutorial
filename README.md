# Using Git locally

## What is Git?

Good afternoon!
Today we are going to be talking about using Git locally.

Now Git is a software for versioning software and collaborating in the creation of software.
You can use Git to handle different versions of software more easily than giving the filenames version tags.
You can also use Git to collaborate in a team and handle conflicts.

Ultimately, Git is used to push and pull your code out to a repository,
which is a location where you keep your code.
The repository can be local or on a server.
The latter lets you share your code or have a location outside of your computer to store it.
In either case, Git provides a set of tools to handle versions and conflicts.

## Creating a new repository

Before we create a new repository to
start a new project, I have set up a project here in a directory named `new-project`,
where it will be stored.
I want to show that it is completely empty.

In Linux, I can use
```sh
ls -a
```

In Windows, I can use
```bat
dir /A
```

In either case, we see that the directory only contains
`./` (a link to the current working directory)
and `../` (a link to its parent directory).

Now we can start by typing in
```sh
git init
```

If we look in the directory, now we have a hidden `.git/` subdirectory in it.

We do not normally touch this subdirectory,
unless we want to change something about how Git interacts with our project.

## Branches
