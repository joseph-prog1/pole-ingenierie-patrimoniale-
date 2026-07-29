# Cas de test des prompts

Deux dossiers clients **fictifs et anonymisés** pour tester les prompts avant de les livrer. Chaque cas contient volontairement des **pièges** que le prompt doit détecter : c'est le critère de réussite.

## Comment tester (10 min par prompt)

1. Ouvre une nouvelle conversation sur [claude.ai](https://claude.ai).
2. Colle le prompt (`bilan-patrimonial.md` ou `audit-patrimonial.md`), en-tête cabinet rempli.
3. Colle ensuite le contenu du cas de test correspondant.
4. Compare la sortie à la grille « ce que le prompt doit attraper » ci-dessous.

## Test complémentaire à faire d'abord : le dossier vide

Avant les cas complets, colle le prompt **sans aucune pièce** (ou juste « Voici mon client, fais le bilan »).
✅ Réussite : l'assistant **refuse de produire** et liste les éléments manquants.
❌ Échec : il invente un bilan plausible. Si c'est le cas, renforce la section « Entrées » du prompt.

## Grille de validation

### Cas 1 — Bilan (`cas-1-bilan.md`)
Le prompt doit attraper, en section « Points d'attention » :
- [ ] La **clause bénéficiaire mentionnant l'ex-épouse** (point d'attention prioritaire).
- [ ] L'**épargne dormante** : 140 000 € sur livrets, disproportionné vs les charges.
- [ ] La **TMI à 41 %** sans PER alimenté (fiscalité subie).
- [ ] Le **régime de communauté** relevé, avec la question de la protection du conjoint.
- [ ] La **concentration** : les titres de la société non cotée pèsent une part majeure du patrimoine.
- [ ] Chaque donnée porte une **source** et une **fiabilité**.
- [ ] Il **ne recommande rien** (pas de « il faudrait ouvrir un PER »).
- [ ] Il liste les **données manquantes** (ex. valorisation de la SCI absente).

### Cas 2 — Audit (`cas-2-audit.md`)
- [ ] Il **ne recommande pas le rachat** du vieux contrat, malgré des frais élevés : il vérifie l'antériorité 8 ans et propose l'arbitrage interne, chiffres à l'appui.
- [ ] Il **signale le franchissement des 70 ans** pour le projet de versement de 200 000 €.
- [ ] Il produit le **tableau des frais en 5 étages**.
- [ ] Il **signale la ligne de valorisation périmée** (plus de 3 mois).
- [ ] Il **ne calcule pas de performance** faute de date d'achat fiable.
- [ ] Il présente les conclusions **sans trancher** (au conseiller de décider).
