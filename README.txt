TUFT & CREATE — SITE STATIQUE POUR GITHUB PAGES

FICHIERS
- index.html : structure de toutes les sections et fenêtres modales
- style.css : styles responsive, couleurs et illustrations CSS
- app.js : langues FR/EN/AR, catalogue modifiable, recherche, filtres, détails, panier, WhatsApp
- assets/products/ : déposer ici les photos séparées des produits

AVANT PUBLICATION
1. Ouvrir app.js et remplacer WHATSAPP_NUMBER = "212600000000" par le numéro WhatsApp réel, avec indicatif pays et chiffres uniquement. Exemple marocain : 2126XXXXXXXX (ne pas mettre +, espaces ou tirets).
2. Dans app.js, modifier le tableau PRODUCTS : nom, prix, description, catégorie, emoji et chemin de l'image.
3. Les prix du catalogue sont des exemples de démonstration : remplace-les par les prix réels.
4. Les photos produit sont facultatives au départ. Sans photo, une illustration emoji est affichée. Pour ajouter une photo, téléverser le fichier dans assets/products/ et garder le chemin correspondant dans app.js.

NOMS DE PHOTOS PRÉVUS (vous pouvez choisir d'autres noms, à condition de modifier app.js)
- assets/products/tufting-gun.jpg
- assets/products/trimmer.jpg
- assets/products/yarn.jpg
- assets/products/accessory-kit.jpg
- assets/products/poster.jpg
- assets/products/custom-design.jpg

PUBLIER SUR GITHUB
1. Ouvrir https://github.com/jant199/Jant-s-Magasin
2. Cliquer Add file > Upload files.
3. Téléverser index.html, style.css et app.js à la racine du dépôt (au même niveau que l'ancien index.html), puis Commit changes. Le nouvel index.html remplace l'ancien fichier.
4. Téléverser les photos dans le dossier assets/products/ : créez ce dossier via Add file > Create new file en saisissant assets/products/.gitkeep, validez, puis ouvrez assets/products et téléversez les photos. Vous pouvez supprimer .gitkeep après avoir ajouté des photos.
5. Pages doit publier depuis main / (root), ou avec votre configuration de déploiement existante qui publie la racine du dépôt.
6. Attendre le déploiement dans Actions, puis recharger https://jant199.github.io/Jant-s-Magasin/ avec Ctrl+F5 (Mac : Cmd+Shift+R).

PERSONNALISER LES PHOTOS
Les cartes utilisent des chemins indépendants. Les fichiers image ne sont pas inclus car vous avez indiqué que vous les téléverserez ensuite. Si une photo manque, le site affiche une icône de remplacement au lieu d'une image cassée.

LIMITES ACTUELLES
- Panier et catalogue fonctionnent dans le navigateur, mais le panier n'est pas synchronisé entre appareils et n'est pas sauvegardé après fermeture/rechargement.
- La commande est envoyée à WhatsApp; aucun paiement en ligne n'est traité.
- Les tarifs sont des exemples, pas des tarifs confirmés.
