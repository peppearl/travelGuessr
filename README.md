# travelGuessr

**EN**

travelGuessr is a web simulator coded in Symfony.
It let users find their next vacation, in France, Europe or in the world.

Users answers questions about their favorite things.
The simulator calculate the best destination thanks to the user's answers.
Then, the user has a few information about the place.

**FR**

travelGuessr est un simulateur codé en Symfony.
Cela permet aux utilisateurs de trouver la prochaine destination de leurs vacances, en France, en Europe ou dans le monde.

Les utilisateurs répondent à des questions sur leurs centres d'intérêts.
Le simulateur calcule alors la meilleure destination suivant les réponses de l'utilisateur.
L'utilisateur peut alors avoir accès à quelques informations concernant la destination en question.

## travelGuessr - Logique algorithmique

Il y aurait un système de points.
Chaque réponse vaut 1, 2, 3, etc. point(s).
Lorsque le questionnaire serait fini, il y aurait alors un calcul du nombre de points et suivant le résultat obtenu, ça sortirait une destination.

Exemple : si l'utilisateur à un total de 12 points, et que le profil montagne est entre 10 et 15 points, alors une destination en montagne
ressortirait (en prenant en compte la localisation (filtre entre France, europe hors France et international).
