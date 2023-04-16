

### Comment définir le nonce ?
*Le nonce est un nombre entier qui est incrémenté à chaque transaction envoyée depuis une adresse particulière. Il est utilisé pour s'assurer que chaque transaction a un identifiant unique, empêchant ainsi la duplication de transactions et le spamming du réseau. Enfin, il est stocké dans la signature de la transaction.*

### Que peut provoquer un saut de valeur de nonce ?
*Une transaction invalide ou des fonds insuffisants pour valider la transaction.*

### Deux transactions sont déclanchées avec le même nonce, (avec des valeurs et/ou recipient différents) que va-t-il se passer ?
*L'une d'elle sera validée et l'autre sera rejetée. La transaction validée est choisie comme étant la première à arriver dans un noeud validateur. Mais ce phénomène relève du hasard.*

### Comment définir le gas ?
*Le gas est une unité de mesure utilisée pour mesurer la quantité de travail qu'une transaction doit effectuer sur la blockchain. Chaque opération dans la blockchain a un coût en gaz qui dépend de sa complexité et de la quantité de ressources qu'elle nécessite pour être effectuée.*

### À quoi sert le gas ?
*Le gas sert à principalement à éviter les attaques DoS et les transactions demandant trop de ressources.*

### Comment peut-on accélérer une transaction ?
*Il est possible d'accélérer une transaction au augmentant le gasPrice.*

### Est-il possible d'effectuer une transaction avec un gasPrice nulle ?
*Oui, mais elle pourrait ne jamais être confirmée*

### Comment définir le recipient d'une transaction ?
Le récipient est une addresse stockée dans le champ *To*

### Quel est le nom de l'algorithme utilisé pour sécuriser la signature d'une transaction ?
ECDSA (Elliptic Curve Digital Signature Algorithm)

### Que génère la compilation d'un contrat solidity ?
-L'ABI (Application Binary Interface). C'est une interface qui définit la manière dont les différents contrats interagissent entre eux. L'ABI est utilisée pour communiquer avec les contrats et appeler les fonctions qui y sont définies.

-Bytecode : C'est le code qui sera exécuté sur la blockchain. Le bytecode est généré en prenant le code source Solidity et en le traduisant en langage de bas niveau qui peut être compris et exécuté par la machine virtuelle Ethereum.



*Sources : Mastering Ethereum: Building Smart Contracts and Dapps - A. Antonopoulos*

*N'hésitez pas à me corriger ou partager vos recommandations*
