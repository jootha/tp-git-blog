+++
date = "2016-02-04T12:00:00+01:00"
draft = true
title = "Mes réponses au TP Git"
+++
# TP Git
## Configuration

git config --global user.name "Mariama Dramé"
git config --global user.email "drame.mariama@hotmail.com"
git config --global http.proxy http://cache.univ-lille1.fr:3128
mkdir GIT
cd GIT
git init .
mkdir content
emacs reponses.md
git add reponses.md
git commit -m Initialisation
    *identifiant --> unique
    *date
    *auteur
    *Message obligatoire

emacs reponses.md (le modifier)
git commit -am "second commit"
git diff "ID1" "ID2"
emacs pokemon.md
git add pokemon.md
git commit -m Pokemon
rm pokemon.md
git add pokemon.md
git commit -m "Supression de Pokemon!"




    
