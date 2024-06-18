icon:material/cube
## 1/ Impression des pièces en 3D

Imprimer toutes les pièces nécessaires en veillant à respecter les recommandations de remplissage des pièces extérieurs (cf. chapitre 1.2). [Les fichiers STL sont disponibles ici](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/3Dprint_files/) .

![POP1-0.png](/../doc/kosmos/pictures/productions_of_parts/POP1-0.png)

**1.1 Pour l'intérieur du caisson :**

Il n'y a pas d'obligation quand au matériau d'impression de ces pièces. Le PET est le matériau que nous avons utilisé du fait qu’il est très facilement accessible dans le commerce. Le PLA parait à écarter tant parfois il arrive au KOSMOS d'être stocké au soleil. La température si elle atteint 60° pourrait déformer des pièces en PLA. 

Le remplissage pourra être alvéolé de manière à économiser de la matière. Nous utilisons régulièrement un remplissage à 20% et une résolution de 0,2mm.

|    Visuel    |Référence|Quantité|Dénomination|Usage|Conseils d'impression|
|------------------------------------|------|------|-----------------|---------------------|---------------------|
|![POP1-1-I1](/../doc/kosmos/pictures/productions_of_parts/POP1-1-I1.png)|[I1](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/3Dprint_files/I1_KOSMOS_V3-0.stl)|1|Section de la raspberry|Cette pièce est la section qui s'insérera dans le tube étanche, c'est le support de la carte raspberry et de divers autres composants.|Positionner des générateurs de supports pour supporter la partie en porte à faux|
|![POP1-1-I2](/../doc/kosmos/pictures/productions_of_parts/POP1-1-I2.png)|[I2](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/3Dprint_files/I2_KOSMOS_V3-0.stl)|1|Section batterie|I2 est la section qui va faire le lien entre la structure Raspberry et la plaque sur laquelle va se positionner les batteries|/|
|![POP1-1-I3](/../doc/kosmos/pictures/productions_of_parts/POP1-1-I3.png)|[I3](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/3Dprint_files/I3_KOSMOS_V3-0.stl)|1|Section de support de la caméra|Cette section s'insère dans le tube et vient admettre la caméra qui pour s'y visser|/|
|![POP1-1-I4](/../doc/kosmos/pictures/productions_of_parts/POP1-1-I4.png)|[I4](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/3Dprint_files/I4_KOSMOS_V3-0.stl)|1|Détrompeur|Fixé à la flange du hublot, il permettra de contraindre les structures internes en rotation et d'éviter que le KOSMOS ne puisse filmer de travers.|/|

​

**1.2 Pour l'extérieur du caisson :**

​

Toutes ces pièces doivent êtres impérativement imprimés en PET. En effet, cette matière est la plus résistante à l'eau de mer parmi les matériaux disponibles en impression 3D FDM. Si vous disposez d'autres technologies, ne pas hésiter à essayer et nous faire part du résultat. Cependant, nous savons que la résine par SLA ne convient pas pour une raison de dureté. Il peut-être intéressant également de travailler à un réducteur sans impression 3D à la fraiseuse uniquement pour rendre la plongée possible à de plus grandes profondeurs.

Nous recommandons un taux de remplissage des pièces qui ne soit pas inférieur à 30%. Toutes nos pièces destinées à l'extérieur du caisson ont un taux de remplissage à 100%.

|    Visuel    |Référence|Quantité|Dénomination|Usage|Conseils d'impression|
|------------------------------------|------|------|-----------------|---------------------|---------------------|
|![POP1-2-R1](/../doc/kosmos/pictures/productions_of_parts/POP1-2-R1.png)|[R1](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/3Dprint_files/R1_KOSMOS_V3-0.stl)|2|Ber|Supporte le tube étanche. Il permet avec R1.2 de soutenir le tube|Positionner un générateur de support pour supporter la partie en porte à faux|
|![POP1-2-R1-2](/../doc/kosmos/pictures/productions_of_parts/POP1-2-R1-2.png)|[R1.2](https://github.com/KonkArLab/KOSMOS/blob/main/hardware/3Dprint_files/R1-2_KOSMOS_V3-0.stl)|2|Fermeture du Ber|Levier pouvant se refermer sur R1 pour bloquer le tube étanche au moyen de vis.|Positionner un générateur de support pour supporter la partie en porte à faux|
|![POP1-2-R2](/../doc/kosmos/pictures/productions_of_parts/POP1-2-R2.png)|[R2](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/3Dprint_files/R2_KOSMOS_V3-0.stl)|1|Support du capteur de positionnement|Réceptacle du capteur de positionnement|/|
|![POP1-2-R3](/../doc/kosmos/pictures/productions_of_parts/POP1-2-R3.png)|[R3](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/3Dprint_files/R3_KOSMOS_V3-0.stl)|1|Embout de croix de Malte|Cette pièce reprend l'effort de la croix de Malte pour la retransmettre à l'arbre qui lui est solidaire au trèpied et donc au sol|Utiliser du support pour maintenir la périphérie en porte à faux ainsi que les alésages.|
|![POP1-2-R4](/../doc/kosmos/pictures/productions_of_parts/POP1-2-R4.png)|[R4](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/3Dprint_files/R4_KOSMOS_V3-0.stl)|1|Entretoise du moteur|Le moteur sera positionné dans ce tube. La hauteur de ce dernier peut-être à modifier pour faire coïncider parfaitement l'alignement du pignon moteur et du premier pignon méné.|/|
|![POP1-2-R5](/../doc/kosmos/pictures/productions_of_parts/POP1-2-R5.png)|[R5](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/3Dprint_files/R5_KOSMOS_V3-0.stl)|1|Bague d'arbre secondaire|R5 permet l'assemblage de l'arbre secondaire (contenant la croix de Malte) avec la boite du réducteur. Elle reprend le serrage de la croix de Malte sans contraindre le reste des pignons|/|
|![POP1-2-R6](/../doc/kosmos/pictures/productions_of_parts/POP1-2-R6.png)|[R6](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/3Dprint_files/R6_KOSMOS_V3-0.stl)|1|Entretoise d'abre primaire|Cette rondelle permet de contraindre les pignons de l'arbre primaire en translation. Sa hauteur doit être ajustée pour ne pas en empécher la rotation libre.|/|
|![POP1-2-R7](/../doc/kosmos/pictures/productions_of_parts/POP1-2-R7.png)|[R7](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/3Dprint_files/R7_KOSMOS_V3-0.stl)|1|Raccord de connectiques étanches du moteur|R7 est l'emplacement où l'on va connecter les câbles du moteur au câble noir cobalt. L'étanchéité sera effectuée en coulant de la résine dans le contenant.|/|
|![POP1-2-R7-2](/../doc/kosmos/pictures/productions_of_parts/POP1-2-R7-2.png)|[R7.2](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/3Dprint_files/R7-2_KOSMOS_V3-0.stl)|1|Couvercle pour le raccord de connectiques étanches du moteur|Permet de fermer R7|/|
|![POP1-2-R8](/../doc/kosmos/pictures/productions_of_parts/POP1-2-R8.png)|[R8](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/3Dprint_files/R8_KOSMOS_V3-0.stl)|1|Raccord de connectiques étanches du capteur de positionnement|R8 est l'emplacement où l'on va connecter les câbles du capteur ILS au câble noir cobalt. L'étanchéité sera effectuée en coulant de la résine dans le contenant.|/|
|![POP1-2-R8-2](/../doc/kosmos/pictures/productions_of_parts/POP1-2-R8-2.png)|[R8.2](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/3Dprint_files/R8-2_KOSMOS_V3-0.stl)|1|Couvercle pour le raccord de connectiques étanches du capteur de positionnement|Permet de fermer R8|/|


_Note  : Toutes les pièces devront être nettoyées de leurs supports et au cours du montage, elles nécessiteront peut-être d'être limées \(papier de verre ou lime à main\) afin de supprimer toutes traces de fils d'anges._

## 2/ Découpe des pièces planes au laser

Le KOSMOS est composé en plus de pièces imprimées en 3D et de visserie Inox de pièces à découper au laser dans des plaques de PMMA et de POM. Ainsi on peut immerger ces pièces dans l'eau sans craindre la pression. Les pièces de l'intérieur du caisson peuvent être aussi imprimées en 3D.  [Les trois fichiers vectoriels évoqués ci-dessous sont disponibles ici. ](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/Laser_cut/)

​

**2.1 Pour l'intérieur du caisson :**

* [Télécharger le fichier de découpe](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/Laser_cut/PMMA-5mm_A5_laser-cut.svg )
* Découper les pièces S1 S2 dans du PMMA de 5mm d'épaisseur \(prévoir l'équivalent de la surface d'une feuille A5\) ;

![POP2-1](/../doc/kosmos/pictures/productions_of_parts/POP2-1.PNG)

​

​

**2.2 Pour l'extérieur du caisson :**

Ces pièces constituent l'enveloppe du réducteur du KOSMOS. On peut les réaliser en PMMA 5mm si on veut voir à travers ou un autre plastique de 5mm comme des plaques de plastique recyclé.

* Il est nécéssaire de sélectionner une plaque de PMMA bien plane de 5mm d'épaisseur \(prévoir l'équivalent de la surface d'une feuille A3\) ;
* [Télécharger le fichier de découpes](https://github.com/KonkArLab/KOSMOS/tree/main/hardware/Laser_cut/PMMA-5mm_A3_Laser-cut.svg) pour lancer une découpe au laser ou à la fraiseuse numérique ;
* Toutes les pièces sont disposées ici de manière à rentrer dans un format A3 \(42\*29,7 cm\).

![POP2-2](/../doc/kosmos/pictures/productions_of_parts/POP2-2.png)

​

​

**2.3 Les pièces en mouvements \(engrenages...\) seront usinés de préférence en POM.**

Ces pièces sont les plus délicates à produire. Il est nécessaire de de s'armer de patience pour réaliser le plus proprement possible ces engrrnages à la fraiseuse à commande numérique dans un matériau comme le POM. Nous avons également fait l'essai avec du PMMA translucide. Ce dernier matériau à l'avantage de pouvoir s'usiner au laser. Ce qui n'est pas la cas du POM.

/!\ ATTENTION : Le POM ne peut être découpé au laser si cette dernière n'est équipé d'une hotte aspirante. Le gaz produit par le POM au passage d'un laser n'est autre que du formaldéhyde (formol). 

* Pour réaliser les découpes au laser, utiliser le fichier présent dans cette archive (hardware/laser_cut/A4_laser-cut.svg). 
* Pour usiner le POM ou un autre matrériau à la fraiseus numérique, utiliser le projet easel présent sur la plateforme inventables : https://www.inventables.com/projects/kosmos_gears


**Recommandatons**
* Il est nécessaire de sélectionner une plaque de POM bien plane de 5mm d'épaisseur ;
* Toutes les pièces sont disposées ici de manière à rentrer dans un format A4 \(21\*29,7 cm\) dans le fichier easel les pièces dépassent légérement de ce format ;
* Utiliser une fraise de 2mm à 2 dents adapté au plastique PP et POM ;
* Paramétrez les vitesses de progressions aux besoins de votre machine ;

​

​

![POP2-3](/../doc/kosmos/pictures/productions_of_parts/POP2-3.PNG)



## 3/ Fabrication du PCB
### 3.1 Stratégie pour le circuit

La fabrication du KOSMOS 3.0 requiert un circuit imprimé (ou PCB). Ce dernier permettra de relier à la carte raspberry les composants et capteurs utiles au fonctionnement. On y retrouvera notamment :
 - Des résistances pour les LED mais aussi pour l'I2C,
 - Les ILS,
 - Un voyant de niveau de batterie,
 - Une horloge (RTC) permettant de mettre la raspberry à l'heure à chaque démarrage,
 - Une série de connectiques qui permettront de se connecter aux alimentations mais aussi de raccorder les différents services. 

**Il existe trois possibilités pour obtenir le PCB (Le détail pour les deux premières méthodes sont disponibles dans les annexes):**

| **Méthode**                          | **Avantages**                                                           | **Inconvénients**                                                                     | **coût totale**                                    |
|--------------------------------------|-------------------------------------------------------------------------|---------------------------------------------------------------------------------------|----------------------------------------------------|
| **Fabrication maison**                   |  - Fabrication d'un seul PCB  - Droit à l'erreur  - Peu coûteux         |  - Processus long  - Nombreuses erreurs possibles  - Nécessite du matériel spécifique |  - 10 à 30 €                                       |
| **Commande à un prestataire spécialisé** |  - Qualité maximale  - Economie de temps à la fabrication et au perçage |  - Obligation de commande groupée (5 ou 10 min)  - Pas de droit à l'erreur             |  - Environ 150 à 200€ pour une dizaine de circuits |
| **Commande au Konk Ar Lab**              |  - Le circuit est issu d'une série testée et validée par l'équipe KOSMOS  |  - Pas de disponibilité certaine                                                      |  - Environ 20€ par circuit                         |

### 3.2 Soudure des composants
 - Souder deux résistances 100ohm sur R1 et R2
 - Souder 6 résistances de 1kohm sur R3,R4,R5,R6,R7,R8
 
![POP3-1](/../doc/kosmos/pictures/productions_of_parts/POP3-1.jpg)

 - Utiliser les chutes de pattes de résistances pour fabriquer les six ponts de masses.

![POP3-2](/../doc/kosmos/pictures/productions_of_parts/POP3-2.jpg)

 - Souder une LED Rouge sur D1 et une LED verte su D2. Attention à la polarité que l'on peut retrouver avec la forme de la LED.


 - Souder trois ils sur SW1, SW2 et SW3 ;


![POP3-3](/../doc/kosmos/pictures/productions_of_parts/POP3-3.jpg)


 - Souder le relai, le témoin de charge et le RTC aux emplacements prédéfinis ; 

![POP3-4](/../doc/kosmos/pictures/productions_of_parts/POP3-4.jpg)

 - Souder 40 broches dupponts ;

![POP3-5](/../doc/kosmos/pictures/productions_of_parts/POP3-5.jpg)
 
 - Souder deux connecteurs JST Male 2 broches sur J2 et J4 en veillant à respecter le sens visible sur les photos ci dessous. 
 - Souder un connecteur JST Male 4 broches  sur J3
 - Souder un connecteur JST Male 5 broches  sur J5

![POP3-6](/../doc/kosmos/pictures/productions_of_parts/POP3-6.jpg)

 - Souder une broches de 3 pins dupont coudés sur J6
 
![POP3-7](/../doc/kosmos/pictures/productions_of_parts/POP3-7.jpg)