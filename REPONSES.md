# Réponses aux questions de réflexion

## Ex 2.1
`chmod 644` donne `rw-r--r--` : lecture/écriture pour le propriétaire, lecture seule pour le groupe et les autres. Le propriétaire ne peut pas l'exécuter car il n'a pas le bit `x`.

## Ex 2.2
Les guillemets autour de "$UTILISATION" évitent une erreur de syntaxe si la variable est vide ou contient des espaces : sans eux, le test devient `[ -ge 80 ]`.
