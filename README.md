# iut_sd2_powerbi_enedis
-Vous devez avoir les autorisations RLS pour acceder au lien du projet : https://app.powerbi.com/links/GFTrntmu3S?ctid=a51a6642-5911-4306-a13c-f4731ab9c63f&pbi_source=linkShare&bookmarkGuid=1bae7264-daf6-4a2b-bf19-ec76345f0012

Ce projet Power BI a été développé dans le but de fournir une visualisation claire et interactive des données liées à **L'energie transmise par Enedis**. Le tableau de bord permet d'explorer des données clés, d'identifier des tendances et de faciliter la prise de décision basée sur les données.

## Fonctionnalités principales

- **Visualisations interactives** : Graphiques dynamiques, tableaux et cartes pour une analyse approfondie.
- **Filtres personnalisés** : Options pour filtrer par étiquette DPE, région, catégorie de logement.
- **Indicateurs clés de performance (KPI)** : Visualisation des données critiques comme **Consommation d'énergie, Emissions de CO2**.

## Sources de données

Pour récupérer les données, nous avons utilisé deux API disponibles sur le site `Data.ademe.fr`. Ces API fournissent des informations sur les logements **existants** et **neufs** du département de Loir-et-Cher. Nous avons ensuite sélectionné les variables nécessaires à notre analyse.

### Liens API :
- [Logements Existants](https://data.ademe.fr/datasets/dpe-v2-logements-existants/api-doc)
- [Logements Neufs](https://data.ademe.fr/datasets/dpe-v2-logements-neufs/api-doc)

Le tableau de bord utilise les données provenant de :
- **adresse-41** : Répertorie tout les logements avec leurs localisation.
- **Logement existants** Répertorie les logements existants avec des données.
- **Logement neufs** Répertorie les logements neufs avec des données.

## Navigation dans le tableau de bord

1. **Page d'accueil** : Choix Pages, Contexte.
2. **Pages thématiques** : Visualisations organisées par catégorie (neuf ou existant ou comparaison).


## Technologies utilisées

- **Microsoft Power BI** : Pour la création et l'hébergement du tableau de bord.
- **Base de données :CSV** : 3 csv 


## Instructions pour l'utilisation

1. **Prérequis** :
   - Power BI Desktop (ou accès au service en ligne Power BI).
   - Droits d'accès aux données .

2. **Ouverture du fichier** :
   - Télécharger le fichier `.pbix` attaché au projet.
   - Ouvrir le fichier avec Power BI Desktop.

3. **Exploration** :
   - Naviguez à travers les pages en utilisant le menu ou les onglets en bas.
   - Utilisez les filtres pour personnaliser votre vue.




## Auteur

- **prenom** : Tristan, Arnaud
- **Organisation** : GreenTech Solutions

** Lien projet
lien :
