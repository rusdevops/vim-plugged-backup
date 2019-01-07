### Instruction

```ShellSession
$ cd .nvim/plugged
$ ls -1 | xargs gmr +@plugged
$ pip install git-archive-all
$ gmr @plugged git-archive-all latest.zip
$ find . -name latest.zip | xargs cp -t vim-plugged-backup
```