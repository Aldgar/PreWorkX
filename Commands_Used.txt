mohamedibrahim@Mohameds-MBP ~ % mkdir PreWorkX
mohamedibrahim@Mohameds-MBP ~ % cd PreWorkX
mohamedibrahim@Mohameds-MBP PreWorkX % mkdir docs
mohamedibrahim@Mohameds-MBP PreWorkX % mkdir reports
mohamedibrahim@Mohameds-MBP PreWorkX % mkdir images
mohamedibrahim@Mohameds-MBP PreWorkX % mkdir src
mohamedibrahim@Mohameds-MBP PreWorkX % mkdir html
mohamedibrahim@Mohameds-MBP PreWorkX % mkdir css
mohamedibrahim@Mohameds-MBP PreWorkX % mkdir js
mohamedibrahim@Mohameds-MBP PreWorkX % mkdir data
mohamedibrahim@Mohameds-MBP PreWorkX % cd docs
mohamedibrahim@Mohameds-MBP docs % touch report_one.txt
mohamedibrahim@Mohameds-MBP docs % touch report_two.txt
mohamedibrahim@Mohameds-MBP docs % cd html
cd: no such file or directory: html
mohamedibrahim@Mohameds-MBP docs % cd PreWorkX
cd: no such file or directory: PreWorkX
mohamedibrahim@Mohameds-MBP docs % cd ~ 
mohamedibrahim@Mohameds-MBP ~ % cd PreWorkX
mohamedibrahim@Mohameds-MBP PreWorkX % cd html
mohamedibrahim@Mohameds-MBP html % touch index.html
mohamedibrahim@Mohameds-MBP html % cd ~
mohamedibrahim@Mohameds-MBP ~ % cd PreWorkX
mohamedibrahim@Mohameds-MBP PreWorkX % cd css
mohamedibrahim@Mohameds-MBP css % touch style.css
mohamedibrahim@Mohameds-MBP css % cd ~
mohamedibrahim@Mohameds-MBP ~ % cd PreWorkX
mohamedibrahim@Mohameds-MBP PreWorkX % cd js
mohamedibrahim@Mohameds-MBP js % touch script.js
mohamedibrahim@Mohameds-MBP js % cd ~
mohamedibrahim@Mohameds-MBP ~ % cd PreWorkX
mohamedibrahim@Mohameds-MBP PreWorkX % cd data
mohamedibrahim@Mohameds-MBP data % cat data.txt
cat: data.txt: No such file or directory
mohamedibrahim@Mohameds-MBP data % touch data.txt
mohamedibrahim@Mohameds-MBP data % cat data.txt
mohamedibrahim@Mohameds-MBP data % echo "Hello Data"
Hello Data
mohamedibrahim@Mohameds-MBP data % cd ~
mohamedibrahim@Mohameds-MBP ~ % cd PreWorkX
mohamedibrahim@Mohameds-MBP PreWorkX % ls
css	data	docs	html	images	js	reports	src
mohamedibrahim@Mohameds-MBP PreWorkX % cd data
mohamedibrahim@Mohameds-MBP data % cat data.txt
mohamedibrahim@Mohameds-MBP data % echo "Hello Data"
Hello Data
mohamedibrahim@Mohameds-MBP data % cat data.txt
mohamedibrahim@Mohameds-MBP data % cd data.txt
cd: not a directory: data.txt
mohamedibrahim@Mohameds-MBP data % echo "Hello Data" >> data.txt
mohamedibrahim@Mohameds-MBP data % cat data.txt
Hello Data
mohamedibrahim@Mohameds-MBP data % cd PreWorkX
cd: no such file or directory: PreWorkX
mohamedibrahim@Mohameds-MBP data % cd ~
mohamedibrahim@Mohameds-MBP ~ % cd PreWorkX
mohamedibrahim@Mohameds-MBP PreWorkX % git init PreWorkX
Initialized empty Git repository in /Users/mohamedibrahim/PreWorkX/PreWorkX/.git/
mohamedibrahim@Mohameds-MBP PreWorkX % git status
warning: could not open directory '.Trash/': Operation not permitted
On branch MoeProjectX
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	deleted:    ../ProjectX/ProjectX-Assesment
	deleted:    ../ProjectX/ProjectX/ProjectX-Assesment
	deleted:    ../README.md
	deleted:    ../development/.DS_Store
	deleted:    ../development/resourcify
	deleted:    ../index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	../.CFUserTextEncoding
	../.DS_Store
	../.cache/
	../.gitconfig
	../.idlerc/
	../.lesshst
	../.local/
	../.m2/
	../.npm/
	../.redhat/
	../.ssh/
	../.viminfo
	../.vscode/
	../.zprofile
	../.zsh_history
	../.zsh_sessions/
	../Applications/
	../Creative Cloud Files/
	../Desktop/
	../Documents/
	../Downloads/
	../Library/
	../Movies/
	../Music/
	../Pictures/
	./
	../Public/
	../X-Plane 12/

no changes added to commit (use "git add" and/or "git commit -a")
mohamedibrahim@Mohameds-MBP PreWorkX % .git
zsh: command not found: .git
mohamedibrahim@Mohameds-MBP PreWorkX % cd repository-PreWorkX
cd: no such file or directory: repository-PreWorkX
mohamedibrahim@Mohameds-MBP PreWorkX % git init .
Initialized empty Git repository in /Users/mohamedibrahim/PreWorkX/.git/
mohamedibrahim@Mohameds-MBP PreWorkX % git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.DS_Store
	PreWorkX/
	css/
	data/
	docs/
	html/
	js/

nothing added to commit but untracked files present (use "git add" to track)
mohamedibrahim@Mohameds-MBP PreWorkX % cd imgaes
cd: no such file or directory: imgaes
mohamedibrahim@Mohameds-MBP PreWorkX % cd images
mohamedibrahim@Mohameds-MBP images % touch .gitkeep
mohamedibrahim@Mohameds-MBP images % cd ~
mohamedibrahim@Mohameds-MBP ~ % cd PreWorkX
mohamedibrahim@Mohameds-MBP PreWorkX % git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.DS_Store
	PreWorkX/
	css/
	data/
	docs/
	html/
	images/
	js/

nothing added to commit but untracked files present (use "git add" to track)
mohamedibrahim@Mohameds-MBP PreWorkX % cd docs
mohamedibrahim@Mohameds-MBP docs % mv report_one.txt reports
mohamedibrahim@Mohameds-MBP docs % mv report_two.txt reports
mohamedibrahim@Mohameds-MBP docs % rm reports
mohamedibrahim@Mohameds-MBP docs % cd ~
mohamedibrahim@Mohameds-MBP ~ % cd PreWorkX
mohamedibrahim@Mohameds-MBP PreWorkX % cd reports
mohamedibrahim@Mohameds-MBP reports % touch report_one.txt
mohamedibrahim@Mohameds-MBP reports % touch report_two.txt
mohamedibrahim@Mohameds-MBP reports % git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	../.DS_Store
	../PreWorkX/
	../css/
	../data/
	../html/
	../images/
	../js/
	./

nothing added to commit but untracked files present (use "git add" to track)
mohamedibrahim@Mohameds-MBP reports % cd ~
mohamedibrahim@Mohameds-MBP ~ % cd PreWorkX
mohamedibrahim@Mohameds-MBP PreWorkX % rm PreWorkX
rm: PreWorkX: is a directory
mohamedibrahim@Mohameds-MBP PreWorkX % rmdir PreWorkX
rmdir: PreWorkX: Directory not empty
mohamedibrahim@Mohameds-MBP PreWorkX % git add css
mohamedibrahim@Mohameds-MBP PreWorkX % git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   css/style.css

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.DS_Store
	PreWorkX/
	data/
	html/
	images/
	js/
	reports/

mohamedibrahim@Mohameds-MBP PreWorkX % git add data
mohamedibrahim@Mohameds-MBP PreWorkX % git add html
mohamedibrahim@Mohameds-MBP PreWorkX % git add images
mohamedibrahim@Mohameds-MBP PreWorkX % git add js
mohamedibrahim@Mohameds-MBP PreWorkX % git add reports
mohamedibrahim@Mohameds-MBP PreWorkX % git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   css/style.css
	new file:   data/data.txt
	new file:   html/index.html
	new file:   images/.gitkeep
	new file:   js/script.js
	new file:   reports/report_one.txt
	new file:   reports/report_two.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.DS_Store
	PreWorkX/

mohamedibrahim@Mohameds-MBP PreWorkX % git commit -m "initial setup"
[main (root-commit) e905325] initial setup
 7 files changed, 1 insertion(+)
 create mode 100644 css/style.css
 create mode 100644 data/data.txt
 create mode 100644 html/index.html
 create mode 100644 images/.gitkeep
 create mode 100644 js/script.js
 create mode 100644 reports/report_one.txt
 create mode 100644 reports/report_two.txt
mohamedibrahim@Mohameds-MBP PreWorkX % git push https://github.com/Aldgar/PreWorkX
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream https://github.com/Aldgar/PreWorkX main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

mohamedibrahim@Mohameds-MBP PreWorkX % git push --set-upstream https://github.com/Aldgar/PreWorkX main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (10/10), 678 bytes | 678.00 KiB/s, done.
Total 10 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Aldgar/PreWorkX
 * [new branch]      main -> main
branch 'main' set up to track 'https://github.com/Aldgar/PreWorkX/main'.
mohamedibrahim@Mohameds-MBP PreWorkX % git checkout -b MoeProjectX
Switched to a new branch 'MoeProjectX'
mohamedibrahim@Mohameds-MBP PreWorkX % git status  
On branch MoeProjectX
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   html/index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.DS_Store
	PreWorkX/

no changes added to commit (use "git add" and/or "git commit -a")
mohamedibrahim@Mohameds-MBP PreWorkX % git add html
mohamedibrahim@Mohameds-MBP PreWorkX % git status
On branch MoeProjectX
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   html/index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.DS_Store
	PreWorkX/

mohamedibrahim@Mohameds-MBP PreWorkX % git commit -m "adding the html code to the html file"
[MoeProjectX d3abfeb] adding the html code to the html file
 1 file changed, 11 insertions(+)
mohamedibrahim@Mohameds-MBP PreWorkX % git push https://github.com/Aldgar/PreWorkX
fatal: The current branch MoeProjectX has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream https://github.com/Aldgar/PreWorkX MoeProjectX

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

mohamedibrahim@Mohameds-MBP PreWorkX % git push --set-upstream https://github.com/Aldgar/PreWorkX MoeProjectX
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 493 bytes | 493.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'MoeProjectX' on GitHub by visiting:
remote:      https://github.com/Aldgar/PreWorkX/pull/new/MoeProjectX
remote: 
To https://github.com/Aldgar/PreWorkX
 * [new branch]      MoeProjectX -> MoeProjectX
branch 'MoeProjectX' set up to track 'https://github.com/Aldgar/PreWorkX/MoeProjectX'.
mohamedibrahim@Mohameds-MBP PreWorkX % 
