# MapReduceProject

### 1.1  Exécution locale

##### 1- Que signifie Map input records ? Et Map output records ?
Map input records est le nombre de paires clé/valeur en entrée pour la fonction map.
Map output records est le nombre de paires paires clé/valeur en sortie pour la fonction map.

##### 2- Quel est le lien entre Map output records et Reduce input records ?
Reduce input groups est le nombre de clé/valeur en entrée de la fonction reduce.
Les valeurs Reduce input groups et Map output records sont égales car les sorties de Map sont les entrées de Reduce.

##### 3- Que signifie Reduce input groups ?
Reduce output records est le nombre de clés en sortie de la fonction Reduce.

### 1.2 Premier contact avec HDFS
