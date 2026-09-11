# Limites et verification

Le pont Base–Solana depend de contrats, programmes, relayeurs, validateurs et racines publiees.
Une preuve d inclusion ne prouve pas a elle seule que le message a ete correctement autorise.
Les tokens enveloppes ajoutent des risques de mint, mapping distant et gouvernance de factory.
Les appels arbitraires et transferts avec appel elargissent fortement la surface de reentrance.
Ce parcours repose sur Bridge.sol, BridgeValidator.sol, MessageLib, SVMBridgeLib et les programmes Solana.
Aucune installation, compilation, transaction, preuve ou execution nouvelle n a ete effectuee.
Aucun statut de deploiement ou d audit n est deduit de ce guide.
Pour verifier, consulter les tests et rapports d audit correspondant exactement a la release utilisee.
