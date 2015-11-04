## Questionnements

#### Quels sont les objectifs de la programmation visuelle ?
- Supprimer/requestionner le métier de programmeur ?
- Montrer ses enjeux, ses qualités, ses limites par rapport à la syntaxe textuelle
  - [Pas plus de 50 entités dans l'interface visuelle ?](https://en.wikipedia.org/wiki/Deutsch_limit)

#### La programmation visuelle peut-elle cohabiter avec la syntaxe textuelle ? 
- Avoir une visualisation textuelle (= fondamentale ?) et visuelle du programme 
  - Objectif : **réunir syntaxe textuelle et syntaxe visuelle**

- **État de l'art _rapide_ des éditeurs visuels de contenu (WYSIWYG)** comme Dreamweaver  
*Attention : ces outils peuvent n'être utilisés que pour du développement (layout de site web) donc non orienté objet*

  - Avantages :
    - Accessibilité, tout le monde peut manipuler l'interface (GUI)

  - Défauts :
    - Le rendu visuel produit un code dit « sale » qui n'est pas standard aux normes du langage
    - L'utilisateur n'a pas conscience de la structure / n'apprend pas
    - Seule la partie visible du rendu fonctionne, le code en fond peut être incorrect
    - Possibilités limitées (« L'outil devrait nous permettre d'en faire plus, pas de nous limiter » _(cit. requise)_)
    
- Pourquoi « surcoucher » la syntaxe textuelle considérée comme élémentaire ? ([\#1](Notes.md))
    
#### Pourquoi utiliser la console/terminal en ligne de code (sans GUI) ?
- Exactitude des informations souhaitées : principe des "commandes" console : mkdir, cd, ls
- Pas de marge d'erreur (possibilité de supprimer des fichiers si une commande contient une faute ou un mauvais paramètre)
- Pas d'artefact visuel : exécution de la commande dans la même fenêtre