## branches 

Commande            Ce qu’elle fait
git branch  Liste les branches. Une étoile *  montre celle où vous êtes
git switch -c ajout-section  Crée la branche ajout-section  et va dessus ( -c  : create)
git switch main  Va sur la branche main 
git merge ajout-section  Fusionne la branche ajout-section  dans la branche où vous
êtes
git branch -d ajout-section  Supprime la branche ajout-section , une fois qu’elle est
fusionnée
git log --oneline --graph --
all  Dessine l’historique avec toutes les branches