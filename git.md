# Gitin käyttöohje

Tässä oppaassa opetellaan käyttämään gittiä.

## Aloitus

git config --global user.name "käyttäjän nimi"
git config --global user.email "käyttjä@mail.com"

## Uuden repositoryn luominen

git init

Komento pitää antaa siinä hakemistossa, joka on projektin juuri.

## Tilan tarkistaminen

git status

## Tiedostojen hallinta

git add tiedosto1.txt tiedosto2.txt
git add .

## Commitin tekeminen

git commit -m "Viesti"

Jos -m valitsin unohtuu ja joudut Vim-editoriin, niin sitten:
1. Insert -näppäimellä kirjoitustilaan
2. Kirjota viesti.
3. Esc-näppäimellä pois kirjoitustilasta
4. Komennolla :wq poistut editorista ja tallennat viestin.

## Etärepositoryn käyttäminen

git remote add etärepon-linkki