TP : Injection des Dépendances – Framework IOC
Nom : Wissal Biyi
Filière : BDCC
Module : Architecture JEE / Spring IOC

Objectif du TP:

L’objectif de ce TP est de comprendre le principe de l’Injection des Dépendances (IOC) et de réduire le couplage entre les différentes couches d’une application Java.

Architecture du Projet:
Le projet est composé de trois couches principales :
Couche DAO : accès aux données
Couche Métier : traitement métier
Couche Présentation : exécution de l'application
<img width="420" height="609" alt="image" src="https://github.com/user-attachments/assets/9193c507-d7fe-47ad-a00c-5b005ec48714" />

Partie 1 : Injection des dépendances
1. Création de l’interface IDao
   Interface permettant de récupérer les données.
   <img width="494" height="153" alt="image" src="https://github.com/user-attachments/assets/0a3e132b-955c-484f-ac33-20bab8afac8f" />
   2. Implémentation DaoImpl

Classe qui implémente IDao et retourne des données simulées.
<img width="512" height="220" alt="image" src="https://github.com/user-attachments/assets/a7204115-1ed0-405e-8529-3390f442b34c" />


3. Création de l’interface IMetier
   <img width="435" height="177" alt="image" src="https://github.com/user-attachments/assets/bf141b03-94c6-43bb-9ae5-2111f9a10b83" />


Interface contenant la méthode calcul().

4. Implémentation MetierImpl
5. <img width="580" height="572" alt="image" src="https://github.com/user-attachments/assets/ef451f6d-6de8-42aa-ad3a-6f74998f7ea6" />


Utilisation du couplage faible via l’interface IDao.



