# demo-git-hub
practicing project
  501  cd d:
  502  mkdir oct25-dcpbatch
  503  cd oct25-dcpbatch/
  504  pwd
  505  ls
  506  clear
  507  git config --list
  508  clear
  509  git config --global user.email "loksai.xyz@gmail.com"
  510  git config --global user.name "Loksai"
  511  git config --list
  512  git config --global user.email "loksai.eta@gmail.com"
  513  git config --list
  514  pwd
  515  mkdir repo1
  516  cd repo1/
  517  ls
  518  pwd
  519  git init
  520  ls -a
  521  cd .git/
  522  ll
  523  clear
  524  cd ..
  525  ls
  526  clear
  527  git staus
  528  git status
  529  clear
  530  echo "rec1" >> file1.txt
  531  ls
  532  git status
  533  git add file1.txt
  534  git status
  535  git commit -m "CM1"
  536  clear
  537  git log
  538  echo "rec1" >> file2.txt
  539  ls
  540  git status
  541  git add file2.txt
  542  git commit -m "CM2"
  543  clear
  544  git log
  545  clear
  546  echo "rec1" >> file3.txt
  547  echo "rec1" >> file4.txt
  548  git status
  549  git add .
  550  clear
  551  git status
  552  git commit -m "CM3"
  553  git log
  554  clear
  555  git log
  556  clear
  557  ls -a
  558  cd .git
  559  ls
  560  cd ..
  561  ls
  562  git status
  563  clear
  564  ls
  565  echo "rec1" >> file5.txt
  566  git status
  567  git add .
  568  git status
  569  git stash
  570  git status
  571  ls
  572  git stash list
  573  echo "rec1" >> file6.txt
  574  git add .
  575  git stash save "This is created for Dec. Rel"
  576  git stash list
  577  ls
  578  git stash show
  579  clear
  580  git stash list
  581  git stash apply
  582  git status
  583  git stash list
  584  git stash save This is created for Dec. Rel1
  585  git stash list
  586  git status
  587  git stash pop
  588  git stash list
  589  git stash drop
  590  git stash list
  591  git status
  592  git stash pop
  593  git status
  594  git stash list
  595  git stash branch dec-rel
  596  clear
  597  git status
  598  git switch -c feature1
  599  git status
  600  git status
  601  git checkout -b feature2
  602  git status
  603  git log
  604  git log
  605  git log --oneline
  606  git log --stat
  607  git log --oneline
  608  git log -2
  609  git log --oneline -2
  610  git status
  611  ls
  612  git ls-files
  613  clear
  614  git rm --cached file5.txt
  615  git status
  616  git rm -f file6.txt
  617  git status
  618  ls
  619  ls
  620  git branch
  621  cd ..
  622  mkdir repo2
  623  cd repo2
  624  git init
  625  ls
  626  ls -a
  627  vi .gitignore
  628  ls -a
  629  git status
  630  git commit -m "Created git ignore file"
  631  ls
  632  ls -a
  633  git status
  634  git add .
  635  git commit -m "Created git ignore file"
  636  git status
  637  l
  638  ls
  639  echo "rec1" >> s1.txt
  640  git status
  641  echo "rec1" >> a1.doc
  642  git status
  643  cat .gitignore
  644  ls
  645  clear
  646  git log
  647  history
  648  ls
  649  ls -a
  650  cat .gitignore
  651  history
