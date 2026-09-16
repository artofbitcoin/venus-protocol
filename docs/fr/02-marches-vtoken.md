# 2. Les marchés vToken

Chaque marché Venus associe un actif sous-jacent à un contrat vToken. Mint crée une position de fournisseur, redeem la réduit, tandis que borrow et repay modifient la dette.

Le solde d’un fournisseur est exprimé en vTokens. La valeur de conversion évolue avec l’index du marché, ce qui permet de représenter les intérêts par un taux de change plutôt que par une écriture périodique sur chaque compte.

Les variantes VBep20 et VBNB adaptent les entrées et sorties aux tokens BEP-20 et au BNB natif. Les contrôles de transfert empêchent qu’un vToken soit utilisé hors des règles du marché.

Le point critique est la cohérence entre cash, réserves, total emprunté et total de vTokens. Ces relations doivent rester compatibles avec les arrondis et les intérêts accumulés.

Suite : [les taux et l’indexation](03-taux-et-interets.md).
