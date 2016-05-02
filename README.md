# Les Thés au Printemps

## TODO

* Click sur programme = ouverture du thème
* Ajouter la vidéo entre le hero et les thèmes

<hr>

## Lancer le serveur

    hugo server -t agency

## Déployer

    # Commiter tous les changements, puis:
    ./deploy.sh

## Exporter le programme en PDF

1. Décommenter les fonts en haut du fichier `themes/agency/static/css/agency.css`
2. Retirer les `<link>` d'import des fonts de `themes/agency/layouts/partials/head.html`
3. Retirer tous les partials sauf `{{partial "programme.html" . }}` dans èthemes/agency/layouts/index.html`
