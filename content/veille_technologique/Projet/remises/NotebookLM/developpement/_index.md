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

L’apprentissage auto-supervisé une forme d'apprentissage non supervisé :
il n'a pas besoin de données étiquetées par des humains, le modèle va créer ses propre "étiquettes" a partir des milliers de données qu'on lui donne. Par exemple on lui donne une phrase simple comme "je veux un verre de ____"  il devra apprendre a prédire le bon mot manquant. Donc on lui donne des données brutes qu'il devra completer avec ses propres étiquettes. Cependant, si on veut que notre IA soit plus précis(pour une niche spécifique) au niveau de sa reconnaissance on va ajouter une étape a l'entrainement: le fine-tuning. Le fine-tuning consiste a passer en mode supervision pour que notre IA soit meilleur pour notre niche.


Exemple :

“pikachu est un pokemon de type ___.”
L’IA doit deviner electrique.

Dans ce cas, si on veut que notre IA puisse identifier le type de chaque pokemon avec une image on devra surement passer en mode supervision pour qu'il comprenne bien la différence entre chaque pokémon.

### l'apprentisage automatique
L’apprentissage auto-supervisé (self-supervised learning, SSL) est basé sur l’apprentissage automatique. L’apprentissage automatique est un champ d’étude de l’intelligence artificielle : il permet aux ordinateurs d’analyser de grandes quantités de données pour y repérer des motifs ou des tendances complexes. Grâce à ce processus, l’IA peut faire des prédictions ou des classifications sur de nouvelles données. Cela permet d’automatiser des tâches complexes sans avoir à programmer manuellement l’IA pour chaque règle ou situation. De nos jours, l'apprentissage automatique est utilisé dans plusieurs domaines, par exemple: pour de la publicité, pour prédire la fluctuations des marchés boursiers ou encore pour la traduction de langue. Souvent, l'apprentissage automatique et l'intelligence artificielle vont être confondu, mais il faut comprendre que l'IA représente l'ensemble des approches qui visent a donner des capacités intellectuelles proche de celle des humains a des machines alors que l'apprentissage automatique est plus précis. C'est l'usage d'algorithmes et de données pour permettre aux machines de s'améliorer et exécuter des tâches sans êtres programmés pour ces taches précisemments.

### Retrieval-Augmented Generation(RAG)

Le RAG(génération à enrichissement contextuel) est une technique qui va permettre l'optimisation de réponses de modèle de langage en intelligence artificielle générative. Cette technique va permettre d'améliorer la qualité des réponses des LLM en exploitant des ressources sans avoir a se re-entrainer. Les chatbots qui utilisent RAG vont être plus précis que ceux qui ne l'utilisent pas. Par contre, la mise en oeuvre de la RAG demande des technologies telles que des bases de données vectorielles qui va coder des nouvelles données rapidement. Ces technologies sont nécessaires parce que les chatbots qui utilisent RAG vont seulement se fier à l'information à laquelle elle a accès donc si les informations ne sont plus récentes l'IA transmettre des informations qui ne sont plus valables.

### Les avantages

L'approche RAG présente plusieurs avantages:

-------  Les LLM fournissent des réponses précises et à jour: vu que les LLM utilisant RAG utilisent des sources externes et pas seulement ces données d'entrainements, il pourra fournir des réponses claires et à jour.

------- moins de chance de donner de fausses informations ou encore des informations imprécises : En se basant sur les données externes pertinentes, la RAG va réduire le risque de produire des informations fabriqués ou faussées.

------- Déployer la RAG est rentable : Déployer la RAG ne nécessite pas de personnalisation de modèle. Cela sauve énormément de temps, car les compagnies n'ont pas a ré-entrainer leur machines a chaque fois qu'il y a de nouvelles données.














### Source
[text](https://fr.wikipedia.org/wiki/Apprentissage_automatique)
[text](https://en.wikipedia.org/wiki/Machine_learning)
[text](https://www.ibm.com/think/topics/self-supervised-learning)
[text](https://www.coursera.org/fr-FR/articles/what-is-machine-learning)
[text](https://fr.wikipedia.org/wiki/G%C3%A9n%C3%A9ration_%C3%A0_enrichissement_contextuel)
[text](https://www.oracle.com/fr/artificial-intelligence/generative-ai/retrieval-augmented-generation-rag/)
[text](https://www.databricks.com/fr/glossary/retrieval-augmented-generation-rag)