# Utilisez une image de base appropriée avec Java et Maven
FROM openjdk:17-jdk-alpine

# Définissez le répertoire de travail
WORKDIR /app/

# Copiez le JAR du microservice dans le conteneur
COPY target/Tp1_Eureka_Server-0.0.1-SNAPSHOT.jar  eureka-server.jar

# Exposez le port sur lequel le microservice écoute
EXPOSE 8761

# Commande pour démarrer le microservice
CMD ["java", "-jar", "eureka-server.jar"]
