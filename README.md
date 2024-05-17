# HappyHourProject
## Projet Happy Hour Toulouse
### Description du Projet
Ce projet a pour but de collecter, analyser et présenter les informations sur les happy hours des bars à Toulouse. Le processus comprend les étapes de web scraping, d'analyse de données, de visualisation, et d'envoi des résultats par e-mail.

Étapes du Projet

## Partie 1 : Extraction des Données

 - Scraping des informations
 - URL de la source : Schlouk Map - Toulouse Happy Hour
   
### Données à extraire :

 - Nom du bar
 - Heures d'ouverture
 - URL de la page spécifique du bar (lien href)
 - Services disponibles (uniquement les services "oui")
 - Prix des boissons pendant et hors happy hour
   
### Stockage des données

Les données extraites seront stockées dans un DataFrame pandas pour une manipulation et une analyse ultérieures.

## Partie 2 : Analyse des Données

Analyse des prix
Identifier les cinq bars proposant les meilleures offres durant les happy hours.
Critères d'analyse : Comparaison des prix des boissons pendant et hors happy hour.

## Partie 3 : Rapport par E-mail

Configuration de l'envoi d'e-mails
Suivre le tutoriel de Mailtrap pour configurer l'envoi d'e-mails avec Python : Tutoriel Mailtrap
Utiliser les bibliothèques smtplib et email.mime pour envoyer les e-mails.
Préparation de l'e-mail
L'e-mail doit être au format HTML.
Inclure le top 5 des meilleurs deals en happy hour à Toulouse, basé sur les analyses effectuées.
Utiliser les scripts d'exemples fournis pour la mise en forme et l'envoi de l'e-mail.

## Configuration et Installation
### Prérequis
Python 3.x
Bibliothèques Python : pandas, requests, beautifulsoup4, smtplib, email.mime
