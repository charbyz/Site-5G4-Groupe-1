+++
title = "DÉVELOPPEMENT"
weight = 25
+++

### Comment utiliser NotebookLM

Un des points forts de NotebookLM est la facilité d'utilisation. Dans cette section, on va voir comment créer
une vidéo qui va expliquer nos notes de cours comme si c'était un podcast.


 ### tutoriel

[params]
 après avoir rechercher NotebookLM dans votre navigateur préféré, vous cliquez sur le premier lien et arriver sur cette interface ou vous trouverez le bouton "Try NotebookLM":

 ![alt text](try.png)

 ensuite on clique sur "Create a new notebook" et vous pourrez ajouter les sources que vous voulez. 
 dans cet exemple on va créer une feuille aide-mémoir pour un examen de soutien technique.
 on clique sur "Upload a source" et ensuite on selectionne les fichiers que l'on veut utiliser.
 Après avoir ajouter vos documents on va cliquer sur "Audio Overview"

 ![alt text](create.png)


 ### Type d’entraînement

D’habitude, quand on parle de LLM, on se fie à deux modèles d’apprentissage : supervisé ou non supervisé.
Dans le cas de NotebookLM, il s’agit d’apprentissage auto-supervisé (self-supervised learning).

 ### Apprentissage supervisé

L’apprentissage supervisé consiste à donner au modèle des exemples avec la bonne réponse fournie.
L’IA apprend en comparant sa prédiction avec la réponse humaine.

Exemple :
On montre 15 000 photos de Pokémon étiquetées comme étant de type Eau ou de type Feu.
Ensuite, l’IA apprend à reconnaître elle-même si un nouveau Pokémon est de type Eau ou de type Feu.


### Apprentissage non supervisé

Dans l’apprentissage non supervisé, on donne des données sans aucune réponse associée.
L’IA doit trouver des structures ou groupes par elle-même.

Exemple :
On donne des photos de Pokémon sans labels indiquant leur type.
L’IA doit apprendre à créer ses propres catégories en détectant des similarités.


### Apprentissage auto-supervisé

L’apprentissage auto-supervisé est un entre-deux :
on fournit des données sans labels humains, mais l’IA génère elle-même les “réponses attendues” à partir du contenu.

Exemple :

“Le Pokémon le plus connu est ____.”
L’IA doit deviner Pikachu ou Dracaufeu.

Elle s’entraîne toute seule en se testant et en corrigeant ses erreurs.

### l'apprentisage automatique
L’apprentissage auto-supervisé (self-supervised learning, SSL) est basé sur l’apprentissage automatique. L’apprentissage automatique est un champ d’étude de l’intelligence artificielle : il permet aux ordinateurs d’analyser de grandes quantités de données pour y repérer des motifs ou des tendances complexes. Grâce à ce processus, l’IA peut faire des prédictions ou des classifications sur de nouvelles données. Cela permet d’automatiser des tâches complexes sans avoir à programmer manuellement l’IA pour chaque règle ou situation.
