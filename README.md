# Ruby on Rails Tutorial exemple d'application

Il s'agit de l'exemple de demande pour
[* Ruby on Rails Tutorial:
Apprenez le développement Web avec Rails *] (http://www.railstutorial.org/)
Par [Michael Hartl] (http://www.michaelhartl.com/).

## Licence

Tout le code source dans [Didacticiel Ruby on Rails] (http://railstutorial.org/)
Est disponible conjointement sous licence MIT et la licence Beerware. Voir
[LICENCE.md] (LICENCE.md) pour plus de détails.

## Commencer

Pour commencer à utiliser l'application, cloner le compte de rechange, puis installer les gemmes nécessaires:

`` `
$ Bundle install - sans production
`` `

Ensuite, migrez la base de données:

`` `
$ Rails db: migrate
`` `

Enfin, exécutez la suite de tests pour vérifier que tout fonctionne correctement:

`` `
$ Rails test
`` `

Si la suite de test passe, vous serez prêt à exécuter l'application dans un serveur local:

`` `
$ Rails server
`` `

Pour plus d'informations, consultez le
[* Ruby on Rails Tutorial * book] (http://www.railstutorial.org/book).
