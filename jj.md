# jj
edited from github
* [Jujutsu docs](https://jj-vcs.github.io/)
* [Google's Git Killer Is INSANELY Better (and it's open source)](https://www.youtube.com/watch?v=cZqFaMlufDY)

## Commands

## push pull

```
jj git init --colocate

jj git fetch

jj bookmark move master --to @-
jj git push
```

## revset language

* set of revisions

```txt
@   current
@-  first parent
@+  first child
```
