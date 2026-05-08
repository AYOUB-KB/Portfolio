# Mini-SOC Maison avec IA

Un projet perso pour comprendre comment ça marche un vrai SOC. Je monte tout chez moi, étape par étape.

## En cours de construction

Je suis en train de :
- Installer Wazuh pour surveiller mes VMs.
- Configurer Suricata pour voir ce qui passe sur le réseau.
- Lancer des attaques contrôlées avec Atomic Red Team.
- Ajouter une couche IA pour m’aider à comprendre les alertes.

Rien n’est parfait. Tout est documenté. Même les erreurs.

## Ce que j’utilise

- Proxmox pour les VMs
- Wazuh + Suricata pour la détection
- Windows 10 + Sysmon, AD, Ubuntu
- Python + Claude (Anthropic) pour l’IA
- Docker pour isoler les services

## À l’intérieur

- `lab/` -> mes VMs et configs
- `detections/` -> règles Wazuh/Suricata
- `ia/` -> scripts d’analyse automatique
- `docs/` -> schémas, notes, erreurs rencontrées
