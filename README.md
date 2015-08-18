# initscripts

Forked version of initscripts with ClearOS changes applied

* git clone git+ssh://git@github.com/clearos/initscripts.git
* cd initscripts
* git checkout c7
* git remote add upstream git://git.centos.org/rpms/initscripts.git
* git pull upstream c7
* git checkout clear7
* git merge --no-commit c7
* git commit
