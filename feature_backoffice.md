Back-Office :

- Voir la liste des utilisateurs
- Supprimer des comptes utilisateurs si nécessaires
- Voir la liste des parties enregistrées par les utilisateurs
- Pouvoir chercher par nom un utilisateur et sa partie enregistrée
- Statistiques
    Afficher le nombre total d'utilisateurs enregistrés et donc d'afficher le nombre de parties enregistrées, afficher une moyenne du temps passé sur une partie
- Pouvoir modifier les accès du back-office si plusieurs admins sont amenés à arriver


Contraintes :

- Authentification sécurisée
    Le back-office doit être protégé par un système d'authentification sécurisé pour que seul l'admin puisse y accéder (gestion des rôles des utilisateurs)
- Protection des données
    Assurer la confidentialité des données stockées de l'utilisateur (MDP chiffré par exemple)
- Sécurité 
    Pas d'injection SQL, protéger XSS, protocole HTTPS
- Interface
    L'interface doit être simple et facile d'utilisation
- Sauvegarde des données
    Mettre en place un système de sauvegarde automatique des données
