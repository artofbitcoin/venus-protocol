# 3. Taux, utilisation et intérêts

Venus calcule les intérêts à partir de l’utilisation d’un marché, c’est-à-dire du rapport entre la dette et les liquidités disponibles. Le modèle JumpRate applique une pente avant puis après un seuil.

L’index de marché progresse au fil du temps. Il sert à convertir les balances de vTokens en valeur sous-jacente et à faire évoluer la dette sans parcourir tous les comptes.

Les taux fournisseur et emprunteur ne sont pas identiques : la différence alimente les réserves du protocole. La réserve est un amortisseur mais ne supprime pas le risque de perte.

La précision fixe-point, la durée écoulée et le bloc de référence sont des éléments de sécurité. Une lecture correcte doit suivre les fonctions d’accrual jusque dans les bibliothèques mathématiques.

Suite : [le Comptroller et le risque](04-comptroller-risque.md).
