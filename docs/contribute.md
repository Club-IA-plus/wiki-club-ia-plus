# Comment contribuer ? 

## Installation du projet

Pour contribuer a ce wiki, ainsi qu'a divers autre projets du ClubIA+, vous avez besoins de connaitre les bases de Git/Github.

La première étape est de cloner ce projet sur votre machine :

``` 
git clone https://github.com/Club-IA-plus/wiki-club-ia-plus
``` 

Ensuite, vous devez entrer dans le dossier du projet que vous venez de cloner sur votre machine :

```
cd wiki-club-ia-plus
``` 

Ensuite, il vous suffit d'utiliser Docker pour lancer le projet :

```
docker-compose up
```

Le projet est désormais visible en local à l'adresse suivante : http://localhost:8000

## Contribution

1. Se positionner sur la branche develop
```
git checkout develop
```

2. Créer une nouvelle branche pour votre fonctionnalité
```
git checkout -b nom-fonctionnalite
```

3. Faire vos modifications et ajouter le code dans la branche
```
git add * 
```

4. Committer vos modifications
```
git commit -m "feat: Add feature X"
```

5. Pousser votre branche sur le dépôt distant
```
git push origin nom-fonctionnalite
```

6. Proposer une merge request
```
Rendez-vous sur la plateforme de gestion du code (GitHub)

Créez une merge request (ou pull request) de votre branche vers develop.

Ajoutez une description claire de vos changements
```













