---
title: Pages
permalink: /docs/site/
---

## Creer une page

**1.** Ajouter une nouvelle page dans le dossier _docs/ 
(create new file exemple.md)
Votre fichier doit commencer par ces quelques lignes.

```
---
title: My Page
permalink: /docs/my-page/
---

Hello World!
```

Le nom donné en permalink ici my-page ceras celui de l'url.

**2.** Editer `_data/docs.yml` vous pouvez créer un nouveau menu ou utiliser ceux déja présent.

```
- title: Bien débuter
  docs:
  - home
  - installation
  - clone
  - themes
  - customization
  - my-page
  
```

ou

```  
- title: Nouveau menu
  docs:
  - my-page
```
