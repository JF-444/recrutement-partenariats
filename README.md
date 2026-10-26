# Liv Services · Recrutement Chargé(e) de partenariats terrain

Site d'une seule page (index.html), sans build, prêt pour Netlify.

## Avant de publier
Copie dans le dossier `images/` les images du site community manager (projet d'Alexis) :
- `logo.png`
- `1.jpg`, `2.jpg`, `3.jpg`, `4.jpg`

## Publier sur Netlify
1. Crée un nouveau dépôt GitHub (ex. `recrutement-partenariats`) et dépose-y `index.html`, `README.md` et le dossier `images/`.
2. Sur netlify.com : Add new project → Import an existing project → GitHub → choisis le dépôt.
3. Build command : vide. Publish directory : la racine. Deploy.
4. Domain management → Add a domain → `recrutement.livservice.com`.
5. Chez ton hébergeur DNS : CNAME `recrutement` → `<ton-site>.netlify.app`.
