# Git
**Git on työkalu, jota käytetään versionhallintaan.**
**Se on helppo yhdistää esim. Visual Studio Codeen jota kautta sen saa siirrettyä vaikka Githubiin.**
### Yleistä tietoa Git:stä
1. Git julkaistiin vuonna 2005
2. Git on ilmainen
3. Git:llä voi hallita pieniä ja myös isompia tiedostoja
# Github
**Github on ilmainen netissä toimiva alusta, jonne voi tallentaa projekteja ja tehdä yhteistyötä muiden kanssa.**
**Githubissa projektit voit asettaa yksityiseksi tai muiden nähtäviksi**
### Yleistä tietoa Githubista
1. Github julkaistiin vuonna 2008
2. Microsoft osti Githubin vuonna 2018
3. Githubia on suht helppo käyttää
## Git:n käyttö
### Git tietojen määrittäminen
- Git ottaminen käyttöön kansiossa: git init
- Käyttäjänimen määrittäminen: git config --global user.email "erikki.esimerkki@gmail.com"
- Git tietojen näyttäminen: git config --list --global
## Githubin käyttö
### Githubin komentoja
- Paikallisen kansion kytkeminen GitHub repositorioon: git remote add origin https://github.com/Githubtunnus/GitHubRepositio.git
- Etärepositio kytköksen tarkistaminen : git remote -v
- Paikallisen työkansion tietojen laittaminen GitHubiin: git push -u origin master