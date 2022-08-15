# Synthetic Aperture Radar - A guide for QGIS
1.	Open the QGIS software. (This guide is based on version 3.24)

    Ouvrez le logiciel QGIS. (Ce guide est basé sur la version 3.24)
    
<p align="center">    
  <img src = "https://github.com/asc-csa/Synthetic_Aperture_Radar_Tutorial/blob/main/Option%201%20-%20QGIS/Tutorial%20Images/Image%201.png">
</p>

2.	On the left side of the page click on “New Project”. You can also use Ctrl + N shortcut on windows or command + N on macOS. 

    Sur le côté gauche de la page, cliquez sur « Nouveau projet ». Vous pouvez également utiliser le raccourci Ctrl + N sous Windows ou la commande + N sous macOS

3.	Next, on the left side of the page click on “Open data source manager”. You can also use Ctrl + L shortcut on windows or command + L on macOS. 

    Ensuite, sur le côté gauche de la page, cliquez sur « Open data source manager ». Vous pouvez également utiliser le raccourci Ctrl + L sous Windows ou la commande +     L sous macOS. 
    
 <p align="center">
    <img src = "https://github.com/asc-csa/Synthetic_Aperture_Radar_Tutorial/blob/main/Option%201%20-%20QGIS/Tutorial%20Images/Image%202.png">
  </p>
  
   On the new window of the Open data source manager you can see a list of options on the left side of the page that can be added. In our case, we will be focusing      on the second and third option named “Vector” and “Raster” respectively.

   Dans la nouvelle fenêtre du gestionnaire de sources de données Ouvertes, vous pouvez voir une liste d’options sur le côté gauche. Dans notre cas, nous nous            concentrerons sur la deuxième et la troisième option nommée respectivement « Vecteur » et « Raster ».
   
 <p align="center">
    <img src = "https://github.com/asc-csa/Synthetic_Aperture_Radar_Tutorial/blob/main/Option%201%20-%20QGIS/Tutorial%20Images/Image%203.png"
         </p>
    
4.	To start with Vector you can upload shape file datasets by clicking on the three dots on the right side of the page as circled in the image above and then click on “Add”. As an example, this guide uploads the countries shape file using via this link: http://www.naturalearthdata.com/features/

    Pour commencer avec les vecteurs, vous pouvez ajouter des Shape files en cliquant sur les trois points sur le côté droit de la page comme encerclé dans l’image ci- dessus, puis cliquez sur « Ajouter ». À titre d’exemple, ce guide ajoute le fichier de forme des pays en utilisant via ce lien:              http://www.naturalearthdata.com/features/
  
  <p align="center">
      <img src = "https://github.com/asc-csa/Synthetic_Aperture_Radar_Tutorial/blob/main/Option%201%20-%20QGIS/Tutorial%20Images/Image%204.png">
            </p>
    

        a.	Click on “110” option as shown in the image. 

        Cliquez sur l’option « 110 » comme indiqué dans l’image.


        b.	Download the countries file on your computer and then extract the content of the zip file. 

        Téléchargez le fichier des pays sur votre ordinateur, puis extrayez le contenu du fichier zip.

        c.	For uploading, select the file with .shp document in the open data source manage. 

        Pour ajouter, sélectionnez le fichier avec le document .shp dans la gestion des sources de données ouvertes. 

5.	Next, to upload the raster file, click on “Raster” on the left side of the page on the “Open data source manager” window as seen on the image under point 3. The uploading can be done similar to step 4 by clicking on the three dots on the right side of the page and then click on “Add”. As an example, this guide uses the open data BC fire taken from this page. Any one of these documents can be selected and downloaded. The zip file contains a folder called imagery that contains the raster files. 
 Index of /users/OpenData_DonneesOuvertes/pub/BC fires (asc-csa.gc.ca)

    Ensuite, pour ajouter le fichier raster, cliquez sur « Raster » sur le côté gauche de la page dans la fenêtre « Open data source manager » comme on le voit sur       l’image sous le point 3.  Vous pouvez les ajouter de la même manière que l’étape 4 en cliquant sur les trois points sur le côté droit de la page, puis en cliquant    sur  « Ajouter ». À titre d’exemple, ce guide utilise les données ouvertes BC fire tirées de cette page. N’importe lequel de ces documents peut être sélectionné et    téléchargé. Le fichier zip contient un dossier appelé imagerie qui contient les fichiers raster. 

6.	At this stage, after uploaded the shape file and the Raster file, the files should be seen on the main page under layers as seen in the image below.  The label (i.e. Canada – Based on the location) can be added by right clicking on the name of the shape file as shown via the arrow and click on “Show Label”.  

    Après avoir téléchargé le fichier de forme et le fichier raster, les fichiers doivent être vus sur la page principale sous « Layers » comme indiqué dans l’image ci-dessous. L’étiquette (Canada – En fonction de l’emplacement) peut être ajoutée en cliquant avec le bouton droit de la souris sur le nom du fichier de forme, comme indiqué via la flèche, puis en cliquant sur « Afficher l’étiquette ».  
    
 <p align="center">
    <img src = "https://github.com/asc-csa/Synthetic_Aperture_Radar_Tutorial/blob/main/Option%201%20-%20QGIS/Tutorial%20Images/Image%205.png">
       </p>
   

7.	By zooming out, you would be able to see the map and the location of the raster file as expected in British Columbia Canada. 
En effectuant un zoom arrière, vous serez en mesure de voir la carte et l’emplacement du fichier raster comme prévu en Colombie-Britannique Canada.

<p align="center">
  <img src = "https://github.com/asc-csa/Synthetic_Aperture_Radar_Tutorial/blob/main/Option%201%20-%20QGIS/Tutorial%20Images/Image%206.png">
    </p>

## Notes:
•	QGIS software runs slow. If you are seeing a blue loading bar at the bottom of the page it means that things are loading. It is best to not continue until the loading is done. 

Le logiciel QGIS fonctionne lentement. Si vous voyez une barre de chargement bleue au bas de la page, cela signifie que les choses se chargent. Il est préférable de ne pas continuer tant que le chargement n’est pas terminé.

•	The label might work but the color might not be visible or be a black text on a black background. You can change that by clicking on “style manager” and then select the “Label setting” tab. 

L’étiquette peut fonctionner, mais la couleur peut ne pas être visible ou être un texte noir sur fond noir. Vous pouvez changer cela en cliquant sur « gestionnaire de style », puis sélectionnez l’onglet « Paramètres d’étiquette ».
<p align="center">
  <img src = "https://github.com/asc-csa/Synthetic_Aperture_Radar_Tutorial/blob/main/Option%201%20-%20QGIS/Tutorial%20Images/Image%207.png">
 </p>

