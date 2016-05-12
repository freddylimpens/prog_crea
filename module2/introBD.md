TITLE: Intro Base de données
MENUTITLE: Bases de données
AUTHOR: Freddy Limpens
LANGUAGE: fr
LOGO: media/


# Séance 1. (2x2h) Collecter et Manipuler des données

Dans cette séance nous allons aborder la notion de données en explorant tout d'abord le monde de l'open data et des possibilités que cette tendance apporte. Nous aborderons ensuite les premières notions de représentation des données avant d'introduire un outils permettant de les manipuler et de les visualiser.  
Lien prise de notes collective : https://oae.univ-lille3.fr/content/lille3/Ey6qIPD1g

## Notions de bases
Une base de données est un dispositif technologique permettant de stocker et récupérer des données brutes. Sur internet, les informations délivrées *aux clients* (votre navigateur) par un *serveur* (ceux de Facebook, Google, Lemonde.fr, Wikipedia.fr, etc.) proviennent toujours d'une base de données:  
![](http://static.commentcamarche.net/www.commentcamarche.net/pictures/bdd-images-basecs.gif)  

 **Intermède participatif** : Les bases de données sont présentes partout. Donner des exemples de domaines d'activités où dont utilisés des DB et pour quel type de données.  
  
Cette vision est cependant très schématique, le terme *"base de données"* étant très générique, car les bases de données sont maintenant organisés en des architectures très complexes et distribuées dans ce qu'on appelle le "cloud computing".

Malgré ces évolutions récentes, une base de donnée reste définie par son modèle de données détaillant les liens entre ses éléments. Voici par exemple le modèle de donnée du logiciel de WikiPedia:
![](https://upload.wikimedia.org/wikipedia/commons/2/2c/Mediawiki_dbschema.svg)

Dans ce dernier cas, on peut découper la complexité de cette représentation à l'aide de "tableaux", exactement comme ceux que vous manipuler dans un logiciel de feuille de calcul. On les appelle plus souvent "tables" dans le jargon. Une table peut représenter par exemple un aspect d'une "entité" du modèle ou une "relation" entre les différentes entités. C'est précisément l'exploitation et la manipulation de ces relations que permettent les bases de données dites "relationnelles", inventées dans les années 70:
![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Relational_key_SVG.svg/300px-Relational_key_SVG.svg.png)  
Tout repose ici sur l'usage d'une "clé unique" qui identifie chaque entité (ici des personnes que l'on décrit à travers différentes tables: une pour l'identité, une autre pour les coordonnées téléphoniques).   

Les bases de données relationnelles sont encore aujourd'hui incontournables et sont au coeur de nombreux logiciels très répandues comme WordPress, Drupal, WikiMedia, etc. et au coeur de nombreux sites web (libération.fr, tous les blogs, wikipedia.org, etc.). Cependant, de nouveaux formats et technologies de base de données sont apparues dans les années 90 afin d'optimiser la "portabilité" des données, c'est à dire le transfert aisé d'un serveur à un autre: XML, JSON, etc. Nous allons voir que ces formats de données plus statiques sont utilisés pour diffuser des données, dans un mouvement encore en plein essor l'OPEN DATA.

## Collecter et représenter les données

Exploration des différents jeux de données disponibles: sites institutionnels, opendata, etc. Voir les liens données en Annexe1

Différents formats sont utilisés dans le domaine de l'OpenData. NOus avons vu ensemble cette séance:
* le .CSV (Comma Separated Value): c'est un format texte, i.e ouvrable dans n'importe quel bon éditeur texte puisqu'il n'inclue pas de mise en forme à la différence des formats   traitement de text (ODT, DOC, etc). Un fichier CSV est essentiellement un tableau dans lequel:
> les valeurs pour les différentes colonnes sont séparés par un signe que l'on choisit la 1ère fois que l'on enregistre le fichier. Un conseil: éviter de choisir la `,` car en France c'est le signe qui sépare les décimales des nombres, donc il y a risque de se retrouver avec 2 colonnes différentes pour les entiers et le décimales d'un nombre à virgule, ex: 12,5 => 12 et 5 dans 2 colonnes séparées. Un signe couramment employé est le `;` ou la tabulation 
> la 1ère ligne donne le nom des colonnes  
* le .XLS: le format Excel pour un tableur est très diffusé. Attention il faut très souvent retraiter ce format et extraire les données des feuillets en autant de fichier .CSV pour une exploitation des données.
* le .JSON: c'est le format d'échange de données sur le Web par excellence. C'est un format "machine" qui sertà stocker les données sous forme "d'objets" ayant différents "champs" décrivant les propriétés de chaque item. La grande différence avec les tableaux c'est qu'un champ peut être décrit avec plusieurs "sous-champs", ce qui se traduit plus difficilement avec un tableau.  

Nous verrons par la suite d'autres formats courants, notamment ceux dédiés aux donnés géoréférencées.  

```comprehension

::Formats des bases de données::[markdown] Parmis les formats suivants, lesquels sont basés sur un format texte:
{
=JSON
=CSV
~XLS
}


```

## Application : Manipuler les données avec CartoDB

[Préparer un CSV pour CartoDB](https://player.vimeo.com/video/100105203){: .lien_video}

Regarder ce tutoriel sur l'utilisation de la plateforme [CartoDB.com](https://cartodb.com/)

## Exercice sur machine

Suivez les étapes suivantes et répondez à la question de l'activité suivante:

- aller suur cartodb.com
- se creer un compte
- aller sur https://ressources.data.sncf.com
- récupérer le jeu de données "Baromètre satisfaction client en gare"
- ouvrir le fichier excel, récupérer (c/c) les valeurs des 2 colonnes : nom de la gare, valeur de satisfaction globale
- créer un fichier csv et y coller ces 2 col. 
- récupérer le fichier "referentiel gare voyageurs" sur data.sncf.com
- normalement le fichier est géocodé par rapport à la colonne "commune", sinon, le faire manuellement en cliquant sur le bouton orange "geo" a côté de la colonne the_geom
- opérer la fusion des 2 datasets ainsi créés en choisissant pour chaque jeus de données la colonne donnant le nom des gares
- une fois la fusion effectuée, faite la requête SQL permettant de ne voir que les gares qui ont un chiffre de satisfaction:  
`
SELECT * FROM voyageurs_merge WHERE satisfaction_globale IS NOT NULL
`

```activite  


::Réponses à l'exercice sur machine:::[markdown]
Renseignez le lien vers la cartographie que vous avez réalisée, puis répondez aux questions suivantes:
-Trouver des représentations qui permettent de visualiser instantanément les gares ayant le meilleure indice de satisfaction. inspecter les résultat, et compter combien de résultats sont affichés par rapport aux nombres de gares pour lesquelles vous avez un chiffre de satisfaction. 
- Que constatez-vous ? Pourquoi ? (aidez-vous de requêtes SQL pour compter les résultats)
{}
    
    
```
