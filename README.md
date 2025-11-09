# AD'PHONE Colmar

Site de la boutique AD'PHONE Colmar

URL en ligne : https://ad-phone.netlify.app/

Ce dépôt contient la version statique du site vitrine de la boutique. Le fichier principal est `index.html` et le design utilise Bootstrap 5 + Bootstrap Icons via CDN.

Contenu principal :

- `index.html` — page d'accueil complète avec :
  - Hero / accroche
  - Section "Nos services" (vente, réparation, accessoires, etc.)
  - Section "Catalogue & Prestations" (réparation toutes marques, réparation express, accessoires électroniques, produits cosmétiques, reconditionné, services annexes)
  - Horaires et informations pratiques
  - Contact & carte Google Maps intégrée
  - Footer avec année automatique
- `logo-adphone.png` (optionnel) — logo/illustration utilisé dans la page (si présent dans le dossier)

Points d'attention / actions possibles :

- Remplacer le lien `tel:` par le numéro de téléphone de la boutique dans la navbar et la section contact pour permettre l'appel direct depuis mobile.
- Compléter les liens WhatsApp et autres réseaux sociaux si vous souhaitez qu'ils pointent vers des comptes spécifiques.
- Ajouter des pages séparées pour chaque prestation si vous souhaitez du contenu détaillé (ex : `reparation.html`, `catalogue.html`).

Prévisualiser localement :

1. Ouvrir directement le fichier `index.html` en double-cliquant dans l'explorateur (méthode rapide sans serveur).

2. Ou lancer un petit serveur HTTP (recommandé si vous utilisez le Google Maps embed ou pour tester chemins relatifs) :

PowerShell (Windows) :

```powershell
# dans le dossier du projet
python -m http.server 8000
# puis ouvrir http://localhost:8000/ dans votre navigateur
```

Dépendances externes :

- Bootstrap 5 (CDN)
- Bootstrap Icons (CDN)

Licence / contact :

- Contact principal : ad.phone680@gmail.com (présent dans la page `index.html`).

---

Si vous voulez que j'ajoute :
- un numéro de téléphone cliquable dans la navbar / contact ;
- des icônes spécifiques sur les cartes du catalogue ;
- ou des pages détaillées pour chaque prestation — dites-moi ce que vous préférez et je l'ajoute.
