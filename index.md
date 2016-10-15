---
layout: index
---

### Install:

```bash
$ brew tap doublenot/git-all
```

```bash
$ brew install git-all
```

### Scripts added:

- `git-all-clone` - clones all the repositories specified in the current working directory in the `.gitclone` file _(note: alternate repository or directory names can be provided by add `",new-repo-name"` to the end of the repository url)_
- `git-all-status` - provides the output of "git status" for every repository in the current working directory
- `git-all-config` - sets the config setting for every repository in the current working directory, use `-d` to remove all settings for a `key`
- `git-all-pull` - executes the "git pull" command for every repository in the current working directory

### Uninstall:

```bash
$ brew uninstall git-all
```

```bash
$ brew untap doublenot/git-all
```

### TODO:

- Add more examples and documentation
- Add scripts to help with multiple repository management (eg. git-all-npm script)
- Convert the shell scripts into node.js scripts