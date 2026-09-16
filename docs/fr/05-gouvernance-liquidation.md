# 5. Gouvernance, réserves et liquidation

XVS donne accès à la gouvernance, tandis que le Timelock impose un délai entre une décision et son effet. Le parcours de lecture doit relier le Governor, le coffre de vote et les contrats administrés.

Les liquidations protègent la solvabilité globale, mais leur exécution dépend du prix, de la liquidité disponible et des limites de close factor. Un marché peut donc rester techniquement liquidable sans garantir une sortie sans perte.

Venus conserve des réserves prélevées sur les intérêts. Les administrateurs peuvent ajuster certains paramètres, ce qui rend la séparation entre rôle opérationnel, gouvernance et urgence essentielle.

VAI ajoute une couche de stablecoin et de dette collatéralisée. Il faut distinguer son mécanisme de mint et de remboursement des marchés de prêt ordinaires.

Dernier chapitre de ce parcours : cette synthèse couvre les invariants lisibles dans le code et renvoie aux tests du dépôt pour une vérification indépendante. Aucune installation, compilation ou exécution n’a été réalisée ici.
