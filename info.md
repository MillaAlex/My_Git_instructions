# Instructions for work with Git

## Git general commands:

- git init - initialization of local repository
- git status - get info from git about its actual status
- git clone - retrieve an entire repository from a hosted location via URL
- git config --list - displays config & user info
## Git configuration commands:

* git config --global user.name “[firstname]” - set a name that is seen when review version history
* git config --global user.email [valid-email] - set an email address
The commands to be entered only once.
## Git display commands:

- git status - get info from git about its actual status
- git log - displays history of all commits with their #-codes
- git log --oneline - displays history of all commits with their #-codes in short version
- git log --oneline --all - displays history of all commits with changes with their #-codes in short version
- git log --graph - displays all commits with graph tree
- git log --oneline --decorate --graph --all - displays all commits with graph tree and history
- git diff - see difference between actual file and the last commit 
- clear - cleaning of terminal window
## Git commit commands:

- git add [file_name] - command to add one for tracking
- git add . - command to add all files and folders from directory for tracking
- git commit -m "comment" - command to fix status of changes
- git commit -a -m - add commit in one line
- git commit -am - add commit in one line
- git checkout [4 symbols]- move from one commit to other one
## Git branch creation commands

* git branch - displays all branches
* git branch [branch_name] - creation of a new branch
* git checkout [branch_name] - switch between branches
* git checkout -b [branch_name] - create and switch to the new branch
* git branch -d [branch_name] - delete branch
* git branch -D [branch_name] - delete already merged branch. BUT: it's impossible to delete a branch while being on it
* git branch -m [old_branch_name] [new_branch_name] - to rename branch
* git merge [branch_name] - merging of branch, to be made when on master branch

- git cherry-pick - берёт изменения, вносимые одним коммитом, и пытается повторно применить их в виде нового коммита в текущей ветке. Эта возможность полезна в ситуации, когда нужно забрать парочку коммитов из другой ветки, а не сливать ветку целиком со всеми внесенными в нее изменениями.

- git rebase — это «автоматизированный» cherry-pick. Он выполняет ту же работу, но для цепочки коммитов, тем самым как бы перенося ветку на новое место.

- git revert — полная противоположность git cherry-pick. Она создаёт новый коммит, который вносит изменения, противоположные указанному коммиту, по существу отменяя его.

## Git gitignore function:

- .gitignore - create this file and write files names to be ignored. The .gitignore-file itself can be moved inside not to commit it.

## Git push & pull functions:

- git push - to send local version to remote repo. One must know addres of the remote repo as well as to be authorized for changes there.

- git pull - takes data from remote repo and merges it with local repo.

- git pull origin master - to pull all possible updates from origin repo.

- cd .. - to change directory

## Steps to push a local repo to a remote one:

1. Create an empty repo on GitHub.
2. git remote add origin [address_from_GitHub] - in terminal VSC
3. git branch -M main
4. git push -u origin main

## Steps to pull a remote repo to local one:

1. git clone [address_from_GitHub] - in terminal VSC
2. cd [folder_name]
3. git add . - created file with all changes
4. git commit -m "message"
5. git push

## Steps for works with Forks:
1. Fork -> Create Fork
2. Copy link of Fork from your account in GitHub
3. git clone [address] - in terminal VSC
4. cd [folder_name] -> make all changes
5. git add .
6. git commit -m "message"
7. git push - to send all changes to remote repo
8. in GitHub: "1 commit ahead" -> Create pull request 



## &#8220;Основные символы&#8221; языка Markdown [1]

&lt;script name&gt; - угловые скобки

&#8220;word&#8221; - двойные кавычки

&#8216;word&#8217; - динарные кавычки

> quote - добавление цитаты

**bold** - жирный шрифт

*italic* - курсив

***bold and italic*** - жирный и курсивный шрифт

[1]: https://learn.microsoft.com/ru-ru/contribute/markdown-reference

![markdown_icon](/markdown_icon.png)

> Per aspera ad astra [Луций Анней Сенека] 