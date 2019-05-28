# git-notes
Git notes.

## See Also

* [AndersDJohnson/gitconfig](https://github.com/AndersDJohnson/gitconfig)
* [AndersDJohnson/github-notes](https://github.com/AndersDJohnson/github-notes)

## Extensions
* [hub](https://github.com/github/hub)
* [gg](https://github.com/qw3rtman/gg)
* [git-extras](https://github.com/tj/git-extras)
* [gitflow](https://github.com/nvie/gitflow)

## Links
* [`git pull` considered harmful](http://stackoverflow.com/questions/15316601/in-what-cases-could-git-pull-be-harmful)

## Credentials

### Credential store

```sh
git config --global credential.helper store
```

This will store credentials in `~/.git-credentials`.

### Windows
* https://github.com/Microsoft/Git-Credential-Manager-for-Windows

## Push Branch to Different Remote Name

```
git push origin local-name:remote-name
```

## Push Delete Tag

```
git push origin :tagname
```

or

```
git push --delete origin tagname
```

## Exceutable

```
git update-index --chmod=+x foo.sh
```

## Conflicts

```
git diff --diff-filter=U --name-only
```

Checkout & resolve conflicts:

```sh
git checkout [--theirs|--ours] PATHS...
```

## Proxy git:// protocol

```sh
git config --global url."https://".insteadOf git://
```

## Contains Commit

To see what tags or branches contain a given commit:

```
git tag --contains <commit>
```

```
git branch --contains <commit>
```

## Selective Merge

https://gist.github.com/katylava/564416
