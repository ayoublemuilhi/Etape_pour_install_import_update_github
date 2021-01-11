# Etape_pour_install_import_update_github
_____________________________installer projet a github le premier fois

 1 - git init (pour faire un dossier nommer  .git)
 2 - git add .
 3 - git commit -m "first commit"
 4 - Exemple: c'esi il'ya donné un (Please tell me who you are.) copy [1 - git config --global user.email "you@example.com" ; 2 -git config --global user.name "Your Name" ]
 5 -again run   git commit -m "first commit"
 6 - git remote add origin https://github.com/ayoublemuilhi/mcinet.git
 7 - git push -u origin master


_____________________________importer projet from github

 1-git clone https://github.com/ayoublemuilhi/mcinet.git
 2- composer install (inside projet pour installer les composer)

____________________________update projet from github
1 - git pull origin master
2 - git add .
3 - git commit -m "message"
4 - git push
