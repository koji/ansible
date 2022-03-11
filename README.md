# ansible

## requirements
- homebrew
- ansible
- mas-cli

```zsh
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
$ brew install ansible
$ brew install mas
```


## how to use

```zsh
$ git clone this repo
$ cd ansible
$ cd local

# if you update any yml files, need to check syntax with the following command
$ ansible-playbook playbook.yml --syntax-check

# run ansible-playbook
$ ansible-playbook playbook.yml -K
```
