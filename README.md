# 1ITF HTML5 Uitdaging 1
Dit zijn de startbestanden voor **Uitdaging 1** voor 1ITF van de Thomas More Hogeschool (campus Geel).

<p align="center">
    <img src="https://www.thomasmore.be/themes/wundertheme/logo.svg" alt="Thomas More Kempen" width="300" />
</p>

## Basisvereisten (eenmalig te installeren)

Volgende tool hoef je maar eenmalig te installeren:

(is normaal al in orde want in Webdesign Basis ben je hier al mee gestart)

- [**Git**](https://git-scm.com/)


## Stappenplan voor een nieuw project op basis van deze repository

### Een GitHub-account aanmaken en configureren 
(is normaal al in orde want in Webdesign Basis ben je hier al mee gestart)

1. Maak, met je mailadres van de hogeschool, een GitHub-account aan op https://github.com. (Als student krijg je extra features zoals private repos)
2. Upgrade van je education account via https://education.github.com/
3. Stel met volgende commando’s lokaal je identiteit in:   
`git config ‐‐global user.name "je naam"`   
`git config ‐‐global user.email "je mailadres"`   
`git config ‐‐global core.editor notepad`


### Opzetten van een lokale repo 
1. Clone deze repo `git clone https://github.com/AnnHannes/Uitdaging1.git`
2. Wis de map **.git** in de repo
3. Initialiseer een nieuwe Git-repo `git init`
4. Voeg alle bestanden (uitgezonderd deze die zijn uitgesloten via **.gitignore**) uit deze map aan de staging area toe   
`git add .`
5. Verplaats de bestanden van de staging area naar de lokale repo `git commit -m "Startbestanden"`
6. Pas de inhoud van ***README.md*** eventueel aan

### Opzetten van een remote repo 
1. Maak een nieuwe, lege, (private) repo **projectNaam** op GitHub   
2. Verbind de lokale repo met de remote repo `git remote add <remote‐name> <remote‐url>`   
bv: `git remote add origin https://github.com/jouwaccount/projectNaam.git`
3. Push de lokale repo naar de remote repo `git push ‐u origin master`

### Stagen en committen van lokaal gewijzigde bestanden 
Maak regelmatig back-ups. Wacht dus niet te lang met wijzigingen op GitHub te plaatsen. 

1. Controleer de status `git status`
2. Voeg alle wijzigingen aan de staging area toe `git add .`
3. Verplaats de bestanden van de staging area naar de lokale repo `git commit -m "Comment"`
4. Push de lokale repo naar de remote repo `git push`

