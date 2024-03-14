
# PROJET 2 : SHARE APP 

## NOM ET PRENOM :
- Massinissa LEKHAL 

## QUELQUES EXPLICATIONS SUR LE PROJET : 

- Développement d'une application de partage qui requiert une authentification pour accéder aux fonctionnalités. Les informations des utilisateurs sont stockées dans une base de données itemUSersBase pour permettre une reconnexion facile. L'application permet de créer un objet et de l'emprunter, ainsi que de le libérer. La libération d'un objet est uniquement possible pour l'utilisateur qui l'a emprunté. Il est possible pour chaque utilisateur d'emprunter jusqu'à deux objets maximum. De plus, un utilisateur peut supprimer un ou plusieurs objets, à condition qu'ils ne soient pas actuellement empruntés par quelqu'un d'autre.

## TESTER L'APPLICATION : 

- Il faut se placer dans shareApp , la racine du projet et taper la commande : 
 1. ``` npm install ``` pour installer le dossier ```node_modules``` 
 2. ``` mkdir baseDoc ``` pour créer le dossier baseDoc qui contiendra notre base de donne 
 3. ``` nodemon``` pour lancer l'application .
 4. ``` mongod --dbpath baseDoc ``` pour lancer notre base de donnes avec mongoDb 
 5. Aller dans un navigateur et taper ``` http://localhost:3000/ ``` 

 - Ajout de la fonctionalité socket.io pour rafraichir les ajouts et les suppressions 
 

 