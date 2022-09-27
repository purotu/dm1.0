# Gitin käyttöohje

Tässä oppaassa opetellaan käyttämään Git-versionhallintaa.

## Aloitus

`
git config --global user.name "käyttäjän nimi"
git config --global user.email "käyttjä@mail.com"
`

## Uuden repositoryn luominen
`
git init
`

Komento pitää antaa siinä hakemistossa, joka on projektin juuri.

## Tilan tarkistaminen

`
git status
`

## Tiedostojen hallinta

`
git add tiedosto1.txt tiedosto2.txt
git add .
`

## Commitin tekeminen

`
git commit -m "Viesti"
`

Jos -m valitsin unohtuu ja joudut Vim-editoriin, niin sitten:
1. Insert -näppäimellä kirjoitustilaan
2. Kirjota viesti.
3. Esc-näppäimellä pois kirjoitustilasta
4. Komennolla :wq poistut editorista ja tallennat viestin.

## Etärepositoryn yhdistäminen

Ennen kuin voit yhdistää paikallisen repositoryn etärepositoryyn, se täytyy luoda esim. Githubissa.

Jos sinulla on paikallinen repository nimeltä **master**, voita antaa seuraavat komennot:


`
git remote add origin *https://linkkietärepositoryyn*
git branch -M main
git push -u origin main
`
