For Q10 & Q11 , below are the logs from git bash:

lenovo@Abilash MINGW64 ~/Desktop/FullStack_SDET/FSGit (master)
$ git checkout b1
Switched to branch 'b1'

lenovo@Abilash MINGW64 ~/Desktop/FullStack_SDET/FSGit (b1)
$ git rebase master
Successfully rebased and updated refs/heads/b1.

lenovo@Abilash MINGW64 ~/Desktop/FullStack_SDET/FSGit (b1)
$ git checkout b2
Switched to branch 'b2'

lenovo@Abilash MINGW64 ~/Desktop/FullStack_SDET/FSGit (b2)
$ git rebase b1
Successfully rebased and updated refs/heads/b2.

lenovo@Abilash MINGW64 ~/Desktop/FullStack_SDET/FSGit (b2)
$

