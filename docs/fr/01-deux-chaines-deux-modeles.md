# Deux chaines, deux modeles

Base Bridge relie Base EVM a Solana et ne remplace pas le pont natif Ethereum vers Base.
Il transporte des tokens, des appels arbitraires et des messages entre deux modeles d execution differents.
Cote Base, des contrats Solidity enregistrent et executent les messages.
Cote Solana, des programmes manipulent comptes, PDA, instructions et mints SPL.
Chaque direction possede son propre cycle de preuve et ses propres identifiants.
La conversion d adresse EVM 20 octets vers pubkey Solana 32 octets doit etre explicite.
Une integration doit fixer chaine source, destination, token et destinataire avant signature.

Suite : [02 — Base vers Solana](02-base-vers-solana.md).
