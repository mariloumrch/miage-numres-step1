# Q1 : Quels sont  les avantages de Gitpod ?
Réponse: c'est un environnement de dev préconfiguré donc pas d'installation en local + démarrage rapide dans le cloud 

# Q2 : Quels sont les défauts de Gitpod ?
Réponse: nécessite une connexion stable + c'est pas gratuit 

# Q3 : Quelle est la taille du fichier jar `api-springboot-0.0.1-SNAPSHOT.jar` ?
Réponse: 20672574 octets 

# Q4 : Qu'est ce que  la RSS ?
Réponse: C'est la quantité de mémoire physique occupé par un processus

# Q5 : Quelle est la valeur de la RSS utilisée par l'api SpringBoot (Préciser l'unité)?
Réponse:  ps -e -o pid,rss,args | grep api-springboot
  16740 178364 java -jar api-springboot/target/api-springboot-0.0.1-SNAPSHOT.jar
  19203  2432 grep api-springboot donc la valeur de la rss utilisé est : 178364 kilo-octets

# Q6 : Quel est le temps de démarrage l'api SpringBoot ?
Réponse: 4.566 s

# Q7 : Quelle est la taille du fichier jar `quarkus-run.jar` ?
Réponse: 662 octets 

# Q8 : Quelle est la valeur de la RSS utilisée par l'api quarkus en mode JVM (Préciser l'unité)?
Réponse: 100176 kilo octets 

# Q9 : Quel est le temps de démarrage l'api Quarkus en mode JVM ?
Réponse: 11.560 s

# Q10 : Quelle est la valeur de la RSS utilisée par l'api quarkus en mode natif (Préciser l'unité)?
Réponse: 39936 kilo‑octets
 
# Q11 : Quel est le temps de démarrage l'api Quarkus en mode natif ?
Réponse: 04:14 min