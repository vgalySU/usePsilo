- Le PGD n'est pas un engagement ou une profession de foi, et si ça l'était, nous n'aurions
  pas la prétention d'en juger !
- C'est en revanche un document de travail expliquant dans les détails, comment _vous_ allez
  gérer _vos_ données. Il vous servira d'abord à vous, et incidemment à nous qui gérons
  physiquement les fichiers.

### Les bénéfices essentiels pour vous:

- Vous "n'oublierez" pas les données. La pratique montre que, sans un PGD, un fichier qui
  n'est pas accédé pendant deux ans ou plus, n'a qu'une probabilité infime d'être accédé
  et utilisé un jour: il est _pratiquement_ perdu.
- Vous retrouverez plus facilement les données que vous cherchez (y compris celles qui ont
  été déposées par d'autres utilisateurs du compte)
- Vous utiliserez plus facilement les données stockées car vous consignerez dans le PGD
  les métadonnées utilisées pour décrire les données.
- Vous partagerez plus facilement les données quand c'est nécessaire.
- Vous valoriserez mieux les données collectées (par ex. possibilités de réanalyse ou de
  méta-analyses)
- Vous vous simplifierez l'écriture des matériels et méthodes, et vous améliorerez leur
  qualité scientifique
- Vous anticipez les demandes des bailleurs de fond (ANR, UE, etc...) qui vont de plus en
  plus vous conditionner leurs financements à la rédaction de PGD. Mais si vous ne rédigez
  un PGD que parce que qu'on vous le demande, c'est dommage car cela veut dire que vous
  n'avez pas pris la mesure des bénéfices mentionnés ci-dessus, et surtout que cela
  constituera une tâche très ennuyeuse pour vous !

### Les bénéfices essentiels pour l'hébergeur:

- On a une visibilité sur le cycle de vos données. On peut ainsi libérer des espaces
  occupés inutilement (exemple de fichiers déposés dans des banques de données publiques,
  ou devenus obsolètes en raison de l'évolution des techniques).
- Quand les utilisateurs ont formalisé sincèrement la gestion de leurs données, ils
  rationalisent d'eux-mêmes l'espace utilisé: par exemple il n'est pas nécessaire de
  stocker des fichiers intermédiaires qui peuvent être simplement reproduits avec une
  procédure informatique (le cas typique est de stocker à la fois des fastq et leur
  alignements bam, alors que ce dernier permet de regénérer un fastq, nombreux exemples en
  imagerie également).
- Cela permet de reduire le nombre de fichiers dont le format (propriétaire, obsolète,
  etc.) les rend inutilisables.
- Cela permet d'anticiper les besoins à venir en espace de stockage sur des bases précises
  (et non au "doigt mouillé") en évitant la surévaluation des besoins (le "par
  sécurité").
- Cela permet d'établir un dialogue avec les chercheurs pour améliorer la gestion de leurs
  données et de celles des collègues.

Vous avez un ou deux exemples de "templates" de PGD dans le [repository GitHub des
utilisateurs de PSILO](https://github.com/ARTbio/usePsilo), auquel vous êtes invités à
vous connecter et vous abonner.

### Quelques points supplémentaires

- Un PGD est évolutif. Il n'est pas nécessaire d'en fournir une version aboutie dès le début
- Il n'est pas nécessairement rédigé comme un texte. Il peut être constitué d'une table ou
  série de tables, d'un repository GitHub ou GitLab, d'un un organigramme, etc., ou d'une
  combinaison de ces formats. Toutes les idées pratiques et utiles sont les bienvenues.
- Un PGD n'est pas un "miroir" des données, ni un catalogue des données. Mais si par
  exemple vous décidez de créer un catalogue de vos données pour un projet, le PGD
  contiendra la manière dont est construit et implémenté ce catalogue.
- Le PGD n'a pas vocation à contenir les données ni d'informations sensibles sur les
  données. Il devrait donc pouvoir être public, ce qui améliore la "trouvabilité"
  (Findability du FAIR) des données qu'il référence pour les autres scientifiques (qui
  pourront vous contacter le cas échéant).
