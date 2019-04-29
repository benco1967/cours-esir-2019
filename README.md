# Cours ESIR 2019

Documentation de base pour le TP

__Rappel pour toute communbication avec moi, n'oubliez pas de me mettre le noms du groupe de TP et le noms des personnes du groupe__

# Objectif
Réaliser un service avec NodeJS et MongoDB offrant une API CRUD. 
+ Cette API sera sécurisée par un JWT fourni par le service élaboré en première partie de TP avec Stéphane Michel.
+ le contrat d'API est celui fourni dans le swagger de ce projet

# Livrable
Le livrable sera un zip ou un dépôt git (accessible) il devra contenir
+ le code 
  + le code du serveur
  + les tests
  + les scripts (s'il y en a)
+ la documentation expliquant comment ça marche, ou pourquoi cela ne marche pas, pas besoin d'être long (des readme.md suffisent ou le lien sur un google doc ou autre)

Le code doit pouvoir être installé et lancé avec les opérations suivantes :
```
git clone // ou // unzip monfichier.zip
npm install
npm test
npm start

```

# Utilisation de MongoDB

Différentes Solutions
+ installer mongo en local sur le pc (si on a les droits)
+ utiliser docker pour lancer un container mongo en local sur le pc (si on a les droits) (vous pouvez trouver un tel container linux [ici](https://github.com/benco1967/mongo-container)
+ utiliser une instance externe sur le cloud [atlas de mongodb](https://www.mongodb.com/cloud/atlas) l'instance de base est gratuite

_remarque :_ Pensez à utiliser des paramètres de configuration pour accéder à votre base de données. En effet pour que je puisse tester vos livrable il me faudra tester sur ma propre base.

# Authentification
L'authentification se fait avec le JWT fourni par le précédent projet. C'est la même authentification que pour la partie CRUD.
