# Correction Élève 4

# Test1 
C’est très bien, c’est la bonne réponse. C’est une bonne initiative de faire des `console.log()` pour déboguer son code. Tu peux directement faire un return du calcul. Si tu n’es pas à l’aise avec ça pour le moment, ce n’est pas grave.
# Test2
Pareil, c’est bien. Petite subtilité, tu as utilisé un double égal `==`, un triple aurait été mieux `===` car il ne convertira pas ta variable en int si c’est une chaîne de caractère. En d’autres termes, il vérifiera en même temps que les deux variables sur lesquelles tu fais ta vérification sont aussi du même type. Idem que le test1 tu peux retourner directement la comparaison, cela retourne un boolean mais pareil si tu n’es pas à l’aise pour l’instant cela n’a pas d’incidence sur le code. Attention à l’indentation de tes deux dernières lignes.
# Test3
La fonction `lastIndexOf()` ne s’utilise pas comme ça. Elle permet de récupérer l’index, dans ta chaîne de caractères, où se situe la dernière fois qu’elle y trouve la valeur que tu lui passe en argument.
Exemple :
```
var string = “index.html”;
return string.lastIndexOf(‘.’); // Retournera 5
```
Je vois que tu as quand même essayé et c’est l’important. 

# Test 3, 4 et 5 :
Lorsque tu as des __hésitations__, des __incompréhensions__ ou encore des __difficultés__, n'hésite en aucun cas à nous envoyer un message, nous sommes là pour ça. On pourra te guider et t’orienter dans la bonne direction mais aussi approfondir ou revoir des notions vu en cours. Je t’encourage vraiment à suivre la correction en cours, à poser toutes les questions possibles et inimaginables et à étudier de nouveau les codes de correction. Si tu ne comprends toujours pas, ce qui n’est rien de grave, viens nous voir on est là pour répéter et surtout reformuler jusqu’à que tu comprennes. Ne reste pas dans ton coin, beaucoup de personnes peuvent t’aider y compris les autres étudiants. Je veillerai personnellement à ce que tu trouves et comprennent toutes les infos dont tu as besoin.
