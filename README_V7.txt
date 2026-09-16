RAYANE ET MARIE DANSE — V7 WEB
================================

Cette version reprend la V6.5 et ajoute :
- connexion Supabase (email / mot de passe)
- données partagées dans PostgreSQL
- import de sauvegarde JSON V6.5
- synchronisation cloud
- actualisation manuelle
- bouton de déconnexion
- clôtures mensuelles stockées dans Supabase

CONFIGURATION
1. Ouvrir index.html ou le déployer sur un hébergeur statique.
2. Au premier lancement, renseigner le Project URL Supabase et la Publishable key.
3. Se connecter avec un compte créé dans Supabase Authentication.
4. Pour migrer les données existantes de V6.5, exporter un backup JSON depuis V6.5 puis l'importer dans l'écran de connexion de V7.

IMPORTANT
- Ne jamais utiliser la Secret key / sb_secret_ dans le navigateur.
- Le script SQL V7 doit déjà avoir été exécuté dans Supabase.
- Rayane et Marie doivent être membres de l'organisation.
- Cette V7 utilise la même interface métier que la V6.5.

DÉPLOIEMENT
Le dossier ne nécessite pas de serveur Node : index.html est une application web statique.
