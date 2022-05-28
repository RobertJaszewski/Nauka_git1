To jest plik README.md o nauce gita.

Tutaj będą wpisywane komendy dotyczące podstaw gita

# utworzenie nowego folderu
mkdir -p workspace/nauka_gita cd workspace/nauka gita

# konfiguracja gita
git config -l git config --globar user.name "RobertJaszewski"

# nie lubimy spamerów
(email jest dołączony do zapisów w git/githubie)

git config --global user.email "RobertJaszewski@users.noreply.github.com"

# cała globalna konfiguracja jest w następującym pliku
cat ~/.gitconfig

# sprawdzamy, czy jesteśmy we właściwej ścieżce
pwd

# powinniśmy zobaczyć sciezke konczaca sie nauka_gita tworzymy repozytorium (inicjializujemy gita)
git init

# repozytorium jest w .git/
ls .git/

# reporzytorium ma swoj plik konfiguracyjny
cat .git/config

# tworzymy README.md
touch README.md

# otwieramy np. atom, nano lub code w katalogu glownym repozytorium
atom . code . git status

# zmien README.md
git status git add README.md

# bez -m, git otworzy domyslny edytor
git commit git log git push

# odswiez w przeglarce swoje repozytorium nauka_gita