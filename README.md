# Le Hangar du Pêcheur – Site web

Site vitrine du restaurant Le Hangar du Pêcheur (Le Conquet, Finistère).
Le site existe en deux versions, chacune dans un seul fichier (les photos y sont intégrées, il n'y a pas de dossier d'images) :

- `index.html` : version ordinateur et tablette ;
- `mobile.html` : version téléphone.

Le visiteur est dirigé automatiquement vers la bonne version selon son appareil. L'adresse à partager est toujours celle de `index.html`.

## Mettre le site en ligne avec GitHub Pages

1. Créez un compte sur [github.com](https://github.com) si besoin.
2. Cliquez sur **New repository**, donnez-lui un nom (par exemple `hangar-du-pecheur`) et laissez-le en **Public**.
3. Sur la page du dépôt, cliquez sur **uploading an existing file**, glissez-déposez `index.html` **et** `mobile.html`, puis validez avec **Commit changes**.
4. Allez dans **Settings → Pages**. Sous **Build and deployment**, choisissez **Deploy from a branch**, la branche `main` et le dossier `/ (root)`, puis **Save**.
5. Après une à deux minutes, le site est disponible à l'adresse `https://VOTRE-NOM.github.io/hangar-du-pecheur/`.

## À compléter avant la mise en ligne

Dans `index.html` **et** `mobile.html`, remplacez les textes entre crochets :

- `[Adresse du restaurant]`
- `[horaires]` (pour chaque jour)
- `[Numéro de téléphone]` (affiché et dans le lien `tel:`)

## Formulaire de réservation

Le formulaire est un exemple : il n'envoie rien pour le moment, car GitHub Pages ne gère pas l'envoi d'e-mails. On peut le remplacer par un lien `tel:` et un lien `mailto:`, ou le relier à un service gratuit comme Formspree.
