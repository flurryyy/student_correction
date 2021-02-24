# Correction Élève 1
## Test1
Bien, retourner directement le calcul fonctionne aussi.
## Test2
Très bien ! Petit tips de refactoring : comme le test1, tu peux retourner directement `int % 2 === 0`, cela retournera directement un boolean
## Test3
Encore très bien ! Tu peux retourner directement `rep[rep.length - 1]`. Ce n’est pas grand chose mais ça peut éviter de déclarer une variable intermédiaire et permettre une meilleure optimisation.
## Test4
Bien ! On aurait pu rajouter une vérification de type sur chaque valeur du tableau (dans ta boucle for avant de vérifier la taille) pour checker si le contenu est bien une string.
## Test5
Sur cet exercice, boucler sur le tableau est la bonne solution mais le fait que certains soit des objets t’as posé problème. Ce n’est pas grave tu as les capacités de réussir cet exercice. Dans le test4 on aurait pu vérifier le type de chaque valeur du tableau, ici c’est pareil on pouvait vérifier si le type était un nombre ou un objet. Si c’est un nombre tu peux l'addition à ton compteur `result` sinon si c’est un objet tu peux refaire appel à ta propre fonction `sum()` et addition le résultat avec `result`. En vérifiant seulement que ce n’était pas un nombre tu as exclu les objets. 
