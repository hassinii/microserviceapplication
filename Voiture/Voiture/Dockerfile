# Utilisation d'une image de base avec Java
FROM openjdk:11-jre-slim

# Création du répertoire de travail
WORKDIR /app

# Copie du fichier JAR de votre application dans le conteneur
COPY target /app/app.jar

# Exposition du port sur lequel l'application Spring Boot écoute
EXPOSE 8081

# Commande pour démarrer l'application Spring Boot
CMD ["java", "-jar", "app.jar"]
