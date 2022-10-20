- Version started on 2022-10-18
- Release Target: V1
  - Release date:
- Pour le moment (2022-10-18), on liste les points importants, on structurera ensuite en s'appuyant (ou pas) sur les templates existants
- 

## Responsable de l'entrepot de données identifié clairement
Il peut y avoir délégation de sous-responsabilité sur des sous-projets ou sous-ensembles des données

## Définir la structure de l'espace de stockage, et la respecter.

- On peut utiliser une représentation schématique (tree, etc) ou déposer un template zippé de l'arborescence des folders et sous folders
- Encourager l'utilisation d'archive tar.gz ou tar.bz (compression + effet de classification)
- mais garder un index du contenu de l'archive avec un `<nom_archive>_readme.md`

## Convention de nommage des Fichiers et Dossiers
- Les `Fichiers` doivent toujours avoir une extension de type `.ext`
- Eviter d'utiliser des `.` qui ne seraient pas séparateurs d'extension
    - Leur préférer des `_` ou `-`
- Eviter d'utiliser des caractères espace ` ` dans les noms de fichiers
- Ne pas utiliser de caractères `spéciaux`dans les noms de fichiers et en particulier `'`, `"`, `$`, etc. Si possible définir
  cette liste de caractère spéciaux à éviter.
  
  voir [characters_in_filenames.md](../characters_in_filenames.md)
- Considérer la pratique de ne pas utiliser de caractère accentués (non UTF-8) dans les noms de fichiers et de dossiers
- Autant que possible, réfléchir à une règle "**inclusive**" de nommage des fichiers, c'est à dire une règle qui spécifie comment
  les fichiers devraient être nommés plutôt que comment ils ne devraient PAS être nommés... (cela évite les zones grises)
  

## Monitorer l'espace de stockage
- extensions présentes et leur représentations
- distribution de la taille des fichiers
- 
