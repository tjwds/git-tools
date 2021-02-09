# git-tools

These are some tools that I use day to day to extend git and get work done.

## installation

For now, just:

* Clone the repository locally
* Make sure your `~/bin` is in your path
* `cd ~/bin && ln /path/to/git-tool-you-want-to-use`

`git foo` just invokes `git-foo`, so it'll just work.

## tools

### git-lines

Usage / example:

```
npm-cli  latest
➜ git lines 5
     1	06bd0e03 chore: add issue templates back & remove legacy settings.yml
     2	fff3e8ea Merge branch 'release/v7.0.0' into latest
     3	3b4ba65b 7.0.0
     4	bbfc75d8 chore: fix weird .gitignore thing that happened somehow
     5	8a2d375d docs: changelog for v7.0.0
```
