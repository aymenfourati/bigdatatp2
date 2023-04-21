## Compte rendu du TP n° 2 : Traitement par Lot et Streaming avec Spark

### Réalisé par Fourati Aymen & Helali Eya



#### Objectifs du TP : 
Utilisation de Spark pour réaliser des traitements par lot et des traitements en streaming.


# Préparation de l'environement

``` 
Lancement des trois contenaires :
Hadoop Master 
Hadoop slave 1 
Hadoop slave 2 
```

![image](./1.jpg)
``` 
Lancer ensuite les démons yarn et hdfs
```
![image](./2.jpg)
![image](./3.jpg)
# Test de Spark avec Spark-Shell

# spark-shell

![image](./4.jpg)
``` 
output : 
```
![image](./5.jpg)
## Spark Batch en Java

``` 
Préparation de l'environnement et Code
```
![image](./6.jpg)
### Test du code en local

![image](./7.jpg)

### Lancement du code sur le cluster
``` 
Copie du fichier target/wordcount-1.jar vers hadoop-master:/root
```
``` 
Output : 
```

![image](./8.jpg)
## Spark Streaming
``` 
Préparation de l'environnement et Code
```
![image](./9.jpg)
```
Test du code en Local
```
![image](./10.jpg)