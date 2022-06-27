Configurer le projet java

Installer le JDK 1.8 
C:\Program Files\Java et vérifier la bonne version

Configuration de l'IDE
Installer STS 3.9
Extraire le zip
Suivre le chemin sts-bundle\sts-3.9.1.RELEASE
Et lancer l'application STS

Importez le projet dans votre IDE
Lancer STS ou bien eclipse 
Cliquer en haut a gauche sur importer
selection Maven > projet maven existant et cliquer sur suivant
Clique droit sur projet et selection properties
Selectionner “Java build path” puis “Libraries”
Editer “JRE System Library” et selectionner “Execution Environment” pour 1.8 et cliquer sur fin.
Cliquer sur “Order and Export” verifier “JRE System Library” et cliquer sur appliquer .

Installer MYSQL8
Importez la base de donnée dans MYSQL workbench
Ouvre workbench et connecter avec MySQLServer
Cliquer sur server et appuyer sur “Data Import”
Choisir l'option “Import from self-Contained file” et chercher la location et cliquer sur le boutton importer
Rafraichir le la base de donnée 

Télécharger Tomcat 8.5


Enfin lancer le projet



