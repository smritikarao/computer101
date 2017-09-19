# computer101
smritikarao@LIBLAB117 MINGW64 ~
$ mkdir love

smritikarao@LIBLAB117 MINGW64 ~
$ cd love

smritikarao@LIBLAB117 MINGW64 ~/love
$ git clone https://github.com/smritikarao/computer101.git
Cloning into 'computer101'...
warning: You appear to have cloned an empty repository.

smritikarao@LIBLAB117 MINGW64 ~/love
$ ls
computer101/

smritikarao@LIBLAB117 MINGW64 ~/love
$ cd computer 101
bash: cd: too many arguments

smritikarao@LIBLAB117 MINGW64 ~/love
$ cd computer101

smritikarao@LIBLAB117 MINGW64 ~/love/computer101 (master)
$ echo "food" > chicken.txt

smritikarao@LIBLAB117 MINGW64 ~/love/computer101 (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        chicken.txt

nothing added to commit but untracked files present (use "git add" to track)

smritikarao@LIBLAB117 MINGW64 ~/love/computer101 (master)
$ git add .
warning: LF will be replaced by CRLF in chicken.txt.
The file will have its original line endings in your working directory.

smritikarao@LIBLAB117 MINGW64 ~/love/computer101 (master)
$ git commit -m "food"
[master (root-commit) 1d2e68a] food
 Committer: Smritika Rao <smritikarao@uvic.ca>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
 create mode 100644 chicken.txt

smritikarao@LIBLAB117 MINGW64 ~/love/computer101 (master)
$ git push

Counting objects: 3, done.
Writing objects: 100% (3/3), 215 bytes | 215.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/smritikarao/computer101.git
 * [new branch]      master -> master

smritikarao@LIBLAB117 MINGW64 ~/love/computer101 (master)
$

smritikarao@LIBLAB117 MINGW64 ~/love/computer101 (master)
$
