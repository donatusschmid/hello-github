## test-of-basic-GitHub-functions
```
 pwd
/Users/donatusschmid
❯ git clone https://github.com/donatusschmid/hello-github
Cloning into 'hello-github'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.
❯ cd hello-github
❯ vi hello.py
❯ python3 hello.py
Hello from GitHub!
❯ git add hello.py
❯ git commit -m "Initial hello.py"
[main c36f478] Initial hello.py
 1 file changed, 6 insertions(+)
 create mode 100644 hello.py
❯ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 367 bytes | 367.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/donatusschmid/hello-github
   1391f27..c36f478  main -> main
4935  git checkout -b feature-update-hello
 4936  vi hello.py
 4937  python3 hello.py
 4938  git add hello.py
 4939  git commit -m "Update hello function"
 4940  git checkout main
 4941  git merge feature-update-hello
 4942  git push origin main
 # This is necessary if changes where made in the browser, like changing readme.md
 4946  git pull origin main --allow-unrelated-histories
 4947  git push origin main
 4948  python3 hello.py



```


