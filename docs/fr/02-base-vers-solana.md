# Base vers Solana

bridgeCall serialise une liste d instructions Solana apres validation de leur forme.
bridgeTransfer ajoute un transfert de token et peut enchainer des instructions distantes.
MessageStorageLib enregistre le payload avec emetteur, nonce et identite canonique.
Les messages sortants sont engages dans une structure authentifiee dont une racine est relayee.
Apres publication de la racine, l utilisateur fournit une preuve puis finalise sur Solana.
Le delai annonce dans le README reflete la mise a jour de racine, pas une finalite universelle.
La taille serialisee et les instructions autorisees sont bornees avant enregistrement.

Suite : [03 — Solana vers Base](03-solana-vers-base.md).
