# Utilisez une image de base appropriée avec Java et Maven
FROM openjdk:8-jdk-alpine

# Définissez le répertoire de travail
WORKDIR /app/

# Copiez le JAR du microservice dans le conteneur
COPY target/Voiture-0.0.1-SNAPSHOT.jar  cars-service.jar

# Exposez le port sur lequel le microservice écoute
EXPOSE 8089

# Commande pour démarrer le microservice
CMD ["java", "-jar", "cars-service.jar"]
