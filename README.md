$ pwd
$ cd /c/Users/DELL/Documents
$ cd projects
$ git init
$ git add .
$ git commit -m "step1"
$ touch projectfiles
$ git add .
$ git commit -m "step1"
$ mkdir week1/.weekfile week2/.weekfile
$ mkdir week1 week2
$ touch week1/.weekfile week2/.weekfile
$ git add .
$ git commit -m "step2"
$ cd week1
$ touch hello.txt
$ git add hello.txt
$ git commit -m "step3"
$ cd ..
$ cp week1/hello.txt week2/hello_copy.txt
$ git add week2/hello_copy.txt
$ git commit -m "step4"
$ cd week1
$ rm hello.txt
$ git add -u
$ git commit -m "step5"
$ vim about_me.txt
$ git add about_me.txt
$ git commit -m "step6"
$ git remote add origin https://github.com/Adewunmi0303/Linux.git
$ git branch -M master
$ git push -u origin master
$ https://github.com/Adewunmi0303/Linux.git
