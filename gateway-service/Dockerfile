# Utilisez une image de base appropriée avec Java et Maven
FROM openjdk:8-jdk-alpine

# Définissez le répertoire de travail
WORKDIR /app/

# Copiez le JAR du microservice dans le conteneur
COPY target/gateway-service-0.0.1-SNAPSHOT.jar  gateway-service.jar

# Exposez le port sur lequel le microservice écoute
EXPOSE 8888

# Commande pour démarrer le microservice
CMD ["java", "-jar", "gateway-service.jar"]
