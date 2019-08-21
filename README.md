# Ansible playbook for automating a setup of a new MacBook Pro for a rich development experience

This will setup a new laptop for software development.

## Requirements:

1. XCode is installed.  Can do so by running `xcode-select --install`
2. Ansible is installed.  Can do so by running `pip install ansible==2.8.4`

### How to use:

##### 1. Install XCode and Ansible:

```
 $ xcode-select --install
 $ sudo easy_install pip
 $ sudo pip install ansible==2.8.4
```

##### 2. Run the ansible playbook:

```
 $ git clone https://github.com/genomics-geek/setup-macbook-playbook.git
 $ cd setup-macbook-playbook
 $ ansible-playbook setup.yml -i hosts -l local
```

### What this includes:

#### Languages

+ Python3
+ Java
+ GO
+ Scala
+ Nim

#### Databases

+ Postgres
+ MySQL
+ Redis

#### Virtual Environment managers

+ pyenv
+ pipenv
+ jenv
+ plenv

#### Javascript tooling

+ Node
+ Yarn
+ Create React App

#### Code formatters

+ Autopep8
+ Prettier

#### Productivity apps

+ Atom
+ VSCodium
+ Slack
+ Skype
+ GitHub Desktop
+ PostMan
+ Google Drive
+ Google Chrome
+ Brave browser
+ Spotify
+ Lastpass

#### Atom plugins

+ teletype
+ git-plus
+ ask-stack
+ linters for python and JS
+ prettier
+ python-autopep8
+ language support for WDL, JSX, Python
