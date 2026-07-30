# Niveau 2 : les skills

**Vous êtes au bon endroit si** vous avez déjà essayé les prompts du niveau 1 et que vous voulez arrêter de recoller votre contexte à chaque conversation. Un **skill**, c'est votre méthode empaquetée une fois pour toutes : Claude connaît votre cabinet, applique votre grille de travail, et produit directement un livrable présentable (PowerPoint, trame, courrier).

📖 **Première fois ici ?** Suivez le [chapitre 2 du guide d'installation](../docs/guide-installation.md#chapitre-2-niveau-2-les-skills), avec captures d'écran : il vous prend par la main du téléchargement au premier livrable.

## Les 5 skills du pack

| Skill | Vous lui donnez | Il vous rend |
|---|---|---|
| [`audit-contrat-av/`](audit-contrat-av/) | Un relevé de contrat d'assurance-vie + le profil du client | Un PowerPoint d'audit : frais décomposés, allocation, options, sans jamais trancher |
| [`bilan-patrimonial/`](bilan-patrimonial/) | Le transcript ou les notes d'un rendez-vous de découverte | Le bilan structuré + le PowerPoint de restitution |
| [`preparation-rdv/`](preparation-rdv/) | Le dossier du client + l'objet du rendez-vous | Une trame de rendez-vous en 1 page (questions ouvertes, objections, clôture) |
| [`comparatif-contrats/`](comparatif-contrats/) | 2 à 4 fiches de contrats + le besoin du client | Un PowerPoint comparatif factuel, sans « gagnant » |
| [`lettre-synthese-annuelle/`](lettre-synthese-annuelle/) | Les situations annuelles des contrats | Un projet de lettre client + son annexe chiffrée |

👀 **Envie de voir le résultat avant d'installer ?** Le dossier [`exemples/`](exemples/) contient de vrais livrables générés par ces skills sur un dossier fictif (la famille Martin) : ouvrez les fichiers `.pdf` directement dans votre navigateur.

## Télécharger un skill (2 minutes)

Chaque dossier de skill contient un fichier `.zip` prêt à l'emploi. Par exemple pour l'audit :

1. Cliquez sur le dossier [`audit-contrat-av/`](audit-contrat-av/) ci-dessus.
2. Cliquez sur le fichier **`audit-contrat-av.zip`**.
3. Cliquez sur le bouton de téléchargement (flèche vers le bas, en haut à droite du fichier, « Download raw file »).
4. Le fichier arrive dans votre dossier « Téléchargements ». **Ne le décompressez pas** : Claude le prend tel quel.

Ensuite, direction le [chapitre 2 du guide](../docs/guide-installation.md#chapitre-2-niveau-2-les-skills) pour le charger dans Claude (5 minutes, captures d'écran à l'appui).

## Personnaliser (le seul fichier à modifier)

Dans chaque skill, un seul fichier vous concerne : **`contexte-cabinet.md`**. Il porte le nom de votre cabinet, votre statut ORIAS, votre ton et votre charte graphique (couleurs, polices, logo). Modifiez-le, rezippez le dossier, rechargez : tous les livrables sortent à vos couleurs. La méthode métier (grilles, trames) vit dans les autres fichiers et n'a pas besoin d'être touchée.

## Les garde-fous intégrés (ne les retirez pas)

- **Entrées manquantes = blocage** : le skill liste ce qui manque au lieu d'inventer.
- **Aucun chiffre inventé** : donnée absente = « donnée non disponible ».
- **Observations, jamais de recommandations** : vous décidez, vous signez.
- **Paramètres fiscaux datés** « à vérifier » : ils changent chaque année.
- **Garde-fou rachat** (antériorité 8 ans, versements avant/après 70 ans) codé en dur dans l'audit.

⚠️ **Rappel données clients** : les skills tournent dans un outil en ligne. Données **anonymisées uniquement** (voir le [chapitre 0 du guide](../docs/guide-installation.md#chapitre-0-avant-de-commencer)). Pour aller plus loin (simulateurs de transmission, analyse de portefeuille, recherche de supports) : le [Charlie Screener](https://www.charliewealth.fr/landing), présenté au chapitre 3 du guide.
