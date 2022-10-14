#TP de CI/CD avec Angular

Nous pouvons découper ce travail en 2 étapes :

1)Lorsque le développeur finit de développer une fonctionnalité sur la branche secondaire "dev", il peut effectuer un "Pull Request" sur la branche principale "main" du projet. Lorsque la "Pull Request" est acceptée, le "CI_pipeline" se lance automatiquement afin d'analyser le code de la pull request (question 4)).

2)Une fois l'analyse effectuée, il ne reste plus qu'à "merger" la branche "dev" sur "main". Ainsi, lorsque l'action est faite, le "CD_pipeline" va se lancer afin de refaire quelques tests et déployer le site codé en "Angular" sur "Github Pages". Pour ceci, notre pipeline de déploiement crée une troisième branche automatiquement sur le repo, nommée "gh-pages", responsable de la mise en ligne du site (question 5)).

