---
clavier: true
gestionGrosMots: true
rechercheContenu: false
---

# Outils d'aide en Sciences

Je suis un chatbot pour vous aider à créer ou analyser un document en sciences.

1. [Je recherche une méthode précise](A faire)
2. [Je cherche à comprendre la consigne](Consigne)


## A Faire

Que faut-il faire ?

  1.[lire un graphique](lire un graphgique)
  2.[Réaliser un graphique](réaliser un graphique)
  3.[Construire un tableau](construire un tableau)
  4.[faire un dessin](faire un dessin)
  5.[faire un schéma fonctionnel](faire un schéma fonctionnel)
  6.[Analyser une expérience](analyser une expérience)
  7.[Comparer des données]
  8.[Analyser des documents]
  9.[Constuire un modèle]

## Consigne 

Je ne comprends pas ce qu'il faut faire dans la consigne

   1. Construire
   2. Analyser
   3. Expliquer
   4. Justifier
   5. Calculer
   6. Indiquer
   7. Modéliser

## Rédaction réponse

Chaque titre de niveau 2 définit une réponse possible du chatbot.
On écrit cette **réponse** en _Markdown_.

On peut utiliser les emojis :+1:, insérer des [liens](https://eyssette.forge.aeif.fr/chatMD/), ou des images (et même préciser la dimension) :

![descriptif de l'image](https://picsum.photos/100)

![descriptif de l'image](https://picsum.photos/100 =300x150) 
<!--commentaire invisible : j'ai précisé ci-dessus la dimension de l'image avec l'indication =300x150 -->

- on peut faire des listes
- mais il ne faut pas que la liste commence immédiatement après le titre 2
- car sinon elle sera considérée comme une liste de mots déclencheurs pour la réponse

## Déclenchement
- déclenchement
- déclenche

Une réponse du chatbot apparaît :
- Si un lien vers cette réponse a été définie dans une option à la fin d'une réponse, pour guider l'utilisateur
- Ou bien si l'utilisateur écrit une réponse qui contient les mots ou expression clés. Le chatbot fait d'abord une recherche d'identité stricte, puis de simples similarités afin de choisir la réponse la plus pertinente

1. [Comment on guide l'utilisateur avec des options à la fin d'une réponse ?](Guider l'utilisateur)

## Guider l'utilisateur
- options
- guider

On peut guider l'utilisateur en laissant à la fin de la réponse (et seulement à la fin) des options.
On fait une liste ordonnée (un chifre puis un point) et on écrit un lien dans chaque item avec l'intitulé de l'option et le titre de l'option, qui doit correspondre à un des titres de niveau 2.
Si on veut permettre le retour au message initial, on laisse le lien vide.

1. [Intitulé option 1](option 1)
2. [Intitulé option 2](option 2)
3. [Retour au message initial]()

## option 1
Voici la première option.

## option 2
Voici la deuxième option



