# Oppimispäiväkirja: Git projektissa

__Mitä hyötyä voisi olla versionhallinnasta, jos kehität projektia yksin?__

Kaikki koodimuutokset tallentuvat versioina. Jos jokin uusi ominaisuus rikkoo koodin, on helppo palata toimivaan versioon ilman tarvetta luoda manuaalisia varmuuskopioita (kuten projekti_final_v2).
Uusia ominaisuuksia voi kokeilla omissa kehityshaaroissaan (feature branch) ilman pelkoa siitä, että toimiva pääkoodi (master/main) sotkeutuu.
Koodi on turvassa etärepositoriossa (esim. GitHubissa), vaikka omalle tietokoneelle tapahtuisi jotain.

__Mitä hyötyä voisi olla versionhallinnasta, jos projektissa on useita kehittäjiä?__

Useampi kehittäjä voi työskennellä saman projektin eri ominaisuuksien parissa yhtä aikaa omissa haaroissaan sotkematta toistensa koodia.
Git auttaa yhdistämään eri kehittäjien tekemät muutokset ja ilmoittaa selkeästi, jos kahden koodarin muutokset ovat ristiriidassa keskenään (merge conflict).
Yhdistämispyyntöjen (Pull Request) avulla tiimi voi tarkistaa ja kommentoida toistensa koodia ennen kuin se hyväksytään päähaaraan.
Nähdään selkeästi, kuka on tehnyt minkäkin muutoksen ja miksi (commit-viestit).

__Miten järjestäisit projektitiimin versionhallinnan 3-4 hengen ohjelmistoprojektikurssilla? Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.__

Päähaara on rauhoitettu (main): Päähaaraan ei koskaan koodata suoraan. Siellä on vain aina toimiva, testattu versio.
Kehityshaara (develop): Integroidaan uudet ominaisuudet ensin yhteiseen develop-haaraan.
Ominaisuushaarat (feature branch): Jokainen uusi tehtävä/ominaisuus aloitetaan omassa haarassaan: git switch -c feature/ominaisuuden-nimi.
Pull Request (PR) & Katselmointi: Kun ominaisuus on valmis, se viedään GitHubiin: git push -u origin feature/ominaisuuden-nimi. Avataan Pull Request develop-haaraan. Vähintään yhden tiimiläisen tulee katselmoida ja hyväksyä PR ennen yhdistämistä.
Säännöllinen päivittäminen: Ennen uuden työn aloittamista haetaan aina uusimmat muutokset: git pull origin develop.

__Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?__

Opintojakso ja sen harjoitukset olivat erittäin hyödyllisiä ja käytännönläheisiä. Hands-on-harjoitukset (kuten Harjoitus 6 ja 7) auttoivat ymmärtämään, miten Git ja GitHub toimivat todellisessa tiimityöskentelyssä eikä vain teoriassa. Merkkikomentojen käyttö ja Pull Requestien tekeminen tulivat tutuiksi.