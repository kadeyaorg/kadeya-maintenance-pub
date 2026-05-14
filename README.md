# go-maintenance-pub

Dépôt **public** pour la distribution de **Go Maintenance** (binaires Windows et documentation HTML).

Le code source et le développement se font sur le dépôt privé `go-maintenance` au sein de l’organisation ; ce dépôt ne contient pas les sources Go, seulement ce qui est utile aux utilisateurs et aux machines.

## Releases

Les exécutables et archives pour mise à jour automatique sont publiés ici :

**[Releases — kadeyaorg/go-maintenance-pub](https://github.com/kadeyaorg/go-maintenance-pub/releases)**

## Documentation (GitHub Pages)

La documentation de l’interface (HTML) est dans le dossier [`docs/`](./docs/). Sommaire : [`docs/index.html`](./docs/index.html).

Pour publier le site :

1. **Settings → Pages**
2. **Build and deployment** : *Deploy from a branch*
3. Branche `main`, dossier **`/docs`**
4. URL du site : `https://kadeyaorg.github.io/go-maintenance-pub/`

La doc est mise à jour automatiquement lors de chaque release publiée depuis le dépôt source (workflow GitHub Actions).
