# hackathon-hackgend
Documentation du 1er Hackathon de la DGGN autour d'une web app de géolocalisation

##Geo-Secours
https://github.com/sicardf/Geo-Secours

##Gendloc++
https://github.com/FunkySayu/GendLoc-

## Socialgendmap
https://github.com/GuillaumeLe/socialgendmap

##FlowTracker
https://github.com/MrDarkSkil/FlowTracker

---

#hackgend le hackathon gendarmerie

Dates : du 18 au 20 avril 2016


##Introduction

La Direction générale de la gendarmerie nationale (DGGN) accueille du 18 au 20 avril 2016 le premier Hackathon de la gendarmerie nationale.

Organisé en partenariat avec l'Agence du patrimoine immatériel de l’État (APIE), cet événement a pour objectif de faire travailler en équipes des étudiants d'écoles d'ingénieurs autour de l'application web Gendloc (conçue par l'adjudant Olivier Favre du PGHM Le Versoud) et d'en exploiter le potentiel.

Ce challenge doit être pour la gendarmerie l'occasion de consolider les liens avec ces écoles dans le domaine de l'innovation.


###Les thèmes

    Thème 1 : mieux interagir avec la personne en détresse à partir du téléphone portable

    Thème 2 : mieux appréhender et utiliser l'environnement de la personne en détresse, à partir des téléphones portables à proximité

    Thème 3 : collecter des informations de masse utiles aux interventions en cas de situation exceptionnelle


###Les équipes


####EISTI / 42 (salle 2013)
Projet GendLoc ++

Sujet 1 : Amélioration des moyens de communication de GendLoc, renvoi de flux vidéo ou photo
Sujet 2 : Clustering d'appels

####ENSTA (salle 2011)
Projet : SocialGendMap (SGM)

Sujet 1 : Contextualisation "réseaux sociaux" de l'information de localisation 
Sujet 2 : Broadcast des téléphones dans la zone

####Epitech Nantes / 42 (salle 2010)
Projet AUXILLIUM

Sujet 1 : Interaction bi-directionnelle
Sujet 2 : Contextualisation de l'incident par des volontaires

####Epitech Montpellier (salle 2009)
Projet Geo Secours

Sujet 1 : 112 en ligne, alerte sans téléphone...
Sujet 2 : plateforme pour l'agrégation et la mise en forme de différentes données (Images, Textes et Localisations) depuis les réseaux sociaux.

###Epitech Nice (salle 2008)
Projet Flow Tracker

Sujet 1 : Page de localisation en fonction du débit
Sujet 2 : Contact des personnes aidantes proches

###Premières restitutions 10h00

Epitech Montpelier
Présentation de l'application et du backoffice, démo en live

####Epitech Nice

Sujet 1 : FlowTracker, amélioration de l'existant gendarmerie adaptation de l'interface en fonction de la bande passante
Sujet 2 : les secours ont besoin d'une aide extérieure

####EISTI / 42 
Sujet 1 : Pendant la communication en phonie, le CORG envoir un SMS -> interface HTML (comme GendLoc) puis l'opérateur demande à la victime d'effectuer certaines actions : 

    télécharger une fiche reflexe

    prendre vidéo (diffusion en direct)

    prendre une photo pour l'envoyer

Amélioration de l'interface utilisateur de gendloc

####ENSTA
Sujet 1 : thème 2, sur une carte des informations de contexte : réseaux sociaux, géographie ou données gendarmerie.
Une seule carte : twitter, instagram, facebook, periscope, possibilité de clustering
Technologies :

    HTML/CSS

    javascript pour le gros de site. Toutes les fonctions liées à la carte sont réalisées à l'aide de leaflet et ses lirairies : leaflet-pulse, leaflet-StyledLayerControl, leaflet-draw, leaflet-markercluster, leaflet-ajax

    php pour faire les requetes à twitter et ajax pour faire le lien avec le javascript



####Epitech Nantes / 42 (salle 2010)
Application pour la mobilisation de volontaires
Les volontaires inscrits peuvent répondre présents ou non
Incidents (événements, danger...) saisis et présentés dans l'application


###Secondes restitutions 14h00

Présentation et points techniques

####Epitech Montpelier

Améliorer la communication lors d'une catastrophe 
url publique pour joindre les services de secours

Techno : 

    Techno serveur : Ruby On Rails 

    Responsive : bootstrap, jquery, jquery-ui

    cartographie : leaflet

    Serveur dédié pris 

    PostgreSQL



####Epitech Nice

FlowTracker : 
    
Partie 1 Secours à victime : 

    appel vocal, 

    sms 

    Web (adaptation bande passante) 


API: http://hackathon.emodyz.com/API/
Site de démonstration: http://hackathon.emodyz.com/
User = root@root.com
Pass = toor

Partie 2 : Les secours ont besoin d'aide extérieure

Technos : 
    Coté backoffice (gendarmerie)

    Debian 8

    Mysql

    PHP5

    HTML5, JS, CSS3 : JQuery à venir

    Existence d'une API en PHP

    Coté client (victime)

    Adaptation à la bande passante page HTML en fonction...

    Images

    Chat

    
Partie 2 : 

    App android


####EISTI / 42 

Rappel du sujet 1 : Etendre les fonctions de GendLoc avec entre autres des flux vidéos.
Envoie photo si la bande passante ne permet pas le flux vidéo

Techno :
Front angularJS 
Back NodeJS express
Flux vidéo webRTC avec notion de room (conférence possible)

Difficultés avec Safari (webRTC)

####ENSTA

Rappel du sujet : 
    sur une carte des informations de contexte : réseaux sociaux, géographie ou données gendarmerie.
    ex : moissonner tous les tweets lancés depuis un périmètre donné sur une carte, avec filtrage du contenu. 
Techno

Coté serveur
PHP + twitteroauth pour authentification twitter  (à venir)

Cote client
JS : leaflet / openstreetmap. 

####Epitech Nantes / 42 (salle 2010)

Projet Auxillium

Proméblatique : 
    Utiliser les ressources humaines dormantes
    Utilisation des dispositifs mobiles
    Maximiser les chances de survie
    
Techniquement

APPS
2 app : transmission d'incident et notification Push
Android avec android studio

Serveur:
    REDIS Geo
    PHP 7
    RESTfull API
    multicanal (sms, 2G, 3G...)
    
Difficultés ? 
difficultés avec REDIS GEO techno pas forcément mature....
gestion Push Pull (push préféré)

###Présentations 10h30 (amphi Delfosse)

####Equipe : Epitech Nice (salle 2008)

Projet FlowTracker

Objectif : améliorer les fonctions de GendLoc 

Front office :  Présentation du fonctionnement de l'application coté victime

    La victime reçoit un appel > SMS > arrivée sur une page web > informations sur un formulaire

    La page s'adapte à la bande passante

    Possibilité de chatter avec la gendarmerie

    Application multilingue. 


Back office : (gendarmerie) accès aux informations. Les échanges sont sécurisés par un système de token.

Techniquement
Une API permet de développer d'autres applications (documenté). 

Questions : 

    Adaptabilité de l'application au terminal utilisé ?

    Comment est gérée l'adaptation à la bande passante ? Est-ce paraméétrable

    Comment cela se traduit pour la victime en terme d'interface ? 

    Un premier écran indique que la victime a bien été géolocalisée, puis en fonction de la bande passante les autres écrans apparaissent. La CSS (permettant d'afficher une page plus belle) est téléchargée à la fin pour afficher les informations essentielles en premier.

    Autre question sur la gestion de la bande passante : quelle est la limite de débit ?


###Epitech Montpelier

Projet Geo Secours

"En situation de crise ... un afflux massif d'appels... difficulité de gérer coté service d'urgence."
En réponse : le projet Geo Secours : une interface citoyen et une interface pour les secours

Url accessible par le citoyen. Celle ci pourrait être communiquée en masse avec le cell-broadcast selon l'évènement

L'idée : répondre à des interrogations de la GN et transmettre des médias.

Permettre d'avoir à l'opérateur une vue d'ensemble de la situation

    Temps réel

    Classement

    Données de masse

    Partage d'informations entre services


Démo de l'application : innondation dans l'appartement de Ginette...
Ginette renseigne le formulaire et ajoute une photo
Visualisation du backoffice, les évennements peuvent-etre triés avec différents critères, système de drag and drop...
Le formulaire à communiquer à la victime peut être élaboré par l'opérateur selon l'évènement afin de proposer des questions simples et fermées.  

Piste d'amélioration : veille sur les RS et veille VISOV par exemple...


Techniquement : 
    Ruby on Rails et librairies opensource
    Accès navigateur web

    Prise en compte les appels malveillants (avec adresse IP et géoloc de l'adresse).



Questions : 

    Qu'est-ce qui est prévu pour communiquer avec la victime ? 

    Un premier message permet de savoir que cela a été pris en compte. Par la suite, chat envisageable...


####EISTI / 42 (salle 2013)

Projet GendLoc ++

Contexte :
Rappel des fonctionnalités de GendLoc

Objectif : diversifier les flux d'information entre victimes et services de secours

Fonctionnalités : 
Partage volontaires d'informations : 

    flux vidéo/audio, 

    géolocalisation, 

    photo

    formulaire

    chat texte

Interface opérateur (idem gendloc)
Envoi de fiche réflexe
L'opérateur peut choisir le canal de communication adapté au cas
Gestion de mode dégradé si le débit est insuffisant. 
une visio conférence avec plusieurs acteurs est envisageable 

Démonstration : 

Technos : 
NodeJS - Express, Angular, webRTC

Axes d'amélioration : 

    WebRTC en attente d'améliorations - incompatible pour le moment avec Safari

    Communication non phonique...



####ENSTA
Projet : SocialGendMap (SGM)

Présentation des membres de l'équipe

Thème 2 choisi : mieux appréhender l'environnement des victime
Récupération d'informations contextuelles

Cartographie à l'occasion de catastrophes ou attentat...

Interface utiliateur : simple et intuitive : 
Récupération de tweets, images...

Techniquement
PHP5, ajax, en JS (SPA), leaflet et OpenStreetMap.

Principe un format commun pour les différents RS, aujourd'hui twitter mais étendable à d'autres API de RS

Fonctionnalités : 

    Clustering

    Ajouts des postes PN et GN


Améliorations :

    Autres RS

    Flux vidéo

    Intégration neogend, gendloc

    cartes de chaleur, big data

    prendre en compte le modèle économique des réseaux sociaux, tel twitter qui limite la gratuité de la récolte à un seuil et une durée


####Epitech Nantes / 42 (salle 2010)
Projet AUXILLIUM

Problématique : 
    Comment faire un usage rationnel des ressources "dormantes"
    Utilisation des dispositifs mobiles (NeoGend)
    Maximiser les chances de survie
    
La solution ; 
Une interface de communication entre les CO et des volontaires.

Procédure
Signalement > Appel au secours et volontaires > prise en charge par des volontaires > arrivée des secours

Interface volontaires

Il s'agit de personnels volontaires reconnus dans leurs capacités à intervenir (secouristes...) 

 3 écrans. : 

    infos de zone

    liste des incidents

    signalement des incidents

    le volontaire déclare s'il peut intervenir ou pas


Interface centre opérationnel 

visualisation dynamique du déplacement des secours vers le lieux de l'incident. 

administration des périmètres de diffusion d'alerte. 


Techniquement

2 app natives Android (compatible avec iOs), une citoyen, une "aidant"
un serveur de traitement BDD

Evolutions

Intégration des réservistes...

Démo 
 
 
### Lauréats

Epitech / Ecole 42 : projet Auxillium

ENSTA : projet SocialGendMap

EISTI / école 42 : projet GendLoc++


Epitech Montpellier au pied du podium
5ème place pour l'Epitech Nice 


###Liens

Les site de présentation : http://gendarmerienationale.github.io/hackathongendloc/

GendLoc installable avec Vagrant : https://github.com/GendarmerieNationale/PA_GENDLOC_final


###Les projets sur GitHub

socialgendmap : https://github.com/GuillaumeLe/socialgendmap
FlowTracker: https://github.com/MrDarkSkil/FlowTracker
Gendloc++: https://github.com/FunkySayu/GendLoc-
Geo-Secours: https://github.com/sicardf/Geo-Secours


Projets forkés vers le github GendarmerieNationale : 


Gendloc++  :  https://github.com/GendarmerieNationale/GendLoc- 
Geo-secours : https://github.com/GendarmerieNationale/Geo-Secours

Nous invitons les contributeurs de ces projet à faire leurs pull request vers ces dépôts, désormais


###Liens presse/médias


###Vidéos

BFMTV : http://bfmbusiness.bfmtv.com/mediaplayer/video/les-news-de-la-tech-la-gendarmerie-nationale-lance-son-premier-hackathon-1804-797556.html

Vidéo Ministère de l'Intérieur : http://www.dailymotion.com/video/x45twj4_hackathon-de-la-gendarmerie-nationale-2016_news

Vidéo Gendarmerie : https://amp.twimg.com/v/9866b346-6114-44c3-82f8-da49d09f63e9


###Articles

Ecole EISTI : https://eisti.fr/fr/article/1er-hackathon-de-la-gendarmerie-nationale

Revue du digital : http://www.larevuedudigital.com/2016/04/15/la-gendarmerie-nationale-organise-son-premier-hackathon-le-18-avril/

Zataz : http://www.zataz.com/gendarmerie-nationale-lance-1er-hackathon/

APIE : http://www.economie.gouv.fr/apie/apie-partenaire-premier-hackathon-gendarmerie-nationale




