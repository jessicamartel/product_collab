---
title: "Guide pratique d'une methologie collaborative dans le developpement ou la refonte de features"
date: 2022-07-06
image: /images/afupday2022.jpg
tags:
  - afup
  - collaboration
  - produit
  - UX
  - UX Research
draft: false
---
Vous avez la sensation d’arriver en bout de chaîne ? De développer des maquettes irréalisables ou des features dont vous ne comprenez pas le sens ? Si cela vous parle, il y a une solution !

Je vous propose de vous présenter une méthodologie UX inclusive et transversale qui fonctionne pour le développement de nouvelles features. Que ce soit le développement d’une messagerie interne ou la refonte d’un tunnel de vente, nous allons détailler une méthodologie éprouvée à travers ces deux exemples très différents pour vous montrer ce qui peut fonctionner et quelles sont les clés du succès.

De la constitution d’une équipe mixte composée de personnes tech et fonctionnelles, à la rédaction des specs techniques et fonctionnelles en passant par la recherche UX, les workflow et les maquettes, nous analyserons en détail les étapes de cette méthode. Ce guide pratique pourra ensuite être utilisé par morceaux ou en intégralité selon vos besoins, vos ressources, votre produit et les spécificités de votre entreprise.

Si vous voulez vous investir aux côtés de vos équipes produit ou si vous manquez de ressources internes (product owner/manager, chef.fe.s de projets etc.), si vous êtes freelance et devez accompagner vos clients dans le cadrage des projets ou simplement si vous souhaitez en apprendre plus sur la partie amont du développement cette conférence est faite pour vous.

<!-- excerpt -->

##Ma conférence "Guide pratique d'une méthodologie UX pour la conception de features" présentée à l'afup day 2022.

Le 20 mai 2022 j'ai eu la chance de présenter une conférence à l'[Afup day](https://event.afup.org/afup-day-2022/programme/), organisé par l'Afup Haut de France.

Fin 2021, un collègue PM de chez Dougs m'avait invité à parler au sein de son entreprise d'une méthodologie que j'applique au quotidien et que je lui avait présentée pour répondre à certains de ces enjeux.

Afin que cela soit utile au plus grand nombre de personne, vous pouvez retrouver ici la transcription de cette conférence ainsi que les slides qui sont expliqués directement ici pour permettre une meilleure accessibilité (n'hesitez pas si pour vous ce n'est pas optimal, je serais ravie de vous la representer en direct où à faire les corrections nécessaires).


#### Script 

Je suis Jessica Product manager chez [Unow](www.unow.fr) un organisme de formation en ligne avec un accompagnement expert. 

Je travaille principalement sur notre LMS (learning management system) ou plateforme de formation que nous développons en interne.

Précédemment je travaillais chez Decitre, un site de vente en ligne de livre qui gérait également plusieurs sites e-commerce en marque blanche sur le même thème. 

Le guide pratique que je vais vous présenter a été initié grâce à un mélange entre des techniques de gestion projet, l’UI-Kit de l’UX-researcher Stephanie Walter et des valeurs personnelles. 

Tel Alexandre Astier qui a adapté la méthode Vogler lorsqu’il a conçu Kaamelott, je vous invite vous aussi à adapter mes propos à vos besoins. Une méthode n’est pas immuable, elle vis à travers vous.

je vais vous présenter une méthodologie pour le développement de feature applicable dans à peu près tous les contextes. Je vais illustrer cela avec deux exemples: le développement d’une messagerie interne un sujet purement produit et la refonte d’un tunnel de vente, une problématique plutôt e-commerce. 

####Avant toute chose : il faut construire une équipe projet. 

Ca semble évident mais il est fréquent d’avoir un pilote de projet qui fait toute la partie amont seul avant que cela ne passe en dev.  

Pour moi, la construction d’une équipe projet est au cœur de la réussite de cette méthode ; pour valoriser le projet en interne et le mener à son terme. 

Elle permet de répondre à trois enjeux : 
- Obtenir l’adhésion globale.
- Apporter des cultures différentes.
- Explorer tous les besoins.

Idéalement, vous souhaitez rassembler: 
- Un ou une PO/PM.
- Un ou unee designer ou Product designer.
- Un membre de l’équipe majoritairement impactée.
- et Une ou plusieurs devs

####Je vous propose de découper notre méthode en 4 étapes, 4 actions à entreprendre. 

Étape 1 : Le Product concept : Pourquoi ? Pour qui ?
Etape 2 : UX research ou Audit : Qu'est-ce qui existe / est possible ? 
Étape 3 : User journey et les workflow : ici on va répondre à Quoi ? Comment ?
enfin Étape 4 : les Specs et le design : Qu’est-ce qu’on va faire et comment on va le faire?  

####Étape 1 : Le Product concept : Pourquoi ? Pour qui ?
On cherche à savoir pourquoi on veut faire cette feature et pour qui. 
On va donc lister de façon exhaustive les cas d’utilisations.
En dégager les besoins associés.
et Identifier les criticités s’il y en a.

Pour l'illustrer, je vais vous montrer à quoi ressemblait notre document pour la refonte d’un tunnel de vente.
Pour cette transcription ecrite voici l'explication :
Nous avions un cas pour commander en retrait magasin un produit en stock. 
Le panier, l’identification et le paiement étaient donc des étapes obligatoires dans excel on represente cela avec une crois, un X.

L’étape de la livraison était critique et présentait un point de vigilance particulier puisqu’il fallait bien identifier le magasin, on représente cela visuellement dans excel avec un triangle orange et l’étape de facturation pouvait être allégée car le magasin pouvait prendre le relais au moment du retrait, on représente cela avec une vague violette.

Par alléger j’entends décharger l'espace visuelle et mettre les informations strictement nécessaires un peu comme pour la création de compte vous pouvez demander soit l’adresse email et le mot de passe ou alors toutes les informations d’adresse, la date de naissance etc. 



####Etape 2 : UX research / Audit : Qu'est-ce qui existe / est possible ? 

Elle peut se faire en parallèle  de l’étape 1. 

La phase d’UX et/ou user research sert à connaître les besoins et ce qui est possible. On représente ça sous forme de WBS (work break down structure), une technique qui permet de bien saisir chaque grain qui compose une feature et, comme on se base sur des comparaisons de l'existant, on vise à couvrir tous les grains possibles pour la feature qui nous intéresse. 

A la base c’est une méthode de management de projet qui permet le découpage hiérarchique en livrables spécifiques des travaux à réaliser.

Prenons l’exemple d’une construction de maison : On identifie les grosses phases par exemple, la conception, la réservation des entreprises, la construction et ensuite on découpe en chantiers par exemple Électricité, plomberie, chauffage. On peut ensuite même imaginer découper plus avec par exemple : panneau électrique, fibre etc 
Dans notre cas on fait pareil pour la feature par exemple dans l’étape  livraison j’ai besoin d’avoir : Une adresse, un numéro etc. Ca ressemble visuellemùent à un organigramme de avec des taches majeures "parents" et des sous taches "enfants".


####Étape 3 : Le parcours utilisateur et les workflow : Quoi ? Comment ?

On crée le parcours utilisateur macro qui permet de répondre à la question Quelles sont les étapes de ma feature ? En se basant sur ce qui existe mais surtout sur nos besoins.

Une des spécificités de cette méthode c’est que plutôt que de faire une userjourney très micro, classique comme je me connecte à ma messagerie, je clique sur l’enveloppe  pour envoyer un message, on va se concentrer sur les grandes étapes indispensables: Accéder à sa boite, envoyer un message, recevoir un message.

Une fois qu’on a nos grandes étapes, on reprend nos grains définis dans l'étape 2 Research et on se pose sur chacun d’eux pour savoir si on les veut ou pas en fonction des différents cas et besoins ainsi que leur niveau de criticité que l’on avait défini à l’étape 1. 

Par exemple, nous avions vu dans le cadre de messageries institutionnelles qu’il y avait des numéros de demandes attribués à chaque message on a estimé que dans notre contexte cela ne répondait à aucun besoin et nous avons décidé d’exclure cette tâche de notre scope.



D’un point de vue pratique nous utilisons un tableau excel assez classique pour faire ca avec les étapes sous divisées en 4 catégories (Essentiel, secondaire, bof et non) et on classe chacun de nos grains et des éléments vus dans les colonnes pour voir à quelle étape on veut le grain et si on le veut ou pas. En général nous prenons en MVP les besoins essentiels, puis les besoins secondaires s’ils ne sont pas compliqués et on laisse tomber ceux des autres colonnes pour notre contexte. 

Chacune des étapes précédentes bien que indépendantes finissent pas se synchroniser. 

On peut maintenant créer les différents workflows pour représenter les parcours utilisateurs définitifs et les ramifications entre eux


Prenons l’exemple de la messagerie ici. Pour l’expert de la formation Unow il va y avoir trois chemins d’utilisations, via la connexion à la messagerie, via un profil participant ou participante et via la réception d’un message. L’objectif de cette étape des workflow est de faire tout le parcours tout ce qui va suivre ces trois chemins et nous aurons donc trois workflow pour cet utilisateur, il faut faire cette démarche pour chaque profil d’utilisateur ou utilisatrice de la feature. Visuellement cela peut ressembler à une mind map où on déroule chaque chemin à partir d'un profil.

Avec tous ces éléments on peut passer à la dernière étape.


####l’ Étape 4 : les Specs et le design : Qu’est-ce qu’on va faire et comment ?  

On élabore 3 types de specs: 
Les spécs fonctionnelles : PM + une personne de l’équipe métier concernée l’objectif est de balayer tous les cas d’usages, de définir les règles métiers en détails et de définir ce qui relève du MVP ou de futures versions. Par exemple, on va définir ici dans le cadre de notre messagerie si le mail de réception d’un nouveau message doit être envoyé en temps réel ou une fois par jour à quelle heure etc.

On définit également ici les KPI qui sont les indicateurs mesurables pour suivre l’utilisation de la feature. Les kpi servent dans un premier temps à mesurer que ce qu’on fait répond au besoin, ensuite ça permet d’objectiver des futures évolutions. On définit des KPi idéaux et on affine ensuite en même temps que vie la feature.

Ensuite le ou la PM travaille avec l’équipe technique les spécs techniques. Le but est de vérifier l'exhaustivité des specs : souvent les développeurs et développeuses permettent à cette étape de donner des précisions importantes qui ont été ratées aux étapes précédentes. Comme ils et elles ont une parfaite connaissance de la manière dont est structurée la donnée et de l’historique des erreurs possibles l’apport de cette étape est considérable. 

Enfin les devs proposent une découpage en lots techniques cohérents fonctionnellement qu’on présente aux métiers pour une livraison en continu. On écrit également à ce stade des scénarii de tests fonctionnels automatisés qui seront mis en place. 


Enfin l'équipe design fait des wireframe puis des maquettes UI pour servir d’appui visuel pour les devs mais aussi pour prototyper la feature et les lots afin d’en faire la démonstration aux personnes décisionnaires et/ou aux users.



Si vous appliquez ce guide de bout en bout avec toutes les étapes et surtout avec les membres impliqués vous avez une feature qui est comprise par tout le monde, qui est fonctionnelle et répond à vos besoins. 

Elle a été éprouvée dans différents contextes avec différentes équipes. 

C’est une méthode modulable que vous pouvez découper pour ne prendre que ce qui vous intéresse selon la configuration de votre entreprise, vos équipes ou les ressources que vous pouvez allouer au projet. 


####Mais il y a quand même des limites, c'est important de les connaître pour maîtriser votre projet.

C’est une méthode d’envergure dont l’aboutissement peut être remis en question en fonction des évolutions stratégiques. Il y a un risque de devoir réduire le périmètre de la feature. 

Elle n’est pas adaptée en l’état dans le cas d’une refonte de parcours car les étapes sont plus variables avec différents parcours qui s’imbriquent. 

Il y a plus de subjectivité dans les attendus, il faut parfois faire preuve de convictions et pas seulement s’appuyer sur des données car les parcours sont très dépendants du contexte et des spécificités produits. Un seul et même parcours peut répondre à des besoins et des supports multiples et toucher plus d’acteurs.


D’ailleurs, je teste une nouvelle méthodologie conçue pour ce genre de parcours chez Unow en ce moment, on pourra peut-être en parler une prochaine fois ?

Merci de m’avoir écouté.



### Conclusion

Présenter cette conférence lors d'un evenement était une première et un gros challenge personnel c'était moins évident que de le présenter en événement privé comme j'avais déjà pu le faire car je devais rester sur des exemples généralistes car le public était mixte mais c'était une occasion en or pour présenter mes convictions sur l'importance de la collaboration entre les équipes techs et produits et l'intêret d'une culture plurielle en interne.

La communauté de l'AFUP était d'une extreme bienveillance, je recommande vraiment de commencer par là si vous voulez vous lancer dans le partage de vos connaissances. Les conférences sont compréhensible par toutes et tous et quand elles sont un peu compliquées, elles sont dynamiques et on apprend toujours quelque chose même si nous ne sommes pas developpeur ou developpeuse.La preuve : ce blog est né suite à la présentation d'[Arnaud](https://twitter.com/ArnaudLigny) sur sa solution [Cecil](https://cecil.app/fr/).
J'ai rencontré des co-conférenciers et conférencières d'un grand soutien alors qu'on ne se connaissait pas, idem pour les Duchess rencontrées pour la première fois physiquement. 

J'ai pu avoir de riches échanges après la conférence auprès de personnes intéressées avec des questions spécifiques à leur secteur et organisation, si c'est le cas pour vous à la lecture de cet article, n'hesitez surtout pas à venir me contacter ca me fera vraiment plaisir.

> Slides: [Guide pratique d'une méthodologie UX pour la conception de features](https://docs.google.com/presentation/d/1uppRL52qhkdhXulx1zpE6KgO9bLS0MUzIN2ru7TN03s/edit?usp=sharing)
