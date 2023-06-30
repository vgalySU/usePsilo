## Preambule
Ce template est directement inspiré du template ANR_PGD_french_v5.md

Pour les chercheurs qui souhaiteraient l'utiliser, son avantage est qu'il comporte
des sections **pré-remplies** liées à la configuration et au mode de fonctionnement
effectif du serveur de stockage PSILO.

# ARTbio/PSILO - Modèle de PGD (français)


## 1. Description des données et collecte ou réutilisation de données existantes

### 1a. Comment les données sont-elles recueillies ou produites et/ou comment peuvent-elles être réutilisées ?


- Pour chaque type de données, expliquer quelles méthodologies et/ou quels logiciels sont utilisés pour les recueillir ou produire.
  Expliquer également comment elles peuvent être lues (logiciels, procédures...) et réutilisées.
- Enoncer les éventuelles limitations techniques, méthodologiques à la réutilisation des données préexistantes.
- Expliquer comment la provenance des données est documentée. Cette provenance peut par ex. être codée dans le nom des fichiers,
  dans des fichiers appariés de métadonnées, dans un ou plusieurs catalogues (tableau de fichiers avec une ou plusieurs colonnes explicative),
  dans une base de metadonnées, etc.
- Indiquer le cas échéant, les raisons pour lesquelles l’utilisation de sources de données existantes a été envisagée mais écartée
  (eg, si les données constituent une référence déjà existante, en quoi elles diffèrent de cette référence et pourquoi) 

### 1b. Quelles données (types, formats et volumes par ex.) seront collectées ou produites ?

- Indiquer les types de données manipulés. Par exemple, bases de données, tableurs, textuel, image, audio, vidéo, médias composites (eg pdf), etc.
- Détailler les formats de données utilisés: la manière selon laquelle les données sont codées pour le stockage, généralement reflétée par
  l'extension du nom de fichier (par exemple pdf, xlsx, txt, bam, czi, etc.).
  Le PGD doit contenir un liste actualisée de toutes les extensions des fichiers collectés.
  Corrolaire: tout fichier _*doit*_ être nommé avec une extension.
- Chaque fois qu'il existe un document de spécification d'un format de données, indiquer la source accessible de ce document.
- Privilégier les formats standards et ouverts car ils facilitent le partage et la réutilisation à long terme des données (plusieurs catalogues fournissent des listes de ces "formats préférés").
- Donner des détails sur les volumes: quantités d'objets, de fichiers, de lignes, de colonnes, etc. et espace de stockage requis (en octets, kilo, mega, ... octets).


## 2. Documentation et qualité des données

### 2a. Quelles métadonnées et quelle documentation (par exemple méthodologie de collecte et mode d'organisation des données) accompagneront les données ?

_Recommandations_:



* Indiquer quelles métadonnées seront fournies pour aider à la recherche et à l’identification des données.
* Indiquer quels standards de métadonnées seront utilisés (par exemple DDI, TEI, EML, MARC, CMDI).
* Utiliser les standards de métadonnées des communautés scientifiques lorsque ceux-ci existent.
* Indiquer comment les données seront organisées au cours du projet, en mentionnant par exemple les conventions de nommage, le contrôle de version et les structures des dossiers. Des données bien classées et gérées de façon cohérente seront plus faciles à retrouver, à comprendre et à réutiliser.
* Penser à la documentation qui serait nécessaire pour permettre une réutilisation des données. Il peut s'agir notamment de l'information sur la méthodologie utilisée pour collecter les données, sur les procédures et méthodes d’analyse utilisées, sur la définition des variables, des unités de mesure, etc.
* Tenir compte de la façon dont ces informations seront obtenues et enregistrées par exemple dans une base de données avec des liens vers chacun des fichiers, dans un fichier texte de type « lisez-moi », dans les en-têtes de fichiers, dans un livre de référence (« code book ») ou dans les cahiers de laboratoire.

### 2b. Quelles mesures de contrôle de la qualité des données seront mises en œuvre ?

_Recommandations_:



* Expliquer comment la qualité et la conformité de la collecte des données seront contrôlées et documentées. Il s'agit là de préciser les processus comme la calibration, la répétition des échantillons ou des mesures, la capture standardisée des données, la validation de saisie des données, la revue par les pairs, ou la représentation basée sur des vocabulaires contrôlés.


## 3. Stockage et sauvegarde pendant le processus de recherche

### 3a. Comment les données et les métadonnées seront-elles stockées et sauvegardées tout au long du processus de recherche ?

_Recommandations_:



* Décrire l'endroit où les données seront stockées et sauvegardées au cours du processus
de recherche et la fréquence à laquelle la sauvegarde sera effectuée. Il est recommandé de
stocker les données dans au moins deux lieux distincts.

* Privilégier l'utilisation de systèmes de stockage robustes, avec sauvegarde automatique,
tels que ceux fournis par les services informatiques de l'institution d'origine. Le
stockage des données sur des ordinateurs portables, des disques durs externes, ou des
périphériques de stockage tels que des clés USB n'est pas recommandé.

#### Note de PSILO:

Les données seront stockées sur le serveur [PSILO](https://psilo.sorbonne-universite.fr).

Le serveur PSILO a une capacité de stockage de 1 Pétaoctets accessible aux utilisateurs (
les auteurs de PGD) à travers le protocole https et un compte utilisateur [NEXTCLOUD](https://github.com/nextcloud)
protégé par un mot de passe.

Les données stockées sur PSILO _ne sont pas_ sauvegardées, cette sauvegarde sur un media
distinct relevant de la responsabilité de l'utilisateur.

Toutefois, la fiabilité du serveur PSILO est estimée à la date du 30 juin 2023 comme suit:

Probabilités de perte de données au cours des années à venir (détail des paramètres du
modèle statistique ci-dessous):
```
1 an:      0.0004297395270471
5 ans:     0.0021468516680796
10 ans:    0.0042890943640744
```


**Paramètres du [modèle statistique utilisés](https://wintelguy.com/raidmttdl.pl):**


<table>
  <tr>
   <td>Total Usable Storage Capacity (GB) 
   </td>
   <td>900000
   </td>
  </tr>
  <tr>
   <td>Number of RAID Groups
   </td>
   <td>5
   </td>
  </tr>
  <tr>
   <td>Number of drives per RAID Group
   </td>
   <td>12
   </td>
  </tr>
  <tr>
   <td>Total Number of Drives:
   </td>
   <td>60
   </td>
  </tr>
  <tr>
   <td>Drive Capacity (GB)
   </td>
   <td>18000
   </td>
  </tr>
  <tr>
   <td>RAID Type:
   </td>
   <td>R6
   </td>
  </tr>
  <tr>
   <td>Drive Throughput (MB/s)
   </td>
   <td>70
   </td>
  </tr>
  <tr>
   <td>Drive MTBF (hour)
   </td>
   <td>1400000
   </td>
  </tr>
  <tr>
   <td>Drive Annual Failure Rate (%)
   </td>
   <td>0.625714285714286
   </td>
  </tr>
  <tr>
   <td>Drive MTTR (hour)
   </td>
   <td>190.857142857143
   </td>
  </tr>
  <tr>
   <td>System MTTDLDF
<p>
(due to multiple drive failures)
   </td>
   <td>22827236110.2509 hours
<p>
2605848.87103321 years
   </td>
  </tr>
  <tr>
   <td>Probability of read error
<p>
during rebuild
   </td>
   <td>0.7627993899340125
   </td>
  </tr>
  <tr>
   <td>System MTTDLLSE
<p>
(due to read error during rebuild)
   </td>
   <td>20398272.0977679 hours
<p>
2328.56987417441 years
   </td>
  </tr>
  <tr>
   <td>Combined system MTTDLTOTAL
   </td>
   <td><strong>20380060.6060392</strong> hours
<p>
<strong>2326.49093676246</strong> years
   </td>
  </tr>
  <tr>
   <td>Probability of data loss over time
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>1 year
   </td>
   <td><strong>0.0004297395270471</strong>
   </td>
  </tr>
  <tr>
   <td>5 years
   </td>
   <td><strong>0.0021468516680796</strong>
   </td>
  </tr>
  <tr>
   <td>10 years
   </td>
   <td><strong>0.0042890943640744</strong>
   </td>
  </tr>
</table>

#### Note de PSILO:
Bien qu'annoncé dans son titre, la section 3a ne comporte aucune _Recommandation__ sur les
**métadonnées**.

C'est pourtant un point essentiel du PGD, qui, s'il est correctement couvert, bénéficie
directement au projet.

_TODO:_ décliner ici les options possible pour les metadonnées des données du projet.
_Nota bene_: Le choix des metadonnées et du système de classement et de lien avec leurs
données reste à la discrétion de l'auteur du PGD.

### 3b. Comment la sécurité des données et la protection des données sensibles seront-elles assurées tout au long du processus de recherche ?

_Recommandations_:



* Expliquer comment les données seront récupérées en cas d'incident.

#### Note de PSILO

Ce point est à la charge de l'utilisateur car il dépend de la stratégie de
sauvegarde mise en place (autres sites de stockage ?).

* Expliquer qui aura accès aux données au cours du processus de recherche et comment l'accès
aux données est contrôlé, en particulier dans le cadre de recherches menées en collaboration.
* Expliquer quelle politique institutionnelle de protection des données est mise en œuvre.


Un compte de stockage sur PSILO est nominatif (un identifiant email unique) et désigne le
responsable des données.

Le responsable des données est libre de partager ses identifiant et mot de passe avec ses
collaborateurs qui bénéficieront le cas échéant des mêmes droits de lectures comme d'écritures
(donc de destruction) que le titulaire du compte de stockage.

En outre, le titulaire du compte de stockage sur PSILO, bénéficie des fonctionnalités de
partage fournies par l'interface NEXTCLOUD:

- Partage en lecture de dossiers ou fichiers spécifiques avec des utilisateurs désignés par
leurs emails (qu'ils aient un compte de stockage sur PSILO ou non)
- Partage en écriture (sauf destruction) de dossiers spécifiques avec des
utilisateurs désignés par leurs emails (qu'ils aient un compte de stockage sur PSILO ou non)
- Partage Public en lecture de dossiers ou fichiers spécifiques selon un lien (URL) stable
à générer (ce lien peut être associé à une publication scientifique).
- Partage Public en écriture (sauf destruction) de dossiers spécifiques selon un lien (URL)
stable à générer (ce lien peut faire office de site téléchargement anonyme).

* Tenir compte de la protection des données, en particulier si vos données sont sensibles
(par exemple données à caractère personnel, politiquement sensibles des informations ou
secrets commerciaux). Décrire les principaux risques et la façon dont ils seront gérés.

La protection des données sur Psilo repose sur le protocole https et une authentification
simple identifiant/mot de passe.

Un système additionel de surveillance automatique propre
à NEXTCLOUD repertories la totalité des connexions (login/password/IP address) dans une base
de données et lance une alerte (informative) lors d'une connexion avec caractéristiques
inhabituelles.

Les mots de passe des utilisateurs sont réinitialisés tous les 18 mois

Si cela est s'avère nécessaire, PSILO peut instaurer une authentification à 2 facteurs

Les données à caractère personel (eg, séquences de personnes) doivent obligatoirement être
anonymisées et aucune clé de dé-anonymisation ne doit se trouver dans les systèmes de fichiers
de PSILO.

Les données à caractère sensible ou concernant des secrets commerciaux doivent être cryptées
avec un protocole robuste.

Si un protocole de chiffrement symétrique est utilisé, la clé
de chiffrement ne sera pas conservée sur PSILO. De plus, ce protocole devra être associé à
une fonction de dérivation de la clé de façon à limiter les cassages de clé par "brut force".
Ex: AES256 associé à PBKDF2.

Si un protocole de chiffrement asymétrique est utilisé (de type RSA),
la clé privé de chiffrement ne sera pas conservée sur PSILO.



## 4. Exigences légales et éthiques, codes de conduite 

### 4a. Si des données à caractère personnel sont traitées, comment le respect des dispositions de la législation sur les données à caractère personnel et sur la sécurité des données sera-t-il assuré ?

_Recommandations_:

Lorsque vous manipulez des données à caractère personnel, veillez à ce que les lois sur la protection des données (par exemple, RGPD) soient appliquées, notamment :



* Obtenir un consentement éclairé pour la préservation et/ou le partage de données personnelles.
* Envisager l'anonymisation des données personnelles pour la préservation et/ou le partage (des données correctement anonymisées ne sont plus considérées comme des données personnelles).
* Envisager la pseudonymisation des données personnelles (la principale différence avec l'anonymisation est que la pseudonymisation est réversible).
* Envisager le chiffrement des données, qui est considéré comme un cas particulier de pseudonymisation (la clé de cryptage doit alors être stockée séparément des données, par exemple par un tiers de confiance).
* Expliquer si une procédure d’accès spécifique a été mise en place pour les utilisateurs autorisés à accéder aux données personnelles.

### 4b. Comment les autres questions juridiques, comme la titularité ou les droits de propriété intellectuelle sur les données, seront-elles abordées ? Quelle est la législation applicable en la matière ?

_Recommandations_:



* Expliquer qui sera le propriétaire des données, c'est-à-dire qui aura le droit d’en contrôler l’accès :
    * Expliquer quelles conditions d'accès s'appliqueront aux données. Les données seront-elles librement accessibles, ou des restrictions seront-elles appliquées ? Si oui, lesquelles ? Envisager l'utilisation de licences concernant l'accès et la réutilisation des données.
    * S'assurer de couvrir, dans l’accord de consortium, ces questions de droits de contrôle d'accès aux données pour les projets multipartenaires et en cas de propriété partagée des données.
* Indiquer si les droits de propriété intellectuelle (par exemple la directive bases de données, droits _sui generis_) sont affectés. Dans l'affirmative, expliquer lesquels et comment cela sera traité.
* Indiquer s'il y a des restrictions sur la réutilisation des données fournies par des tiers.

### 4c. Comment les éventuelles questions éthiques seront-elles prises en compte, les codes déontologiques respectés ?

_Recommandations_:



* Déterminer si les questions d'éthique auront une incidence sur la façon dont les données seront stockées et transférées, qui pourra les voir ou les utiliser et quelles durées de conservation leur seront appliquées. Démontrer que ces aspects sont bien pris en compte et planifiés.
* Adopter les codes de conduite nationaux et internationaux et le code d’éthique institutionnel et vérifier si une revue des pratiques (par exemple par un comité d'éthique) est requise pour ce qui concerne la collecte de données dans le cadre du projet de recherche.


## 5. Partage des données et conservation à long terme

### 5a. Comment et quand les données seront-elles partagées ? Y-a-t-il des restrictions au partage des données ou des raisons de définir un embargo ?

_Recommandations_:



* Expliquer comment les données pourront être retrouvées et partagées (par exemple, par le dépôt dans un entrepôt de données de confiance, l'indexation dans un catalogue, par l’utilisation d'un service de données sécurisé, par le traitement direct des demandes de données, ou l'utilisation de tout autre mécanisme).
* Définir le plan de préservation des données et fournir l’information sur la durée d’archivage pérenne des données.
* Expliquer à quel moment les données seront rendues disponibles. Indiquer les délais de publication prévus. Expliquer si une utilisation exclusive des données est revendiquée et, dans l'affirmative, pour quelle raison et pour combien de temps. Indiquer si le partage des données sera différé ou limité, par exemple pour des raisons de publication, pour protéger la propriété intellectuelle ou le dépôt de brevets.
* Indiquer qui pourra utiliser les données. S'il s’avère nécessaire de restreindre l'accès pour certaines communautés ou d’imposer un accord pour le partage de données, expliquer comment et pourquoi. Expliquer les mesures qui seront prises pour dépasser ou minimiser ces restrictions.

### 5b. Comment les données à conserver seront-elles sélectionnées et où seront-elles préservées sur le long terme (par ex. un entrepôt de données ou une archive) ?

_Recommandations_:



* Indiquer quelles données ne doivent pas être divulguées ou doivent être détruites pour des raisons contractuelles, légales, ou réglementaires.
* Indiquer comment il sera décidé quelles données garder. Décrire les données qui seront à préserver à long terme.
* Décrire les utilisations (et/ou les utilisateurs) prévisibles des données dans un cadre de recherche.
* Indiquer où les données seront déposées. Si aucun entrepôt reconnu n'est proposé, démontrer dans le plan de gestion des données que les données pourront être prises en charge efficacement au-delà de la durée de financement du projet. Il est recommandé de démontrer que les politiques des entrepôts et les procédures de dépôts (y compris les standards de métadonnées, et coûts mis en œuvre) ont été vérifiés.

### 5c. Quelles méthodes ou quels outils logiciels seront nécessaires pour accéder et utiliser les données ?

_Recommandations_:



* Indiquer si les utilisateurs potentiels auront besoin d’outils spécifiques pour l’accès et la (ré)utilisation des données. Tenir compte de la durée de vie des logiciels nécessaires pour accéder aux données.
* Indiquer si les données seront partagées via un entrepôt, si les demandes d’accès seront traitées en direct, ou si un autre mécanisme sera utilisé.

### 5d. Comment l'attribution d'un identifiant unique et pérenne (comme le DOI) sera-t-elle assurée pour chaque jeu de données ?

_Recommandations_:



* Expliquer comment les données pourraient être réutilisées dans d'autres contextes. Les identifiants pérennes devraient être appliqués de manière à ce que les données puissent être localisées et référencées de façon fiable et efficace. Les identifiants pérennes aident aussi à comptabiliser les citations et les réutilisations.
* Indiquer s’il sera envisagé d’attribuer aux données un identifiant pérenne. Typiquement, un entrepôt pérenne de confiance attribuera des identifiants pérennes.


## 6. Responsabilités et ressources en matière de gestion des données

### 6a. Qui (par exemple rôle, position et institution de rattachement) sera responsable de la gestion des données (c'est-à-dire le gestionnaire des données) ?

_Recommandations_:



* Décrire les rôles et les responsabilités concernant les activités de gestion des données, par exemple : saisie des données, production des métadonnées, qualité des données, stockage et sauvegarde, archivage et partage des données. Nommer la(es) personne(s) responsable(s) impliquée(s) dans la mesure du possible.
* Pour les projets menés en collaboration, expliquer comment s’effectue la coordination des responsabilités de gestion des données entre partenaires.
* Indiquer qui est responsable de la mise en œuvre du PGD, et qui s'assure qu'il est examiné et, si nécessaire, révisé.
* Envisager des mises à jour régulières du PGD.

### 6b. Quelles seront les ressources (budget et temps alloués) dédiées à la gestion des données permettant de s'assurer que les données seront FAIR (Facile à trouver, Accessible, Interopérable, Réutilisable) ?

_Recommandations_:



* Expliquer comment les ressources nécessaires (par exemple le temps) à la préparation des données pour le partage/préservation (curation des données) ont été chiffrées. Examiner et justifier soigneusement toutes les ressources nécessaires pour diffuser les données.
* Il peut s'agir de frais de stockage, de coût matériel, de temps de personnel, de coûts de préparation des données pour le dépôt, de frais d’entrepôt et d'archivage.
* Indiquer si des ressources supplémentaires sont nécessaires pour préparer les données en vue de leur dépôt ou pour payer tous les frais demandés par les entrepôts de données. Si oui, précisez le montant et comment ces coûts seront couverts.

