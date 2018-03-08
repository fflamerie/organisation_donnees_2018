
# Préserver - sauvegarder

## Les grands principes et les bonnes pratiques pour préserver vos données
### Stockage vs. archivage

| Phase | Practice | Definition|
| : - | : -: | : - |
| <mark>During</mark> research | Data <mark>storage</mark> | The storage of data while the research is being conducted, *i.e.* while data are being produced or collected (for reuse), analysed and/or processed, and prepared for publication.|
| <mark>After</mark> research |  Data <mark>archiving</mark>|The long-term saving of data after the research has been completed, *i.e.* the archiving of data in a durable and searchable environment, possibly with access rights.|

Source : Zeeland, H. van & Ringersma, J. (2017). The development of a research data policy at Wageningen University & Research: best practices as a framework. _LIBER Quarterly_, _27_(1), 153‑170. https://doi.org/10.18352/lq.10215


### Les sauvegardes : le principe 3,2,1
Au moins pour chacun des items :

* 3 copies,
* 2 supports,
* 1 en-dehors du site.

## Comment définir une stratégie de sauvegarde?
Pour définir une stratégie de sauvegarde, on retiendra notamment les éléments suivants à prendre en compte.

* L'existence d'une politique de sauvegarde au niveau de votre structure (équipe, labo, institution).

* Les différents types de sauvegarde.

  * Une sauvegarde **complète** concerne  toutes les données.
  * Une sauvegarde **incrémentale** consiste à sauvegarder uniquement les données modifiées depuis la dernière sauvegarde partielle.
  * Une sauvegarde **différentielle** consiste à sauvegarder uniquement les données modifiées depuis la dernière sauvegarde complète.

* Dans tous les cas on veille à ne pas écraser les sauvegardes antérieures accidentellement.

* La durée de conservation de la sauvegarde.

* L'espace disque nécessaire.

* La gestion des versions s'il s'agit de sauvegarder des données réparties sur différents appareils.

* Le niveau de sécurisation des données à assurer - voir _infra_ quelques éléments concernant la sécurité.

* La nécessité de vérifier régulièrement que les sauvegardes sont bien effectuées :
  * en restaurant les fichiers de la sauvegardes et en s'assurant qu'ils puissent être lus,
  * en contrôlant l'intégrité des fichiers : date de modification, taille du fichier, somme de contrôle (_checksum value_) ou empreinte.

Traduit et adapté de :

UK Data Service. (n.d.). Data backup. _UK Data Service_. Repéré à https://www.ukdataservice.ac.uk/manage-data/store/backup

The University of Edinburgh. (n.d.). Storage and security. _MANTRA Research Data Management Training_. Repéré à http://mantra.edina.ac.uk/storageandsecurity/


## Un point sur la sauvegarde en ligne
Les services en ligne commerciaux tels que DropBox, Google Drive, etc. sont attractifs, car ils permettent de synchroniser des données entre plusieurs ordinateurs, de collaborer, et de disposer d'une copie en ligne des données.

Leurs caractéristiques englobent généralement :
* le stockage et la synchronisation des fichiers en ligne et entre plusieurs ordinateurs,
* la mise à disposition d'un espace de stockage en ligne,
* une offre de services minimale gratuite, des services complémentaires (y compris de l'espace de stockage supplémentaire) étant soumis à tarification.


Ils peuvent donc présenter les avantages suivants (variables en fonction des services).
* Aucune intervention de l'utilisateur n'est nécessaire pour que la sauvegarde soit effectuée.
* Ils permettent de répondre au critère "1 copie hors site".
* Ils permettent de versionner et d'encrypter les fichiers.
* Ils sont multi-plateformes.

Ils présentent toutefois notamment les limites suivantes.
* Les serveurs de la plupart des opérateurs sont situés en-dehors de l'Europe, ce qui peut être bloquant s'il est exigé que vos données soient stockées à l'intérieur de cette zone.
* La société commerciale qui opère le service peut modifier ses conditions d'utilisation, faire faillite, etc. Et les conditions d'utilisation existantes peuvent être très contraignantes et/ou problématiques.

Traduit et adapté de : The University of Edinburgh. (n.d.). Storage and security. _MANTRA Research Data Management Training_. Repéré à http://mantra.edina.ac.uk/storageandsecurity/


Exemple Google, rubrique _Your content in our services_ des [Conditions d'utilisation - version 2017-10-25](https://www.google.com/intl/en/policies/terms/) :

>Some of our Services allow you to upload, submit, store, send or receive content. You retain ownership of any intellectual property rights that you hold in that content. In short, what belongs to you stays yours.
>
>When you upload, submit, store, send or receive content to or through our Services, **you give Google (and those we work with) a worldwide license to use, host, store, reproduce, modify, create derivative works (such as those resulting from translations, adaptations or other changes we make so that your content works better with our Services), communicate, publish, publicly perform, publicly display and distribute such content**. The rights you grant in this license are for the limited purpose of operating, promoting, and improving our Services, and to develop new ones. **This license continues even if you stop using our Services (for example, for a business listing you have added to Google Maps)**. Some Services may offer you ways to access and remove content that has been provided to that Service. Also, in some of our Services, there are terms or settings that narrow the scope of our use of the content submitted in those Services. Make sure you have the necessary rights to grant us this license for any content that you submit to our Services.


## Un point sur le matériel : trucs et astuces pour vos clés USB, etc.

Si vous utilisez des CDs, DVDs ou des clés USB pour des données en cours ou pour une copie de sauvgarde supplémentaire (en + des 3 définies _supra_), vous pourrez retenir les bonnes pratiques suivantes.

* Assurez-vous que les versions _master_ de vos donnée sont bien mises à jour et sauvegardés sur un disque réseau.
* Choisissez des produits de haute qualité provenant de fabriquants réputés.
* Suivez les instructions du fabriquant pour l'entretien et la manipulation, y compris les conditions environmentales et l'étiquetage.
* Etiquetez le support.
* Vérifiez périodiquement le support pour vous prémunir de sa défaillance et rafraîchissez périodiquement les données (_i. e._ recopiez-les sur un nouveau support).
* Assurez-vous que les données privées ou confidentielles sont encryptés.

Traduit et adapté de : The University of Edinburgh. (n.d.). Storage and security. _MANTRA Research Data Management Training_. Repéré à http://mantra.edina.ac.uk/storageandsecurity/


## Récapitulatif concernant les supports

![storage_solutions](img/storage_solutions.png)

Source : Research Data Netherlands. (n.d.). Storing data. _Essentials 4 Data Support_. Repéré à http://datasupport.researchdata.nl/en/start-the-course/iii-the-research-phase/storing-data/



## Automatiser ses sauvegardes personnelles

2 exemples :
* Pour Mac : [TimeMachine](https://support.apple.com/fr-fr/HT201250)
* Pour Windows : [SyncToy](https://www.microsoft.com/en-us/download/details.aspx?id=15155)



## Pour aller plus loin : la sécurité des données

La fiche Mantra donne d'autres exemples de pertes de données, concernant y compris des données sur d'autres supports, et traite également la question de la sécurité des données.

Voir : _Session 3: Data storage & security_
The University of Edinburgh. (n.d.). Do-It-Yourself Research Data Management Training Kit for Librarians. _MANTRA Research Data Management Training_. Repéré à http://mantra.edina.ac.uk/libtraining.html

**Ressources pour aborder la question de la sécurité des données**

UK Data Service. (n.d.). Data security. _UK Data Service_. Repéré à https://www.ukdataservice.ac.uk/manage-data/store/security

The University of Edinburgh. (n.d.). Storage and security. _MANTRA Research Data Management Training_. Repéré à http://mantra.edina.ac.uk/storageandsecurity/
