
# Documenter
![icone_documenter](img/icone_documenter.png)

Documenter =
* décrire
* contextualiser


Pour :
* retrouver
* citer (créditer)
* utiliser
* gérer

Documenter = créer des données sur des données = créer des métadonnées

## Documentation et métadonnées, le formel et l'informel

On peut distinguer les métadonnées formelles et informelles.

* Métadonnées non formelles = documentation en **texte libre** rédigée en **langage naturel** = lisible par des **humains**
* Métadonnées formelles =  documentation **organisée** et structurée, en recourant si possible à des **vocabulaires contrôlés**, des normes = lisible par des **machines** (et par des humains)

Voir : Strasser, C. (2015). _Research Data Management_. National Information Standards Organization. Repéré à http://www.niso.org/apps/group_public/download.php/15375/PrimerRDM-2015-0727.pdf


>Documentation is sometimes considered a form of metadata, because it is information about data, and when it is very structured it can be. The importance of metadata lies in the potential for machine-to-machine interoperability, providing the user with added functionality, or 'actionable' information.

Source : The University of Edinburgh. (n.d.). Documentation, metadata, citation. _MANTRA Research Data Management Training_. Repéré à http://mantra.edina.ac.uk/documentation_metadata_citation/

Un exemple : la date

| Informel | Formel | Encore plus formel
: - | : - | : -
Ce fichier a été créé le 19 janvier 2018 | Date de création : 19/01/2018 |`<dc:created>2018-01-19</dc:created>`

Normes utilisées dans l'exemples encore plus formel :
- Dublin Core,
- ISO 8601 pour la date.

Un exemple réel et commenté de Dublin Core : voir "Exemple de standard" :  Projet DoRANum. (n.d.). Métadonnées, standards et formats [Fiche synthétique]. _DoRANum_. Repéré à http://doranum.fr/fiche-synthetique-metadonnees-standards-formats/

### Un (tout petit) peu plus sur le formel
Les métadonnées peuvent être regroupées en 3 grands types.

* Métadonnées **descriptives** - champs communs tels que titre, auteur, identifiant, date, ou encore résumé, mots-clé, etc. -  pour **retrouver** et **citer**
* Métadonnées **administratives** - métadonnées relatives à la préservation, aux droits et aux spécificités techniques (formats) - pour **utiliser** et **gérer**
* Métadonnées de **structure** - relations entre les différentes composantes d'un jeu de données par exemple (schéma décrivant les relations entre les tables d'une base de données par exemple) - pour **utiliser** et **gérer**

Source : The University of Edinburgh. (n.d.). Documentation, metadata, citation. _MANTRA Research Data Management Training_. Repéré à http://mantra.edina.ac.uk/documentation_metadata_citation/

### Un (tout petit) peu plus sur l'informel : le cahier de laboratoire

Pour en savoir plus sur ce mode de documentation, spécifique à certaines disciplines et que l'on n'évoquera pas aujourd'hui, voir écrans 12-16 de :

The University of Edinburgh. (n.d.). Documentation, metadata, citation. _MANTRA Research Data Management Training_. Repéré à http://mantra.edina.ac.uk/documentation_metadata_citation/.

Le Gurdon Institute propose des critères de choix et un **tableau comparatif** de différents outils disponibles, voir :

The Gurdon Institute. (2018). Electronic Lab Notebooks - for prospective users. _The Gurdon Institute_. Repéré à https://www.gurdon.cam.ac.uk/institute-life/computing/elnguidance?mc_cid=7dce7efa97&mc_eid=[UNIQID]

### Un peu plus sur l'informel : le fichier  `readme`

![read_me_poisson](img/read_me_poisson.jpg)

Source : Samuk, K., Xue, J., &amp; Rennison, D. J. (2018, 2 février). _Data from: Exposure to predators does not lead to the evolution of larger brains in experimental populations of threespine stickleback_ [Dataset]. https://doi.org/10.5061/dryad.dh3h417

Aujourd'hui nous allons nous concentrer sur un mode de documentation simple et utilisable dans tous les contextes, pour tous les projets quelles que soient leurs dimensions, le fichier `readme`.

#### Exemples de fichier  `readme`
Les [3 exemples](https://github.com/fflamerie/organisation_donnees_2018/tree/2018_03_23/readme_exemples) de fichiers `readme` proviennent des sources suivantes.

1. Exemple 1

Wilkinson, T. C. (2017, 24 novembre). _Project Panormos Archaeological Survey: Method Design (survey-design)_ [Dataset]. _Zenodo_. https://doi.org/10.5281/zenodo.1063932

2. Exemple 2

De Valença, J. C., Kurniawan, A., Wagterveld, R. M., Wood, J. A., & Lammertink, R. G. H. (2017). _Influence of Rayleigh-Bénard convection on electrokinetic instability in overlimiting current conditions_ [Dataset]. https://doi.org/10.4121/uuid:b55184a0-930d-4b5c-940b-fd3038e05d83

3. Exemple 3

4TU Centre for Research Data. (2017, décembre). Guidelines for creating a README file. Repéré à http://researchdata.4tu.nl/fileadmin/editor_upload/pdf/README/Guidelines_for_creating_a_README_file.pdf

#### Modèles de fichier  `readme`

Nous avons retenu [2 modèles](https://github.com/fflamerie/organisation_donnees_2018/tree/2018_03_23/readme_templates) pour créer un fichier  `readme` au niveau d'un jeu de données :

* Modèle de Delft

4TU Centre for Research Data. (2017, décembre). Guidelines for creating a README file. Repéré à http://researchdata.4tu.nl/fileadmin/editor_upload/pdf/README/Guidelines_for_creating_a_README_file.pdf

* Modèle de Cornell

Cornell Research Data Management Service Group. (n.d.). Guide to writing « readme » style metadata. _Research Data Management Service Group_. Repéré à https://data.research.cornell.edu/content/readme


##### Le modèle de readme de Delft
Les 3 points de **bonne pratique** du modèle Delft :

>* Créez 1 readmefile pour chaque jeu de données.
>* Nommez le fichier **README**, pas readme, read_me, ABOUT, etc.
>* Ecrivez votre document `readme` comme un fichier texte simple ; enregistrez-le en  **README.txt** ou **README.md** si vous écrivez en Markdown. Ou utilisez **README.pdf** si la mise en forme est importante pour votre fichier.

NB **jeu de données**  dans ce contexte =

* 1 fichier,
* ou 1 ensemble de fichiers reliés entre eux et formatés de façon identique,
* ou 1 ensemble de fichiers regroupés logiquement ensemble (ex : 1 collection de scripts Matlab).

**La structure** - NB chaque item comprend des éléments **obligatoires** et facultatifs, on cite seulement ici le détail de la section 1, c'est surtout celle-ci que nous allons essayer de compléter aujourd'hui.

>1. _Introductory information_
>
> * **Title of the dataset**
> * **For each file or group of similar files, a short description of what data it contains**
> * Explain the file naming convention, if applicable
> * Format of the file if not obvious from the file name
> * If the data set includes multiple files that relate to each other, the relationship between the files or a description of the file structure that holds them
> * Contact information; in case users have questions regarding the data files
>
>2. _Methodological information_
>3. _Data specific information_
>4. _Sharing and Access information_

##### Le modèle de readme de Cornell
Les bonnes pratiques en plus

>* Nommez le `readme` de façon à ce qu'il puisse être facilement associé avec les données qu'il décrit.
>* Formatez le document de façon à ce qu'il soit facile à comprendre (_i. e._ séparez les éléments d'information importants par des lignes blanches, plutôt que de rassembler toutes les informations dans un seul long praragraphe).
>* Formatez des fichiers `readme` multiples de façon identique ; présentez les informations dans le même ordre, en utilisant la même terminologie.
> * Utilisez des formats de date normalisés. Format suggéré : norme  W3C/ISO 8601, qui définit la notation normalisée internationale  : YYYYMMDD  ou YYYYMMDDThhmmss.
> * Suivez les conventions scientifiques de votre discpline pour les termes taxonomiques, géospatiaux et géologiques. Autant que possible, utilisez des termes de taxonomie et vocabulaires standardisés.

Rappel :  définition vocabulaire contrôlé

>Un vocabulaire contrôlé est un ensemble organisé de mots et expressions utilisés pour indexer du contenu et/ou le retrouver par navigation ou recherche. Typiquement, il inclut des termes préférentiels et leurs variantes et opère dans un périmètre défini ou décrit un domaine spécifique.

Source : Confederation of Open Access Repositories. (2018). Vocabulaires contrôlés. Repéré à https://www.coar-repositories.org/files/coar-cv-infog-f_27052042-3.pdf

Le modèle de `readme` de Cornell est plus détaillé, il inclut notamment un inventaire exhaustif des fichiers et des informations concernant les versions des fichiers.

On mentionne ici seulement la structure générale ; comme pour le modèle de Delft certains éléments sont **obligatoires** et d'autres facultatifs. Les items sont globalement les mêmes, l'ordre des rubriques change en revanche. Cornell fournit un modèle téléchargeable de ce fichier `readme`.

> * General information
> * Data and file overview
> * Sharing and access information
> * Methodological information
> * Data-specific information

## Le formel et l'informel en pratique
### Comment?
Les métadonnées peuvent être renseignées de différentes façons :
* dans un nom de fichier,
* dans un fichier `readme`,
* dans un fichier XML,
* dans une base de données,
* ou encore dans les fichiers de données eux-mêmes.

Lorsque vous devrez choisir comment les enregistrer, prenez en compte :
* l'expertise dont vous disposez,
* la complexité de votre projet,
* vos collègues,
* votre propre niveau de confort.

Traduit de : IAP. (2016). Research Data Management 101: The Lifecycle of a Dataset. Communication présentée au MIT, MIT Libraries. Repéré à https://libraries.mit.edu/data-management/files/2014/05/rdm101_IAP2016_20160112-1.pdf

Nous avons évoqué brièvement tout à l'heure le _Dublin Core_, qui est un schéma de métadonnées standardisé.

Dans la mesure du possible, les schémas standardisés comme le _Dublin Core_ sont à privilégier, car

* ils assurent que vous ayez un ensemble d'informations complet et normalisé,
* ils permettent d'organiser et de combiner votre jeu de données plus facilement avec d'autres.


Certains sont généralistes, comme le _Dublin Core_, d'autre spécifiques à des disciplines. Ces derniers sont à privilégier, car ils sont plus précis, et utilisés au sein de votre communauté.

De premières ressources pour les connaître et les trouver.
* Aperçu synthétique de premier niveau

Projet DoRANum. (n.d.). Métadonnées, standards et formats [Fiche synthétique]. _DoRANum_. Repéré à http://doranum.fr/fiche-synthetique-metadonnees-standards-formats/

* Exemples de standards de métadonnées et d'ontologies, ainsi qu'une étude de cas dans le domaine biomédical

Stanford. (n.d.). Advanced metadata. _Stanford Libraries_. Repéré à http://library.stanford.edu/research/data-management-services/data-best-practices/creating-metadata/advanced-metadata


* Répertoire complet, organisé par discipline et recensant à la fois des modèles et des outils

Research Data Alliance. (n.d.). Metadata Directory. Repéré à http://rd-alliance.github.io/metadata-directory/tools/

### A quel niveau?
Qu'elle soit formelle ou informelle, on a vu que la documentation pouvait être positionnée à différents niveaux.
On retiendra 3 niveaux à documenter, pour lesquels produire, sous une forme à adapter, de la documentation.

* Niveau 1 : niveau du projet
* Niveau 2 : niveau du fichier ou de la base de données
* Niveau 3 : niveau de la variable ou de l'objet

>* Project level: what the study set out to do, how it contributes new knowledge to the field, what the research questions/hypotheses were, what methodologies were used, what sampling frames were used, what instruments and measures were used, etc. A complete academic thesis normally contains this information in detail, but a published article may not. If a dataset is shared, a detailed technical report will need to be included for the user to understand how the data were collected and processed. You should also provide a sample bibliographic citation to indicate how you would like secondary users of your data to cite it in any publications, etc.
>* File or database level: how all the files (or tables in a database) that make up the dataset relate to each other; what format they are in; whether they supercede or are superceded by previous files. A readme.txt file is the classic way of accounting for all the files and folders in a project.
>* Variable or item level: the key to understanding research results is knowing exactly how an object of analysis came about. Not just, for example, a variable name at the top of a spreadsheet file, but the full label explaining the meaning of that variable in terms of how it was operationalised.


Source : The University of Edinburgh. (n.d.). Documentation, metadata, citation. _MANTRA Research Data Management Training_. Repéré à http://mantra.edina.ac.uk/documentation_metadata_citation/

Pour le niveau "Projet", voir les ressources de Stanford :

Stanford Libraries. (n.d.). Basic approach to metadata. _Stanford Libraries_. Repéré à http://library.stanford.edu/research/data-management-services/data-best-practices/creating-metadata/basic-approach-metadata

Stanford Libraries. (n.d.). Case study: Basic metadata. _Stanford Libraries_. Repéré à http://library.stanford.edu/research/data-management-services/case-studies/case-study-basic-metadata
