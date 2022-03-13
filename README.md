# ansible playbooks

## requirements
- homebrew
- ansible
- mas-cli

```zsh
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
$ brew install ansible
$ brew install mas
```

### how to check app id with mas
```zsh
$  mas search Xcode
497799835  Xcode                                               (13.2.1)
1388020431  DevCleaner for Xcode                               (2.3.1)
1179007212  Code School for Xcode Free -Learn How to Make Apps (1.1.3)
431748264  Pluralsight: Learn Tech Skills                      (3.24)
1083165894  Course for Xcode 7 Lite                            (1.0)
```

## how to use playbook
```zsh
$ git clone this repo
$ cd ansible
$ cd local

# if you update any yml files, need to check syntax with the following command
$ ansible-playbook playbook.yml --syntax-check

# run ansible-playbook
$ ansible-playbook playbook.yml -K
```
