# tarea
la nota es de 20 exelente

ssh-keygen -t rsa -b 4096 -C "Email de github"
cat ~/.ssh/id_rsa.pub

git remote add origin [ssh o http]
git remote -v
git remote remove origin

# opcion 1
git fetch origin master
git merge origin/master
git merge origin/master --allow-unrelated-histories

# opcion 2
git pull origin master


