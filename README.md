# network-calc

Calculateur de plages réseau IPv4 en une seule page HTML + JS, sans dépendance. Ouvrez `index.html` dans un navigateur.

## Fonctions

1. **Calcul d'une plage** : IP + masque (pointé, `/24` ou `24`, wildcard détecté) → réseau, broadcast, première et dernière IP, nombre d'hôtes, wildcard, classe, type d'adresse, vue binaire, sous-réseau précédent/suivant.
2. **Découpage** : à partir d'un réseau de départ, plan VLSM (liste de besoins nommés) ou sous-réseaux de taille égale (par nb d'hôtes ou nb de sous-réseaux), avec blocs libres restants et export vers Excel.
3. **Par classe et nb d'hôtes** : classe A/B/C + début d'adressage partiel → réseau et masque proposés, aligné dans le réseau de classe, liste des IP utilisables et broadcast.
4. **Outils** : appartenance d'une IP à un réseau, agrégation de routes, table de référence /0 à /32.
