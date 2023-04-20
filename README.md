**Projet Distance d'arret**

Membres du projet:
- BENZIDANE El Yazid
- MIM Akram
- MARZOUGUI Wassim

**Descriptif du projet:**

Notre sujet de recherche concerne l'étude de l'évolution de la vitesse en fonction du temps lors du
freinage d'un véhicule. Cette thématique revêt un intérêt majeur dans de nombreux domaines,
notamment scientifique, technique, commercial, mais aussi sociétal.
En effet, comprendre comment la vitesse d'un véhicule varie pendant le freinage permet de mieux
appréhender les mécanismes physiques à l'œuvre dans ce processus. Cela peut ensuite conduire à
l'amélioration de la sécurité routière en développant des systèmes de freinage plus performants.
D'un point de vue commercial, les constructeurs automobiles ont tout intérêt à concevoir des
voitures dotées d'un système de freinage efficace pour offrir un niveau de sécurité maximal à leurs
clients. De même, les professionnels de l'assurance peuvent utiliser ces données pour évaluer les
risques liés aux accidents de la route.
Enfin, d'un point de vue sociétal, la compréhension des mécanismes impliqués dans le freinage
permet de sensibiliser les conducteurs à l'importance du respect des distances de sécurité et de la
vitesse limite sur les routes. Cela contribue à améliorer la sécurité des usagers de la route et à
réduire le nombre d'accidents de la circulation.

**Problématique:**

Comment notre modèle dynamique peut-il aider à mieux comprendre et optimiser le processus de freinage en analysant l'évolution de la vitesse et les facteurs influençant la décélération d'un véhicule en mouvement ?


Semaine 10 mars:
- Définiton de la problématique
- recherche documentaire
- recherche de modèles

Semaine 17 Mars:

Nous avons hésité entre plusieurs modèles. Nous avons défini plus précisemment le caractère dynamique de notre projet grace aux recherches documentaires.

Semaine 24 Mars:

Nous avons fais des recherches sur les formules de physique qui pourraient nous aider. Nous avons trouvé la formule v=v0*at.

Semaine 31 Mars:

Nous avons décidé des paramètres à prendre en compte. certains paramètres sont négligeables ou trop compliqués à intégrer au modèle comme les différents systèmes de freinage, les systèmes d'abs, l'aérodynamise des véhicules ou encore la densité de l'air. 

Semaine 7 Avril:

Nous avons commencé à effectuer des tests sur python avec des graphiques en utilisant matplotlib afin de visualiser l'avancée de notre travail. Nous avons vu qu'il etait possible d'utiliser la méthode d'Euler afin de calculer la vitesse, c'est une méthode qui utilise l'équation diférentielle suivante: 
dv/dt = -µ * g - (0.5 * ρ * Cd * A * v²) / m qu'il faut résoudre afin d'avoir la vitesse. Cette méthode à été écartée car elle prend en compte la resistance de l'air qui dépend du modèle de véhicule, de la densité de l'air, de la surface frontale, etc...

Semaine 14 Avril:

Nous avons finalisé le code python. Nous avons remarqué que la masse s'annule dans les calculs car plus la masse du véhicule est importante, plus le système de freinage est performant donc adapté.

Semaine 21 Avril:

Nous avons finalisé la présentation et réparti les roles entre les membres du groupe. nous avons effectué les derniers tests et les ecemples de graphique afin de les montrer.

**Description du modèle:**

<img width="620" alt="Formule1" src="https://user-images.githubusercontent.com/125645155/233501182-cc737c81-e370-4dd5-ac4e-429f476284fd.png">
