# Validation et gouvernance

BridgeValidator combine signatures autorisees et seuils configurables pour accepter un message.
Les signataires, partenaires et seuils constituent une racine de confiance hors consensus des deux chaines.
Le contrat borne le nombre et le seuil des validateurs partenaires.
Les guardians peuvent suspendre le pont mais leurs pouvoirs doivent rester separes des mises a jour ordinaires.
Les initializers sont des frontieres critiques pour owner, guardians et adresses de contrats immuables.
La feuille de route indique que CrossL2Inbox pourrait remplacer ce validateur Stage 0.
Une application doit afficher clairement ce modele de confiance et sa version de deploiement.

Suite : [05 — Limites et verification](05-limites-et-verification.md).
