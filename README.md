# StageManager (APPLICATION EN LIGNE DE COMMANDES)

StageManager est une application en ligne de commande développée dans le cadre d'un projet scolaire.  
Elle permet aux étudiants de postuler à des stages, aux maîtres de stage d'en créer et aux jurys d'attribuer des notes aux candidatures.  

[!] ATTENTION  

pour des raisons d'utilisation de "scanf", si on modifie le fichier "data_stage.txt" faut **pas mettre de retour à la ligne à la fin** car le programme croit qu'il reste des lignes à traiter et met du buffer dans les variables  

## Exemple de fichier valide :
5008 63
1
638
1061 03
0
0
2548 63
0
1
517
3040 04
1
517

J'ai tenté par plusieurs moyens de chercher comment contourner... il faudrait utiliser `fgets` mais ici on ne l'utilise pas.  

## À améliorer :  
- Remplacer `scanf` par `fgets` pour une gestion plus robuste des entrées  
- Ajouter une vérification automatique pour détecter les erreurs de format  
