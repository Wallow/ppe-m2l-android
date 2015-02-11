..author: Guilhem MAS-PAITRAULT
.. sectnum::
   :depth: 2

########################
PPE M2L Back-End Project
########################

.. image:: https://badge.fury.io/gh/Erwhann-Rouge%2Fppe-m2l-android.svg
    :target: http://badge.fury.io/gh/Erwhann-Rouge%2Fppe-m2l-android

Projet de PPE pour le BTS SIO de 2015, en lien avec le projet `PPE M2L
Front-End Project <https://github.com/Ekitchi/ppe-mdl-frontend>`_.

But du projet :
===============
Réaliser le client Android d'un serveur REST dans le contexte de la Maison des Ligues
de Lorraine (M2L).

Dépendances :
=============
* Android SDK 16 minimum

Installation :
==============
* Cloner le dépot : ``git clone https://github.com/Erwhann-Rouge/ppe-m2l-android.git``

Fonctionalités :
================

Site vitrine :
--------------
But :
^^^^^
Permet la navigation et la consultation de données.

Actions :
^^^^^^^^^
* Créer un modèle de données simple.
* Créer les objects PHP pour les gérer.

L'affichage et la navigation seront pris en charge par l'équipe front-end.

Interface Administration :
--------------------------
But :
^^^^^
Permet l'ajout de données au site via une interface de type WYSIWYG.

Actions :
^^^^^^^^^
* Faire évoluter du modèle de données et les objets php pour gérer
  l'enregistrement de données.

La création des formulaires et de l'espace administrateur sera prise en
charge
par l'équipe front-end.

Module de gestion des users :
-----------------------------
But :
^^^^^
Permet l'inscription et la gestion des utilisateurs, ainsi que de leurs droits
associés. Permet également à chaque utilisateur d'éditer les informations le
concernant.

Actions :
^^^^^^^^^
* Ajouter une table ``users`` ainsi que l'objet associé.
* Implémenter une gestion des droits utilisateurs.

La création des formulaires supplémentaires de l'interface administrateur sera
prise en charge par l'équipe front-end. De même que l'espace membre.

Module d'administration de ligue :
----------------------------------
But :
^^^^^
Permet l'édition des infos relatives à une ligue par son administrateur dédié.

Actions :
^^^^^^^^^
* Création du statut d'administrateur de ligue.
* Création des objets permettant

Les formulaires de gestion de ligue sont évidemment du ressort de l'équipe
front-end.

Module SOS partenaire :
-----------------------
But :
^^^^^
Permet aux joueurs ou équipes de planifier et organiser des rencontres
amicales.

Actions :
^^^^^^^^^
* A voir

