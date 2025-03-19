Dans nos données, nous avons 4 indices de performance:
- la distance totale parcourue lors de la course 'distance'
- le temps total de course 'elapsed_time'
- et la vitesse maximale atteinte
- la vitesse moyenne de la course 



Formatage: 
Je supprimes les colonnes superflues: 
SnowFall est toujours nulle, pareil pour photcount. 
PrecipitationSum et RainSum retournent la même valeur, on ne garde que RainSum.
Deux courses pour peu de km ont un temps de course > 9h, on suppose l'erreur ou l'oubli d'arrêter l'application 
et on supprime ces lignes.