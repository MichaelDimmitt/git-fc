## git-fc
git fc - a thin future commit management system built on top of git

What do I need to do today?
```
git fc -m do thing
git fc -m do second thing
```
when you finally do git commit -m 'blah' bash says whoa buddy you have # of future commits! 
please copy your commit message and ammend it to one of these future commits, removing the prefixed "future commit, " syntax.

Additionally `git commit` on its own, will check if prepended future commits exist.

And if only one future commit exists it will ask if you want to use that commit message and if yes will throw you into a `git commit --amend`
