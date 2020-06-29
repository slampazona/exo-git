# Exos git.

Pour commencer, regarder la page `Insight > Network` permet de se faire une bonne idée de l'état actuel de l'espace de travail.

## Régler les conflit

### La terre le vent et le feu

Michel et Henriette, les deux DJs officiels de l'école, ont décidé de mettre la playlist à jour, mais chacun de leur côté, histoire d'aller plus vite.

Sauf que le partage des tâches n'a pas été bien fait. Résultat ils se sont tous les 2 attaqués à la playlist Funk...

:memo: TODO
- Commencer par fusionner la branche de Henriette sur master en local.
- Puis fusionner la branche de Michel de la même manière. Il va falloir régler les conflits !


<details>
<summary>Pour fusionner</summary>

:warning: Toujours s'assurer, avec `git status`, d'être placé sur la branche qui "reçoit" le code.

1 solution, 3 syntaxes : 
- La classique : 
  1. Rappatrier la branche distante en local `git fetch origin henriette:henriette`
  2. Récupérer les changements `git pull . henriette`
- La raccourcie :
  1. Récupérer directement les changements depuis la branche distante `git pull origin henriette`
- La raccourcie plus propre :
  1. Rappatrier la branche en local PUIS récupérer les changements `git merge origin/henriette`

</details>


