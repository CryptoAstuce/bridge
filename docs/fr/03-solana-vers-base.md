# Solana vers Base

Le programme Solana cree un message sortant identifie par un PDA et un nonce.
Un relais transmet ensuite le message a Base avec les signatures et metadonnees attendues.
BridgeValidator pre-valide les messages pendant la phase Stage 0 du protocole.
Le contrat suit les messages deja executes afin d empecher un rejeu.
L etat doit etre marque avant les appels externes pour fermer la reentrance inter-chaine.
Le gas limite et le destinataire EVM font partie des donnees critiques du message.
Un echec d execution ne doit pas rendre ambigu le statut de consommation du message.

Suite : [04 — Validation et gouvernance](04-validation-et-gouvernance.md).
