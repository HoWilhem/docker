# Utiliser l'image CLI de PHP
FROM php:8.2-cli

# Copier votre fichier
COPY microservice.php /app/index.php

# Exposer le port
EXPOSE 8000

# Lancer avec le serveur web interne PHP (plus léger)
CMD ["php", "-S", "0.0.0.0:8000", "/app/index.php"]