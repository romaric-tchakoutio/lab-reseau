# lab-reseau – Romaric Tchakoutio

Carnet de laboratoires réseau réalisés pendant ma préparation à la certification **Cisco CCNA 200-301** (parcours Cisco Networking Academy), puis au **CCNP Enterprise**.

Chaque labo contient : l'objectif, la topologie et le plan d'adressage, les commandes utilisées, les vérifications (`show`, `ping`), ce que j'ai appris et les erreurs rencontrées.

## Progression

| # | Labo | Sujets | Statut |
|---|---|---|---|
| 01 | Switch avec SVI et deux PC : connectivité de bout en bout | hostname, mots de passe console/enable, chiffrement, bannière, SVI VLAN 1, passerelle, adressage PC, `show ip interface brief`, ping, sauvegarde | En cours |

## Structure

```
lab-reseau/
├── CCNA/           Labos du parcours CCNA (ITN, SRWE, ENSA)
├── CCNP/           Labos du parcours CCNP Enterprise (à venir)
└── home-lab/       Labo physique : matériel, topologie, configurations réelles (à venir)
```

## Outils

- Cisco Packet Tracer (simulation)
- GNS3 / Cisco CML (émulation IOS XE)
- Home lab physique : Cisco ISR 4321, Catalyst 2960-X, Catalyst 3650 (en construction)

## Conventions

- Noms d'équipements : `SW1`, `SW2`, `R1`, `PC1`, `PC2`
- Un dossier par labo, numéroté dans l'ordre du cours
- `configs/` contient le `running-config` final de chaque équipement
- Les mots de passe des labos sont volontairement simples (`123`, `1234`) : environnements d'entraînement, jamais de production
