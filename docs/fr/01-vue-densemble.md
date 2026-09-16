# 1. Vue d’ensemble de Venus Protocol

Venus Protocol est un marché monétaire déployé sur BNB Chain. Les utilisateurs fournissent des actifs, reçoivent des vTokens et peuvent emprunter en déposant une garantie.

Le parcours part des contrats vToken, du Comptroller et des modèles de taux. Le vToken représente la position économique du fournisseur et comptabilise les intérêts sans conserver un solde séparé hors chaîne.

Le Comptroller centralise les contrôles de marché : actifs autorisés, facteur de collatéral, capacité d’emprunt et liquidation. Le code utilise un proxy Diamond dont les facettes séparent les responsabilités.

Le protocole comprend aussi XVS, la gouvernance et des mécanismes propres à Venus comme VAI. Cette documentation décrit les invariants lisibles dans le dépôt, pas un audit ni une garantie de déploiement.

Suite : [les marchés vToken](02-marches-vtoken.md).
