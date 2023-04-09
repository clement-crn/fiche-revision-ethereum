*N'hésitez pas à me corriger ou partager vos recommandations 

### Comment définir le nonce ?
Le nonce est un nombre entier qui est incrémenté à chaque transaction envoyée depuis une adresse particulière. Il est utilisé pour s'assurer que chaque transaction a un identifiant unique, empêchant ainsi la duplication de transactions et le spamming du réseau. Enfin, il est stocké dans la signature de la transaction.

### Que peut provoquer un saut de valeur de nonce ?
Une transaction invalide ou des fonds insuffisants pour valider la transaction.

### Deux transactions sont déclanchées avec le même nonce, (avec des valeurs ou recipient différents) que va-t-il se passer ?
L'une d'elle sera validée et l'autre sera rejetée. La transaction validée est choisie comme étant la première à arriver dans un noeud validateur. Mais ce phénomène relève du hasard.


