# Sonolix — état des services

Miroir public de la page d'état de Sonolix, hébergé **hors de l'infrastructure**
pour une seule raison : une page de statut doit rester lisible quand la
plateforme qu'elle décrit ne répond plus.

- La page interroge en direct `https://ris.sonolix.fr/statut/etat.json`.
- Si la plateforme est muette, elle affiche l'instantané `etat.json` déposé ici,
  en disant clairement qu'il s'agit du dernier état connu.

Ce dépôt ne contient **aucune donnée de santé, aucune donnée patient et aucun nom
de cabinet** : uniquement des voyants de service. Toute la mesure et toutes les
données restent sur la VM HDS.
