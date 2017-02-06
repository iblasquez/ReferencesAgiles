# Références bibliographiques/webographiques utilisées/utilisables pour l'élaboration de cours sur les méthodes, pratiques et techniques agiles ...
<!-- => retour à la ligne, 2 espaces .... -->
<!-- undescore dans URL, mettre un espace après -->

Ce travail est le fruit d'une synthèse réalisée à partir des cours créés par [Isabelle BLASQUEZ](https://twitter.com/iblasquez) à l'automne 2014 pour des étudiants en [IUT Informatique](http://www.iut-informatique.fr/) s'appuyant sur plusieurs années d'intérêt porté aux méthodes agiles...   
Ces cours ont été construits en respectant le défi suivant : *chaque transparent devait être extrait d'un document sur l'agilité déjà en ligne sur le web.*... Le module est maintenant terminé et je souhaite partager les références agiles utilisées afin que chacun puisse, à son tour, retrouver aisément une référence et construire plus rapidement ses présentations agiles....

Merci à tous mes ami(e)s des communautés Agile, Java, Software Craftsmanship et autres qui ont toujours été disponibles et avec qui j'ai pu avoir de longues discussions passionées et enthousiastes qui m'ont permis d'avancer et de mieux appréhender le monde de l'agilité !
Merci également à tous ceux qui n'ont pas hésiter à se lancer dans l'[aventure d'#iutagile](http://www.iutagile.com/) qui permet aujourd'hui de proposer des cours d'agilité en IUT.   

Les cours suivants se sont inscrits dans une partie du **module M3301 Méthodologie de la production d’applications** du [PPN du DUT Informatique](http://www.ac-versailles.fr/public/upload/docs/application/pdf/2014-02/dut_informatique.pdf) (Programme Pédagogique National). Ils ont permis aux étudiants de découvrir et d'approfondir les méthodes, pratiques et techniques agiles en abordant les points suivants :

* [Du développement classique au développement agile…](#devClassiqueAgile)
* [Marshmallow Challenge : un jeu sérieux (Serious Game)](#marshmallowChallenge)
* [Lego4Scrum : Apprentissage de Scrum par la simulation](#lego4Scrum)
* [Découverte de la Gestion de produit agile (Scrum, Kanban)](#scrumKanban)
* Le Bon Produit (*the Right Product*) : De la vision aux features : les outils du Product Owner 
	* [Ateliers Innovation Games pour travailler sur la vision du produit](#visionProduit)
	* [Découverte du Lean Startup, de la méthode Running Lean et des Canvas](#leanStartup)
	* [Impact Mapping : Théorie et pratique](#impactMapping)
* [User Story : l'histoire utilisateur au coeur du process agile](#userStory)
	* [Découverte du Story Mapping](#storyMapping)
	* [Atelier PODOJO : USTA (User Story - Tests d'Acceptance)](#podjoUSTA)
* Le Produit de qualité (*the Product Right*) ...
	* [Pas d'agilité sans excellence technique ! ... Découverte du mouvement Software Craftsmanship](#SoftwareCraftsmanship)
	* [Les tests au centre de la qualité logicielle : TDD – ATDD - BDD - Classification – Coding Dojo](#tests_xDD)  
* [La Rétrospective en pratique : Ateliers, Agiles Games & Innovation Games](#retro)  
* [Quid de l'agilité aujourd'hui ?](#quidAgile)

Les ressources utilisées pour traiter ces différents points sont listées ci-après.  
A partir de maintenant [cette liste devient collaborative](https://help.github.com/categories/collaborating/), libre à vous de la compléter et de la faire évoluer via une petite [pull request](https://help.github.com/articles/creating-a-pull-request/) ! N'hésitez pas à participer ! Tout feedback est bien sûr  le bienvenu ...

**Avant de commencer...**

* **Un petit plan bien pratique pour s'y retrouver dans le vaste monde de l'agilité :  Bienvenue sur nos lignes ! ;-)**
![agile Subway Map](/agileSubwayMap.png)
Image extraite de [http://guide.agilealliance.org/subway.html](http://guide.agilealliance.org/subway.html).  
Le plan est interactif sur le site de l'[agile alliance](http://www.agilealliance.org/) depuis cette [URL](http://guide.agilealliance.org/subway.html). 


* **Quelques liens pour s'y retrouver dans le jargon agile...**  
[http://guide.agilealliance.org](http://guide.agilealliance.org)  
[http://referentiel.institut-agile.fr/](http://referentiel.institut-agile.fr/)  
[http://www.mountaingoatsoftware.com/agile](http://www.mountaingoatsoftware.com/agile)   
[https://www.scrum.org/Resources/Scrum-Glossary](https://www.scrum.org/Resources/Scrum-Glossary)  
[http://www.aubryconseil.com/post/2007/07/17/262-glossaire-scrum](http://www.aubryconseil.com/post/2007/07/17/262-glossaire-scrum)   
[http://thierry-leriche-dessirier.developpez.com/tutoriels/general/memento-scrum-destination-equipe](http://thierry-leriche-dessirier.developpez.com/tutoriels/general/memento-scrum-destination-equipe)

* **Peetic : Une étude de cas imaginée et proposée par [Pablo Pernot](https://twitter.com/pablopernot) : Site de rencontre pour animaux et plus si affinité !**
[http://www.areyouagile.com/2012/11/peetic/](http://www.areyouagile.com/2012/11/peetic/)  
[http://www.areyouagile.com/2014/06/de-lidee-au-plan-de-livraison/ ](http://www.areyouagile.com/2014/06/de-lidee-au-plan-de-livraison/)  
[https://github.com/pablopernot/peetic](https://github.com/pablopernot/peetic)  


* **Des outils pour timeboxer en ligne**:  
[http://e.ggtimer.com/](http://e.ggtimer.com/)    
[http://www.online-stopwatch.com](http://www.online-stopwatch.com)  
 
------------------------ 
## Du développement classique au développement agile… <a id="devClassiqueAgile"></a> 

### Articles & Présentations
<!-- En Ligne --> 
[http://www.emarketeur.fr/qualite/triangle-qualit-aide-gerer-contraintes](http://www.emarketeur.fr/qualite/triangle-qualit-aide-gerer-contraintes)  
[http://jargonf.org/wiki/effet_ de_tunnel](http://jargonf.org/wiki/effet_de_tunnel)  
[http://fr.wikipedia.org/wiki/Cycle_ en_V](http://fr.wikipedia.org/wiki/Cycle_en_V)  
[http://www.agileproductdesign.com/blog/dont_ know_ what_ i_ want.html](http://www.agileproductdesign.com/blog/dont_know_what_i_want.html)    
[http://www.redbooks.ibm.com](http://www.redbooks.ibm.com)  
[http://300gp.ovh.net/~sitecoll/gpi3/site.php?rubrique=297](http://300gp.ovh.net/~sitecoll/gpi3/site.php?rubrique=297)  
[http://www.agileconnection.com/article/relating-pmbok-practices-agile-practices-part-2-4](http://www.agileconnection.com/article/relating-pmbok-practices-agile-practices-part-2-4)  
[http://enterpriseagilist.blogspot.fr/2014/08/Agile-Contract-Management-1.html](http://enterpriseagilist.blogspot.fr/2014/08/Agile-Contract-Management-1.html)   
[www.agilemanifesto.org](www.agilemanifesto.org)    
[http://msdn.microsoft.com/fr-fr/library/dd997578.aspx](http://msdn.microsoft.com/fr-fr/library/dd997578.aspx)      
[https://www.scrumalliance.org/community/articles/2014/july/agilossary  ](https://www.scrumalliance.org/community/articles/2014/july/agilossary)  
[http://guide.agilealliance.org/subway.html](http://guide.agilealliance.org/subway.html)
<!-- PDF --> 
[http://www.emse.fr/~picard/cours/2A/gp/GP-Introduction.pdf](http://www.emse.fr/~picard/cours/2A/gp/GP-Introduction.pdf)   
[http://www.math-info.univ-paris5.fr/~janiszek/_ media/enseignement/03_ gestion_projet.pdf](http://www.math-info.univ-paris5.fr/~janiszek/_media/enseignement/03_gestion_projet.pdf)   
[http://membres-lig.imag.fr/dubousquet/docs/2.2_CyclesDeVie.pdf](http://membres-lig.imag.fr/dubousquet/docs/2.2_CyclesDeVie.pdf)     
[https://www.projet-plume.org/files/bonnespratiques_ envol2010_ cc_ 0.pdf](https://www.projet-plume.org/files/bonnespratiques_envol2010_cc_0.pdf)  
[http://www.software-tester.ch/PDF-Files/FR_ ISTQB_ FL_ Syll_ 2011_Released.pdf](http://www.software-tester.ch/PDF-Files/FR_ISTQB_FL_Syll_2011_Released.pdf)
[http://www.aubryconseil.com/download/490](http://www.aubryconseil.com/download/490)   
<!-- Transparents--> 
[http://slideplayer.fr/slide/513583/](http://slideplayer.fr/slide/513583/)  
[http://fr.slideshare.net/RichardPDoerer/what-isagile-henrik-kniberg-august-20-2013](http://fr.slideshare.net/RichardPDoerer/what-isagile-henrik-kniberg-august-20-2013) 
[http://www.slideshare.net/slideshow/embed_code/34487140](http://www.slideshare.net/slideshow/embed_code/34487140)  
[http://www.slideshare.net/agnes_crepet/introduction-a-lagiliteiutlyon1decembre2011](http://www.slideshare.net/agnes_crepet/introduction-a-lagiliteiutlyon1decembre2011)
[http://fr.slideshare.net/rvignes/lentreprise-agile-29135486](http://fr.slideshare.net/rvignes/lentreprise-agile-29135486)  

### Illustrations
<!-- Twitter--> 
[https://twitter.com/GEFeminin/status/497306219057782784/photo/1](https://twitter.com/GEFeminin/status/497306219057782784/photo/1)
[https://twitter.com/SabEnBzh/status/414291164703891456/photo/1](https://twitter.com/SabEnBzh/status/414291164703891456/photo/1)
[https://twitter.com/alg_malek/status/424511366146588673/photo/1 ](https://twitter.com/alg_malek/status/424511366146588673/photo/1 ) 
<!-- Joies du code--> 
[http://lesjoiesducode.fr/post/95172054995/quand-on-me-dit-que-je-vais-pouvoir-coder-apres-3-mois](http://lesjoiesducode.fr/post/95172054995/quand-on-me-dit-que-je-vais-pouvoir-coder-apres-3-mois)   
[http://lesjoiesducode.fr/post/75046110363/quand-je-peux-enfin-lancer-les-tests-unitaires-sur-mon](http://lesjoiesducode.fr/post/75046110363/quand-je-peux-enfin-lancer-les-tests-unitaires-sur-mon) 
<!-- Autres--> 
[http://www.projectcartoon.com/](http://www.projectcartoon.com/)  
[http://emmanuelchenu.blogspot.fr/search/label/Illustrations](http://emmanuelchenu.blogspot.fr/search/label/Illustrations)  
[http://uneviededev.wordpress.com](http://uneviededev.wordpress.com)    
[http://itscertainlyuncertain.blogspot.de/search/label/Agile%20Manifesto](http://itscertainlyuncertain.blogspot.de/search/label/Agile%20Manifesto)    
[http://ayeba.wikispaces.com/Le+mod%C3%A8le+de+cycle+de+vie+en+cascade+%28th%C3%A9orie+vs+pratique%29](http://ayeba.wikispaces.com/Le+mod%C3%A8le+de+cycle+de+vie+en+cascade+%28th%C3%A9orie+vs+pratique%29)   
[http://ayeba.wikispaces.com/D%C3%A9veloppement+d%27un+Produit](http://ayeba.wikispaces.com/D%C3%A9veloppement+d%27un+Produit)     

### Video
La différence entre le cinéma belge et français d'après B.Poelvoorde : 
[https://www.youtube.com/watch?v=wtvRJG7NMQ8](https://www.youtube.com/watch?v=wtvRJG7NMQ8)   

------------------------
## Marshmallow Challenge : un jeu sérieux (Serious Game) <a id="marshmallowChallenge"></a> 
 
### Articles & Présentations
[http://marshmallowchallenge.com](http://marshmallowchallenge.com)    
[http://marshmallowchallenge.com/TED_Talk.html](http://marshmallowchallenge.com/TED_Talk.html)    
[http://marshmallowchallenge.com/TED_ Talk_ filesTED2010_ Tom_ Wujec_ Marshmallow_ Challenge_ Web_Version.pdf](http://marshmallowchallenge.com/TED_Talk_filesTED2010_Tom_Wujec_Marshmallow_Challenge_Web_Version.pdf)     
[http://www.osez-oser.com/article-le-marshmallow-challenge-exercice-de-cohesion-d-equipe-86815918.html](http://www.osez-oser.com/article-le-marshmallow-challenge-exercice-de-cohesion-d-equipe-86815918.html)
[http://www.areyouagile.com/2011/04/les-enfants-et-le-marshmallow-challenge/](http://www.areyouagile.com/2011/04/les-enfants-et-le-marshmallow-challenge/)  
[http://efficacite-performance.org/outils-et-exemples/team-building-et-papier-a4](http://efficacite-performance.org/outils-et-exemples/team-building-et-papier-a4)

[http://e.ggtimer.com/](http://e.ggtimer.com/)


[http://fr.slideshare.net/RichardPDoerer/what-isagile-henrik-kniberg-august-20-2013](http://fr.slideshare.net/RichardPDoerer/what-isagile-henrik-kniberg-august-20-2013)  
[http://www.slideshare.net/slideshow/embed_code/34487140](http://www.slideshare.net/slideshow/embed_code/34487140) 
 

### Illustrations
[https://twitter.com/MatthieuGarde/status/420123879609499648/photo/1 ](https://twitter.com/MatthieuGarde/status/420123879609499648/photo/1 ) 
[https://twitter.com/helenbevan/status/494383774449541120](https://twitter.com/helenbevan/status/494383774449541120) 


------------------------
## Lego4Scrum : Apprentissage de Scrum par la simulation <a id="lego4Scrum"></a> 
 
### Livres
**Le scrum guide de Ken Schwaber et Jeff Sutherland**  
[https://www.scrum.org/scrum-guide](https://www.scrum.org/scrum-guide)  
[http://www.scrumguides.org/download.html](http://www.scrumguides.org/download.html)

**Scrum et XP depuis les Tranchées de Henrik Kniberg**
[http://www.infoq.com/resource/news/2007/06/scrum-xp-book/en/resources/ScrumAndXpFromTheTrenches_French.pdf](http://www.infoq.com/resource/news/2007/06/scrum-xp-book/en/resources/ScrumAndXpFromTheTrenches_French.pdf)

**Scrum : Le guide pratique de la méthode agile la plus populaire de Claude Aubry** 
[http://www.aubryconseil.com/pages/Livre-Scrum](http://www.aubryconseil.com/pages/Livre-Scrum) 
  

### Articles & Présentations
<!-- En Ligne -->
[http://www.lego4scrum.com/](http://www.lego4scrum.com/)  
[http://www.scrumalliance.org/resources/621](http://www.scrumalliance.org/resources/621)  
[http://www.fabrice-aimetti.fr/dotclear/public/traductions/LEGO-for-extended-SCRUM-simulation-FR.pdf](http://www.fabrice-aimetti.fr/dotclear/public/traductions/LEGO-for-extended-SCRUM-simulation-FR.pdf)  
[http://www.fabrice-aimetti.fr/dotclear/public/traductions/Lego4Scrum-stories.pdf](http://www.fabrice-aimetti.fr/dotclear/public/traductions/Lego4Scrum-stories.pdf)   
[http://www.aubryconseil.com/post/Le-backlog-de-produit](http://www.aubryconseil.com/post/Le-backlog-de-produit)  
[http://opatou.blogspot.fr/2012/01/ken-schwaber-co-fondateur-de-la-methode.html](http://opatou.blogspot.fr/2012/01/ken-schwaber-co-fondateur-de-la-methode.html)  
[http://www.bouzin-agile.fr/?post/2010/09/08/Reunion-d-estimation-Enlevez-vos-t-shirts](http://www.bouzin-agile.fr/?post/2010/09/08/Reunion-d-estimation-Enlevez-vos-t-shirts)  
[http://rules.ssw.com.au/Management/RulesToBetterScrumUsingTFS/Pages/Do-You-Know-How-To-Size-Stories-Effectively.aspx](http://rules.ssw.com.au/Management/RulesToBetterScrumUsingTFS/Pages/Do-You-Know-How-To-Size-Stories-Effectively.aspx)  
[http://blog.octo.com/extreme-quotation-planning-agile-sous-steroides/](http://blog.octo.com/extreme-quotation-planning-agile-sous-steroides/)   
[https://twitter.com/iCOLABOREMOS/status/508968113086668800](https://twitter.com/iCOLABOREMOS/status/508968113086668800)  
[http://www.mountaingoatsoftware.com/agile/scrum/overview](http://www.mountaingoatsoftware.com/agile/scrum/overview)    
[http://blog.ippon.fr/2010/12/24/pour-noel-ippon-vous-offre-sa-vision-de-lagilite/](http://blog.ippon.fr/2010/12/24/pour-noel-ippon-vous-offre-sa-vision-de-lagilite/)     
[http://fr.slideshare.net/calton13/lagilit-dans-les-projets-informatiques-et-physiques?ref=http://talondagile.fr/blog/](http://fr.slideshare.net/calton13/lagilit-dans-les-projets-informatiques-et-physiques?ref=http://talondagile.fr/blog/)  
[http://jhattat.wordpress.com/2014/04/29/lego4scrum-deux-ans-apres/](http://jhattat.wordpress.com/2014/04/29/lego4scrum-deux-ans-apres/)
   

### Vidéos
Agility meets Rugby : [http://vimeo.com/51872147](http://vimeo.com/51872147)  
La Gestion de Produit Agile en deux mots :
[http://www.youtube.com/watch?v=3qMpB-UH9kA](http://www.youtube.com/watch?v=3qMpB-UH9kA)  


------------------------
## Découverte de la Gestion de produit agile (Scrum, Kanban) <a id="scrumKanban"></a> 
 
### Livres

**Le scrum guide de Ken Schwaber et Jeff Sutherland**  
[https://www.scrum.org/scrum-guide](https://www.scrum.org/scrum-guide)  
[http://www.scrumguides.org/download.html](http://www.scrumguides.org/download.html)

**Scrum et XP depuis les Tranchées de Henrik Kniberg**
[http://www.infoq.com/resource/news/2007/06/scrum-xp-book/en/resources/ScrumAndXpFromTheTrenches_French.pdf](http://www.infoq.com/resource/news/2007/06/scrum-xp-book/en/resources/ScrumAndXpFromTheTrenches_French.pdf)

**Scrum : Le guide pratique de la méthode agile la plus populaire de Claude Aubry** 
[http://www.aubryconseil.com/pages/Livre-Scrum](http://www.aubryconseil.com/pages/Livre-Scrum) 


**Kanban and Scrum - making the most of both by Henrik Kniberg and Mattias Skarin**
[http://www.infoq.com/minibooks/kanban-scrum-minibook](http://www.infoq.com/minibooks/kanban-scrum-minibook)  
**Kanban et Scrum - tirer le meilleur des deux Traduit par Claude Aubry, Frédéric Faure,
Antoine Vernois et Fabrice Aimetti**  
[http://www.infoq.com/resource/news/2010/01/kanban-scrum-minibook/en/resources/KanbanAndScrum-French.pdf](http://www.infoq.com/resource/news/2010/01/kanban-scrum-minibook/en/resources/KanbanAndScrum-French.pdf)

**Kanban in action de Marcus Hammarberg and Joakim Sundén**  
[http://www.manning.com/hammarberg/](http://www.manning.com/hammarberg/)

**Kanban pour l'IT - Une nouvelle méthode pour améliorer les processus de développement de Laurent Morisseau**   
[http://www.dunod.com/informatique-multimedia/developpement/methodes-modelisation-uml/kanban-pour-lit](http://www.dunod.com/informatique-multimedia/developpement/methodes-modelisation-uml/kanban-pour-lit)  


### Pour s'y retrouver dans le jargon agile !
[http://guide.agilealliance.org](http://guide.agilealliance.org)  
[http://referentiel.institut-agile.fr/](http://referentiel.institut-agile.fr/)  
[http://www.mountaingoatsoftware.com/agile](http://www.mountaingoatsoftware.com/agile)   
[https://www.scrum.org/Resources/Scrum-Glossary](https://www.scrum.org/Resources/Scrum-Glossary)  
[http://www.aubryconseil.com/post/2007/07/17/262-glossaire-scrum](http://www.aubryconseil.com/post/2007/07/17/262-glossaire-scrum)   
[http://thierry-leriche-dessirier.developpez.com/tutoriels/general/memento-scrum-destination-equipe/](http://thierry-leriche-dessirier.developpez.com/tutoriels/general/memento-scrum-destination-equipe/)  
 

### Articles & Présentations
<!-- En Ligne -->  
[http://blog.soat.fr/2010/05/un-apercu-de-scrum-pour-neophyte-%E2%80%A6/](http://blog.soat.fr/2010/05/un-apercu-de-scrum-pour-neophyte-%E2%80%A6/)
[http://www.aubryconseil.com/post/2006/11/21/125-scrum-en-bref](http://www.aubryconseil.com/post/2006/11/21/125-scrum-en-bref)   
[http://growingagile.co.za/2014/09/who-owns-the-meetings-in-scrum/](http://growingagile.co.za/2014/09/who-owns-the-meetings-in-scrum/) 
[http://guide.agilealliance.org/guide/taskboard.html](http://guide.agilealliance.org/guide/taskboard.html)  
[http://referentiel.institut-agile.fr/taskboard.html](http://referentiel.institut-agile.fr/taskboard.html)    
[http://www.mountaingoatsoftware.com/agile/scrum/task-boards](http://www.mountaingoatsoftware.com/agile/scrum/task-boards)  
[http://agiletools.wordpress.com/2007/11/24/task-boards-telling-a-compelling-agile-story/](http://agiletools.wordpress.com/2007/11/24/task-boards-telling-a-compelling-agile-story/)  
[http://www.aubryconseil.com/post/Tableau-a-2-niveaux](http://www.aubryconseil.com/post/Tableau-a-2-niveaux)   
[http://www.aubryconseil.com/post/Le-petit-Scrum-illustre-a-Grenoble](http://www.aubryconseil.com/post/Le-petit-Scrum-illustre-a-Grenoble)   
[http://www.aubryconseil.com/post/2008/05/13/412-definition-de-fini-a-la-fin-d-un-sprint](http://www.aubryconseil.com/post/2008/05/13/412-definition-de-fini-a-la-fin-d-un-sprint)   
[http://guide.agilealliance.org/guide/definition-of-done.html](http://guide.agilealliance.org/guide/definition-of-done.html)   
[http://referentiel.institut-agile.fr/sashimi.html](http://referentiel.institut-agile.fr/sashimi.html)  
[http://www.coactiv.fr/definition-of-done/](http://www.coactiv.fr/definition-of-done/)
[http://www.infoq.com/fr/news/2014/03/process-definition-done](http://www.infoq.com/fr/news/2014/03/process-definition-done)  
[http://www.fabrice-aimetti.fr/dotclear/index.php?post/2011/03/25/Caracteristiques-d-un-Product-Owner](http://www.fabrice-aimetti.fr/dotclear/index.php?post/2011/03/25/Caracteristiques-d-un-Product-Owner)  
[http://ouelcum.wordpress.com/2014/02/11/les-36-qualites-dun-product-owner/](http://ouelcum.wordpress.com/2014/02/11/les-36-qualites-dun-product-owner/)    


[http://www.crisp.se/kanban](http://www.crisp.se/kanban)  
[http://blog.crisp.se/2009/11/16/henrikkniberg/kanban-kick-start-example](http://blog.crisp.se/2009/11/16/henrikkniberg/kanban-kick-start-example)  
[http://blog.xebia.fr/2014/01/17/les-dix-kanbandements/](http://blog.xebia.fr/2014/01/17/les-dix-kanbandements/)
[http://info.leankit.com/kanban-roadmap](http://info.leankit.com/kanban-roadmap)   
[http://www.aubryconseil.com/post/Pourquoi-kanbaniser-du-Scrum](http://www.aubryconseil.com/post/Pourquoi-kanbaniser-du-Scrum)     
[http://www.aubryconseil.com/post/Ma-presentation-sur-les-bacs](http://www.aubryconseil.com/post/Ma-presentation-sur-les-bacs)   
[http://www.morisseauconsulting.com/2013/07/17/apportez-votre-kanban-en-vacances/](http://www.morisseauconsulting.com/2013/07/17/apportez-votre-kanban-en-vacances/)   
[http://thierrycros.net/?post/2013/10/14/mon-Kanban-perso](http://thierrycros.net/?post/2013/10/14/mon-Kanban-perso)  
 
<!-- PDF --> 
[http://www.newtechusa.com/Resources/Scrums3333.pdf](http://www.newtechusa.com/Resources/Scrums3333.pdf)  
[http://www.areyouagile.com/pdf/dod.pdf](http://www.areyouagile.com/pdf/dod.pdf)  
[http://www.aubryconseil.com/media](http://www.aubryconseil.com/media)  
[http://www.aubryconseil.com/download/871](http://www.aubryconseil.com/download/871)  
[http://www.crisp.se/file-uploads/kanban-example.pdf](http://www.crisp.se/file-uploads/kanban-example.pdf) 

<!-- Transparents--> 
[http://fr.slideshare.net/davesharrock/5-whys-of-scrum](http://fr.slideshare.net/davesharrock/5-whys-of-scrum)  
[http://fr.slideshare.net/calton13/kanban-pour-tous](http://fr.slideshare.net/calton13/kanban-pour-tous)  
[http://fr.slideshare.net/claudeaubry/kanban-scrum-tirer-le-meilleur-des-2](http://fr.slideshare.net/claudeaubry/kanban-scrum-tirer-le-meilleur-des-2)  
[http://fr.slideshare.net/glours/personal-kanban-21504855](http://fr.slideshare.net/glours/personal-kanban-21504855)


### Illustrations
<!-- Twitter--> 
[https://twitter.com/iCOLABOREMOS/status/508968113086668800](https://twitter.com/iCOLABOREMOS/status/508968113086668800)  
[https://twitter.com/ealliaume/status/460668306152628224](https://twitter.com/ealliaume/status/460668306152628224)
<!-- Autres-->
[http://www.implementingscrum.com/section/blog/cartoons/](http://www.implementingscrum.com/section/blog/cartoons/)  
[http://blog.ippon.fr/2010/12/24/pour-noel-ippon-vous-offre-sa-vision-de-lagilite/](http://blog.ippon.fr/2010/12/24/pour-noel-ippon-vous-offre-sa-vision-de-lagilite/)   
[http://wall-skills.com/2013/kanban-5-steps/](http://wall-skills.com/2013/kanban-5-steps/)  
[http://fr.pinterest.com/pin/365495325981359619/](http://fr.pinterest.com/pin/365495325981359619/)  
[http://www.pinterest.com/pin/253749760225722444/](http://www.pinterest.com/pin/253749760225722444/)  
[http://www.biggerplate.com/mindmaps/z47894/les-10-etats-d-esprit-du-kaizen](http://www.biggerplate.com/mindmaps/z47894/les-10-etats-d-esprit-du-kaizen)
     

### Facilitations graphiques
[http://itscertainlyuncertain.blogspot.de/2014/01/scrum-on-one-page.html](http://itscertainlyuncertain.blogspot.de/2014/01/scrum-on-one-page.html)  
[http://itscertainlyuncertain.blogspot.de/2014/01/kanban-on-one-page.html](http://itscertainlyuncertain.blogspot.de/2014/01/kanban-on-one-page.html)   
[https://leanpub.com/agileplanet](https://leanpub.com/agileplanet)  


### Jeux
[http://www.crisp.se/gratis-material-och-guider/multitasking-name-game](http://www.crisp.se/gratis-material-och-guider/multitasking-name-game)  
[Multitasking-Name-Game-EN.pdf (Crisp)](https://docs.google.com/viewer?a=v&pid=sites&srcid=YWlnbHUub3JnfGFnaWxlLWludGVyZXN0LWdyb3VwLWx1eGVtYm91cmd8Z3g6MWUxYjFhNDBjZTViNzNmNA)  
[http://www.getkanban.com/](http://www.getkanban.com/)  
[http://kanbanzine.wordpress.com/](http://kanbanzine.wordpress.com/)   

[http://blog.valtech.fr/2012/02/17/serious-game/](http://blog.valtech.fr/2012/02/17/serious-game/)  
[http://www.aubryconseil.com/post/Le-multi-taches-c-est-mal](http://www.aubryconseil.com/post/Le-multi-taches-c-est-mal)  
[http://www.morisseauconsulting.com/2013/06/10/getkanban-vs-kanbanzine-le-challenge/](http://www.morisseauconsulting.com/2013/06/10/getkanban-vs-kanbanzine-le-challenge/)  
[http://www.aubryconseil.com/post/Apprendre-Kanban-avec-Kanbanzine](http://www.aubryconseil.com/post/Apprendre-Kanban-avec-Kanbanzine)   


### Vidéos 
Les 3 rôles de Scrum en 5 minutes : [http://www.orange-business.com/fr/blogs/usages-dentreprise/management-de-projet/les-3-roles-de-scrum-en-5-minutes](http://www.orange-business.com/fr/blogs/usages-dentreprise/management-de-projet/les-3-roles-de-scrum-en-5-minutes)  
La Gestion de Produit Agile en deux mots : [http://www.youtube.com/watch?v=3qMpB-UH9kA](http://www.youtube.com/watch?v=3qMpB-UH9kA)  
Il était une fois la vie d'un product owner : [https://www.youtube.com/watch?v=c0RZsewej88](https://www.youtube.com/watch?v=c0RZsewej88)    
Scrum et Kanban avec Claude Aubry, Antoine Vernois et Fabrice Aimetti : [https://www.youtube.com/watch?v=PmTQOS9nFm8&list=PLDEAC2DBF6F8B6A20](https://www.youtube.com/watch?v=PmTQOS9nFm8&list=PLDEAC2DBF6F8B6A20)  
Personal Kanban : retrouvez votre efficacité : [http://www.infoq.com/fr/presentations/personal-kanban-retrouvez-votre-efficacite](http://www.infoq.com/fr/presentations/personal-kanban-retrouvez-votre-efficacite) 

------------------------
## Ateliers Innovation Games pour travailler sur la vision du produit <a id="visionProduit"></a> 
 
### Livres
**Innovation Games: Creating Breakthrough Products Through Collaborative Play de Luke Hohmann**  
[http://www.amazon.fr/Innovation-Games-Creating-Breakthrough-Collaborative/dp/0321437292](http://www.amazon.fr/Innovation-Games-Creating-Breakthrough-Collaborative/dp/0321437292)  

**Gamestorming : Jouer pour innover : pour les innovateurs, les visionnaires et les pionniers de Dave Gray, Sunni Brown et James Macanufo**
[http://diateino.izibookstore.com/produit/30/9782354561079](http://diateino.izibookstore.com/produit/30/9782354561079)

### Articles & Présentations
<!-- En Ligne -->  
[http://www.qualitystreet.fr/2009/07/29/la-vision-du-produit/](http://www.qualitystreet.fr/2009/07/29/la-vision-du-produit/)  
[http://lyon.clubagilerhonealpes.org/activites/activites-passees/saison-2011-2012--preparer-votre-transition-agile/fil-rouge/atelier-1-definir-sa-vision-produit](http://lyon.clubagilerhonealpes.org/activites/activites-passees/saison-2011-2012--preparer-votre-transition-agile/fil-rouge/atelier-1-definir-sa-vision-produit)  
[http://www.agilex.fr/2011/05/jeux-en-pratique/](http://www.agilex.fr/2011/05/jeux-en-pratique/)  
[http://www.aubryconseil.com/post/2007/10/29/320-souvenir-du-futur](http://www.aubryconseil.com/post/2007/10/29/320-souvenir-du-futur)  
[http://leadinganswers.typepad.com/leading_ answers/2007/03/release_ and_ite.html](http://leadinganswers.typepad.com/leading_answers/2007/03/release_and_ite.html)
[http://agilarium.blogspot.fr/2012/09/formation-innovation-games-toulouse.html](http://agilarium.blogspot.fr/2012/09/formation-innovation-games-toulouse.html)
[http://www.aubryconseil.com/post/2007/10/04/305-features-themes-epics-et-stories](http://www.aubryconseil.com/post/2007/10/04/305-features-themes-epics-et-stories)

### Jeux
[http://www.innovationgames.com/](http://innovationgames.com/)  
[http://www.innovationgames.com/product-box/](http://innovationgames.com/product-box/)  
[http://www.innovationgames.com/remember-the-future/](http://innovationgames.com/remember-the-future/)

###Video
Présentation des Innovation Games : [https://www.youtube.com/watch?v=fP4QSIB-mbw](https://www.youtube.com/watch?v=fP4QSIB-mbw)  
Utilisation des « Jeux Agiles » dans les projets : [https://www.youtube.com/watch?v=QwiZFkmPtrE](https://www.youtube.com/watch?v=QwiZFkmPtrE)  
10 outils pour rendre votre équipe auto-organisée : [https://www.youtube.com/watch?v=lfHkl3sPVz0 ](https://www.youtube.com/watch?v=lfHkl3sPVz0)

------------------------
## Découverte du Lean Startup, de la méthode Running Lean et des Canvas <a id="leanStartup"></a> 
 
### Livres
**The Lean Startup d'Eric Ries**  
[http://theleanstartup.com/](http://theleanstartup.com/)  
[http://sachachua.com/blog/2012/02/visual-book-notes-the-lean-startup-by-eric-ries/](http://sachachua.com/blog/2012/02/visual-book-notes-the-lean-startup-by-eric-ries/)  

**Running Lean d'Ash Maurya - *How to Iterate from Plan A to a plan that works***  
[http://runninglean.co/](http://runninglean.co/)  
[http://sachachua.com/blog/2012/12/visual-book-review-running-leanash-maurya/ ](http://sachachua.com/blog/2012/12/visual-book-review-running-leanash-maurya/ )

**Lean Analytics: Use Data to Build a Better Startup Faster d'Alistair Croll et Benjamin Yoskovitz**
[http://leananalyticsbook.com/ ](http://leananalyticsbook.com/ ) 

**Business Model Generation de de Alexander Osterwalder et Yves Pigneur** 
[http://businessmodelgeneration.com/book](http://businessmodelgeneration.com/book)  
**Value Proposition Design : : How to Create Products and Services Customers Want de Alexander Osterwalder et Yves Pigneur**  
[https://strategyzer.com/value-proposition-design](https://strategyzer.com/value-proposition-design)

### Articles & Présentationss
<!-- En Ligne -->  
[http://www.startuplessonslearned.com/](http://www.startuplessonslearned.com/)  
[http://practicetrumpstheory.com/](http://practicetrumpstheory.com/)  
[http://practicetrumpstheory.com/lean-analytics-the-one-metric-that-matters-and-other-provocations/](http://practicetrumpstheory.com/lean-analytics-the-one-metric-that-matters-and-other-provocations/)  
[http://theleanstartup.com/principles](http://theleanstartup.com/principles)  
[http://theleanstartup.com/casestudies](http://theleanstartup.com/casestudies)   
[http://blog.xebia.fr/2013/05/23/introduction-a-lean-startup/](http://blog.xebia.fr/2013/05/23/introduction-a-lean-startup/)   
[http://blog.fastmonkeys.com/2014/06/18/minimum-viable-product-your-ultimate-guide-to-mvp-great-examples/](http://blog.fastmonkeys.com/2014/06/18/minimum-viable-product-your-ultimate-guide-to-mvp-great-examples/)  
[http://cupcakepictures.com/2014/04/the-cake-model-of-product-planning/](http://cupcakepictures.com/2014/04/the-cake-model-of-product-planning/)  
[https://blog.kissmetrics.com/abcs-of-mvps/](https://blog.kissmetrics.com/abcs-of-mvps/)  

[http://speckyboy.com/2014/09/18/building-minimum-viable-products-spotify/](http://speckyboy.com/2014/09/18/building-minimum-viable-products-spotify/)  
[http://ayeba.fr/2013/06/spotify-est-agile-a-grande-echelle/](http://ayeba.fr/2013/06/spotify-est-agile-a-grande-echelle/) 

[http://www.lucie-pinzano.com/2012/5-modeles-economiques-internet-innovants/](http://www.lucie-pinzano.com/2012/5-modeles-economiques-internet-innovants/)   
[http://www.businessmodelgeneration.com/](http://www.businessmodelgeneration.com/)  
[http://15marches.fr/business/business-model-generation](http://15marches.fr/business/business-model-generation)  
[http://wiki.ayeba.fr/Le+Business+Model+Canvas+encore+mieux+-+Cr%C3%A9er+une+Proposition+de+Valeur](http://wiki.ayeba.fr/Le+Business+Model+Canvas+encore+mieux+-+Cr%C3%A9er+une+Proposition+de+Valeur)  
[http://wiki.ayeba.fr/Carte+de+l%27Empathie](http://wiki.ayeba.fr/Carte+de+l%27Empathie)  
[http://businessmodelalchemist.com/2012/09/test-your-value-proposition-supercharge-lean-startup-and-custdev-principles.html](http://businessmodelalchemist.com/2012/09/test-your-value-proposition-supercharge-lean-startup-and-custdev-principles.html)  
 
[http://leblogdewalter.com/2013/11/26/lean-canvas-par-ash-maurya/](http://leblogdewalter.com/2013/11/26/lean-canvas-par-ash-maurya/)  
[http://demontiers.com/2014/03/ma-traduction-francaise-du-lean-canvas/](http://demontiers.com/2014/03/ma-traduction-francaise-du-lean-canvas/)
[http://practicetrumpstheory.com/businessmodelcanvas/](http://practicetrumpstheory.com/businessmodelcanvas/)  
[http://practicetrumpstheory.com/why-lean-canvas/](http://practicetrumpstheory.com/why-lean-canvas/)  
[http://practicetrumpstheory.com/the-lean-stack/](http://practicetrumpstheory.com/the-lean-stack/)  
[http://blog.xebia.fr/2013/07/29/se-lancer-dans-le-lean-startup-avec-le-lean-canvas-part-1/](http://blog.xebia.fr/2013/07/29/se-lancer-dans-le-lean-startup-avec-le-lean-canvas-part-1/) 
[http://blog.xebia.fr/2013/12/04/se-lancer-dans-le-lean-startup-avec-le-lean-canvas-part-2/](http://blog.xebia.fr/2013/12/04/se-lancer-dans-le-lean-startup-avec-le-lean-canvas-part-2/)   
[http://www.b2corporate.com/startup-business-model-e-rischi-da-eliminare](http://www.b2corporate.com/startup-business-model-e-rischi-da-eliminare)
[http://www.sebastiensacard.fr/articles/2012/lean-canvas-or-business-model-canvas-which-one-should-you-use/](http://www.sebastiensacard.fr/articles/2012/lean-canvas-or-business-model-canvas-which-one-should-you-use/)   
[http://www.socialbusinessmodels.ch/content/entre-les-canevas-mon-coeur-balance-business-model-canvas-lean-canvas-lean-startup-social](http://www.socialbusinessmodels.ch/content/entre-les-canevas-mon-coeur-balance-business-model-canvas-lean-canvas-lean-startup-social)  
[http://leblogdewalter.com/2013/04/29/lentonnoir-du-lean-marketing/](http://leblogdewalter.com/2013/04/29/lentonnoir-du-lean-marketing/)
<!-- PDF --> 
[http://files.darrylfeldman.com/WhyMVP.pdf](http://files.darrylfeldman.com/WhyMVP.pdf)
[https://dl.dropboxusercontent.com/u/1018963/Articles/HowSpotifyBuildsProducts.pdf](https://dl.dropboxusercontent.com/u/1018963/Articles/HowSpotifyBuildsProducts.pdf)  
[http://www.businessmodelstore.com/documents/businessmodelcanvasfr.pdf](http://www.businessmodelstore.com/documents/businessmodelcanvasfr.pdf)  
[http://www.laval-technopole.fr/sites/default/files/Fiche%20pratique%20N18%20Busines%20Modele%20Canvas.pdf](http://www.laval-technopole.fr/sites/default/files/Fiche%20pratique%20N18%20Busines%20Modele%20Canvas.pdf)  
[http://www.cci.fr/c/document_library/get_file?uuid=8bdbfba5-7ee7-4340-ba9b-01592cb57360&groupId=10928](http://www.cci.fr/c/document_library/get_file?uuid=8bdbfba5-7ee7-4340-ba9b-01592cb57360&groupId=10928  )  
[http://www.socialbusinessmodels.ch/sites/default/files/u1/articles/Comparatif%20de%20canevas%20de%20construction%20de%20mod%E8les%20d%27affaires.pdf](http://www.socialbusinessmodels.ch/sites/default/files/u1/articles/Comparatif%20de%20canevas%20de%20construction%20de%20mod%E8les%20d%27affaires.pdf)  
<!-- Transparents--> 
[http://fr.slideshare.net/ndeverge/a-story-of-my-incoming-product-using-leanstartup](http://fr.slideshare.net/ndeverge/a-story-of-my-incoming-product-using-leanstartup)  
[http://fr.slideshare.net/camilleroux/le-lean-startup-ce-nest-pas-que-des-canvas](http://fr.slideshare.net/camilleroux/le-lean-startup-ce-nest-pas-que-des-canvas)  
[http://fr.slideshare.net/calton13/crer-le-bon-produit-avec-le-lean-canva-format-scrumdaycomments169slideshare](http://fr.slideshare.net/calton13/crer-le-bon-produit-avec-le-lean-canva-format-scrumdaycomments169slideshare) 
<!--Exemples -->
[https://github.com/LabAixBidouille/LabAixBidouille.github.io/wiki/Compte-rendu-12-Juillet](https://github.com/LabAixBidouille/LabAixBidouille.github.io/wiki/Compte-rendu-12-Juillet)
[http://blog.typhonfute.fr/presentation-typhon-fute/](http://blog.typhonfute.fr/presentation-typhon-fute/)  
[http://blog.typhonfute.fr/les-ateliers-de-co-construction/](http://blog.typhonfute.fr/les-ateliers-de-co-construction/)
[http://blog.typhonfute.fr/running-lean-canvas ](http://blog.typhonfute.fr/running-lean-canvas ) 
[http://www.ekito.fr/people/vendre-son-appart-avec-du-lean-startup-et-du-lean-analytics/](http://www.ekito.fr/people/vendre-son-appart-avec-du-lean-startup-et-du-lean-analytics/)  


### Illustrations
[http://wall-skills.com/2013/lean-startup-principles/](http://wall-skills.com/2013/lean-startup-principles/)  
[http://leblogdewalter.com/2013/05/02/infographie-du-lean-marketing/](http://leblogdewalter.com/2013/05/02/infographie-du-lean-marketing/)  
  
 
### Facilitations graphiques
[http://itscertainlyuncertain.blogspot.de/2014/01/lean-on-one-page.html](http://itscertainlyuncertain.blogspot.de/2014/01/lean-on-one-page.html)
[http://itscertainlyuncertain.blogspot.de/2014/01/lean-startup-on-one-page.html](http://itscertainlyuncertain.blogspot.de/2014/01/lean-startup-on-one-page.html)
[https://leanpub.com/agileplanet](https://leanpub.com/agileplanet)
[http://sachachua.com/blog/2012/12/visual-book-review-running-leanash-maurya/](http://sachachua.com/blog/2012/12/visual-book-review-running-leanash-maurya/)
  

### Jeux
[http://batmat.net/blog/post/2008/02/05/Danseuse-%3A-quel-cote-de-votre-cerveau-utilisez-vous-le-plus](http://batmat.net/blog/post/2008/02/05/Danseuse-%3A-quel-cote-de-votre-cerveau-utilisez-vous-le-plus) 
[https://twitter.com/FascinatingVids/status/508988196995485696/photo/1 ](https://twitter.com/FascinatingVids/status/508988196995485696/photo/1 )


### Vidéos 
[https://labs.spotify.com/2014/03/27/spotify-engineering-culture-part-1/](https://labs.spotify.com/2014/03/27/spotify-engineering-culture-part-1/)  
[https://labs.spotify.com/2014/09/20/spotify-engineering-culture-part-2](https://labs.spotify.com/2014/09/20/spotify-engineering-culture-part-2)   
[https://www.youtube.com/watch?v=IEDJ5bRRtvs&feature=youtu.be&a](https://www.youtube.com/watch?v=IEDJ5bRRtvs&feature=youtu.be&a)  
[https://www.youtube.com/watch?v=f_dcTR4z85w](https://www.youtube.com/watch?v=f_dcTR4z85w) 


### Outils numériques 
[https://canvanizer.com](https://canvanizer.com)   
[https://canvanizer.com/new/business-model-canvas](https://canvanizer.com/new/business-model-canvas)  
[http://leancanvas.com/](http://leancanvas.com/)



------------------------
## Impact Mapping : Théorie et pratique <a id="impactMapping"></a> 
 
### Livres
**Impact Mapping de Gojko Adzic**  
[http://impactmapping.org/book ](http://impactmapping.org/book )

**Agile with Guts - A pragmatic guide to value-driven development de Nicolas Gouy**
[http://www.infoq.com/minibooks/agile-guts](http://www.infoq.com/minibooks/agile-guts)


### Articles & Présentationss
<!-- En Ligne -->  
[http://www.wdpm.org/organisation-produit](http://www.wdpm.org/organisation-produit)  
[http://www.aubryconseil.com/post/De-la-vision-a-la-story](http://www.aubryconseil.com/post/De-la-vision-a-la-story)   
[http://www.aubryconseil.com/post/Chapitre-treize](http://www.aubryconseil.com/post/Chapitre-treize)   
[http://www.davidbrocard.org/blog/le-bon-produit](http://www.davidbrocard.org/blog/le-bon-produit)   

[http://www.mindmapping.com](http://www.mindmapping.com)  
[http://www.impactmapping.org](http://www.impactmapping.org)  
[http://fr.impactmapping.org](http://fr.impactmapping.org)  
[http://fr.impactmapping.org/drawing.php](http://fr.impactmapping.org/drawing.php)  
[http://fr.impactmapping.org/example.php](http://fr.impactmapping.org/example.php)  
[http://fr.impactmapping.org/role.php](http://fr.impactmapping.org/role.php)  
[http://gojko.net](http://gojko.net)  
[http://gojko.net/effect-map](http://gojko.net/effect-map)  
[http://blog.octo.com/en/impact-mapping-business-success-in-software-development](http://blog.octo.com/en/impact-mapping-business-success-in-software-development)  
[http://theagilecoach.co.nz/impact-mapping](http://theagilecoach.co.nz/impact-mapping)  
[http://www.ithaquecoaching.com/articles/la-notion-dobjectif-smart-120.html](http://www.ithaquecoaching.com/articles/la-notion-dobjectif-smart-120.html)  
[http://fr.wikipedia.org/wiki/Cinq_pourquoi](http://fr.wikipedia.org/wiki/Cinq_pourquoi)   
[http://www.startuplessonslearned.com/2008/11/five-whys.html](http://www.startuplessonslearned.com/2008/11/five-whys.html)  
[http://www.aubryconseil.com/post/Souvenir-des-impacts](http://www.aubryconseil.com/post/Souvenir-des-impacts)  
[http://www.aubryconseil.com/post/Effet-Impact](http://www.aubryconseil.com/post/Effet-Impact)  
[http://www.aubryconseil.com/tag/impact%20mapping](http://www.aubryconseil.com/tag/impact%20mapping)  
<!--Exemples -->
[http://www.aubryconseil.com/post/Mindmap-de-la-vision](http://www.aubryconseil.com/post/Mindmap-de-la-vision)  
[http://www.aubryconseil.com/post/Pourquoi-kanbaniser-du-Scrum](http://www.aubryconseil.com/post/Pourquoi-kanbaniser-du-Scrum)  
[http://www.aubryconseil.com/post/Lecture-d-Impact-Mapping-au-Club](http://www.aubryconseil.com/post/Lecture-d-Impact-Mapping-au-Club)    
[http://www.areyouagile.com/2012/11/peetic/](http://www.areyouagile.com/2012/11/peetic/)  
[http://www.areyouagile.com/2014/06/de-lidee-au-plan-de-livraison/ ](http://www.areyouagile.com/2014/06/de-lidee-au-plan-de-livraison/)    
[https://github.com/pablopernot/peetic](https://github.com/pablopernot/peetic)  
<!-- PDF --> 
[http://goodrequirements.com/downloads/Agile2013_ImpactMapping_PO_CheatSheet.pdf](http://goodrequirements.com/downloads/Agile2013_ImpactMapping_PO_CheatSheet.pdf)  
[https://submissions.agilealliance.org/system/attachments/attachments/000/000/238/original/ImpactMapping_Agile2013.pdf](https://submissions.agilealliance.org/system/attachments/attachments/000/000/238/original/ImpactMapping_Agile2013.pdf)  
<!-- Transparents--> 
[http://fr.slideshare.net/chassa/2013-0603specification-byexamplewithgherkinchristianhassa](http://fr.slideshare.net/chassa/2013-0603specification-byexamplewithgherkinchristianhassa)  
[http://fr.slideshare.net/jhattat/impact-mapping10](http://fr.slideshare.net/jhattat/impact-mapping10)
### Illustrations
<!-- Twitter--> 
[https://twitter.com/romaincouturier/status/512141925982679040/photo/1](https://twitter.com/romaincouturier/status/512141925982679040/photo/1)
[https://twitter.com/sachac/status/404029237054554112](https://twitter.com/sachac/status/404029237054554112)
[https://twitter.com/nicolas_gouy/status/393742959398494208/photo/1 ](https://twitter.com/nicolas_gouy/status/393742959398494208/photo/1 )
[https://twitter.com/nicolas_gouy/status/398108177712939008/photo/1 ](https://twitter.com/nicolas_gouy/status/398108177712939008/photo/1 )
<!-- Autres-->
[https://www.flickr.com/photos/sachac/10863630135](https://www.flickr.com/photos/sachac/10863630135)
[http://www.impactmapping.org/site/poster_im_print_1500.jpg](http://www.impactmapping.org/site/poster_im_print_1500.jpg)   


### Facilitations graphiques
[http://itscertainlyuncertain.blogspot.fr/2013/12/impact-mapping-on-one-page.html](http://itscertainlyuncertain.blogspot.fr/2013/12/impact-mapping-on-one-page.html)  
[https://leanpub.com/agileplanet ](https://leanpub.com/agileplanet )


### Outils numériques
[https://www.mindmup.com](https://www.mindmup.com/)  
[http://mind42.com](http://mind42.com/)  
[http://www.xmind.net](http://www.xmind.net/ )  

 
###Google Group
[https://groups.google.com/forum/?hl=fr#!forum/impact-mapping](https://groups.google.com/forum/?hl=fr#!forum/impact-mapping)  



------------------------
## User Story : l'histoire utilisateur au coeur du process agile <a id="#userStory"></a> 
 
### Livres
**User Stories Applied by Mike Cohn**  
[http://www.mountaingoatsoftware.com/books/user-stories-applied](http://www.mountaingoatsoftware.com/books/user-stories-applied)

**Fifty Quick Ideas to Improve your User Stories by by Gojko Adzic and David Evans**  
[https://leanpub.com/50quickideas](https://leanpub.com/50quickideas) 

**Spécifiez agile - Expression de besoins : la boite à outils du Product Owner par Thierry Cros**  
[https://leanpub.com/agile-expression-de-besoins](https://leanpub.com/agile-expression-de-besoins)

**Specification by Example - How successful teams deliver the right software by Gojko Adzic** 
[http://specificationbyexample.com/](http://specificationbyexample.com/)


### Articles & Présentationss
<!-- En Ligne -->  
[http://xp123.com/articles/invest-in-good-stories-and-smart-tasks/](http://xp123.com/articles/invest-in-good-stories-and-smart-tasks/)  
[http://obenhamid.me/2014/01/les-6-piliers-dune-bonne-user-story-scrum/](http://obenhamid.me/2014/01/les-6-piliers-dune-bonne-user-story-scrum/)  
[http://lolcx.blogspot.fr/2010/09/user-stories-atdd-et-bdd.html](http://lolcx.blogspot.fr/2010/09/user-stories-atdd-et-bdd.html) 
[http://thierrycros.net/?post/2013/03/18/Esth%C3%A9tique-du-backlog](http://thierrycros.net/?post/2013/03/18/Esth%C3%A9tique-du-backlog)  

[http://www.mountaingoatsoftware.com/agile/user-stories](http://www.mountaingoatsoftware.com/agile/user-stories)   
[http://www.mountaingoatsoftware.com/agile/scrum/product-backlog/example](http://www.mountaingoatsoftware.com/agile/scrum/product-backlog/example)  

[http://managedagile.com/2013/05/28/product-backlog-grooming-iceberg/](http://managedagile.com/2013/05/28/product-backlog-grooming-iceberg/)   
[http://www.aubryconseil.com/post/Un-%C3%A9l%C3%A9ment-du-backlog-de-produit](http://www.aubryconseil.com/post/Un-%C3%A9l%C3%A9ment-du-backlog-de-produit)   
[http://www.aubryconseil.com/post/2008/12/02/504-elements-du-backlog-features-stories-et-spikes-revisites](http://www.aubryconseil.com/post/2008/12/02/504-elements-du-backlog-features-stories-et-spikes-revisites)   
[http://www.aubryconseil.com/post/2007/10/04/305-features-themes-epics-et-stories](http://www.aubryconseil.com/post/2007/10/04/305-features-themes-epics-et-stories)   
[http://www.aubryconseil.com/post/Inventaire-de-definition-de-produit](http://www.aubryconseil.com/post/Inventaire-de-definition-de-produit)   
[http://guide.agilealliance.org/guide/split.html](http://guide.agilealliance.org/guide/split.html)   
[http://www.qualitystreet.fr/2011/03/24/agilite-10-strategies-pour-des-user-stories-suffisamment-petites/](http://www.qualitystreet.fr/2011/03/24/agilite-10-strategies-pour-des-user-stories-suffisamment-petites/)  
[http://www.agileforall.com/2009/10/patterns-for-splitting-user-stories/](http://www.agileforall.com/2009/10/patterns-for-splitting-user-stories/)  
[http://www.agileforall.com/2012/01/new-story-splitting-resource/](http://www.agileforall.com/2012/01/new-story-splitting-resource/)    
[http://gojko.net/2012/01/23/splitting-user-stories-the-hamburger-method/](http://gojko.net/2012/01/23/splitting-user-stories-the-hamburger-method/)    
[http://www.coactiv.fr/3-manieres-de-decouper-ses-user-stories/](http://www.coactiv.fr/3-manieres-de-decouper-ses-user-stories/)  

[http://www.qualitystreet.fr/2009/02/16/user-story-vs-use-case-soyez-agile/](http://www.qualitystreet.fr/2009/02/16/user-story-vs-use-case-soyez-agile/)  
[http://www.qualitystreet.fr/2007/03/30/user-stories-use-cases-les-differences/](http://www.qualitystreet.fr/2007/03/30/user-stories-use-cases-les-differences/)  
[http://www.aubryconseil.com/post/2007/04/09/203-user-stories-et-use-cases](http://www.aubryconseil.com/post/2007/04/09/203-user-stories-et-use-cases)  

[http://www.aubryconseil.com/post/Tableau-a-2-niveaux](http://www.aubryconseil.com/post/Tableau-a-2-niveaux)  
[http://www.aubryconseil.com/post/Pourquoi-kanbaniser-du-Scrum](http://www.aubryconseil.com/post/Pourquoi-kanbaniser-du-Scrum)     
[http://www.morisseauconsulting.com/2013/07/17/apportez-votre-kanban-en-vacances/](http://www.morisseauconsulting.com/2013/07/17/apportez-votre-kanban-en-vacances/)   
[http://www.aubryconseil.com/post/Ma-presentation-sur-les-bacs](http://www.aubryconseil.com/post/Ma-presentation-sur-les-bacs)    
[http://www.aubryconseil.com/post/Ma-presentation-au-ScrumDay-2014](http://www.aubryconseil.com/post/Ma-presentation-au-ScrumDay-2014)  
[http://www.aubryconseil.com/post/Story-Dojo](http://www.aubryconseil.com/post/Story-Dojo)   
[http://jfallet.wordpress.com/2014/01/02/les-bacs-de-culture-cest-kiss/](http://jfallet.wordpress.com/2014/01/02/les-bacs-de-culture-cest-kiss/)   
[http://www.aubryconseil.com/post/Les-conditions-de-realisation](http://www.aubryconseil.com/post/Les-conditions-de-realisation)   

[http://www.aubryconseil.com/post/La-pratique-Definition-de-pret-pour-une-story](http://www.aubryconseil.com/post/La-pratique-Definition-de-pret-pour-une-story)  

[http://www.aubryconseil.com/post/2008/05/13/412-definition-de-fini-a-la-fin-d-un-sprint](http://www.aubryconseil.com/post/2008/05/13/412-definition-de-fini-a-la-fin-d-un-sprint)   
[http://guide.agilealliance.org/guide/definition-of-done.html](http://guide.agilealliance.org/guide/definition-of-done.html)   
[http://referentiel.institut-agile.fr/sashimi.html](http://referentiel.institut-agile.fr/sashimi.html)  
[http://www.coactiv.fr/definition-of-done/](http://www.coactiv.fr/definition-of-done/)  
[http://www.infoq.com/fr/news/2014/03/process-definition-done](http://www.infoq.com/fr/news/2014/03/process-definition-done)

[http://www.infoq.com/fr/articles/virtual-panel-tdd-bdd](http://www.infoq.com/fr/articles/virtual-panel-tdd-bdd)  

<!-- PDF -->
[https://submissions.agilealliance.org/system/attachments/attachments/000/000/093/original/Patton_Agile_Requirements___Product_Mgmt.pdf](https://submissions.agilealliance.org/system/attachments/attachments/000/000/093/original/Patton_Agile_Requirements___Product_Mgmt.pdf)  
[http://www.mountaingoatsoftware.com/uploads/presentations/User-Stories-Product-Backlog-Scrum-Gathering-Chicago-2008.pdf](http://www.mountaingoatsoftware.com/uploads/presentations/User-Stories-Product-Backlog-Scrum-Gathering-Chicago-2008.pdf)  
[http://www.ibm.com/developerworks/rational/library/user-stories-product-backlog/user-stories-product-backlog-pdf.pdf](http://www.ibm.com/developerworks/rational/library/user-stories-product-backlog/user-stories-product-backlog-pdf.pdf)  
[http://www.agileforall.com/wp-content/uploads/2009/10/Story-Splitting-Cheat-Sheet.pdf](http://www.agileforall.com/wp-content/uploads/2009/10/Story-Splitting-Cheat-Sheet.pdf)   

<!-- Transparents-->
[http://fr.slideshare.net/yquenechdu/rdiger-des-user-stories](http://fr.slideshare.net/yquenechdu/rdiger-des-user-stories)    
[http://fr.slideshare.net/RichardPDoerer/what-isagile-henrik-kniberg-august-20-2013](http://fr.slideshare.net/RichardPDoerer/what-isagile-henrik-kniberg-august-20-2013)  
[http://fr.slideshare.net/chassa/2013-0603specification-byexamplewithgherkinchristianhassa](http://fr.slideshare.net/chassa/2013-0603specification-byexamplewithgherkinchristianhassa)  


### Illustrations
<!-- Twitter--> 
[https://twitter.com/acassaigne/status/280091718144122880/photo/1](https://twitter.com/acassaigne/status/280091718144122880/photo/1)  
[https://twitter.com/aslak_hellesoy/status/511858669286612992 ](https://twitter.com/aslak_hellesoy/status/511858669286612992)  

<!-- Autres-->
[http://scrum4you.wordpress.com/2008/10/11/product-backlog-eisberg/](http://scrum4you.wordpress.com/2008/10/11/product-backlog-eisberg/)  
[http://www.agileforall.com/2013/02/splitting-stories-in-french/](http://www.agileforall.com/2013/02/splitting-stories-in-french/)     
[http://ryangreenhall.blogspot.fr/2008/10/mind-mapping-behaviour-driven.html](http://ryangreenhall.blogspot.fr/2008/10/mind-mapping-behaviour-driven.html)  


### Facilitations graphiques
[http://itscertainlyuncertain.blogspot.de/2014/03/invest.html](http://itscertainlyuncertain.blogspot.de/2014/03/invest.html)   
[https://leanpub.com/agileplanet](https://leanpub.com/agileplanet)   


### Vidéos
La Gestion de Produit Agile en deux mots : [http://www.youtube.com/watch?v=3qMpB-UH9kA](http://www.youtube.com/watch?v=3qMpB-UH9kA)  
Il était une fois la vie d'un product owner : [https://www.youtube.com/watch?v=c0RZsewej88](https://www.youtube.com/watch?v=c0RZsewej88)


------------------------
## Découverte du Story Mapping <a id="#storyMapping"></a> 
 
### Livres
**User Story Mapping - Discover the Whole Story, Build the Right Productde Jeff Patton**  
[http://shop.oreilly.com/product/0636920033851.do](http://shop.oreilly.com/product/0636920033851.do)  

**User Stories Applied by Mike Cohn**  
[http://www.mountaingoatsoftware.com/books/user-stories-applied](http://www.mountaingoatsoftware.com/books/user-stories-applied) 

### Articles & Présentations
<!-- En Ligne -->  
[http://guide.agilealliance.org/guide/storymap.html](http://guide.agilealliance.org/guide/storymap.html)  
[http://referentiel.institut-agile.fr/storymap.html](http://referentiel.institut-agile.fr/storymap.html)  
 
[http://freethinker.addinq.uy/post/66131430961/a-la-conquete-du-story-mapping](http://freethinker.addinq.uy/post/66131430961/a-la-conquete-du-story-mapping)  
[http://www.agileproductdesign.com/blog/the_new_backlog.html](http://www.agileproductdesign.com/blog/the_new_backlog.html)  
[http://winnipegagilist.blogspot.fr/2012/03/how-to-create-user-story-map.html](http://winnipegagilist.blogspot.fr/2012/03/how-to-create-user-story-map.html)  
[http://www.qualitystreet.fr/2013/03/05/user-story-mapping-un-gros-plus-pour-les-product-owner/](http://www.qualitystreet.fr/2013/03/05/user-story-mapping-un-gros-plus-pour-les-product-owner/)  
[http://www.qualitystreet.fr/2011/03/24/agilite-10-strategies-pour-des-user-stories-suffisamment-petites/](http://www.qualitystreet.fr/2011/03/24/agilite-10-strategies-pour-des-user-stories-suffisamment-petites/)   
[http://www.agileforall.com/2009/10/patterns-for-splitting-user-stories/](http://www.agileforall.com/2009/10/patterns-for-splitting-user-stories/)  
[http://alistair.cockburn.us/Walking+skeleton](http://alistair.cockburn.us/Walking+skeleton)   
[http://blog.codeclimate.com/blog/2014/03/20/kickstart-your-next-project-with-a-walking-skeleton](http://blog.codeclimate.com/blog/2014/03/20/kickstart-your-next-project-with-a-walking-skeleton/)  


[http://www.areyouagile.com/2014/06/de-lidee-au-plan-de-livraison](http://www.areyouagile.com/2014/06/de-lidee-au-plan-de-livraison)  
[http://itscertainlyuncertain.blogspot.de/2013/12/a-story-mapping-workshop.html](http://itscertainlyuncertain.blogspot.de/2013/12/a-story-mapping-workshop.html)  

[http://www.stickyminds.com/article/story-mapping-wrong-way](http://www.stickyminds.com/article/story-mapping-wrong-way)  
 
<!-- PDF --> 
[http://www.agileforall.com/wp-content/uploads/2009/10/Story-Splitting-Cheat-Sheet.pdf](http://www.agileforall.com/wp-content/uploads/2009/10/Story-Splitting-Cheat-Sheet.pdf)     
[http://www.agileproductdesign.com/downloads/user_story_mapping_quickref_comic.pdf](http://www.agileproductdesign.com/downloads/user_story_mapping_quickref_comic.pdf)    

<!-- Transparents--> 
[http://fr.slideshare.net/yquenechdu/rdiger-des-user-stories](http://fr.slideshare.net/yquenechdu/rdiger-des-user-stories)   
[http://fr.slideshare.net/SteveRogalsky/user-story-mapping-in-practice](http://fr.slideshare.net/SteveRogalsky/user-story-mapping-in-practice)  
[http://fr.slideshare.net/chassa/2013-0509story-mapsagilemeetupbp](http://fr.slideshare.net/chassa/2013-0509story-mapsagilemeetupbp)   
  

### Illustrations
<!-- Twitter--> 
[https://twitter.com/ramuncho/status/469792239066316800](https://twitter.com/ramuncho/status/469792239066316800)  


### Facilitations graphiques
[http://itscertainlyuncertain.blogspot.de/2013/12/story-mapping-on-one-page.html](http://itscertainlyuncertain.blogspot.de/2013/12/story-mapping-on-one-page.html)  
[https://leanpub.com/agileplanet](https://leanpub.com/agileplanet)

### Atelier
Atelier eXtreme Story Map :
[http://2014.agile-grenoble.org/programme.html#/session/267](http://2014.agile-grenoble.org/programme.html#/session/267)
[https://twitter.com/ramuncho/status/532110500251725824](https://twitter.com/ramuncho/status/532110500251725824)  
[https://twitter.com/ramuncho/status/521899152754876418](https://twitter.com/ramuncho/status/521899152754876418)   

### Vidéos 
Jeff Patton on learning the ‘game’ of Agility and building the right thing : [http://www.infoq.com/interviews/agile2014-jeff-patton-agility](http://www.infoq.com/interviews/agile2014-jeff-patton-agility)

### Outils numériques 
[https://www.cardboardit.com](https://www.cardboardit.com/)  
[http://www.targetprocess.com](http://www.targetprocess.com/)  
[https://www.featuremap.co/fr (https://www.featuremap.co/fr)  
[http://www.post-it.com/wps/portal/3M/en_US/PostItNA/Home/Ideas/Plus-App](http://www.post-it.com/wps/portal/3M/en_US/PostItNA/Home/Ideas/Plus-App/)  
Un simple outil de mindmap






------------------------
## Atelier PODOJO : USTA (User Story - Tests d'Acceptance) <a id="#podojoUSTA"></a> 
 
### Livres
**User Stories Applied by Mike Cohn**  
[http://www.mountaingoatsoftware.com/books/user-stories-applied](http://www.mountaingoatsoftware.com/books/user-stories-applied)


### Articles & Présentations
<!-- En Ligne -->  
[http://att2013.herokuapp.com/event/256](http://att2013.herokuapp.com/event/256)  
[http://www.fxbodin.com/blog/2013/12/17/mon-premier-po-dojo-et-ce-que-jy-ai-appris/](http://www.fxbodin.com/blog/2013/12/17/mon-premier-po-dojo-et-ce-que-jy-ai-appris/)   
[http://www.agilex.fr/2014/01/podojo-atelier-dexperimentation-pour-product-owner/](http://www.agilex.fr/2014/01/podojo-atelier-dexperimentation-pour-product-owner/)   
[http://www.aubryconseil.com/post/Story-Dojo](http://www.aubryconseil.com/post/Story-Dojo)   
[http://www.coactiv.fr/podojo-paris/](http://www.coactiv.fr/podojo-paris/)  
[https://groups.google.com/forum/?hl=fr#!topic/podojo/T26UDdfSjdc](https://groups.google.com/forum/?hl=fr#!topic/podojo/T26UDdfSjdc)    
  
[http://xp123.com/articles/invest-in-good-stories-and-smart-tasks/](http://xp123.com/articles/invest-in-good-stories-and-smart-tasks/)   
[http://www.mountaingoatsoftware.com/agile/user-stories](http://www.mountaingoatsoftware.com/agile/user-stories)  
[http://guide.agilealliance.org/guide/split.html](http://guide.agilealliance.org/guide/split.html)  
[http://www.agileforall.com/2009/10/patterns-for-splitting-user-stories/](http://www.agileforall.com/2009/10/patterns-for-splitting-user-stories/)  

[http://www.fabrice-aimetti.fr/dotclear/index.php?post/2011/03/25/Caracteristiques-d-un-Product-Owner](http://www.fabrice-aimetti.fr/dotclear/index.php?post/2011/03/25/Caracteristiques-d-un-Product-Owner)  
[http://ouelcum.wordpress.com/2014/02/11/les-36-qualites-dun-product-owner/](http://ouelcum.wordpress.com/2014/02/11/les-36-qualites-dun-product-owner/)    
 
<!-- PDF --> 
[https://submissions.agilealliance.org/system/attachments/attachments/000/000/093/original/Patton_ Agile_ Requirements___ Product_ Mgmt.pdf](https://submissions.agilealliance.org/system/attachments/attachments/000/000/093/original/Patton_Agile_Requirements___Product_Mgmt.pdf)    
[http://www.agileforall.com/wp-content/uploads/2009/10/Story-Splitting-Cheat-Sheet.pdf](http://www.agileforall.com/wp-content/uploads/2009/10/Story-Splitting-Cheat-Sheet.pdf) 

<!-- Transparents--> 
[http://fr.slideshare.net/yquenechdu/rdiger-des-user-stories](http://fr.slideshare.net/yquenechdu/rdiger-des-user-stories) 
[http://fr.slideshare.net/chassa/2013-0603specification-byexamplewithgherkinchristianhassa](http://fr.slideshare.net/chassa/2013-0603specification-byexamplewithgherkinchristianhassa)

### Illustrations
<!-- Twitter--> 
[https://twitter.com/ramuncho/status/521899152754876418](https://twitter.com/ramuncho/status/521899152754876418)  
[https://twitter.com/ramuncho/status/453988188290179072](https://twitter.com/ramuncho/status/453988188290179072)  
[https://twitter.com/acassaigne/status/280091718144122880](https://twitter.com/acassaigne/status/280091718144122880)

### Facilitations graphiques

### Vidéos 
Les 3 rôles de Scrum en 5 minutes : [http://www.orange-business.com/fr/blogs/usages-dentreprise/management-de-projet/les-3-roles-de-scrum-en-5-minutes](http://www.orange-business.com/fr/blogs/usages-dentreprise/management-de-projet/les-3-roles-de-scrum-en-5-minutes)  
La Gestion de Produit Agile en deux mots : [http://www.youtube.com/watch?v=3qMpB-UH9kA](http://www.youtube.com/watch?v=3qMpB-UH9kA)  
Il était une fois la vie d'un product owner : [https://www.youtube.com/watch?v=c0RZsewej88](https://www.youtube.com/watch?v=c0RZsewej88)


### Google Group
[https://groups.google.com/forum/#!forum/podojo](https://groups.google.com/forum/#!forum/podojo)

------------------------
## Pas d'agilité sans excellence technique !... Découverte du mouvement Software Craftsmanship <a id="#SoftwareCraftsmanship"></a> 
 
### Livres

**Software Craftsmanship de Sandro Mancuso**  
[https://leanpub.com/socra](https://leanpub.com/socra)  
*Sur le blog de Xebia : Chaque semaine, découvrez un chapitre du livre de Sandro Mancuso sur le Craftsmanship !*
[http://blog.xebia.fr/2014/09/24/chaque-semaine-decouvrez-un-chapitre-du-livre-de-sandro-sur-le-craftsmanship](http://blog.xebia.fr/2014/09/24/chaque-semaine-decouvrez-un-chapitre-du-livre-de-sandro-sur-le-craftsmanship)  
[http://blog.xebia.fr/2014/09/30/chaque-semaine-decouvrez-un-chapitre-du-livre-de-sandro-mancuso-sur-le-craftsmanship-chapitre-2/](http://blog.xebia.fr/2014/09/30/chaque-semaine-decouvrez-un-chapitre-du-livre-de-sandro-mancuso-sur-le-craftsmanship-chapitre-2/)   
[http://blog.xebia.fr/2014/10/21/chapitre-3-du-livre-de-sandro-mancuso-sur-le-craftsmanship/](http://blog.xebia.fr/2014/10/21/chapitre-3-du-livre-de-sandro-mancuso-sur-le-craftsmanship/)  
[http://blog.xebia.fr/2014/10/28/chapitre-4-du-livre-de-sandro-mancuso-sur-le-software-craftsmanship/](http://blog.xebia.fr/2014/10/28/chapitre-4-du-livre-de-sandro-mancuso-sur-le-software-craftsmanship/)  
[http://blog.xebia.fr/2014/11/04/chapitre-5-du-livre-de-sandro-mancuso-sur-le-software-craftsmanship/](http://blog.xebia.fr/2014/11/04/chapitre-5-du-livre-de-sandro-mancuso-sur-le-software-craftsmanship/)

**The Pragmatic Programmer: From Journeyman to Master by Andrew Hunt and David Thomas**
[https://pragprog.com/book/tpp/the-pragmatic-programmer](https://pragprog.com/book/tpp/the-pragmatic-programmer) 

**Refactoring Improving the Design of Existing Code by Martin Fowler**
[http://martinfowler.com/books/refactoring.html](http://martinfowler.com/books/refactoring.html)

**Refactoring to Patterns by Joshua Kerievsky**  
[http://industriallogic.com/xp/refactoring/](http://industriallogic.com/xp/refactoring/)

**Agile Software Development, Principles, Patterns and Practices by Robert C. Martin** 
[http://www.objectmentor.com/resources/books.html](http://www.objectmentor.com/resources/books.html)
[http://www.amazon.com/exec/obidos/ASIN/0135974445/objectmentorinc](http://www.amazon.com/exec/obidos/ASIN/0135974445/objectmentorinc)

**Clean Code: A Handbook of Agile Software Craftsmanship by Robert C. Martin**
[http://www.objectmentor.com/resources/books.html](http://www.objectmentor.com/resources/books.html)  
[http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)

**The Clean Coder : A Code of Conduct for Professional Programmers by Robert C. Martin**
[http://www.pearsonhighered.com/educator/product/Clean-Coder-The-A-Code-of-Conduct-for-Professional-Programmers/9780137081073.page](http://www.pearsonhighered.com/educator/product/Clean-Coder-The-A-Code-of-Conduct-for-Professional-Programmers/9780137081073.page)  
[http://pierrepironin.fr/the-clean-coder/](http://pierrepironin.fr/the-clean-coder/)  
 
**Continuous Delivery - Reliable Software Releases through Build, Test, and Deployment Automation by Jez Humble and David Farley**  
[http://www.thoughtworks.com/continuous-delivery](http://www.thoughtworks.com/continuous-delivery)  
[http://www.amazon.com/dp/0321601912?tag=contindelive-20](http://www.amazon.com/dp/0321601912?tag=contindelive-20) 


### Articles & Présentations
<!-- En Ligne --> 
[http://www.agilemanifesto.org/](http://www.agilemanifesto.org/)  
[http://agilemanifesto.org/iso/fr/](http://agilemanifesto.org/iso/fr/)  
[http://agilemanifesto.org/iso/fr/principles.html](http://agilemanifesto.org/iso/fr/principles.html)   

[http://wiki.ayeba.fr/space/content?tag=manifeste](http://wiki.ayeba.fr/space/content?tag=manifeste)   
[http://labaixbidouille.github.io/PrezATMrs/presentation.html](http://labaixbidouille.github.io/PrezATMrs/presentation.html)  
[http://manifesto.softwarecraftsmanship.org](http://manifesto.softwarecraftsmanship.org)   

[http://www.touilleur-express.fr/2011/01/20/craftsmanship](http://www.touilleur-express.fr/2011/01/20/craftsmanship)  
[http://blog.xebia.fr/2011/01/31/software-craftsmanship-en-pratique/](http://blog.xebia.fr/2011/01/31/software-craftsmanship-en-pratique/)   
[http://codurance.com/blog/](http://codurance.com/blog/)  
[https://blog.crafting-labs.fr/](https://blog.crafting-labs.fr/)

[http://www.occitech.fr/blog/2014/11/intro-dette-technique/](http://www.occitech.fr/blog/2014/11/intro-dette-technique/)   
[http://c2.com/cgi/wiki?WardExplainsDebtMetaphor](http://c2.com/cgi/wiki?WardExplainsDebtMetaphor)   
[http://martinfowler.com/bliki/TechnicalDebt.html](http://martinfowler.com/bliki/TechnicalDebt.html)   
[http://blog.octo.com/maitriser-sa-dette-technique/](http://blog.octo.com/maitriser-sa-dette-technique/)  

[http://blog.codinghorror.com/code-smells/](http://blog.codinghorror.com/code-smells/)  
[http://badcodesmellstaxonomy.mikamantyla.eu/](http://badcodesmellstaxonomy.mikamantyla.eu/)  
[http://www.rogoit.de/webdesign-typo3-blog-duisburg/clean-code-regeln-smells-und-heuristiken/](http://www.rogoit.de/webdesign-typo3-blog-duisburg/clean-code-regeln-smells-und-heuristiken/)   
[http://www.java-project.fr/clean-code/](http://www.java-project.fr/clean-code/)  
 
[http://www.cleancoder.com](http://www.cleancoder.com)  
[http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)   
[http://blog.8thlight.com/uncle-bob/2014/05/08/SingleReponsibilityPrinciple.html](http://blog.8thlight.com/uncle-bob/2014/05/08/SingleReponsibilityPrinciple.html)  
[http://blog.8thlight.com/uncle-bob/2014/05/12/TheOpenClosedPrinciple.html](http://blog.8thlight.com/uncle-bob/2014/05/12/TheOpenClosedPrinciple.html)  
 
[http://de.slideshare.net/iksgmbh/clean-codevortraggearconf](http://de.slideshare.net/iksgmbh/clean-codevortraggearconf)   
[http://williamdurand.fr/2013/07/30/from-stupid-to-solid-code/](http://williamdurand.fr/2013/07/30/from-stupid-to-solid-code/)  
[http://zeroturnaround.com/rebellabs/object-oriented-design-principles-and-the-5-ways-of-creating-solid-applications/](http://zeroturnaround.com/rebellabs/object-oriented-design-principles-and-the-5-ways-of-creating-solid-applications/)
[http://thetechnologistinyou.blogspot.fr/2012/09/solid-principles-quick-introduction.html](http://thetechnologistinyou.blogspot.fr/2012/09/solid-principles-quick-introduction.html)  
[http://blog.xebia.fr/2011/07/18/les-principes-solid/](http://blog.xebia.fr/2011/07/18/les-principes-solid/)    

[http://c2.com/cgi/wiki?XpSimplicityRules](http://c2.com/cgi/wiki?XpSimplicityRules)  
[http://xp.c2.com/YouArentGonnaNeedIt.html](http://xp.c2.com/YouArentGonnaNeedIt.html)  
[http://www.xprogramming.com/Practices/PracNotNeed.htm](http://www.xprogramming.com/Practices/PracNotNeed.htm) 
[http://c2.com/cgi/wiki?DontRepeatYourself](http://c2.com/cgi/wiki?DontRepeatYourself)   
[http://www.artima.com/intv/dry.html](http://www.artima.com/intv/dry.html)  
[https://pragprog.com/articles/tell-dont-ask](https://pragprog.com/articles/tell-dont-ask)   
[http://fr.wikipedia.org/wiki/Loi_de_D%C3%A9m%C3%A9ter](http://fr.wikipedia.org/wiki/Loi_de_D%C3%A9m%C3%A9ter)  
[http://articles.coreyhaines.com/posts/thoughts-on-pair-programming/](http://articles.coreyhaines.com/posts/thoughts-on-pair-programming/)  

[http://williamdurand.fr/2013/06/03/object-calisthenics/](http://williamdurand.fr/2013/06/03/object-calisthenics/)  
[http://fr.slideshare.net/KLabCyscorpions-TechBlog/object-calisthenics-34557136](http://fr.slideshare.net/KLabCyscorpions-TechBlog/object-calisthenics-34557136)  
[http://blog.netapsys.fr/devoxx-france-2014-les-object-calisthenics/](http://blog.netapsys.fr/devoxx-france-2014-les-object-calisthenics/)   

[http://www.gilzilberfeld.com/2014/06/no-srp-no-tdd.html](http://www.gilzilberfeld.com/2014/06/no-srp-no-tdd.html)  
[http://www.gilzilberfeld.com/2014/09/testability-good-design.html](http://www.gilzilberfeld.com/2014/09/testability-good-design.html)  
[http://blog.frankel.ch/your-code-coverage-metric-is-not-meaningful](http://blog.frankel.ch/your-code-coverage-metric-is-not-meaningful)   

[http://martinfowler.com/articles/workflowsOfRefactoring/](http://martinfowler.com/articles/workflowsOfRefactoring/)  

[http://www.duchess-france.org/code-retreat-mode-demploi-retour-sur-le-global-day-of-code-retreat-2011/](http://www.duchess-france.org/code-retreat-mode-demploi-retour-sur-le-global-day-of-code-retreat-2011/)
[http://www.pierregillon.com/2014/05/comment-modifier-du-code-spaghetti.html](http://www.pierregillon.com/2014/05/comment-modifier-du-code-spaghetti.html) 

[http://www.thoughtworks.com/insights/blog/introducing-software-testing-cupcake-anti-pattern](http://www.thoughtworks.com/insights/blog/introducing-software-testing-cupcake-anti-pattern)  
[http://martinfowler.com/bliki/TestPyramid.html](http://martinfowler.com/bliki/TestPyramid.html)  
[http://www.mountaingoatsoftware.com/blog/the-forgotten-layer-of-the-test-automation-pyramid](http://www.mountaingoatsoftware.com/blog/the-forgotten-layer-of-the-test-automation-pyramid)   

[http://www.extremeprogramming.org/](http://www.extremeprogramming.org/)  
[https://docs.google.com/presentation/d/1TzMhyTkZad9jsNe2sG_gUQ20bOpw8IGYqvsFrEZEZPk/edit#slide=id.p](https://docs.google.com/presentation/d/1TzMhyTkZad9jsNe2sG_gUQ20bOpw8IGYqvsFrEZEZPk/edit#slide=id.p)  

[http://pages.zeroturnaround.com/Java-Tools-Technologies.html?%20Technologies%202014](http://pages.zeroturnaround.com/Java-Tools-Technologies.html?%20Technologies%202014)  
[http://martinfowler.com/bliki/ContinuousDelivery.html](http://martinfowler.com/bliki/ContinuousDelivery.html)  
[http://www.itilfrance.com/index.php?pc=pages/docs/pratique-05/171-04.inc&pb=haut_ entete_pratique.inc](http://www.itilfrance.com/index.php?pc=pages/docs/pratique-05/171-04.inc&pb=haut_entete_pratique.inc)   
[http://blog.octo.com/devops-de-lintegration-continue-au-deploiement-continu/](http://blog.octo.com/devops-de-lintegration-continue-au-deploiement-continu/)  
[http://continuousdelivery.com/](http://continuousdelivery.com/)  
[http://blog.xebia.fr/2014/10/20/continuous-delivery-continuous-value-for-business-publie-dans-it-expert/](http://blog.xebia.fr/2014/10/20/continuous-delivery-continuous-value-for-business-publie-dans-it-expert/)  

[https://www.docker.com](https://www.docker.com)   
[https://www.docker.com/whatisdocker/](https://www.docker.com/whatisdocker/)  
[http://blog.ippon.fr/2014/04/14/docker-presentation-part-1/](http://blog.ippon.fr/2014/04/14/docker-presentation-part-1/)   

<!-- PDF --> 
[http://techtrends.xebia.fr/techtrends-xebia-craft.pdf](http://techtrends.xebia.fr/techtrends-xebia-craft.pdf)  
[http://techtrends.xebia.fr/](http://techtrends.xebia.fr/)  
[http://www.industriallogic.com/wp-content/uploads/2005/09/smellstorefactorings.pdf](http://www.industriallogic.com/wp-content/uploads/2005/09/smellstorefactorings.pdf)   
[http://lostechies.com/wp-content/uploads/2011/03/pablos_ solid_ebook.pdf](http://lostechies.com/wp-content/uploads/2011/03/pablos_solid_ebook.pdf)
[http://www.objectmentor.com/resources/articles/srp.pdf](http://www.objectmentor.com/resources/articles/srp.pdf)   
[http://www.objectmentor.com/resources/articles/ocp.pdf](http://www.objectmentor.com/resources/articles/ocp.pdf)   
[http://www.objectmentor.com/resources/articles/lsp.pdf](http://www.objectmentor.com/resources/articles/lsp.pdf)   
[http://www.objectmentor.com/resources/articles/isp.pdf](http://www.objectmentor.com/resources/articles/isp.pdf)   
[http://www.objectmentor.com/resources/articles/dip.pdf](http://www.objectmentor.com/resources/articles/dip.pdf)  
[http://www.cs.helsinki.fi/u/luontola/tdd-2009/ext/ObjectCalisthenics.pdf](http://www.cs.helsinki.fi/u/luontola/tdd-2009/ext/ObjectCalisthenics.pdf)  
[http://devlog.cnrs.fr/_ media/jdev2013/jdev2013/t6/t6p_ jdev13_ part2_test-agilite.pdf](http://devlog.cnrs.fr/_media/jdev2013/jdev2013/t6/t6p_jdev13_part2_test-agilite.pdf)   

<!-- Transparents--> 
[http://fr.slideshare.net/ElsassJUG/soire-qualit-logicielle-avec-sonar](http://fr.slideshare.net/ElsassJUG/soire-qualit-logicielle-avec-sonar)  
[http://fr.slideshare.net/jeromeavoustin/clean-code-en-pratique-14732075](http://fr.slideshare.net/jeromeavoustin/clean-code-en-pratique-14732075)  
[http://fr.slideshare.net/wokier/agile-france-2013-dette-technique-21893854](http://fr.slideshare.net/wokier/agile-france-2013-dette-technique-21893854)  
[http://fr.slideshare.net/cluelessjoe/coder-propre](http://fr.slideshare.net/cluelessjoe/coder-propre)  
[http://fr.slideshare.net/lemiorhan/coderetreat-practice-to-master-your-crafts](http://fr.slideshare.net/lemiorhan/coderetreat-practice-to-master-your-crafts)  
[http://fr.slideshare.net/rdohms/writing-code-you-wont-hate-tomorrow](http://fr.slideshare.net/rdohms/writing-code-you-wont-hate-tomorrow)  
[http://fr.slideshare.net/ClementBouillier/20131024-qualit-de-code-et-sonar-mug-lyon](http://fr.slideshare.net/ClementBouillier/20131024-qualit-de-code-et-sonar-mug-lyon)  
[http://fr.slideshare.net/ndeloof/docker-bdxio](http://fr.slideshare.net/ndeloof/docker-bdxio)  


### Illustrations
<!-- Twitter--> 
[https://twitter.com/francesc/status/449206943987793920](https://twitter.com/francesc/status/449206943987793920)  
[https://twitter.com/CiaranMcNulty/status/517654863623487488](https://twitter.com/CiaranMcNulty/status/517654863623487488)   
[https://twitter.com/mfeathers/status/504795462877323265](https://twitter.com/mfeathers/status/504795462877323265)    
[https://plus.google.com/113819754152966550582/posts/aoMQC2r92Gv](https://plus.google.com/113819754152966550582/posts/aoMQC2r92Gv)    
[https://twitter.com/Sniperovitch/status/509036332526886912](https://twitter.com/Sniperovitch/status/509036332526886912)  
[https://twitter.com/UberFacts/status/391968860435677185](https://twitter.com/UberFacts/status/391968860435677185)   
[https://twitter.com/nfonrose/status/523368648304766976](https://twitter.com/nfonrose/status/523368648304766976)   
<!-- Autres-->
[http://lesjoiesducode.fr/post/31452862688/quand-le-stagiaire-me-dit-que-les-tests-cest-pour](http://lesjoiesducode.fr/post/31452862688/quand-le-stagiaire-me-dit-que-les-tests-cest-pour) 
[http://memegenerator.net/instance/39432129](http://memegenerator.net/instance/39432129)  
[http://img0.mxstatic.com/wallpapers/92e875b279aa0e52dc1b5cc12443416a_large.jpeg](http://img0.mxstatic.com/wallpapers/92e875b279aa0e52dc1b5cc12443416a_large.jpeg)  
[http://lostechies.com/derickbailey/2009/02/11/solid-development-principles-in-motivational-pictures/](http://lostechies.com/derickbailey/2009/02/11/solid-development-principles-in-motivational-pictures/)   

[http://geek-and-poke.com/](http://geek-and-poke.com/)  
[http://uneviededev.wordpress.com/2014/09/18/le-syndrome-de-stockholm](http://uneviededev.wordpress.com/2014/09/18/le-syndrome-de-stockholm)   
[http://www.osnews.com/comics](http://www.osnews.com/comics)


### Facilitations graphiques
[http://itscertainlyuncertain.blogspot.de/2014/01/tdd-on-one-page.html](http://itscertainlyuncertain.blogspot.de/2014/01/tdd-on-one-page.html)  
[http://continuousdelivery.com/2014/02/visualizations-of-continuous-delivery](http://continuousdelivery.com/2014/02/visualizations-of-continuous-delivery)


### Vidéos 
La culture du programmeur : [https://www.parleys.com/play/53677169e4b0593229b8583f](https://www.parleys.com/play/53677169e4b0593229b8583f)   
Extremist Programming : l'art de s'amuser avec du code : [https://www.parleys.com/play/535f51ade4b03397a8eee8e0](https://www.parleys.com/play/535f51ade4b03397a8eee8e0)  
La voie du programmeur : [https://www.youtube.com/watch?v=njbBjVDoE2I](https://www.youtube.com/watch?v=njbBjVDoE2I)   
Software Craftsmanship par Antoine Vernois : [http://www.webtv.univ-montp2.fr/18704/agile-tour-montpellier-2013-avec-antoine-vernois](http://www.webtv.univ-montp2.fr/18704/agile-tour-montpellier-2013-avec-antoine-vernois)  
Chasser la dette technique de votre code source : [https://www.youtube.com/watch?v=d3XYhUikeIA](https://www.youtube.com/watch?v=d3XYhUikeIA)  
SOLID JavaScript In A Wobbly (World Wide Web) : [https://www.youtube.com/watch?v=TAVn7s-kO9o](https://www.youtube.com/watch?v=TAVn7s-kO9o)  
Du legacy au Cloud :  
[https://www.parleys.com/play/5148922a0364bc17fc56c85a/about](https://www.parleys.com/play/5148922a0364bc17fc56c85a/about)  
[https://www.parleys.com/play/5148922a0364bc17fc56c85c/about](https://www.parleys.com/play/5148922a0364bc17fc56c85c/about)  
[https://www.parleys.com/play/5148922a0364bc17fc56c85e/about](https://www.parleys.com/play/5148922a0364bc17fc56c85e/about)  
Le bon testeur il teste.... et le mauvais testeur il teste aussi : [https://www.parleys.com/play/535fa85be4b03397a8eee8e8/](https://www.parleys.com/play/535fa85be4b03397a8eee8e8/)


### Podcast 
[http://lescastcodeurs.com/](http://lescastcodeurs.com/)    
[http://unetassedethepodcast.com/](http://unetassedethepodcast.com/)  

### Quelques guildes de développeurs ...
[http://fierdetredeveloppeur.org/](http://fierdetredeveloppeur.org/)  
[http://www.humancoders.com/](http://www.humancoders.com/)  
[https://jecode.org/](https://jecode.org/)  
[http://www.brownbaglunch.fr/](http://www.brownbaglunch.fr/)  

[http://www.jtips.info/index.php?title=JavaUserGroups](http://www.jtips.info/index.php?title=JavaUserGroups)  
[http://lescastcodeurs.com](http://lescastcodeurs.com/)  
[http://www.devoxx.com](http://www.devoxx.com/)  
[http://www.devoxx.fr](http://www.devoxx.fr/)  
[http://www.duchess-france.org](http://www.duchess-france.org/)  
[http://codesorceresses.eu](http://codesorceresses.eu)  
[http://www.devoxx4kids.org/france](http://www.devoxx4kids.org/france/)  
[http://codinggouter.org](http://codinggouter.org)  
[http://codeweek.eu](http://codeweek.eu)  
[http://www.codeweekfrance.org](http://www.codeweekfrance.org)   

[https://plus.google.com/u/0/communities/115611122573484378363](https://plus.google.com/u/0/communities/115611122573484378363)  
[http://www.meetup.com/london-software-craftsmanship](http://www.meetup.com/london-software-craftsmanship/)   
[http://www.meetup.com/paris-software-craftsmanship](http://www.meetup.com/paris-software-craftsmanship)  
[http://www.meetup.com/Software-Craftsmanship-Toulouse](http://www.meetup.com/Software-Craftsmanship-Toulouse)  
[https://github.com/dojo-toulouse](https://github.com/dojo-toulouse) 
[https://groups.google.com/forum/#!forum/software-craftsmanship-toulouse](https://groups.google.com/forum/#!forum/software-craftsmanship-toulouse)   

------------------------
## Les tests au centre de la qualité logicielle : TDD – ATDD - BDD - Classification – Coding Dojo <a id="#tests_xDD"></a> 
 
### Livres
**xUnit Test Patterns: Refactoring Test Code By Gerard Meszaros**  
[http://xunitpatterns.com/](http://xunitpatterns.com/)

**Test Driven Development: By Example by Kent Beck**  
[http://www.informit.com/store/test-driven-development-by-example-9780321146533](http://www.informit.com/store/test-driven-development-by-example-9780321146533)  
[http://www.amazon.fr/Test-Driven-Development-By-Example/dp/0321146530](http://www.amazon.fr/Test-Driven-Development-By-Example/dp/0321146530)  

**Growing Object-Oriented Software Guided by Tests by Steve Freeman and Nat Pryce**  
[http://www.growing-object-oriented-software.com/](http://www.growing-object-oriented-software.com/)  

**Refactoring Improving the Design of Existing Code by Martin Fowler**
[http://martinfowler.com/books/refactoring.html](http://martinfowler.com/books/refactoring.html)

**Clean Code: A Handbook of Agile Software Craftsmanship by Robert C. Martin**
[http://www.objectmentor.com/resources/books.html](http://www.objectmentor.com/resources/books.html)  
[http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882](http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)

**Design Patterns : Elements of Reusable Object-Oriented Software By Erich Gamma, Richard Helm, Ralph Johnson, John Vlissides**  
[http://www.informit.com/store/design-patterns-elements-of-reusable-object-oriented-9780201633610](http://www.informit.com/store/design-patterns-elements-of-reusable-object-oriented-9780201633610)  
[http://www.amazon.fr/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612](http://www.amazon.fr/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612)  

**Head First Design Patterns By Eric Freeman, Elisabeth Robson, Bert Bates, Kathy Sierra**  
[http://shop.oreilly.com/product/9780596007126.do](http://shop.oreilly.com/product/9780596007126.do)  

**The Coding Dojo Handbook - a practical guide to creating a space where good programmers can become great programmers - by Emily Bache**  
[https://leanpub.com/codingdojohandbook](https://leanpub.com/codingdojohandbook)

**Mocks, Fakes and Stubs - and other techniques in Test Driven Development, illustrated with Code Katas - by Emily Bache**  
[https://leanpub.com/mocks-fakes-stubs](https://leanpub.com/mocks-fakes-stubs)

**ATDD by Example: A Practical Guide to Acceptance Test-Driven Development by Markus Gärtner**
[http://www.informit.com/store/atdd-by-example-a-practical-guide-to-acceptance-test-9780321784155](http://www.informit.com/store/atdd-by-example-a-practical-guide-to-acceptance-test-9780321784155)  
[http://www.infoq.com/articles/atdd-by-example-book](http://www.infoq.com/articles/atdd-by-example-book)  

**The RSpec Book: Behaviour-Driven Development with RSpec, Cucumber, and Friends by David Chelimsky, Dave Astels, Zach Dennis, Aslak Hellesøy, Bryan Helmkamp, Dan North**
[https://pragprog.com/book/achbd/the-rspec-book](https://pragprog.com/book/achbd/the-rspec-book)

**The Cucumber Book: Behaviour-Driven Development for Testers and Developers by Matt Wynne and Aslak Hellesøy**  
[https://pragprog.com/book/hwcuc/the-cucumber-book](https://pragprog.com/book/hwcuc/the-cucumber-book)

**BDD in Action - Behavior-Driven Development for the whole software lifecycle by John Ferguson Smart**  
[http://www.manning.com/smart/](http://www.manning.com/smart/)

**Agile Testing - A Practical Guide for Testers and Agile Teams by Lisa Crispin and Janet Gregory**
[http://agiletester.ca/](http://agiletester.ca/)  

**JUnit Mise en oeuvre pour automatiser les tests en Java de Benoit GANTAUME**  
[http://www.editions-eni.fr/livres/junit-mise-en-oeuvre-pour-automatiser-les-tests-en-java/.35747a537b05babdf613a9bffa1964f8.html](http://www.editions-eni.fr/livres/junit-mise-en-oeuvre-pour-automatiser-les-tests-en-java/.35747a537b05babdf613a9bffa1964f8.html)  
[http://www.junit.fr/](http://www.junit.fr/)

**Domain-Driven Design: Tackling Complexity in the Heart of Software by Eric Evans**
[http://www.amazon.fr/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215](http://www.amazon.fr/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215)

**Autres livres toujours utiles à consulter** :  
Tous ceux de la partie [Pas d'agilité sans excellence technique ! ... Découverte du mouvement Software Craftsmanship](#SoftwareCraftsmanship)


### Articles & Présentations
<!-- En Ligne -->  
[http://butunclebob.com/ArticleS.UncleBob.TheThreeRulesOfTdd](http://butunclebob.com/ArticleS.UncleBob.TheThreeRulesOfTdd)  
[http://codebetter.com/darrellnorton/2004/05/10/notes-from-test-driven-development-by-example-kent-beck/](http://codebetter.com/darrellnorton/2004/05/10/notes-from-test-driven-development-by-example-kent-beck/)  
[http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata](http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata)  

[http://www.codingdojo.org/cgi-bin/index.pl?KataCatalogue](http://www.codingdojo.org/cgi-bin/index.pl?KataCatalogue)  
[http://craftsmanship.sv.cmu.edu/katas](http://craftsmanship.sv.cmu.edu/katas)  
[https://github.com/emilybache/](https://github.com/emilybache/)

[http://blog.octo.com/coder-a-pas-de-chaton-a-lecole-du-tech-lead](http://blog.octo.com/coder-a-pas-de-chaton-a-lecole-du-tech-lead)  
[http://agileinaflash.blogspot.fr/2009/02/red-green-refactor.html](http://agileinaflash.blogspot.fr/2009/02/red-green-refactor.html)  

[http://www.gilzilberfeld.com/2014/06/no-srp-no-tdd.html](http://www.gilzilberfeld.com/2014/06/no-srp-no-tdd.html)  
[http://www.gilzilberfeld.com/2014/09/testability-good-design.html](http://www.gilzilberfeld.com/2014/09/testability-good-design.html)   

[http://martinfowler.com/articles/mocksArentStubs.html](http://martinfowler.com/articles/mocksArentStubs.html)  
[http://bruno-orsier.developpez.com/mocks-arent-stubs/](http://bruno-orsier.developpez.com/mocks-arent-stubs/)  
[http://stackoverflow.com/questions/4570303/using-tdd-top-down-vs-bottom-up](http://stackoverflow.com/questions/4570303/using-tdd-top-down-vs-bottom-up)  

[http://blog.ippon.fr/2011/10/03/eclipse-ameliorer-sa-productivite-grace-aux-raccourcis-clavier/](http://blog.ippon.fr/2011/10/03/eclipse-ameliorer-sa-productivite-grace-aux-raccourcis-clavier/)  
[http://blog.xebia.fr/2010/11/03/tdd-et-productivite/](http://blog.xebia.fr/2010/11/03/tdd-et-productivite/)  

[http://www.thoughtworks.com/insights/blog/introducing-software-testing-cupcake-anti-pattern](http://www.thoughtworks.com/insights/blog/introducing-software-testing-cupcake-anti-pattern)  
[http://www.duncannisbet.co.uk/test-automation-basics-levels-pyramids-quadrants](http://www.duncannisbet.co.uk/test-automation-basics-levels-pyramids-quadrants)  
[http://martinfowler.com/bliki/TestPyramid.html](http://martinfowler.com/bliki/TestPyramid.html)  
[http://www.mountaingoatsoftware.com/blog/the-forgotten-layer-of-the-test-automation-pyramid](http://www.mountaingoatsoftware.com/blog/the-forgotten-layer-of-the-test-automation-pyramid)    
[http://www.exampler.com/old-blog/2003/08/21/#agile-testing-project-1](http://www.exampler.com/old-blog/2003/08/21/#agile-testing-project-1)   
[http://gojko.net/2013/10/21/lets-break-the-agile-testing-quadrants/](http://gojko.net/2013/10/21/lets-break-the-agile-testing-quadrants/)   

[http://www.pierregillon.com/2013/08/bdd-behaviour-driven-development.html](http://www.pierregillon.com/2013/08/bdd-behaviour-driven-development.html)
[http://fitnesse.org/](http://fitnesse.org/)
[http://jbehave.org/](http://jbehave.org/)
[http://cukes.info/](http://cukes.info/)
[http://www.specflow.org/](http://www.specflow.org/)
[http://robotframework.org/](http://robotframework.org/)
[http://dannorth.net/introducing-bdd/](http://dannorth.net/introducing-bdd/)
[http://dannorth.net/2012/05/31/bdd-is-like-tdd-if/](http://dannorth.net/2012/05/31/bdd-is-like-tdd-if/)  
[http://lizkeogh.com/](http://lizkeogh.com/)
[http://unil.im/bdd](http://unil.im/bdd)  
[http://unil.im/bddrapide](http://unil.im/bddrapide)  
[http://arolla.developpez.com/tutoriels/java/bdd-with-jbehave/](http://arolla.developpez.com/tutoriels/java/bdd-with-jbehave/)  
[http://www.pierregillon.com/2013/10/bdd-lexemple-du-kata-potter.html](http://www.pierregillon.com/2013/10/bdd-lexemple-du-kata-potter.html)   
[http://www.infoq.com/fr/articles/virtual-panel-tdd-bdd](http://www.infoq.com/fr/articles/virtual-panel-tdd-bdd)  

<!-- PDF --> 
[http://lyjia.net/ressources/Les_ aventures_d_Alice.pdf](http://lyjia.net/ressources/Les_aventures_d_Alice.pdf)  
[http://www.cs.bgu.ac.il/~fsen141/wiki.files/class-5-TDD-short.pdf](http://www.cs.bgu.ac.il/~fsen141/wiki.files/class-5-TDD-short.pdf)   
[http://www.eecs.yorku.ca/course_ archive/2003-04/W/3311/sectionM/case_ studies/money/KentBeck_ TDD_byexample.pdf](http://www.eecs.yorku.ca/course_archive/2003-04/W/3311/sectionM/case_studies/money/KentBeck_TDD_byexample.pdf)  
[http://qualitycoding.org/files/BowlingGameObjective-C.pdf](http://qualitycoding.org/files/BowlingGameObjective-C.pdf)  
[http://www.cs.unm.edu/~rstehwien/CS580/lectures/TDD-2_Bowling%20Game%20Kata.pdf](http://www.cs.unm.edu/~rstehwien/CS580/lectures/TDD-2_Bowling%20Game%20Kata.pdf)
[http://devlog.cnrs.fr/_media/jdev2013/jdev2013/t6/jdev2013-fbo.pdf](http://devlog.cnrs.fr/_media/jdev2013/jdev2013/t6/jdev2013-fbo.pdf)  
[http://testobsessed.com/wp-content/uploads/2011/04/atddexample.pdf](http://testobsessed.com/wp-content/uploads/2011/04/atddexample.pdf)

<!-- Transparents--> 
[http://fr.slideshare.net/elapsetech/propulsez-votre-architecture-grce-au-tdd-et-aux-mocks](http://fr.slideshare.net/elapsetech/propulsez-votre-architecture-grce-au-tdd-et-aux-mocks)  
[http://fr.slideshare.net/mdclement/fizzbuzz-guided-kata](http://fr.slideshare.net/mdclement/fizzbuzz-guided-kata)  
[http://fr.slideshare.net/GuillaumeEhret/le-bon-testeur-il-teste-le-mauvais-testeur-il-teste](http://fr.slideshare.net/GuillaumeEhret/le-bon-testeur-il-teste-le-mauvais-testeur-il-teste)  
[http://fr.slideshare.net/michalczyzcs3b/outsidein-testing-step-by-step](http://fr.slideshare.net/michalczyzcs3b/outsidein-testing-step-by-step)   
[http://fr.slideshare.net/chassa/2013-0603specification-byexamplewithgherkinchristianhassa](http://fr.slideshare.net/chassa/2013-0603specification-byexamplewithgherkinchristianhassa)  
 
### Illustrations
<!-- Twitter--> 
[https://twitter.com/SciencePorn/status/502175592457187329](https://twitter.com/SciencePorn/status/502175592457187329)  
[https://twitter.com/web_ eau_net/status/426397428699258880](https://twitter.com/web_eau_net/status/426397428699258880) 
[https://twitter.com/grammarware/status/428835767285477376](https://twitter.com/grammarware/status/428835767285477376)
<!-- Joies du code--> 
[http://lesjoiesducode.fr/post/98960240314/quand-je-respecte-les-specs-du-client-a-la-lettre](http://lesjoiesducode.fr/post/98960240314/quand-je-respecte-les-specs-du-client-a-la-lettre)   
[http://www.commitstrip.com/fr/2014/10/15/when-i-thoroughly-follow-the-requirements/](http://www.commitstrip.com/fr/2014/10/15/when-i-thoroughly-follow-the-requirements/)  
<!-- Autres--> 
[https://uneviededev.files.wordpress.com/2014/09/sketchnote01.png](https://uneviededev.files.wordpress.com/2014/09/sketchnote01.png)  
[http://www.targetprocess.com/blog/2009/07/mind-maps-bdd-continuous-integration-design.html](http://www.targetprocess.com/blog/2009/07/mind-maps-bdd-continuous-integration-design.html)  

[http://www.growing-object-oriented-software.com/figures.html](http://www.growing-object-oriented-software.com/figures.html)  
[http://emmanuelchenu.blogspot.fr/search/label/Illustrations](http://emmanuelchenu.blogspot.fr/search/label/Illustrations)  
[http://emmanuelchenu.blogspot.fr/search/label/Caricatures/](http://emmanuelchenu.blogspot.fr/search/label/Caricatures/)  

### Facilitations graphiques
[http://itscertainlyuncertain.blogspot.de/2014/01/tdd-on-one-page.html](http://itscertainlyuncertain.blogspot.de/2014/01/tdd-on-one-page.html)  
repris dans le livre **Agile Planet** disponible sur : [https://leanpub.com/agileplanet](https://leanpub.com/agileplanet) 

### Vidéos 
Is TDD Dead? [http://martinfowler.com/articles/is-tdd-dead/](http://martinfowler.com/articles/is-tdd-dead/)
  
Du legacy au Cloud :  
[https://www.parleys.com/play/5148922a0364bc17fc56c85a/about](https://www.parleys.com/play/5148922a0364bc17fc56c85a/about)  
[https://www.parleys.com/play/5148922a0364bc17fc56c85c/about](https://www.parleys.com/play/5148922a0364bc17fc56c85c/about)  
[https://www.parleys.com/play/5148922a0364bc17fc56c85e/about](https://www.parleys.com/play/5148922a0364bc17fc56c85e/about)
  
Testing and Refacotoring Legacy Code Par Sandro Mancuso : [https://www.youtube.com/watch?v=WpKb1XqSiUs ](https://www.youtube.com/watch?v=WpKb1XqSiUs )

Legacy code refactoring for dummies (par Laurent Valdès et Sébastian Le Merdy)   
[http://www.xebia.tv/youtube?videoId=TKCOJDVMjtE](http://www.xebia.tv/youtube?videoId=TKCOJDVMjtE)  
[https://www.youtube.com/watch?v=TKCOJDVMjtE#t=14](https://www.youtube.com/watch?v=TKCOJDVMjtE#t=14)  
  
Le bon testeur il teste.... et le mauvais testeur il teste aussi : [https://www.parleys.com/play/535fa85be4b03397a8eee8e8/](https://www.parleys.com/play/535fa85be4b03397a8eee8e8/)


### Outils
[http://infinitest.github.com](http://infinitest.github.com/)  
[https://code.google.com/p/fest](https://code.google.com/p/fest)  
[https://github.com/alexruiz/fest-assert-2.x](https://github.com/alexruiz/fest-assert-2.x)   
[http://joel-costigliola.github.io/assertj](http://joel-costigliola.github.io/assertj/)  
[https://code.google.com/p/hamcrest](https://code.google.com/p/hamcrest)  
[http://hamcrest.org/](http://hamcrest.org/)  

[http://www.happyprog.com](http://www.happyprog.com)  

[http://projectlombok.org/](http://projectlombok.org/)  

[https://www.jetbrains.com/estore/students/](https://www.jetbrains.com/estore/students/)  
[https://www.jetbrains.com/idea/help/tutorials.html](https://www.jetbrains.com/idea/help/tutorials.html)   


------------------------
## La Rétrospective en pratique : Ateliers, Agiles Games & Innovation Games <a id="#retro"></a> 
 
### Livres
**Agile Retrospectives: Making Good Teams Great by Esther Derby and Diana Larsen**
[https://pragprog.com/book/dlret/agile-retrospectives](https://pragprog.com/book/dlret/agile-retrospectives)  

**Project Retrospectives: A Handbook for Team Reviews by Norman Kerth**
[http://www.informit.com/store/project-retrospectives-a-handbook-for-team-reviews-9780133488579](http://www.informit.com/store/project-retrospectives-a-handbook-for-team-reviews-9780133488579)  

**Tirer profit des rétrospectives agiles - Une boîte à outils d'activités de rétrospective par Luis Gonçalves et Ben Linders**  
[https://leanpub.com/gettingvalueoutofagileretrospectives_FR](https://leanpub.com/gettingvalueoutofagileretrospectives_FR)  

**The Culture Game by Daniel Mezick**  
[http://newtechusa.net/about/the-culture-game-book/](http://newtechusa.net/about/the-culture-game-book/)  
Version française minibook : **Jeu de Culture: Outils pour le manager agile traduit par Olivier Destrade**  
[http://www.infoq.com/fr/minibooks/Mezick-Culture-game](http://www.infoq.com/fr/minibooks/Mezick-Culture-game)  


### Articles & Présentations
<!-- En Ligne -->  
[http://guide.agilealliance.org/guide/heartbeatretro.html](http://guide.agilealliance.org/guide/heartbeatretro.html)  
[http://referentiel.institut-agile.fr/retro.html](http://referentiel.institut-agile.fr/retro.html)  
[http://referentiel.institut-agile.fr/heartbeatretro.html](http://referentiel.institut-agile.fr/heartbeatretro.html)  
[http://agilemanifesto.org/iso/fr/principles.html](http://agilemanifesto.org/iso/fr/principles.html)  

[http://fr.wikipedia.org/wiki/Roue_de_Deming](http://fr.wikipedia.org/wiki/Roue_de_Deming)  
[http://qualite-aquitainepdca.com/apropos/methode-pdca](http://qualite-aquitainepdca.com/apropos/methode-pdca/)  

[http://ayeba.fr/2014/02/la-retrospective-cle-de-lamelioration-continue](http://ayeba.fr/2014/02/la-retrospective-cle-de-lamelioration-continue)  
[http://www.qualitystreet.fr/2008/08/28/retrospectives-des-moments-cles](http://www.qualitystreet.fr/2008/08/28/retrospectives-des-moments-cles/)  

[http://www.mccarthyshow.com/core-community](http://www.mccarthyshow.com/core-community/)  
[http://www.mccarthyshow.com/download-the-core](http://www.mccarthyshow.com/download-the-core/)  
[http://www.infoq.com/interviews/mccarthy-core-protocols](http://www.infoq.com/interviews/mccarthy-core-protocols)   

[http://www.perfectiongame.org](http://www.perfectiongame.org)  
[http://fredericmirman.blogspot.fr/2012/10/evalutation-iterative-le-perfection-game.html](http://fredericmirman.blogspot.fr/2012/10/evalutation-iterative-le-perfection-game.html)   
[http://partageons-ce-qui-nous-departage.com/perfection-game](http://partageons-ce-qui-nous-departage.com/perfection-game)  
[http://www.fabrice-aimetti.fr/dotclear/index.php?tag/Jeu](http://www.fabrice-aimetti.fr/dotclear/index.php?tag/Jeu)  
[http://www.benlinders.com/2014/getting-feedback-with-the-perfection-game/](http://www.benlinders.com/2014/getting-feedback-with-the-perfection-game/)  
[http://www.methodsandtools.com/archive/archive.php?id=106](http://www.methodsandtools.com/archive/archive.php?id=106)  
[http://unil.im/m3301pf](http://unil.im/m3301pf)  

[http://www.qualitystreet.fr/2010/06/18/truc-de-coach-etes-vous-la-meilleure-equipe-de-la-planete/](http://www.qualitystreet.fr/2010/06/18/truc-de-coach-etes-vous-la-meilleure-equipe-de-la-planete/)  

[http://innovationgames.com/speed-boat/](http://innovationgames.com/speed-boat/)  
[http://www.qualitystreet.fr/2011/09/15/un-speed-boat-sinon-rien/](http://www.qualitystreet.fr/2011/09/15/un-speed-boat-sinon-rien/)  
[http://blogs.versionone.com/agile_management/2011/07/01/reinvigorated-retrospectives/](http://blogs.versionone.com/agile_management/2011/07/01/reinvigorated-retrospectives/)  
[http://kannallc.com/?p=151](http://kannallc.com/?p=151)  
[http://xnopre.blogspot.fr/2012/12/speed-boat-pour-etat-des-lieux.html](http://xnopre.blogspot.fr/2012/12/speed-boat-pour-etat-des-lieux.html)   

[http://blog.octo.com/animer-des-retrospectives-diteration/](http://blog.octo.com/animer-des-retrospectives-diteration/)  

[http://www.qualitystreet.fr/2010/11/30/return-on-time-invested-le-roti-en-image-et-le-lean-en-pratique/](http://www.qualitystreet.fr/2010/11/30/return-on-time-invested-le-roti-en-image-et-le-lean-en-pratique/)   

[http://agilepartnership.com/blogit/2010/06/02/are-we-only-having-fun/](http://agilepartnership.com/blogit/2010/06/02/are-we-only-having-fun/)  

[http://www.agilaction.com/que-faire-quand-votre-retrospective-sessouffle/](http://www.agilaction.com/que-faire-quand-votre-retrospective-sessouffle/)   
[http://retrospectives-agiles.fr/](http://retrospectives-agiles.fr/)  
[http://www.gogamestorm.com/?tag=luke-hohmann&paged=2](http://www.gogamestorm.com/?tag=luke-hohmann&paged=2)  
[http://www.aubryconseil.com/post/Innovation-et-jeux-a-Paris](http://www.aubryconseil.com/post/Innovation-et-jeux-a-Paris)  

[http://www.romanpichler.com/blog/product-owner-sprint-retrospective/](http://www.romanpichler.com/blog/product-owner-sprint-retrospective/)  

<!-- PDF --> 
[http://www.fabrice-aimetti.fr/dotclear/public/traductions/Perfection_Game.pdf](http://www.fabrice-aimetti.fr/dotclear/public/traductions/Perfection_Game.pdf)    
<!-- Transparents--> 
[http://fr.slideshare.net/yannickgrenzinger/apprendre-a-apprendre](http://fr.slideshare.net/yannickgrenzinger/apprendre-a-apprendre)  
[http://fr.slideshare.net/glours/innovation-game-rtrospective](http://fr.slideshare.net/glours/innovation-game-rtrospective)  
[http://fr.slideshare.net/FlorianChauveau/agilit-les-perfection-games-en-action](http://fr.slideshare.net/FlorianChauveau/agilit-les-perfection-games-en-action)  
[http://fr.slideshare.net/YvesHanoulle/the-core-protocols-zen](http://fr.slideshare.net/YvesHanoulle/the-core-protocols-zen)  

### Illustrations
<!-- Twitter--> 
[https://twitter.com/romaincouturier/status/513993899241897985](https://twitter.com/romaincouturier/status/513993899241897985)
<!-- Autres--> 
[http://www.qualitystreet.fr/2010/11/30/return-on-time-invested-le-roti-en-image-et-le-lean-en-pratique/](http://www.qualitystreet.fr/2010/11/30/return-on-time-invested-le-roti-en-image-et-le-lean-en-pratique/)  


### Facilitations graphiques
[http://itscertainlyuncertain.blogspot.fr/2014/01/retrospectives-on-one-page.html](http://itscertainlyuncertain.blogspot.fr/2014/01/retrospectives-on-one-page.html)   
repris dans le livre **Agile Planet** disponible sur : [https://leanpub.com/agileplanet](https://leanpub.com/agileplanet) 


### Vidéos 
Video de présentation des Innovation games : 
[https://www.youtube.com/watch?v=fP4QSIB-mbw ](https://www.youtube.com/watch?v=fP4QSIB-mbw )


------------------------
## Quid de l'agilité aujourd'hui ? <a id="#quidAgile"></a> 

### Articles & Présentations
<!-- En Ligne -->  
[https://www.rallydev.com/community/agile/no-more-business-usual](https://www.rallydev.com/community/agile/no-more-business-usual)  
[http://blog.octo.com/mon-projet-est-il-agile/](http://blog.octo.com/mon-projet-est-il-agile/)  

[http://www.agilaction.com/lagilite-en-chiffre/](http://www.agilaction.com/lagilite-en-chiffre/)
<!-- PDF -->   
[http://www.versionone.com/pdf/2013-state-of-agile-survey.pdf](http://www.versionone.com/pdf/2013-state-of-agile-survey.pdf)  
<!-- Transparents--> 
[http://fr.slideshare.net/RomainKuzniak/quest-ce-quune-bonne-appication](http://fr.slideshare.net/RomainKuzniak/quest-ce-quune-bonne-application)   

### Illustrations
<!-- Autres--> 
[http://pm.versionone.com/AgilePoster.html](http://pm.versionone.com/AgilePoster.html)  
[http://guide.agilealliance.org/subway.html](http://guide.agilealliance.org/subway.html)   


------------------------
Une autre proposition ?
------------------------
## Titre <a id="nomAncre"></a> 
### Livres
### Articles & Présentations
<!-- En Ligne -->  
<!-- PDF --> 
<!-- Transparents--> 
### Illustrations
<!-- Twitter--> 
<!-- Joies du code--> 
<!-- Autres--> 
### Facilitations graphiques
### Jeux
### Vidéos 
### Outils numériques 
### Google Group


