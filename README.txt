BookVault – Site avec panneau d'administration (Netlify CMS)

DÉPLOIEMENT
1) Mettez ce dossier dans un dépôt GitHub (branche 'main').
2) Sur Netlify, connectez le site à ce dépôt (New site from Git).
3) Dans Site Settings → Identity : activez Identity, autorisez les inscriptions,
   puis activez Git Gateway (Enable Git Gateway).
4) Allez sur https://votre-domaine/admin et connectez-vous pour modifier le contenu.
5) Le fichier data/books.json contient vos livres; vous pouvez les gérer depuis le panneau.

REMARQUES
- Le fichier _redirects force tout le trafic vers https://bookvault.one
- Les livres du catalogue et de la section 'En vedette' sont chargés depuis /data/books.json
- Les images uploadées via l'admin iront dans images/uploads (chemin /images/uploads/...)
