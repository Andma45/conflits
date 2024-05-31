LOCAL

# conflits

Si tu n'as jamais entendu parler de conflits dans git, ne t'inquiète pas, tu auras à les gérer assez souvent en travaillant sur certains projets d'équipe.
Les conflits sont généralement inévitables lorsque tu travailles en équipe.
Dans cette quête, nous allons aborder ce que sont les conflits et comment nous pouvons les gérer.

# Revenir en arrière

Pour bien comprendre comment corriger une erreur, tu dois déjà savoir où se situe ton erreur. Pour rappel, tes fichiers passent par 3 "étapes" :

espace de travail (fichiers pas encore "addés")

Index (ou stage) (fichiers "addés" mais pas "commités")

HEAD (fichiers "commités")

Tu es dans le cas où tu sais que ton développement est buggé et tu as identifié un commit ou le projet fonctionnait bien.
Dans ce cas là, tu peux utiliser :

reset (hard ou soft)

revert

checkout
