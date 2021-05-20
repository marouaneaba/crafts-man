### Craft Man
Ce repositiers liste l'ensemble des bonnes pratiques, méthodes à utiliser dans un projet agile, fonctionne en itération:
## Le manifeste agile:
## User storie:
- Dans le contexte agilité un user-storie découper en deux partie DoR et DoD.
- Un développeur ne doit pas dépasser deux US à la fois.
- Avoir un US DoR faut le développeur passe par les trois prosessus : ANALYSE, 3 AMIGOS, CONCEPTION.
- Dans le proscessus de developpement l'US faut le découper en taches ils ont du feedback (SMART): Front, BackEnd, Bdd, ... .
## SOLID:
S:
O:
L:
D:
## Code smell:
Un ensembles des pratiques ou maniéres d'écrire du code, permettent de rendre le code façile à maintenir.
Sonar permet d'analyser notre code et de vérifier le code smile.
## Refactoring:
Améliorer la qualité du code sans impacter ou changer le comportement attendu de la méthode.

La meilleur façon de faire le refactoring c'est d'appliquer TDD qui permet d'avoir un feedback en continue, et travailler en itération pour simplifier le refectoring.

La meilleur façon de faire le refactoring pour du code legacy:
1. Découper la méthode  en petite morceaux.
2. TDD en utilisent **Tests par propriétés**.

## Boy Scout Rule:
## Clean code:
## Code Legacy:
## Documentation:
## Test automatisé (unitaire, fonctionnelle, integration):
La meilleur façon de faire des tests c'est de découper en trois partie:

**// Given** : la condition initiale, c'est de préparer les objets pour notre scénario de test.

**// WHEN** : l'action permet d'éxécuter le scénario.

**// THEN** : le résultat attendu (checker le résultat).

Cette pratique on l'utilise pour tous les types du test.
## Architecture: 
#### DDD:
#### Hexagonale et clean archi:
## Dette Technique:
## Egoless Programming:

## DevSecOps:
Qu'on dit **DevSecOps** on parle du construction du code, sécurité, et déploimenet.
L'objectif c'est d'automatiser notre flux de travail, pour accélérer le TTM, rendre une fonctionnalité disponible dans un envirenement le plus rapidement possible, avoir le feedback de notre réalisation fonctionnelle ou technique pour améliorer notre qualité.
Notre flux de travail et découper en deux trois partie:
1. CI: Intégration continue l'objectif c'est de checker la qualité du code réaliser par un développeur avant le merger avec notre code source, ce qui  permet d'améliorer la qualité de notre code. 

Les étapes permettent de checker la qualité de notre code: vérifier  le build projet, lancer les tests pré-deploy de notre application pour vérifier les impacts duu code réaliser ce qui permet d'éviter des régression, analyser la qualité du code avec des outils **Ex: sonar**, deploy notre artifact dans notre repository privé.
3. Séc: un ensemble des pratiques  et outils permettent d'analyser la sécuurité de notre amélioration.
4. CD : permet de faire des checks post-deploy et automatisé les taches pour deployer notre artifact dans un envirenement.

Récupération du l'artifact, lancer des checks post-deploy, automatisé les taches pour deploy dans un envirenement.



## Conclusion:
Une grand partie du temp et d'investissement doit étre fait sur l'architecture, code qualité, et tester notre application (TUs, Test-Intégration, Pair-Test). 

Un bon poduit c'est le résultat d'un travail collaboratif (3 Amigos, conception review, code review, pair-programming, mob-programming, pair-test, ...) tous les membres de l'équipe doivent être impliqués dans la construction et la réalisation.

<br/>
<br/>
<br/>
<br/>
Contact: Marouane ABKARIM - mar.abakarim@gmail.com
