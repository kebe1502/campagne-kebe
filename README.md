# Héberger ce site sur GitHub Pages

Ce dépôt contient une page de campagne (HTML/CSS/JS). Suivez les instructions ci-dessous pour la publier sur GitHub Pages.

Étapes rapides (recommandées) :

1. Copier `campagne-kebe (1).html` en `index.html` (déjà fait localement par ce script).
2. Créer un dépôt GitHub et ajouter le remote `origin`.
3. Pousser la branche `main` puis activer GitHub Pages depuis les paramètres du dépôt (Source: `main` / root).

Commandes utiles (remplacez `USERNAME` et `REPO`):

```bash
# depuis ce dossier
git remote add origin https://github.com/USERNAME/REPO.git
git branch -M main
git push -u origin main
```

Alternatives automatisées (avec GitHub CLI `gh`):

```bash
gh repo create REPO --public --source=. --remote=origin --push
# puis dans l'interface GitHub → Settings → Pages, choisissez Source: `main` / root
```

Notes:
- Si vous préférez servir depuis `docs/`, déplacez `index.html` dans `docs/` et configurez Pages sur `main` / `docs/`.
- Si vous souhaitez que je crée le dépôt distant et pousse pour vous, autorisez-moi (ou fournissez la commande `gh repo create`).

Contactez-moi si vous voulez que j'automatise la création du dépôt distant et la configuration Pages.
# Com-Peda-AEERTM