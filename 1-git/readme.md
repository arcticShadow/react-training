# Git

Git will be your best friend, and your worst enemy.

Git is a version control system, it is intended to allow us to share and distribute various iterations of our work, in a distributed manor. 

Another way to say this, is it allows us to backup work in progress remotely, and share it with our team mates. 

## Branches

Git (and most Version control systems) allow you to operate multiple 'branches' at the same time. you may have one or more branches at any given time, and you may switch between them as you like. 

In addition, in most scenarios, there will be some established practices that nominate a 'common' branch (or multiple common branches) These common branches are used to 'merge' code together. 

Its very common place for `development` to be the name of a common branch.

## Code Review

Code review is not part of Git. Code Review sometimes referred to as PR, Peer Review, Pull Request, MR, Merge Request, and many other things I can't recall. While technically most o these things are not the same, they all are similar enough to consider them the same, until you know the differences. 

For now, consider code review to be the act of looking/reading someone elses code, and 'approving' it for merge into the common branch - often into the `development` branch. 

### Who can do a code review?

Anyone can do a code review - If you work with a team of other developers on similar work, your peers are often going to do a code review for you, and in return you can code review for them.

Code review is as much about learning for yourself, and it is confirming that others have done things correctly. 

The goal of a code reive wis not to examine 100% of the written code. The original author has already done that. 

The goal should be to identify silly mistakes, code smells, or areas for improvement. And don't forget to ask clarifying questions - if you don't understand what you are reading, it may very well be too complex

### What is good code?

There is no such thing as good coed in my opinion. 

Code can always be improved, regardless of what level the author is at. Code is only as good as the knowledge that was used to craft it.
