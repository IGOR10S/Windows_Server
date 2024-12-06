# Che cos'è Anycast ?

Anycast è una tecnologia che fornisce più percorsi di routing a un gruppo di endpoint a cui viene assegnato lo stesso indirizzo IP. Ogni dispositivo del gruppo annuncia lo stesso indirizzo in una rete e i protocolli di routing vengono usati per scegliere quale sia la destinazione migliore.

Anycast consente di ridimensionare un servizio senza stato, ad esempio DNS o HTTP, posizionando più nodi dietro lo stesso indirizzo IP e usando il routing ECMP (Equal-Cost Multi-Path) per indirizzare il traffico tra questi nodi. Anycast è diverso da unicast, in cui ogni endpoint ha un proprio indirizzo IP separato.
