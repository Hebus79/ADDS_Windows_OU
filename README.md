# ADDS_Windows_OU

Quête WCS ADDS Windows Organisation Units


# 1) Dans le gestionnaire de serveur sur l'Active Directory, après un clic droit sur le serveur choisir " Utilisateurs et ordinateur Active Directory" dans le menu déroulant

![ADDS_OU](https://github.com/Hebus79/ADDS_Windows_OU/blob/main/images/1-Gestionnaire_de_serveur.png)



## 2) Création d'OU
Après un clic droit sur wilders.lan, choisir "Nouveau" puis "Unité d'organisation"

![ADDS_OU](https://github.com/Hebus79/ADDS_Windows_OU/blob/main/images/2-Creation_OU.png)


## 3) Création d'un groupe
Après un clic droit sur l' OU "wilders_students", choisir "Nouveau" puis "Groupe"

![ADDS_OU](https://github.com/Hebus79/ADDS_Windows_OU/blob/main/images/3-Creation-groupe.png)

Créer le groupe "Students"

![ADDS_OU](https://github.com/Hebus79/ADDS_Windows_OU/blob/main/images/3-2-Creation-groupe.png)



## 4) Création d'un utilisateur

Après un clic droit sur l'OU "Wilders_students", dans le menu déroulant choisir "Nouveau" puis "Utilisateur"
![ADDS_OU](https://github.com/Hebus79/ADDS_Windows_OU/blob/main/images/4-Creation_utilisateur.png)

Créer un nouvel utilisateur "Wilder1" par exemple

![ADDS_OU](https://github.com/Hebus79/ADDS_Windows_OU/blob/main/images/4-2-Creation_utilisateur.png)


## 5) Rattacher l'utilisateur a un groupe

Dans les propriétes du groupe "Students" choisir "Membres" et ajouter le nouvel utilisateur à ce groupe

![ADDS_OU](https://github.com/Hebus79/ADDS_Windows_OU/blob/main/images/5-Ajout_utilisateur_au_groupe.png)


