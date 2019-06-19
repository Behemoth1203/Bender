VERSION CONTROL SYSTEM
Télecharger Git :
https://git-scm.com

S'inscrire sur le site de Github:
https://github.com/join
 
Lien du dossier
https://github.com/Behemoth1203/Bender

Git config --global user.email "adresse mail"
Git config --global user.name "name"

COMMIT:
Fonction "touch" permet de créer un fichier
Git status => permet de savoir si les documents sont sauvegardé ou non
Git add "file" => track le fichier dans le projet
Git commit => sauvegarde les changements
Git commit -m => permet de mettre un message lors du commit
Git commit -a => équivalent à un "add" et un commit
Git add .extension
Git add --all
Touch gitignore => pour ignorer des fichiers dans le dossier
Git log => affiche les derniers commit => -n nombre pour réduire le nombre
Git log --oneline
Git lop -p => lier à un fichier
Git diff => montre les modifications des fichiers depuis le dernier commit

Revenir en arrière:
Git checkout "id du commit" => reviens à se commit
Git checkout "id du commit" nom du fichier => fais revenir le fichier comme il était à ce moment
Git checkout master => revenir au présent
Git revert "id" => defait un commit
Git reset "id" --hard => ramène le projet, les fichiers à ce commit

Branches:
Git branch "nom" > créer la branche
Git checkout "nom" change de branche
Git merge "nom" => fusionne la branche "nom" dans la branche actuel
Git branch -d "nom" => supprime la branche "nom"
Git merge --no-ff "nom" => permet de fusionner en parallèle, et d'éviter les erreur (corriger les erreurs)
Git rebase "nom" : ajoute les commit d'où l'on est à la branche "nom"
Git rebase "nom" -i => intéractif

Historique
Git commit --amend => changer le message de commit, modifie le commit précèdent

Remisage:
Git stash => supprime les modifs et les stock.
Git stash save "texte"=>  créer un stash et le nomme
Git stash list => affiche la liste des docs en suspends
Git stash show stash@{x} => affiche le stash numéro x
Git stash show stash@{x} => affiche le stash numéro x
Git stash show stash@{x} -p => affiche les modifications enregistrer dans le stash x
Git stash aplly => remet en forme les sauvegarde
Git stash drop => vide les modifs sauvegarder
Git stash pop stash@{x} : apply + drop
Gti stash -u : inclus les nouveaux fichiers dans le stash






