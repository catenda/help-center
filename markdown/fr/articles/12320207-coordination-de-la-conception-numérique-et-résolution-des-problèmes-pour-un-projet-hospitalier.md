# Coordination de la conception numérique et résolution des problèmes pour un projet hospitalier

> Secteur : Construction de santé / BIM (modélisation des informations du bâtiment) Persona : David, coordonnateur BIM pour un grand entrepreneur général.

**Scénario :** David gère le modèle de construction numérique pour une nouvelle aile d'hôpital. C'est un projet extrêmement complexe impliquant des dizaines d'équipes spécialisées. Les modèles architecturaux, structurels et MEP (Mécanique, Électricité, Plomberie) sont constamment mis à jour par différents cabinets de conseil. La responsabilité principale de David est de fédérer (combiner) ces modèles dans Catenda Hub pour identifier et résoudre les clashes _avant_ qu'ils ne deviennent des problèmes coûteux sur le chantier.

Lors de sa vérification de coordination hebdomadaire, il doit enquêter sur un problème critique potentiel signalé par le gestionnaire de site : la structure de support d'une grande machine IRM au deuxième étage pourrait ne pas s'aligner avec les derniers plans architecturaux et électriques.

**Solution utilisant Catenda Hub :** David utilise un flux de travail précis dans Catenda Hub pour gérer efficacement cette tâche de coordination complexe.

### **1. Centralisation des données sur la page « Modèles » :**

D'abord, David accède à la **page Modèles**. Ici, il peut voir tous les derniers modèles IFC téléchargés par les différentes équipes, chacun avec son numéro de révision et son statut. Il sélectionne les modèles pertinents pour la zone d'intérêt :

- ARCH-Hospital-Wing-rev04.ifc
- STRUCT-MRI-Support-rev02.ifc
- MEP-Elec-Room204-rev05.ifc

Il ouvre les trois dans la **Visionneuse 3D** fédérée. La plateforme les combine en un seul jumeau numérique navigable de cette section de l'hôpital.

### **2. Identification du clash et création d'un « Signet » :**

En naviguant dans le modèle 3D, David repère immédiatement le problème. Les supports en acier structurel de la machine IRM pénètrent un mur où les architectes ont maintenant placé une salle principale de commutation électrique. De plus, la pénétration du sol pour les tuyaux de refroidissement de la machine entre en conflit avec un chemin de câbles nouvellement acheminé. Pour communiquer clairement ce problème complexe en plusieurs parties, une simple capture d'écran ne suffira pas. Au lieu de cela, David utilise la fonctionnalité **Signets** :

- Il isole uniquement les éléments qui clashent : les supports en acier, le mur spécifique, le disjoncteur, et le chemin de câbles.
- Il utilise une coupe de section pour créer une vue claire et dégagée du point de collision.
- Il enregistre cet état précis — y compris l'angle de caméra, la visibilité des objets et la coupe de section — comme un signet intitulé « **Clash : Support IRM vs. Salle électrique 204** ».

### **3. Création et attribution d'un problème exploitable :**

Une fois le signet créé, David crée un **Problème** (ou « Sujet » dans Catenda Hub). Dans la description du problème, il écrit : « @Architectes, @Structurel, @MEP - Nous avons un clash critique entre la structure de support de l'IRM et la disposition révisée de la salle électrique. Le signet joint montre l'emplacement exact et les éléments impliqués. Le Structurel doit confirmer si les supports peuvent être déplacés, et le MEP doit vérifier un nouvel itinéraire pour le chemin de câbles. Veuillez fournir une solution avant la fin vendredi. » Il relie le problème directement au signet qu'il vient de créer.

### **4. Conduite de la résolution collaborative :**

L'architecte en chef, l'ingénieur structural et le coordonnateur MEP reçoivent une notification instantanée. Lorsqu'ils cliquent sur le lien dans le problème, Catenda Hub ouvre le modèle 3D et les amène à la **vue exacte que David a enregistrée dans le signet**. Il n'y a pas d'ambiguïté ni de temps perdu à essayer de trouver le problème. Ils utilisent la section des commentaires du problème pour discuter des solutions. L'architecte confirme que la position de la salle électrique est fixée. L'ingénieur structural effectue une analyse rapide et propose une conception de support révisée, en joignant un croquis. Le coordonnateur MEP confirme qu'il peut réacheminer le chemin de câbles.

### **Résultats et avantages :**

En exploitant les pages Modèles et Signets, David a transformé un problème potentiellement chaotique et coûteux en un problème structuré, traçable et rapidement résolu.

- **Clarté absolue :** Le signet fournissait une « source unique de vérité » pour le problème, éliminant toute mauvaise interprétation qui pourrait résulter d'e-mails ou d'appels téléphoniques.
- **Économies de temps importantes :** Les parties prenantes du projet ont résolu le problème en quelques heures de collaboration numérique, économisant des jours ou même des semaines par rapport aux méthodes traditionnelles d'échange de fichiers.
- **Prévention des coûts :** L'identification numérique de ce clash a prévenu les coûts massifs de démolition sur site, de remaniement et de retards de projet qui se seraient produits si l'acier avait été érigé au mauvais endroit.

### **Responsabilité améliorée :**

L'ensemble du processus de découverte, de communication et de résolution est documenté dans un seul problème, créant une piste d'audit claire pour le dossier du projet.
