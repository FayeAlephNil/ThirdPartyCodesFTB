# Contributing

This is a community project and will not succeed without your contributions, so first of all, thank you for contributing. Now here are your guidelines

## Forking

The first step in contributing is to make a fork, this is done with the fork button in the upper right hand corner of the github page. To do this you must have made a github account.

## Git

If you do not know git very well I recommend you do the (Hello World)[https://guides.github.com/activities/hello-world/] example on the github guides page

## Making your changes

Now you will want to download the github app for your operating system, this can be done at (the github desktop website)[http://desktop.github.com/]. After doing so you will want to go to your fork's github page and hit the "Clone in Desktop" button. This will allow you to select a cloning directory. After doing so you will be able to access the directory as normal and be able to add/modify/delete files as you wish

### Guidelines

All pack files are to be in json with the extension .json in the following format
```
{
  "name": "<name of pack>",
  "authors": [<list of authors>],
  "code": "<pack code>",
  "link": "<link to a page or forum post for your pack>",
  "mcversion": "<version>",
  "listed": <true if listed else false>
}
```

A good example of this is the (tolkiencraft file)[json/tolkiencraft2.json]

## Making a pull request

When you are finished with your changes and have pushed them click the third icon on the right hand side of this github page. This icon looks like a merging symbol. Then click "Create a Pull Request". Then click "compare across forks". Now select your fork from the list provided on the right hand side dropdown. Write up a short summary of your changes and I will then review them and either tell you to revise them, reject them, or merge them into the main repo.
