ACTION
Développer un plugin, en CakePHP 5,pour un moteur de flux de travail, “workflow engine” en anglais, avec un système d'automates à états finis ; puis dans un deuxième l’associer à un système de queue de tâches.

ÉTAPES
- Créer la structure initiale du plugin en utilisant CakePHP 5, nommée « AutomatePlugin ».
- S'inspirer finement du fonctionnement et de la structure de toutes les tables de l’automate à états finis du framework Radicore PHP de Tony Marston pour l'architecture de l'automate à états finis. Relire 20 fois toute documentation à ce sujet. 
- Cette structure doit être indépendante de tables déjà existantes. Ne pas modifier la structure de la table commandes par exemple.
- Intégrer des fonctionnalités de gestion d’états, de transitions et de conditions, etc. au sein du plugin. 
- Utiliser des plugins CakePHP compatibles pour enrichir les fonctionnalités, en particulier l'automatisation des tâches de fond et l’interface utilisateur.
    - Par exemple CakePHP/CrudView Plugins pour l’UI ou CakePHP/Queue pour la gestion des tâches,
    - fournir tout le code nécessaire à l’implémentation de ces plugins.
- Tester l’automate en simulant différents scénarios de tous les cas de figure possibles.
- Fournir tout le code nécessaire pour chacune des étapes.
  
PERSONA
Agir en tant que développeur CakePHP expérimenté, ayant des connaissances en conception de plugins et en programmation d’automates.

EXEMPLES
- Exemple de structure de code pour les transitions d’états.
- Code d’initialisation d’un état dans le framework Radicore pour inspiration.
- Syntaxe d’un workflow de transitions illustratif.

### CONTEXTE
- Le plugin doit permettre de modéliser des processus sous forme d’automate pour faciliter la gestion des états et des transitions dans une application développée sous CakePHP 5.
- L'EDI utilisé est LazyVim, avec une configuration axée sur CakePHP, dans un environnement de développement open-source.

### CONTRAINTES
- Utiliser uniquement les plugins CakePHP compatibles avec la version 5.
- Écrire du code compatible avec la structure MVC de CakePHP.
    - Code formaté dans un style cohérent avec CakePHP (PSR-12).
    - Tout le code, et en particulier chaque fonction, doit être parfaitement commenté (PHPDoc).

### TEMPLATE
- Présenter le code dans un bloc de code brut (PhpDoc), et structurer l’explication en sections avec des titres pour chaque étape du développement (ex : Création du Plugin, Gestion des États, etc.).
- Toujours fournir  un exemple de code.
