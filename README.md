# Project5Star
Utilisation d'IOT dans les moyens de transport pour limité la propagation de virus et améliorer le confort voyageur.

## Description
Ce projet est un système qui transforme les moyens de transport ferroviaire à un système intelligent dans le but d’ameliorer le confort et securité du voyageur.

Le projet est composé de deux étapes :

- Smart Train : Installation du système de détecteurs dans les trains classique. Les types de détecteur sont : places occupé et libre, port du masque, temperature des voyageurs, aeration (temp, humidité, CO2), reconnaissance des toux et éternuement etc. 
- Smart Railway : Exploitation de ce système de détecteurs à partir d’une plateforme SI qui notifie le voyageur et entreprise de l’état de santé (Health Score) des compartiments, du train, et peut être généralisé sur l’état de santé de tout les lignes ferroviaire pendant une pandémie.


## Smart Train :
Pour rendre le Train ferroriaire classic intelligent, on va utilisé different detecteurs connecté a une machine central qui collecte en temps réel ces information, les traites et enfin affiche l'état global de chaque compartiment et voiture du train. L'état est simplifié en un rang entre 0 et 5. Le 0 signifie que le compartiment est risqué, et il y a une forte probabilité de contamination si un voyageur est infecté par le virus. Le 5 signifie que le compartiment est très bien monitoré, et il y a moins de risque qu'un voyageur infecté contamine les autres voyageur.

Pour mesuré l'état du compartiment dans la probabilité de la contamination, on va utilisé plusieur type de detecteurs :
Hygiene :
- Détecteurs de l'occupation des chaises de train.
- Détecteurs des masques des voyageurs
- Détecteurs des temperatures des voyageurs
- Détecteurs des toux et éternuements
- Détecteurs des movements humain
- etc

Confort :
- Détecteurs de la température
- Détecteurs de l'humidité
- Détecteurs de CO2
- Détecteurs de particule
- Détecteurs de bruit
- Détecteurs de vibration de train
- etc
