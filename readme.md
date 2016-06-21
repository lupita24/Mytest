hola aldo

cs06@cs06:~$ git init MyTest
Initialized empty Git repository in /home/cs06/MyTest/.git/
cs06@cs06:~$ cd MyTest/
cs06@cs06:~/MyTest$ ls
cs06@cs06:~/MyTest$ ls
cs06@cs06:~/MyTest$ git add .
cs06@cs06:~/MyTest$ git commit -m 'MI primer commit'

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'cs06@cs06.(none)')
cs06@cs06:~/MyTest$ git config --global user.email "jatch21@gmail.com"
cs06@cs06:~/MyTest$ git clone https://github.com/lupita24/Mytest.git
Cloning into 'Mytest'...
warning: You appear to have cloned an empty repository.
Checking connectivity... done.
cs06@cs06:~/MyTest$ cd ..
cs06@cs06:~$ sudo rm -R MyTest/
sudo: unable to resolve host cs06
[sudo] password for cs06: 
cs06@cs06:~$ git clone https://github.com/lupita24/Mytest.git
Cloning into 'Mytest'...
warning: You appear to have cloned an empty repository.
Checking connectivity... done.
cs06@cs06:~$ cd Mytest/
cs06@cs06:~/Mytest$ ls
cs06@cs06:~/Mytest$ touch readme.md
cs06@cs06:~/Mytest$ ls
readme.md
cs06@cs06:~/Mytest$ vi readme.md 
cs06@cs06:~/Mytest$ git status
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	readme.md

nothing added to commit but untracked files present (use "git add" to track)
cs06@cs06:~/Mytest$ git add .
cs06@cs06:~/Mytest$ git commit -m 'Mi primer commit'
[master (root-commit) 15e9743] Mi primer commit
 1 file changed, 1 insertion(+)
 create mode 100644 readme.md
cs06@cs06:~/Mytest$ git config --global user.email "you@example.com"
cs06@cs06:~/Mytest$ git config --global user.email "aniluaf1415@gmail.com"
cs06@cs06:~/Mytest$ git config --global user.name "Your Name"
cs06@cs06:~/Mytest$ git config --global user.name "lupíta24"
cs06@cs06:~/Mytest$ git push
Username for 'https://github.com': lupita24
Password for 'https://lupita24@github.com': 
Counting objects: 3, done.
Writing objects: 100% (3/3), 216 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/lupita24/Mytest.git
 * [new branch]      master -> master
cs06@cs06:~/Mytest$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean
cs06@cs06:~/Mytest$ 

