# tfgetws
## shell-prompt indicator for Terraform Active-Workspace

### how to install
1. clone it to your computer.
1. `cd` to this repo.
1. `ln -s $(pwd)/tfgetws ~/bin/`
1. enjoy!

### how to use
#### tfgetws basic function
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

#### `terraform workspace list` alias
```
tfgetws a
tfgetws all
tfgetws g
tfgetws get
```

#### usage
```
tfgetws help
```

#### tfsetws
* simple wrapper to `terraform workspace select $1`

### merge onto your shell's prompt

* see [install manual](https://github.com/ykamenashi/tfgetws/blob/master/installer.bash.template)
