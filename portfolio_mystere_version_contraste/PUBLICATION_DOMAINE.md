# Publication de mysterekongoli.fr

1. Vérifier la disponibilité de mysterekongoli.fr sur https://whois.afnic.fr/ puis l’acheter auprès du registrar choisi, à votre nom.
2. Sur GitHub, créer un dépôt public `portfolio` (ou un dépôt `VOTRE_IDENTIFIANT.github.io`). Décompresser et téléverser les fichiers du ZIP à la racine du dépôt. Vérifier les textes avant publication : toute information présente dans le dépôt public est visible.
3. GitHub : Settings > Pages > Build and deployment : Deploy from a branch, main, /(root), puis Save.
4. Dans GitHub Settings > Pages > Custom domain, saisir `mysterekongoli.fr`, Save. Vérifier le domaine GitHub si proposé.
5. Dans la zone DNS du registrar, définir ces quatre entrées A pour @ (supprimer les entrées A/AAAA incompatibles qui existent pour @) :
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
6. Pour www, créer un CNAME pointant vers `VOTRE_IDENTIFIANT.github.io` (en remplaçant l’identifiant), sans chemin /portfolio.
7. Attendre la propagation DNS (jusqu’à 24 heures), activer Enforce HTTPS dans Settings > Pages dès que l’option apparaît.
8. Vérifier les versions https://mysterekongoli.fr et https://www.mysterekongoli.fr avant de diffuser.

Documentation officielle : https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

**Attention :** la présence de CNAME dans ce dossier ne signifie PAS que le domaine est réservé ni que le site a été publié. L’utilisateur doit acheter le domaine et configurer son compte GitHub/DNS.
