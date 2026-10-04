# Utiliser le tableau de suivi d’activité Teliosa

Le fichier [tableau-suivi-activite.xlsx](../ressources/tableau-suivi-activite.xlsx) contient deux onglets : **Mon suivi**, à remplir, et **Exemple fictif**, pour comprendre le fonctionnement. Chaque ligne correspond à une semaine. Les semaines suivies peuvent traverser deux mois : le total affiché est un total de période, pas automatiquement un total mensuel.

## Remplir une ligne

| Colonne | Ce qu’il faut saisir |
|---|---|
| Semaine du | Le lundi de la semaine observée, au format JJ/MM/AAAA. |
| Demandes reçues | Nouvelles demandes de renseignement reçues pendant la semaine. Compter une seule fois une même demande poursuivie par plusieurs messages. |
| RDV pris | Nouveaux rendez-vous réservés pendant la semaine, même s’ils ont lieu plus tard. |
| Séances réalisées | Séances effectivement tenues pendant la semaine, quelle que soit la date de réservation. |
| Encaissements (€) | Montants effectivement reçus sur la période, sur une base cohérente d’une semaine à l’autre. |
| Observation | Un fait utile : absence, changement de page, origine récurrente des demandes. |
| Action suivante | Une seule action précise, choisie à partir de l’observation. |

Les cellules de saisie ont un fond clair. La ligne de total contient des calculs : conservez ses formules.

## Zéro et case vide ne veulent pas dire la même chose

Saisissez **0** si vous avez vérifié qu’il n’y a eu aucun événement ou encaissement. Laissez vide si l’information manque. Tous les totaux restent vides tant qu’une ligne commencée ne comporte pas une date et les quatre données numériques. La mention « Saisie à compléter » reste visible sur la ligne concernée.

Ne remplissez pas de ligne sans indiquer la semaine correspondante. Renseignez uniquement les périodes terminées. Le fichier propose treize lignes pour suivre jusqu’à treize semaines ; pour une nouvelle période, repartez d’une copie vierge plutôt que de saisir en dessous des lignes prévues.

## Lire les résultats

Les demandes, les réservations et les séances ne concernent pas nécessairement les mêmes personnes. Ne calculez pas un « taux de conversion » en divisant simplement les réservations de la semaine par les demandes de cette même semaine : certaines réservations peuvent provenir de demandes plus anciennes.

Les encaissements ne sont pas le bénéfice. Ils peuvent inclure des acomptes ou des paiements de prestations réalisées à une autre date. Ce tableau ne calcule ni charges, ni impôts, ni chiffre d’affaires comptable.

## Garder un suivi léger

Utilisez des comptes et des observations globales. Les noms, motifs de consultation, données de santé et coordonnées des clients n’ont pas leur place ici. Conservez votre copie de travail dans votre espace privé ; ne la déposez pas dans un dépôt GitHub public.

Pour passer de la mesure à l’action, consultez le [bilan hebdomadaire](bilan-hebdomadaire.md).
