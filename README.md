# tfgetws
## shell-prompt indicator for Terraform Active-Workspace

### how to install
1. clone it to your computer.
1. `cd` to this repo.
1. `ln -s $(pwd)/tfgetws ~/bin/`
1. enjoy!

### how to use
```
$ ls -d ./.terraform
-> ./.terraform/
$ tfgetws
-> default

ls -d ./.terraform
-> ls: ./.terraform/: No such file or directory
$ tfgetws
$
```

### merge onto your shell's prompt

TODO
