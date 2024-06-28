icon:material/waves
# Déploiement de Kosmos

## 1- Démarage

## 2- Remise en route
Cette partie explique les étapes de remise en route du système KOSMOS après un temps d'unitilisation.

### 2.1- Mise à jour du software
### Vérification de l'OS
- Vérifier la version de l'OS sur la carte SD de la Raspeberry Pi.
La dernière version de l'OS est Debian 12, (si la version est différente de la dernière version, réinstaller l'OS)
- Taper dans un terminal
```
cat /ect/os-release
```

### Vérification du programme
- Vérifier ensuite que le code est à jour
Toujours dans le terminal, vérifier que vous êtes bien sur la branche `dev_stereo` et récupérer la dernière version du code
```
git checkout dev_stereo //Vérifier la branche sur laquelle on se trouve
git pull //Récupérer la dernière version du code
```
- Vérifier que les dossiers CSV et Vidéo de la clé USB sont bien vides pour ne pas avoir de porblème de stockage

### 2.2- Vérification de la partie hardware
### Vérification des engrenages moteur
- Ouvrer le caisson des engrenages du moteur
- Faire tourner les engrenages manuellement pour s'assurer que rien ne bloque

### Mise au point de la caméra

???+ Note

        Pour être optimal, les réglages doivent s'effectuer dans une atmosphère lumineuse


- Nettoyer le filtre de la caméra et l'objectif avec un produit pour nettoyer les lunettes et un mouchoir  
  ![objectif](../../pictures/deployment/objectif.jpg){ width="300"} ![filtre_lens](../../pictures/deployment/filtre_lens.jpg){ width="300"}
- Démarrer la caméra
- Régler l'ouverture de l'objectif entre 2.8 et 4  
   ![reglage_objectif](../../pictures/deployment/reglage_objectif.jpg){ width="300"}
- Placer une mire à environ 5m  
   ![mire](../../pictures/deployment/mire.jpg){ width="300"}
- Connectez vous à l'interface web (10.42.0.1)
- Vérifier avec le live ou le preview de la caméra que la mire est net, modifier le focus si nécessaire
- Serrer la vis pour fixer les réglages de la caméra  
   ![vis_reglage](../../pictures/deployment/vis_reglage.jpg){ width="300"}
- Vérifier que l'image est toujours net et que les paramètres n'ont pas bougés en serrant la vis

### Lubrification des joints

???+ Warning

        Cette étape est indispensable et est à réaliser avec soin, elle assure l'étanchéité du système

- Déviser les connecteurs des caps  
  ![joints](../../pictures/deployment/joints.jpg){ width="300"}
- Vérifier qu'il n'y ait pas de cheveux sur vos joints  
- Graisser chaque joint (la couche de graisse doit être fine et homogène)  
  ![graisse](../../pictures/deployment/graisse.jpg){ width="300"}
- Reviser les connecteurs sans oublier les joints  
  ![joints_valve](../../pictures/deployment/joints_valves.jpg){ width="300"}
- Serrer pour assurer l'étanchéité  
  ![serrage_exte](../../pictures/deployment/serrage_exte.jpg){ width="300"}
  ![serrage_inte](../../pictures/deployment/serrage_inte.jpg){ width="300"}

- Déviser les caps des extrémitées (hublot transparent, et caps noir)
- Répéter les opérations ci dessus  
  ![joint_top](../../pictures/deployment/joint_top.jpg){ width="300"}

- Enlever les joints autour des "entretoises"
- Répéter les opérations ci dessus  
  ![joint_entretoise](../../pictures/deployment/joint_entretoise.jpg){ width="300"}

### Encapsulation
- Fermer le caisson de kosmos  
   <img src="https://github.com/Hclothilde/Documentation_KOSMOS/blob/d7f3a26780ae5b1e7ddae37c8ff18bae6e9926e9/docs/pictures/assembly_guide/ventilateur_cable.jpg"  width="300"/>

### Vérification du fonctionnement géneral de Kosmos
- Démarrer la caméra
- Connectez vous à l'interface web (10.42.0.1)
- Vérifier les paramètres dans l'onglet config:
   - 00_system_mode :
   - 01_system_record_button_gpio :
   - 02_system_stop_button_gpio :
   - 03_system_led_b :
   - 04_system_led_r :
   - 05_system_shutdown :
   - 06_system_moteur :
   - 10_motor_esc_gpio :
   - 11_motor_power_gpio :
   - 12_motor_button_gpio :
   - 13_motor_vitesse_min : 
   - 14_motor_vitesse_favorite : 
   - 15_motor_pause_time : 
   - 20_csv_step_time : 
   - 21_csc_file_name : 
   - 30_picam_file_name : 
   - 31_picam_resolution_x : 
   - 32_picam_resolution_y : 
   - 33_picam_preview :
   - 34_picam_framérate : 
   - 35_picam_record_time :
   - 36_picam_conversion_mp4 :
   - 37_picam_awb :
     
- Vérifier avec le live que la caméra est positionnée de façon à ce que l'image soit droite
- Démarer une vidéo
- Observer si le moteur tourne correctement
- Arreter la video et vérifier que l'enregistrement c'est bien passé (création d'un fichier cvs et conversion du fichier vidéo h264 en mp4)


  