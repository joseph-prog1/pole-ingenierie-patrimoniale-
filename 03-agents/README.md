# Niveau 3 : les agents

Un pôle d'ingénierie patrimoniale complet : des agents spécialisés (`.claude/agents/`), chacun avec une responsabilité unique, orchestrés sur un workflow « dossier client complet ».

🚧 **En construction.** Principes déjà actés :

- Chaque agent **bloque explicitement** si ses entrées manquent, plutôt que de produire une sortie plausible.
- Les calculs (frais, droits, contrôles SRI/profil) sont **déterministes** : l'agent appelle des calculateurs, il ne calcule pas lui-même.
- Toute sortie est un projet à valider par le conseiller, avec traçabilité (source et fiabilité sur chaque donnée).
- Le statut du cabinet (COA, CIF...) est un **paramètre de configuration**, jamais codé en dur.

Installation : voir le [guide](../docs/guide-installation.md), chapitre 3.
