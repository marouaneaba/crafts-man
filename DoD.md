## DOD Type:
- DOD techinque de la PR.
- DOD représente un travail/US terminé.



## Chaque team doit avoir un DoD réprésent un ensemble des critiers stricts, réspécter par l'ensemble des équipe travaillent dans le projet ou sur le produit:

- Les développeurs responsables de la qualité du code livrer, le code livrer doit étre accompagner avec des TUs,et TIntégration/BDD, des tests qui couvre tous les cas utilisations du code impléménter.
- Analyser les impacts: le code implémenter impacts sur d'autre coté du projet ou fonctionnalité (modification méthode public, transverses, communes, ou impact d'autre fonctionnalité, ... ), et tous les TUs, test intégration/BDD en local sont ok (vert).
- Le code impacté touche-t-il un périmètre autre que celui demandé par ton US / TS / BugFix (modification de fonction transverses, communes, etc...) ?

- Le code lisible et compréhensible utilisé un langage métier (omniprésent), si n'est pas le cas faut faire une documentation technique du code.
- Fonctionnnelle attendu et critiére d'acceptance sont ils OK 
Lancer l’application en local et vérifier manuellement si le fonctionnement est en accord avec la demande du product owner
	s’assurer que la fonctionnalité implémentée réponde au besoin du Product Owner (pair-test). (déploiment par branche)-(envirenement par équipe).
- Analyser la qualité du code avec SonarLint.
- Passage de la revew de code, créer une PR permet à l'équipe de développement de communiquer, échanger sur le code, et de mettre des commentaire, une PR contient le feedback de l'équipe de développement, CI, et l'esemble du crittiées stricts de la DoD.

- Re-Lire le code avant de le push:qualité technique, qualité fonctionnelle (re-Lire US, re-Lire la conception technique, re-Lire ton brouillon, re-Lire critére d'acceptance, re-Lire les régles métier, voir la couverture du code, regarde sonar pour code smile, couverture du code, vérifier les impacts du code: modification méthode déja utiliser, ... ).

- Re-Lire l'US et vérifier que tous ce qui est montioné dans l'US correspand ce qui est construit par plus ni moins ( ce qui est developpé == ce qui se trouve dans l'US).
- Le pair test est fait en local.
- Est ce que ta réalisation est passé par une conception (POO).
- Est ce que une méthode public était modifier, si oui est ce que les impacts de la méthode ils sont analysé (find usage).

## Conclusion:
Un développeur est responsable de la qualité technique et métier du produit, doit connaitre les bonnes pratique et méthode pour faire des livraisons de la qualité.

Qualité fontionnelle: Attendu par le métier et critiére d'acceptance.
Qualité technique: Review code, CI, TUs, impact (non régression).

Chaque équipe doit mettre une définition de terminer qui est explicite à l'équipe scrum, chaque list de DoD c'est une template initiale et a améliorer avec le temp par l'amélioratoin continue (Rétro) pour l'adapter à l'équipe.
