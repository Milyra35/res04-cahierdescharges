Arborescence :

- Accueil                       -> route: /
- Connexion                     -> route: /login
- Inscription                   -> route: /register
- Déconnexion                   -> route: /log-out
- Mon compte                    -> route: /(user-id)/my-account
- Modifier le compte            -> route: /(user-id)/my-account/edit
- Supprimer le compte           -> route: /(user-id)/my-account/delete
- Liste de parties              -> route: /(user-id)/my-games
- Progression du joueur         -> route: /(user-id)/(file-slug)/progress
- Tous les PNJ                  -> route: /villagers
- PNJ spécifique                -> route: /villagers/(villager-id)
- Politique de confidentialité  -> route: /confidentiality
- Mentions légales              -> route: /legal-notices
- Crédits                       -> route: /credits

Pages accessible pour l'utilisateur connexté 
- Accueil
- Connexion
- Inscription
- Tous les PNJ
- PNJ spécifique
- Politique de confidentialité  
- Mentions légales              
- Crédits                       

Pages accessibles pour l'utilisateur non connecté

- Accueil (avec tuto et partie pour upload le fichier seulement si l'utilisateur est connecté)
- Connexion
- Inscription
- Tous les PNJ
- PNJ spécifique
- Politique de confidentialité  
- Mentions légales              
- Crédits                       

Pages accessibles pour l'admin

- Admin                 -> route: /admin
- Liste utilisateurs    -> route: /admin/all-users
- Liste parties         -> route: /admin/all-saved-games
- Supprimer utilisateur -> route: /admin/(user-id)/delete
- Statistiques          -> route: /admin/statistics
- Modifier le compte    -> route: /admin/(admin-id)/edit