# Lab 01 - Switch avec SVI et deux PC


## 1. Objectif

Ce lab applique les étapes de configuration de base vues dans la formation Cisco Networking Academy, puis vérifie la connectivité entre deux PC et un switch.

1. Nom d'hôte
2. Mot de passe console
3. Mot de passe du mode privilégié
4. Chiffrement des mots de passe
5. Adresse IP du switch (SVI VLAN 1) et passerelle
6. Vérification de la configuration
7. Adressage des PC
8. Test de connectivité (ping)
9. Sauvegarde de la configuration

## 2. Topologie
<img width="1902" height="1132" alt="lab01-topologie" src="https://github.com/user-attachments/assets/5ddfdd8a-16d5-4a7b-852e-0394b95e9347" />

## 3. Plan d'adressage

Réseau utilisé : 192.168.10.0/24

| Équipement | Interface | Adresse IP | Masque | Passerelle |
|---|---|---|---|---|
| SW1 | VLAN 1 (SVI) | 192.168.10.253 | 255.255.255.0 | 192.168.10.254 |
| PC1 | Fa0 | 192.168.10.1 | 255.255.255.0 | 192.168.10.254 |
| PC2 | Fa0 | 192.168.10.2 | 255.255.255.0 | 192.168.10.254 |
