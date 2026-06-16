# Manuel d'export IFC Archicad

Lorsque vous exportez un IFC, gardez à l'esprit ce qui est pertinent pour votre export IFC. Le fichier IFC peut être volumineux et difficile à traiter s'il contient beaucoup d'informations. Il est donc important de ne pas exporter d'informations inutiles. Dans ce rapport, vous trouverez différents conseils pour filtrer votre exportation IFC dans Archicad.

Pour exporter l'ensemble du projet. Vous devez vous placer en vue 3D. Assurez-vous que vous utilisez le bon traducteur.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056907/3ed1a2d39b9276705eca2953/image-0.png?expires=1781092800&signature=727a3898f989f68df24662a23ff14957bf59781f3bc27d84f57a5035967a4361&req=dicmFsx4lIFYFb4V1XW4gSsqFAIns%2BLVOCRTS1jsXxQqqssEUzUY2qHudMas%0AwiXzkKrZCxh05B46OxMksUBk8A%3D%3D%0A)

Cliquez sur le bouton des options pour voir un résumé de vos paramètres d'export IFC. Sous le filtre de modèle, vous pouvez également choisir de filtrer davantage.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056913/07e3a491c52e1af168324efe/image-1.png?expires=1781092800&signature=5003112051c8e8137b5bd8a0b7928b9d95227b2fe1f992494c057307472e3fe0&req=dicmFsx4lIBcFb4V1XW4gbS3lr63ymIv%2Bs4YYj8FOwEC8e03LRJ%2F1CBZuT%2F3%0A3q1TIGFHJXIvB8QkpSEHWMf08w%3D%3D%0A)

**Paramétrage de l'export IFC**

La boîte de dialogue Traducteurs IFC vous permet d'afficher ou de modifier les paramètres des traducteurs, ou de créer de nouveaux traducteurs.

Si vous souhaitez modifier votre export IFC, il est recommandé de dupliquer l'un des traducteurs prédéfinis afin de ne pas perturber l'un des traducteurs par défaut.

Cliquez sur nouveau > Dupliquer  > sélectionnez le traducteur que vous souhaitez dupliquer.

Si vous souhaitez fusionner l'IFC, vous pouvez le faire sous la même bannière.

![image-2.png](https://catenda-as.intercom-attachments-1.com/i/o/271056923/31605f86d13eb419fbb6b898/image-2.png?expires=1781092800&signature=a48f835dcf19dd3d20fafae1efca1ed8b731d7bbda7652f171b36ce73a05c3bb&req=dicmFsx4lINcFb4V1XW4gQA38htLLYIQOAE6xdxWgLSyC37l6Z8dKATf2fdr%0Ae0nMCShTSpN%2BRiDkcmZGbegXzQ%3D%3D%0A)

---

**Différent paramétrage de l'export**

1. Le filtre de modèle vous permet de filtrer ce que vous voulez exporter par différents pré-réglages.

2. Le type mapping vous permet de choisir le type d'IFC sous lequel chaque élément est exporté.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056934/9c3eded88c73ec7e25ba4f4c/image-3.png?expires=1781092800&signature=4254158355f2ae65d52a4d2bf021496d0121849c85ee0ea279f94b6244161f56&req=dicmFsx4lIJbFb4V1XW4gfe0uzqiQldsKSXT2h%2FU0X1wYWMro6zFlyz8PDvw%0AQqWqqhwtmS%2BuEGqYeUXFypF0ZA%3D%3D%0A)

3. La conversion de la géométrie vous permet de choisir le type de géométrie que vous souhaitez exporter.

4. Le mapping des propriétés vous permet de définir des critères basés sur les types.

5. La conversion des données vous permet de choisir le type de données que vous souhaitez exporter du modèle.

6. La conversion des unités vous permet de choisir les unités de mesure que vous souhaitez exporter dans votre IFC.

---

**Type Mapping for IFC Export**

Lorsqu'un IFC est exporté, un type IFC est attribué à tous les éléments du modèle.

Si vous sélectionnez le traducteur IFC que vous souhaitez utiliser, vous pouvez ensuite aller dans le mapping de type et cliquer sur le bouton "Map IFC Types for import" pour gérer le type de mapping de que vous souhaitez pour votre IFC exporté.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056940/57204561a8ccd3176e04d381/image-4.png?expires=1781092800&signature=8b2550d1949b9bcf2166050a67b0157d580cbf7308ffb90554f3424dd1d003dd&req=dicmFsx4lIVfFb4V1XW4gRT3Fi9%2FTyVfVfmhSH8DRamqc%2FFvbJuyRfAk7nhc%0AqQSucfuCAs4ih7jWnNIOcahFzg%3D%3D%0A)

Type mapping mainly have to different options to sort your IFC types by.

Element type:

Each element is automatically assigned a basic IFC type. You can se each element\`s assigned IFC type in project manager and in element settings.

Classification:

This method allows more flexible and detailed IFC type mapping, according to specify classification standards. Zone and opening elements are set to a fixed IFC type. IFCSpace and IFCOpeningElements.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056943/3731267714f7fa4930235354/image-5.png?expires=1781092800&signature=4ac137b61b9aaca454a4d031b64b1b3aaa697ae7457151121487d7eb18d4a218&req=dicmFsx4lIVcFb4V1XW4gaWRyW4wYZJh5THfO3CBEboYzzFw%2Fd1eDlkOJ%2FYT%0AeiJvrhqWfZiO2GWM0q56Mt8alg%3D%3D%0A)

---

**Property mapping**

Inside property mapping (File > IFC > Interoperability > Property Mapping) you can choose what kind of version of IFC you want to export. you have the standard IFC2x3 and the standard IFC4. You can also add psets to export with your IFC. If you do this you should make a duplicate of the IFC schema you choose.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056948/23de75ed67ebb8120f9ef63d/image-6.png?expires=1781092800&signature=2314c41343dba2f942862c4fb165cc070dcfa98658050e223df6a2fe8cecd606&req=dicmFsx4lIVXFb4V1XW4gX0eUSHQutujQy5PjUI1pttrN6jFy0gn5Wmw5l2r%0AvnVe595gd%2F5OcH05ksfM1MFdjA%3D%3D%0A)

After you’ve made a duplicate of your standard IFC you can add the properties you want to that new preset by selecting the IFC schema and clicking on _Map IFC Properties for Export_.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056955/8fd00cf142ae8d45a0fb7df1/image-7.png?expires=1781092800&signature=e66c9d5f53bbfae153da829dffb45bc582bc112cc3198628772d8798ecf6aabf&req=dicmFsx4lIRaFb4V1XW4gct4hmNJw3Cxmyiu4iXSGkjI8COu4X1sCPk6Gl1D%0AoF5KclTEvV0MOwQ%2BOYYH9OHrDw%3D%3D%0A)

**Data conversion for IFC export**

Under data conversion you select what kind of data in addition to geometry you want to get out of your IFC export. check the boxes of what you want to export.

Element parameters reads the Archicad element parameter and converts it to IFC quantities or IFC properties. Depending on their type. By choosing this option you significantly increase the file size.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056963/bf0e775372c6fc6418e2727a/image-8.png?expires=1781092800&signature=7ae773823614711d50cdd4f7780fab8d8cc35ab2e7acad5a5c0474d4a31c0b92&req=dicmFsx4lIdcFb4V1XW4geoCNQZckbiMZP52Jc8%2BroBx3DCAZ7qhaLrtGOkQ%0AFPsbhSQya9mPEkHsU%2FfnXUXAaA%3D%3D%0A)

IFC Base Quantities reads the parameters of size, area and volume. If you don’t check this box off you may have trouble importing your IFC to Catenda Hub.

---

**Exporting grids in the IFC**

Sometimes you want the grids exported as well to be able to see them in Catenda Hub.

Go to the model filter for IFC Export and make sure the checkbox “Grid system and Elements” are checked.

![](https://catenda-as.intercom-attachments-1.com/i/o/271056967/a5906d5103e06c85f450f730/image-9.png?expires=1781092800&signature=3a57123c1e36ed368dda2ace93eedada56dfdcdf15dc0758d05956a4b252e149&req=dicmFsx4lIdYFb4V1XW4gdOixTR1uP%2BLnKVfHKCnuIne5TpHJDkHqYAkaNdU%0ASCC8qRvvbFCiGISg7JnUXeSwcw%3D%3D%0A)
