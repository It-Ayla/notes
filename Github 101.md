# My notes

![](https://ktar.com/wp-content/uploads/2021/10/notebook-pen-unsplash-900x506.jpg)

It's like creating a magic book that remembers everything you do in your computer folder.

```shell
git init
```
So, when you do git add, you're telling Git, "Hey, I want to save these particular changes in my magic backpack because they're important." It's a way of saying, "Remember these changes for me!"
```shell
git add <files> or .
```
When you do `git commit`, it's like zipping up your magic backpack. You're saying, "I'm done selecting the changes I want to save, now let's officially save them in my backpack." Git will then create a snapshot of your project at that moment, keeping track of all the changes you added with `git add`. It's like taking a picture of your room after you've decided what to pack. This snapshot is something you can go back to later if needed.
```shell
git commit -m "commit description"
```
magine you have a magical assistant who helps you keep track of what's going on in your room. When you say `git status`, it's like asking your magical assistant, "Hey, what's the current state of my room and the magic backpack?"
```shell
git status
```

```shell
git log [--oneline]
git diff commit1-id commit2-id 

```
```shell
git clone https://token@github.com/username/repo_name.git
```
---
Enjoy coding ...
