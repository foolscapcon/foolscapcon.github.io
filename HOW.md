# creation
- github site creation
- added remote tracking of jekyll-now https://github.com/barryclark/jekyll-now

dougbeal-imac:foolscapcon.github.io dougbeal$ git remote add jekyll-now https://github.com/barryclark/jekyll-now
dougbeal-imac:foolscapcon.github.io dougbeal$ git remote -v
jekyll-now	https://github.com/barryclark/jekyll-now (fetch)
jekyll-now	https://github.com/barryclark/jekyll-now (push)
origin	https://github.com/foolscapcon/foolscapcon.github.io (fetch)
origin	https://github.com/foolscapcon/foolscapcon.github.io (push)
dougbeal-imac:foolscapcon.github.io dougbeal$ git branch --track jekyll-now jekyll-now/master
error: the requested upstream branch 'jekyll-now/master' does not exist
hint: 
hint: If you are planning on basing your work on an upstream
hint: branch that already exists at the remote, you may need to
hint: run "git fetch" to retrieve it.
hint: 
hint: If you are planning to push out a new local branch that
hint: will track its remote counterpart, you may want to use
hint: "git push -u" to set the upstream config as you push.
dougbeal-imac:foolscapcon.github.io dougbeal$ git fetch jekyll-now
warning: no common commits
remote: Counting objects: 1288, done.        
remote: Total 1288 (delta 0), reused 0 (delta 0), pack-reused 1288        
Receiving objects: 100% (1288/1288), 8.17 MiB | 430.00 KiB/s, done.
Resolving deltas: 100% (710/710), done.
From https://github.com/barryclark/jekyll-now
 * [new branch]      kramdown-and-rouge -> jekyll-now/kramdown-and-rouge
 * [new branch]      master     -> jekyll-now/master
 * [new tag]         v1.0.0     -> v1.0.0
 * [new tag]         v1.1.0     -> v1.1.0
 * [new tag]         v1.2.0     -> v1.2.0
dougbeal-imac:foolscapcon.github.io dougbeal$ git branch --track jekyll-now jekyll-now/master
Branch jekyll-now set up to track remote branch master from jekyll-now.

- merge in jekyll-now
git checkout master
git merge --squash jekyll-now # don't really want detailed history from jekyll-now
