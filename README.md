prasr@Prachi MINGW64 /c/gunjan/gunjan/projects
$ git init
Initialized empty Git repository in C:/gunjan/gunjan/projects/.git/

prasr@Prachi MINGW64 /c/gunjan/gunjan/projects (master)
$ git add README.md
fatal: pathspec 'README.md' did not match any files

prasr@Prachi MINGW64 /c/gunjan/gunjan/projects (master)
$ git add README.md

prasr@Prachi MINGW64 /c/gunjan/gunjan/projects (master)
$ git commit -m "first coomit"
[master (root-commit) f0d8ea9] first coomit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md

prasr@Prachi MINGW64 /c/gunjan/gunjan/projects (master)
$ git branch
* master

prasr@Prachi MINGW64 /c/gunjan/gunjan/projects (master)
$ git branch -M main

prasr@Prachi MINGW64 /c/gunjan/gunjan/projects (main)
$ git branch
* main

prasr@Prachi MINGW64 /c/gunjan/gunjan/projects (main)
$ git remote add origin git@github.com:gunjanrawal/projects.git

prasr@Prachi MINGW64 /c/gunjan/gunjan/projects (main)
$ git push -u origin main
The authenticity of host 'github.com (20.207.73.82)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 213 bytes | 213.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:gunjanrawal/projects.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

prasr@Prachi MINGW64 /c/gunjan/gunjan/projects (main)
$ git push -u origin main

Everything up-to-date
branch 'main' set up to track 'origin/main'.
