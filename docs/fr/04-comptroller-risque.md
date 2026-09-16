# 4. Comptroller et risque de solvabilité

Le Comptroller décide si un compte peut entrer dans un marché, emprunter, transférer ou retirer sa garantie. Il agrège les valeurs des marchés et applique les facteurs de collatéral.

Les marchés ne sont pas tous équivalents. Le code distingue les actifs supportés, les plafonds, les facteurs de risque et les éventuels modes isolés afin de limiter les corrélations dangereuses.

La liquidation intervient lorsque la valeur ajustée des garanties ne couvre plus la dette. Le liquidateur rembourse une partie admissible et reçoit une saisie majorée par l’incentive prévu.

Les facettes du Diamond Comptroller séparent les politiques et les mises à jour d’état. Cette modularité augmente la surface de gouvernance : l’adresse de chaque facette et la procédure de remplacement comptent autant que l’algorithme.

Suite : [gouvernance et liquidation](05-gouvernance-liquidation.md).
