# workshop-conditions-generales-2019

Le workshop propose de travailler des outils et des compositions interactives et imprimables permettant de visualiser et comprendre le processus de travail des graphistes et donc sa valeur, mais également les questions de temporalité, de nécessités techniques, etc. Nous interrogerons les formes que peuvent prendre un contrat, un document de conditions générales, et autres « documents types » qui sont rarement mis au devant de la scène et pourtant fondamentaux pour les graphistes.

Vos projets permettront de générer des documents pour plusieurs supports : la notion d’édition hybride concerne des projets existants sous plusieurs formes de publications (papier, écran, performée…) en considérant chaque forme comme complémentaire aux autres.

## conditions / méthodologie de travail en groupe

* se mettre en mode "bienveillance" avec tout le monde, essayer de voir les choses avec enthousiasme et curiosité
* écouter et faire attention à la répartition de la parole
* toujours faire des propositions plutôt qu'uniquement des critiques négatives
* toute contribution a de la valeur et fait avancer le projet — éviter la dévalorisation ou l'auto-dévalorisation (exprimer des doutes si nécessaire mais éviter de commencer par "c'est nul ce que j'ai fait")
* essayer de voir le meilleur dans chaque proposition et focaliser dessus
* plutôt que de fonctionner de manière binaire (ça ou ça), tenter de combiner (des idées, des propositions...)
* se mettre d'accord sur un fil rouge commun, et accepter les tentatives divergentes
* créer des moments de mise en commun dans le groupe
* se repartir le travail, changer de rôles pour que tout le monde puisse avoir fait l'expérience des différents rôles et faciliter la reprise du projet en cas d'absence d'une personne
* partager régulièrement les documents en cours de travail


## exemples de sites:
* http://brutalistwebsites.com/
* http://www.ecogex.com/delectable/
* Crazy Cool Websites https://www.facebook.com/groups/393558204075688/

## projets web-to-print
* Paul Soulellis, Printed Web http://soulellis.com/projects/library/ et http://printedweb.org/
* Michael Mandiberg, Print Wikipedia http://dennygallery.com/exhibitions/fromaaaaatozzzap/ et https://github.com/mandiberg/printwikipedia
* James Bridle, The Iraq War: A Historiography of Wikipedia Changelogs http://booktwo.org/notebook/wikipedia-historiography/

## guide web-to-print
* http://kabk.github.io/govt4-coding/print-css-tips.html
* http://prepostprint.dev.schr.fr/en:resources

## à lire
* “Workshop PrePostPrint - Chercher, manipuler, partager, imprimer”, Strabic, juin 2017: http://strabic.fr/Workshop-PrePostPrint
* Hybrid Publishing Group: https://hpg.io/
* “Documenter une production en design graphique”, mémoire Antoine Gelgon: https://github.com/Antoine-Gelgon/memoire-dnsep
Vous pouvez lire le mémoire au format PDF ici: http://esad-gv.net/designgraphique/_ressources/2014-2015/Memoires_DNSEP_2015/Antoine_Gelgon_-_Documenter_une_production_en_design_graphique.pdf
* Workshop HTML sauce cocktail: https://github.com/HEAR/HTML_sauce-cocktail-workshop-OSP
* Dispersive Edition, workshop par Raphaël Bastide: https://raphaelbastide.com/workshops/dispersive/

# outils

## code:

* Github: système de gestion collaborative de fichiers (versions) http://github.com/
* Jsfiddle: plateforme pour enregistrer des bouts de code http://jsfiddle.net/ (mes fiddles: https://jsfiddle.net/user/lfurter/fiddles/ )
* Fontsquirrel webfonts generator: pour générer des typos qui vont sur le web https://www.fontsquirrel.com/tools/webfont-generator

**HTML** (contenus et structure de votre page)
* https://openclassrooms.com/courses/apprenez-a-creer-votre-site-web-avec-html5-et-css3/votre-premiere-page-web-en-html
* http://cours-web.ch/html/
* http://www.delprat.org/cours/

**CSS** (style graphique des éléments dans la page)
* http://cssreference.io/
* https://openclassrooms.com/courses/apprenez-a-creer-votre-site-web-avec-html5-et-css3/memento-des-proprietes-css

**JAVASCRIPT** (actions sur les éléments de la page)
* https://cours-web.ch/js/


## sites de typo open source (gratuites, modifiables, redistribuables):
* https://www.google.com/fonts → le plus de choix
* http://open-foundry.com/hot30 → sélection
* http://fontain.org/ → sélection
* http://love-letters.be/foundry.html → fondrie open source (et Belge!!)
* http://osp.kitchen/foundry/ → fondrie open source (et Belge!!)
* http://www.velvetyne.fr/ → fondrie open source
* http://typotheque.interstices.io/ → sélection

## graphisme
* principes de base: http://lorainefurter.net/documents/petit_manuel_graphisme_regles.pdf
* Typo Guide (règles typographiques): http://web.archive.org/web/20160122014347/http://www.typoguide.ch
* Ponctuations et espaces: http://www.typoguide.ch/tmp/

# tuto

## GITHUB

* Créer un compte sur: https://github.com/join?source=login
* Télécharger l’application GitHub Desktop: https://desktop.github.com/
* Ouvrir l’application et se connecter (Menu GitHub Desktop > Preferences > bouton sign in)
* Aller sur internet, sur le site https://github.com/furter/culture-graphique
* Cliquer sur le bouton vert “Clone or Download” et cliquer sur Open in Desktop
(si cette étape ne fonctionne pas, pas de panique, on regardera ensemble!)

## INTÉGRER UNE FONTE DANS VOTRE SITE

* Téléchargez la fonte (voir sites ci-dessus) 
* Convertissez-la pour le web: https://www.fontsquirrel.com/tools/webfont-generator
* Sauvegardez le dossier avec les fontes pour le web sur votre ordinateur. 
* Mettre les fichiers .WOFF et .WOFF2 dans le dossier de fontes de votre site
* Copier le contenu du fichier .css dans la feuille de style de votre site (attention à bien vérifier que le chemin vers les fichiers soit juste, ne pas oublier d’indiquer les dossiers, par exemple en ajoutant fonts/ ex: url('fonts/sporting_grotesque_normal.woff2') )
* Supprimer le reste
