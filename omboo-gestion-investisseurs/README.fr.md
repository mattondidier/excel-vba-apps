# Omboo : gestion d'investisseurs et de trésorerie en Excel VBA

🇬🇧 [English version](README.md)

**Du dépôt de l'investisseur au suivi des règlements : investissements, échéances, trésorerie et communication, dans une seule application Excel pilotée par VBA.**

Développé en 2020.

![Démo d'Omboo](assets/omboo-demo.gif)

## Le problème

Une société qui reçoit les fonds de nombreux investisseurs doit enregistrer chaque investissement, suivre les échéances de règlement, tenir sa trésorerie par caissier et par moyen de paiement, et garder le contact avec ses investisseurs. Omboo regroupe tout cela dans un seul outil, utilisable sans installation sur n'importe quel poste équipé d'Excel.

## Fonctionnalités

**Accès et administration**
- Connexion par utilisateur et mot de passe, avec choix de la langue (français ou anglais)
- Gestion des droits d'accès
- Fiche de l'entité, mise à jour de l'application et aperçu des jours fériés

**Paramétrage**
- Modes de paiement, dont le mobile money (MoMo, Orange Money, YUP)
- Modes d'affiliation et motifs de caisse
- Formules d'investissement
- Investisseurs, employés et prestataires

**Gestion courante**
- Journal des investissements : date, formule, investisseur, moyen de paiement, montant, avec calcul automatique des échéances
- Journal des opérations diverses
- Gestion des règlements par échéance

**Communication**
- Préparation des messages, campagnes d'e-mailing et envoi de SMS groupés

**Analyse**
- 15 états : analyses croisées investisseurs et formules, trésorerie journalière (globale et par caissier), état global de trésorerie
- Recettes, dépenses et résultat de trésorerie par période, mois par mois
- Règlements en attente
- Historiques des investissements, des opérations diverses, des règlements et des flux de trésorerie
- Recherche multicritère (dates, formule, investisseur, moyen de paiement), analyse graphique et impression

## Sous le capot

| Élément | Détail |
|---------|--------|
| Langage | VBA (Excel) |
| Interface | Barre de menus personnalisée, formulaires (UserForms) pour chaque module |
| Données | Tables de paramétrage, journaux et historiques stockés dans le classeur |
| Calculs | Échéancier généré à la saisie, états de trésorerie agrégés par période, caissier et moyen de paiement |

## Statut

Le fichier source n'est plus disponible. Cette fiche s'appuie sur la vidéo de démonstration.

## Auteur

**Didier Matton** | Ingénieur financier | Data Scientist Full Stack | Python, Django, VBA, BI & LLMs | Finance quantitative
