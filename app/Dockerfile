# Utilisation de l'image officielle Python
FROM python:3.13.0-alpine3.20

# Définition du répertoire de travail
WORKDIR /app

# Copie du script sum.py dans le conteneur
COPY sum.py /app/

# Commande pour garder le conteneur actif
CMD ["tail", "-f", "/dev/null"]
