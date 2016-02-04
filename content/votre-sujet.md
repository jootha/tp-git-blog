+++
date = "AAAA-MM-DDT:12:00:00+01:00"
draft = true
title = "Mes réponses au TP Git"
+++

# TP Git
## Configuration

git config --global user.name "Melissa Maerten"
git config --global user.email "me.maerten@gmail.com"
git config --global http.proxy http://cache.univ-lille1.fr:3128
mkdir git
cd git
gir init .
mkdir content
vi content/votre-sujet.md
git add votre-sujet.md
git commit -m
	" * identifiant unique
	  * date
	  * auteur
	  * Message obligatoire "
git diff
git diff "ID1" "ID2"
vi content/pokemon.md
git add pokemon.md
git commit -m Pokemon
git rm content/pokemon.md
git add pokemon.md
git comit -m "Suppression de Pokemon"
