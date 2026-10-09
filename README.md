# Mariam Barham — site vitrine et boutique

Site front-end en HTML, Tailwind CSS et JavaScript, préparé pour un dépôt GitHub et un déploiement Vercel.

## Démarrer en local

Ouvrir `index.html` dans un navigateur. Pour un test plus proche d'un hébergement web, utiliser l'extension **Live Server** de Visual Studio Code.

## Structure

- `index.html` : structure et contenu de la page
- `css/style.css` : identité visuelle et responsive
- `js/app.js` : catalogue, catégories, favoris, panier et préparation WhatsApp
- `admin.html` : interface de gestion du catalogue (ajout, modification, suppression, import/export JSON)
- `js/admin.js` et `css/admin.css` : logique et styles de l’administration
- `assets/logo-mariam-barham.png` : logo utilisé par le site

## Limites de l’administration actuelle

La page `admin.html` permet de modifier le catalogue dans le navigateur courant et d’exporter/importer une sauvegarde JSON. Le stockage est local (`localStorage`) : les modifications ne sont pas partagées avec les autres visiteurs ou appareils et peuvent être effacées par le navigateur. Cette page n’a pas de connexion sécurisée ; ne considérez pas son lien comme une protection. Pour administrer la boutique une fois publiée, il faudra connecter une base de données et un système d’authentification avec contrôle des accès (par exemple Supabase).

## Avant la mise en ligne commerciale

1. Remplacer les produits de démonstration par le catalogue réel et les photos fournies.
2. Confirmer les prix au détail et les règles de prix en gros.
3. Confirmer le numéro WhatsApp de commande et les modalités de livraison.
4. Vérifier toutes les coordonnées et les textes commerciaux.

Les prix actuels sont des exemples de démonstration, et la commande WhatsApp demande explicitement confirmation des prix et disponibilités. Aucun paiement en ligne n'est traité par ce site.
