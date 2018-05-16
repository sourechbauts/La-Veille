# La Veille à BeCode 

Il est important de faire de la veille pour se tenir à jour des dernières avancées, des derniers langages de programmation, des derniers outils et tutoriels... bref pour être toujours à jour et se perfectionner.  

## Comment se déroule la veille
Chaque jour, l'un/e d'entre nous choisit un article ou un sujet lié au développement web qui a fait récemment une actualité, idéalement lié à ce que nous sommes en train de travailler à ce moment-là. Il peut s'agir par exemple d'une nouvelle techno, d'une propriété CSS inconnue ou récente, etc.

Elle consiste généralement en une présentation informelle animée par l'apprenant/e aux autres membres de la classe, éventuellement à l'aide du projecteur, suivi d'une séance de réactions. Elle a lieu à un moment précis de la journée (à Central, c'est 9h45). La veille en elle-même ne doit pas durer plus d'une quinzaine de minutes, et sa préparation ne doit pas dépasser au total une heure. 

C' est un moment de convivialité permettant à chacun(e) de s'exercer à la prise de parole en public, à partager une découverte / lecture / apprentissage... qui nous a personnellement intéressé et que nous avons envie de partager. Sans se prendre la tête mais en ayant toujours à coeur de bien faire. Vivre ensemble un moment de "gai savoir": cette lumière qui nous illumine au moment de comprendre quelque chose.

## A ton tour!
Afin de pouvoir s'organiser, chaque étudiant doit s'inscrire en clonant ce repo et en modifiant le fichier [agenda](./agenda.md) en suivant cette procédure:

Via le terminal :  

1. Crée un dossier sur ton disque local qui s'appellera (par exemple) "/home/user/becode/veille"   
`mkdir /home/user/becode/veille`  
1. va dedans: `cd /home/user/becode/veille`
1. Clone ce repo:   `git clone https://github.com/becodeorg/La-Veille.git`
1. Déplace toi dans le dossier 'La-Veille'  
1. Mets à jour ta copie locale avec les mises à jour des autres:   `git pull`  
1. Crée une nouvelle branche en lui donnant ton prénom et ton nom, afin de minimiser le risque de conflit:    `git branch {prenom-nom}` (remplace la partie entre `{}`)
1. Va sur ta branche:  
 `git checkout {prenom-nom}`   
1. Dis à Github qu'il doit créer ta branche également sur github.com et pas seulement en local: 
 `git push --set-upstream origin {prenom-nom}`  
1. Ouvre le fichier [agenda.md](./agenda.md) et ajoute la **date de passage**, **le sujet**, **ton prénom et ton nom** en bas de la liste (qui doit rester chronologique)  
1. Commit avec un message descriptif, par exemple:  
   - `git add .` (pour ajouter les fichiers modifiés sur le stage du prochain commit)  
   - `git commit -m "Ajout de ma prochaine veille sur les dégradés en CSS"` : le commit en lui-même   
1. Applique tes changements de ta branche vers la branche "master":   
   - `git checkout master`  
   - `git merge {prenom-nom}`  
1. Mets à jour le repository sur le serveur de Github:  `git push`


## Besoin d'un sujet?

Voici quelques suggestions:  
- les Gradients en CSS  
- utiliser des générateurs de code  
- ... 

## Suis les comptes twitter suivants:
- [Smashing Magazine](https://twitter.com/smashingmag)
- [Sara Soueidan](https://twitter.com/SaraSoueidan)
- [Stephanie Walter](https://twitter.com/WalterStephanie)
- [Christian Heilmann](https://twitter.com/codepo8)
- [Teddy](https://twitter.com/teddykishi)
- [Alexandre](https://twitter.com/pixeline)


## Sujets potentiels 

- jQuery
- Vue.js
- SVG
- Flexbox
- Les langages de programmation côté serveur 
- React.js
- Les bibliothèques JavaScript 
- Les serveurs Web 
- Les systèmes de gestion de contenu (CMS) 
- Les systèmes d'exploitation 
- JavaScript Content Delivery Network 
- Les widgets des réseaux sociaux 
- Les outils d'analyse du trafic 
- Responsive design
- Le scroll infini
- Le défilement parallaxe 
- Les vidéos dans le web
- Les micro-interactions pour améliorer l’UX 
- Le material design
- Robots.txt
- Trouver des images gratuites et libres de droits
- Sitemap
- Format d’image pour le web
- SASS
- Grille CSS/SASS
- JavaScript Scope and Closures
- Form Validation 
- ...

