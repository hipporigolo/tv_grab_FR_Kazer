tv grab FR Kazer
================

Il s'agit d'un simple script bash utilisé pour récupérer les infos EPG (guide électronique des programmes) destiné à être transmises vers le logiciel TVHeadEnd.
Télécharge les infos EPG via le site http://www.kazer.org

Installation
------------
- Dans le script remplacez VOTRE_CLEF par votre clef kazer (disponible dans l'onglet Mes Chaînes).
- Placer le script à l'endroit approprié (/usr/bin/ si utilisé sur un NAS Synology).
- Tester le script en le lancant à l'aide de la commande tv_grab_kazer, vous devez voir sur l'écran des données xml.
- Configurer TVHeadEnd en lui indiquant dans Internal Grabber XMLTV : France Kazer
