# git-notes
Git notes.

See also:
* [AndersDJohnson/gitconfig](https://github.com/AndersDJohnson/gitconfig)

## Extensions
* [hub](https://github.com/github/hub)
* [gg](https://github.com/qw3rtman/gg)
* [git-extras](https://github.com/tj/git-extras)

## Credentials
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
