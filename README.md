# Scrapping des kebab dans Paris à partir du site : https://www.kebab-frites.com

## Dresser manuellement la liste des kebab à partir de chaque arrondissement

1. Prendre le nom de l'enseigne

2. Prendre le nom de l'arrondissement (Paris 01, Paris 02, *etc*.)

Les mots doivent être séparés par un espace.

- [Liste des kebab relevés manuellement](./donnees/listekebab.csv)

> [!WARNING]
> Le lien sur le [Kebab du XVème ](https://www.kebab-frites.com/kebab/kebab-du-15eme-xveme-paris-15.html) est mort. Les données ont été corrigées manuellement.

> [!WARNING]
> Le Restaurant çamoluk a été localisé « Place Édith Piaf », alors qu'il n'existe aucune adresse en ce lieu. La bonne adresse est « 28 Rue de la py ». La donnée a été corrigée manuellement.

## Vérifier tous les caractères spéciaux et créer les adresses U.R.L.

## Vérifier l'existence des adresses U.R.L.

- [Liste des adresses U.R.L. des kebab](./donnees/adresse-url-kebab.csv)

## Télécharger les données et créer la base de données

- Fichier Excel : [Liste des kebab localisés](./kebab/Scrapping-Liste-des-kebab-Paris.xls)

- Fichier C.S.V. : [Liste des kebab localisés](./kebab/Scrapping-Liste-des-kebab-Paris.csv)

## Aller sur le site de BD-Adresse et faire la manipulation pour récupérer les localisations

- [Données issues de la base Adresse](./donnees/Scrapping-Liste-des-kebab-Paris.geocoded.csv)

## Vérifier les localisations avec une image

- Fichier P.N.G. : [Localisation des kebab](./kebab/Scrapping-Liste-des-kebab-Paris-BD-Adresse.png)

## Insérer les localisations dans la base de données créée précédemment

- Fichier Excel : [Liste des kebab localisés](./kebab/Scrapping-Liste-des-kebab-Paris-BD-Adresse.xls)

- Fichier C.S.V. : [Liste des kebab localisés](./kebab/Scrapping-Liste-des-kebab-Paris-BD-Adresse.csv)
