# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Helppoa oli peruskomentojen kuten git status ja git add käyttö. Vaikeinta oli alussa haarautumisen (branching) ja yhdistämisen (merging) logiikan ymmärtäminen sekä mahdollisten ristiriitojen hallinta. Oppimista auttoi komentojen toistaminen käytännössä VS Coden terminalissa ja vaiheittainen eteneminen harjoitusten mukaan. Esteet selvitin lukemalla ohjeita, tarkistamalla tilanteen git status -komennolla ja kysymällä neuvoa.
## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| Komento | Kuvaus |
| --------| ------ |
| `git init` | Luo uuden tyhjän Git-repositorion |
| `git status` | Näyttää työhakemiston ja indeksin tilan |
| `git add .` | Lisää kaikki muutetut tiedostot indeksöintiin (stage) |
| `git commit -m "viesti"` | Tallentaa muutokset historiaan viestin kanssa |
| `git branch` | Näyttää kaikkien haarojen luettelon |
| `git switch -c haara` | Luo uuden haaran ja siirtyy siihen |
| `git merge haara` | Yhdistää valitun haaran nykyiseen haaraan |
| `git log --oneline` | Näyttää tiivistetyn commit-historian |