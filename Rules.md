# Système Light - Règles

Système de jeu générique pour du JDR.

## Attributs

Les **Attributs** représentent les caractéristiques physiques et mentales du personnage. Ils sont représentés par une valeur de dé, pouvant être d4, d6, d8, d10 et d12, représentant le maximum humain.   
Un personnage surhumain peut posséder des attributs composés de plusieurs dés (exemple : d12+d6 en Corps).

### Liste d'Attributs
- **Chance** : Bonne étoile du personnage.
- **Charisme** : Capacité à impressionner par son apparence et son aura.
- **Corps** : Capacités physiques.
- **Esprit** : Capacités mentales.
- **Rapidité** : Temps de réaction.
- **Sens** : Vue, odorat, ouïe, goût et toucher.

### Test d'Attribut
Pour réaliser un Test d'Attribut on lance simplement le dé d'Attribut.

#### Difficultés
- **Normal** : 4
- **Complexe** : 6
- **Difficile** : 8
- **Surhumain**  : 10
- **Impossible** : 12+

### Résultat de 1
Lorsque le dé d'Attribut obtient un 1 comme résultat, cela n'indique pas automatiquement un échec. Cependant, même en cas de réussite, quelque chose se passe mal, à la discrétion du MJ (temps supplémentaire, outil détérioré, etc.).

---

## Compétences

Les **Compétences** représentent les connaissances et savoir-faire acquis par le personnage. Elles sont représentées par une valeur numérique allant de 0 à 10.

### Liste Compétences
- **Combat** : Mains nues et combat avec une arme de mêlée.
- **Connaissances** : Somme des savoirs divers et variés.
- **Expression** : Persuader, séduire et intimider.
- **Discrétion** : Être discret et passer inaperçu.
- **Mouvement** : Course, saut, escalade, etc.
- **Technique** : Conduite, sécurité, mécanique etc.
- **Tir** : Utilisation d'armes à feu et d'armes de jet.
- **Vigilance** : Être à l’affût et repérer les détails, fouille, investigation.

### Compétences Optionnelles
- **Informatique** : Utilisation des systèmes informatiques, piratage.
- **Occultisme** : Connaissances magiques, mythes et légendes.
- **Pilotage** : Conduite d'automobiles, pilotage d'avions et de vaisseaux.

### Test de Compétence
Pour réaliser un Test de Compétence on lance le dé d'Attribut et on ajoute au résultat le score de la Compétence associée.

#### Difficultés
- **Normal** : 8
- **Complexe** : 12
- **Difficile** : 16
- **Surhumain**  : 20
- **Impossible** : 24+

---

## Vie & Mental

### Vie
La **Vie** est une jauge représentant l'état physique d'un personnage. Les blessures et la fatigue diminuent la Vie du personnage.   
A 0 point de Vie, le personnage est considéré comme inconscient et reste vivant autant de minutes que son dé de Corps.  
*Exemple : Avec d10 en Corps, un personnage reste inconscient 10 minutes avant de mourir.*

#### Calcul
**Vie** = Corps + Rapidité.

### Mental
Le **Mental** représente l'état psychique du personnage. L'utilisation de la magie et les évènements traumatisants diminuent le Mental du personnage.   
A 0 point de Mental, le personnage est épuisé et peine à rester conscient, il subit un Désavantage à toutes ses actions.

#### Calcul
**Mental** = Esprit + Sens.

---

## Dés Bonus

Lors d'un test d'Attribut ou de Compétence, le joueur peut dépenser des points de Vie ou de Mental pour obtenir un ou plusieurs **Dés Bonus**, représenté par un d4 pour un jet d'Attribut et un d6 pour un test de Compétence.   
Les résultats des Dés Bonus sont ajoutés au total du jet d'Attribut ou de Compétence.   
Les Dés Bonus peuvent être déclarés avant ou après le jet, cependant le coût est doublé s'ils sont déclarés après le jet d'Attribut ou de Compétence.   
On ne peut ajouter des Dés Bonus qu'une seule fois par jet.

### Attribut
Le choix de dépenser des points de Vie ou de Mental dépend de l'Attribut utilisé. On dépense de la Vie pour les tests de Corps et de Rapidité et du Mental pour Esprit et Sens.   
Un test utilisant du Charisme peut utiliser des points de Vie ou de Mental.   
Il est impossible d'ajouter des Dés Bonus pour un test de Chance.

### Coût
Le premier dé coûte 1 point de Vie ou de Mental, le coût est cumulatif et augmente de +1 pour chaque dé supplémentaire.
- 1 Dé Bonus = 1 point de Vie ou de Mental.  
- 2 Dés Bonus = 3 points de Vie ou de Mental.  
- 3 Dés Bonus = 6 points de Vie ou de Mental.

Le maximum de Dés Bonus utilisable pour un jet donné est à la discrétion du MJ. Je recommande un maximum compris entre 3 et 5.

---

## Combat

Les combats sont organisés en Tour qui durent une poignée de secondes. Chaque Tour, un personnage dispose d'une Action et d'une Réaction.   
L'Action englobe toute action entreprise par le personnage pendant le tour, attaquer, sprinter, lancer un sort, esquiver, actionner un mécanisme, etc.   
La Réaction permet au personnage de réagir à une attaque pour tenter d'esquiver ou de parer l'assaut.

### Rapidité d'Action
Les personnages agissent en fonction de la Rapidité de l'action effectuée :
1. **Action Rapide** : Action réflexe, Attaque / Tir / Sort rapide, Technomancie.
2. **Action Normal** : Action simple, Attaque / Tir, Sorcellerie, Thaumaturgie.
3. **Action Lente** : Action complexe, Attaque / Tir visé, Chamanisme, Radiance.

### Réaction
Chaque personnage bénéficie d'une Réaction par tour pour se défendre avec un test de Parade ou d'Esquive.
- **Parade** : Corps + Combat (le bonus d'arme s'applique).
- **Esquive** : Corps | Rapidité + Combat | Mouvement | Vigilance.

### Jet d'Attaque
Au corps à corps, les personnages effectuent un test opposé de Corps + Combat.
A distance, le personnage qui tire doit réussir un test de Sens + Tir opposé à un jet de Rapidité + Combat | Mouvement | Vigilance de la cible.

### Dégâts
Les dégâts des armes sont représentés par un multiplicateur allant de 1 à 10 :
- 1 : Mains nues
- 2 : Armes légères (couteaux, armes contondantes, etc.)
- 3 : Armes (épée, lance, arc, pistolet, etc.)
- 4-5 : Armes de guerre (épée à deux mains, fusils, etc.)
- 6-8 : Armes lourdes (explosifs, fusil sniper, etc.)
- 8-10 : Armes magiques et non-conventionnelles
La Marge de Réussite multiplié par les dégâts de l'arme représente le nombre de points de Vie que perd la cible.

### Armure
L'Armure permet de résister aux dégâts et est représenté par une valeur entière qui est soustrait aux dégâts de l'arme.

### Exemple
_Un chevalier tente de frapper avec son épée un brigand, il dispose de d10 en Corps, 5 en Combat et possède une arme avec un bonus de maniement de +2.   
Il lance son d10 et obtient 6, son résultat total s'élève à 6 + 5 + 2 = 13.   
En face, le brigand essaie d'esquiver, il dispose de d8 en Rapidité et de 5 en Combat.   
Il lance son d8 et obtient 3, son résultat total s'élève à 3 + 5 = 8.   
Le chevalier dépasse son adversaire de 13 - 8 = 5, c'est la Marge de Réussite. Son épée à un score de Dégâts de 3 mais le brigand dispose d'une armure légère d'une valeur de 1.   
Les dégâts que subit le brigand son égaux à 5 x (3 - 1) = 10 points de Vie._

### Action Groupée
En cas de combat contre plusieurs adversaires, on effectue qu'un seul jet, additionnant les jets des deux groupes s'opposant pour déterminer qui l'emporte.

-- END --
