# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Helppoa oli koodin lähettäminen GitHubiin komennolla git push. Vaikeinta ja hämmentävintä oli ymmärtää git fetch -komennon toiminta ja se, miten etärepositorion seuranta-haarat (kuten origin/new-feat) toimivat. Oppimista auttoi git status -komennon jatkuva käyttö, jotta näin, onko paikallinen haara jäljessä vai edellä etäpalvelinta. Esteet selvitin suorittamalla git pull -komennon ja lukemalla терминалин virheilmoituksia huolellisesti.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| Komento | Kuvaus |
| --------| ------ |
| `git remote add origin URL` | Linkittää paikallisen repositorion GitHub-palvelimeen |
| `git remote -v` | Näyttää etärepositorion osoitteet (fetch ja push) |
| `git push -u origin haara` | Lähettää haaran GitHubiin ja asettaa seurannan |
| `git fetch` | Haetaan etärepositorion uusimmat tiedot ilman yhdistämistä |
| `git pull` | Haetaan ja yhdistetään etärepositorion muutokset |
| `git tag nimi` | Luo uuden tunnisteen (tag) nykyiseen commit-versioon |
| `git push --tags` | Lähettää kaikki paikalliset tunnisteet GitHubiin |