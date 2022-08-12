$ git clone [ssh-url] [folder-name]
$ cd [folder-name]
$ git checkout -b [new-feature]
$ git add .
$ git commit -m "information added in readme"
$ git checkout master
$ git branch

- master
  readme
  $ git remote -v
  origin git@github.com:[forked-repo-owner-username]/[repo-name].git (fetch)
  origin git@github.com:[forked-repo-owner-username]/[repo-name].git (push)
  $ git push origin readme
