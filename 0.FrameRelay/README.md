# INF1075

## Configuration:

- Tous IPs, Masques Sous-Réseaux et Passerelles
- Root Bridge doivent avoir la priorité la plus basse
- Créer tous les VLANs sur les Root Bridges
- Créer les noms de domaines VTP
- Faire attention de créer des "Trunk" pour les ports requis
- Faire attention de créer les deux commutateurs en redondance comme client
- Assigner les VLANs aux ports 1-15 sur les commutateurs clients
- Désactiver STP sur les ports 1-15 sur les commutateurs clients
- Protéger lest ports 1-15 contre les boucles
- Configurer la connectivitée inter-VLAN sur les routeurs
- Utiliser EIGRP comme protocole de routage sur AS100
- Utiliser Frame Relay comme protocole WAN 

# Topologie

![alt tag](https://github.com/setrar/INF1075/blob/master/0.FrameRelay/FrameRelay.png)
