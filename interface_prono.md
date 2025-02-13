
## Règles ##

Le but du jeu est de faire un programme python permettant de faire un pari
pour chaque match de la coupe du monde. Le programme doit donner pour chaque
math un score.

Le programme:
* doit être écrit en **python**
* ne doit pas écrire de fichier sur la machine à par lui-même (mise à jour OTA)
* peut utiliser la connexion réseau
* doit sortir un résultat avec un temps d'éxecution de moins de 3 min
* respecter le format de sortie
* sera exécuté une fois pour chaque match, un jour avant celui-ci


**En de non respect aucun point ne sera attribué.**

## Interface d'entrée ##

Le programme devrait être un programme python nommé `<trigramme>_prono.py`
, pour NSU cela donne par exemple: `NSU_prono.py`.

Le programme sera exécuté avec la commande suivante: `python <trigramme>_prono.py <pays1> <pays2>`.

> Le pays1 et pays2 sera parmis l'un des suivants (les deux étant différent):
> * Allemagne
> * Angleterre
> * Arabie_saoudite
> * Argentine
> * Belgique
> * Bresil
> * Cameroun
> * Canada
> * Croatie
> * Danemark
> * Equateur
> * Espagne
> * France
> * Ghana
> * Japon
> * Maroc
> * Pologne
> * Portugal
> * Coree
> * Iran
> * Pays_Bas
> * Qatar
> * Senegal
> * Serbie
> * Suisse
> * Tunisie
> * Uruguay

## Interface de sortie ##

Le programme doit sortie un résultat dans la sortie strandard au format texte.
Il devra être formaté de la manière suivante: `<score pays1> - <score pays2>`. Ce qui donne par exemple: `2 - 0`.

 Le score doit être un entier **entre 0 et 9**.

 ## Calcul des points ##

**Seul le score final du match compte**. En cas de tirs au but le score avant la
 session de tirs au but sera pris.
