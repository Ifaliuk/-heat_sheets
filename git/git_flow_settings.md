git flow init -d

* git config gitflow.branch.master master
* git config gitflow.branch.develop develop
* git symbolic-ref HEAD refs/heads/master
* git commit --allow-empty --quiet -m Initial commit
* git branch --no-track develop master
* git checkout -q develop
* git config gitflow.prefix.feature feature/
* git config gitflow.prefix.bugfix bugfix/
* git config gitflow.prefix.release release/
* git config gitflow.prefix.hotfix hotfix/
* git config gitflow.prefix.support support/
* git config gitflow.prefix.versiontag
* git config gitflow.path.hooks <path>:/.git/hooks
