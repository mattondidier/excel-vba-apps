# DIGESC : logiciel de gestion commerciale en Excel VBA

🇬🇧 [English version](README.md)

**De la facture au tableau de bord : achats, ventes, stock, caisse et trésorerie d'une PME, dans une seule application Excel pilotée par VBA.**

Développé en 2018-2019, dans le cadre de mon master technologique.

![Démo de DIGESC](assets/digesc-demo.gif)

▶ **Démonstration complète :** [voir la vidéo sur YouTube](https://www.youtube.com/watch?v=vkNjocGOuQI)

## Le problème

Une petite entreprise commerciale doit suivre ses clients, ses fournisseurs, ses produits répartis dans plusieurs dépôts, ses documents commerciaux et sa caisse. DIGESC regroupe tout cela dans un seul outil, utilisable sans installation sur n'importe quel poste équipé d'Excel.

## Fonctionnalités

**Accès et administration**
- Connexion par utilisateur, avec mot de passe défini à la première connexion
- Gestion des utilisateurs par l'administrateur, avec droits d'accès par menu (Fichier, Paramétrage, Traitement, Analyse)
- Fiche de l'entreprise (raison sociale, adresse, numéro de contribuable, site web) et choix du dossier de sauvegarde

**Paramétrage**
- Modes de règlement : espèces, banque, crédit, Orange Money, MoMo
- Taux de TVA, familles de produits, conditionnements, unités de vente
- Dépôts de stockage, catégories de clients, fournisseurs et salariés
- Motifs de mouvements de stock et de caisse

**Bases de données**
- Produits : famille, prix d'achat et de vente, TVA, stocks minimum, maximum et d'alerte, quantités par dépôt, fournisseurs principal et secondaire, code-barres, photo
- Tiers : clients, fournisseurs et salariés, avec catégorie, contacts et responsable

**Documents commerciaux**
- Pro forma, bon de commande, bon de livraison, facture d'achat, facture de vente
- Numérotation automatique par année et par type de document
- Calcul complet de la facture : remise, escompte, transport (port facturé, avancé ou dû) avec sa TVA, TVA, précompte sur achat, net à payer, échéance et mode de règlement

**Caisse**
- Vente au comptoir avec photo du produit, tickets de caisse numérotés et solde des ventes du jour

**Journaux**
- Journal de stock, journal de trésorerie, suivi des règlements

**Analyse**
- État du stock global, par dépôt et par période
- Trésorerie par période et état du caissier du jour
- Ventes et achats mois par mois, avec graphiques

**Échanges de données**
- Import de données depuis un classeur Excel
- Export de chaque liste en PDF ou en Excel, et impression

## Sous le capot

| Élément | Détail |
|---------|--------|
| Langage | VBA (Excel) |
| Code | Environ 6 000 lignes, 17 formulaires (UserForms), 7 modules, 470 procédures |
| Données | Une feuille unique sert de base de données, chaque table occupe un bloc de colonnes |
| Architecture | Routines génériques d'affichage, d'ajout, de modification et de suppression, réutilisées par tous les formulaires |
| Calculs | Agrégations par `SumIfs` pour les états de stock, de trésorerie et de performance |
| Interface | Menu d'accueil animé, barre de progression, styles de boutons centralisés dans un module dédié |
| Exports | PDF via `ExportAsFixedFormat`, import par ouverture d'un classeur externe |

## Statut

Le fichier Excel n'est pas public. Une démonstration est possible sur demande.

La gestion prévisionnelle était prévue pour une version suivante.

## Suite du projet

DIGESC est en cours de refonte en application web avec Django.

## Auteur

**Didier Matton** | Ingénieur financier | Data Scientist Full Stack | Python, Django, VBA, BI & LLMs | Finance quantitative
