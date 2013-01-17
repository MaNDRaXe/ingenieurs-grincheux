############################################################################################
Soin et alimentation des ingénieurs informatique (ou pourquoi les ingénieurs sont grincheux)
############################################################################################

:date: 2012-07-19 20:04
:tags: traduction, développeurs 
:category: Informatique
:author: MaNDRaXe
:slug: ingenieurs-grincheux


--------------------

**Préambule**

Suite à la lecture du billet `"The care and feeding of software engineers (or, why engineers are grumpy)"`__ écrit par `Nicholas C. Zakas`__\, `Bertrand Tornil`__ et moi-même avons été frappés par sa pertinence et avons décidés de le diffuser autour de nous. Malheureusement, la barrière de la langue n'a pas permis une diffusion aussi large que nous le voulions. C'est pourquoi nous nous sommes attelés à sa traduction que nous vous proposons ici.

.. __ : http://www.nczonline.net/blog/2012/06/12/the-care-and-feeding-of-software-engineers-or-why-engineers-are-grumpy/
.. __ : http://nczonline.net/
.. __ : http://www.tornil.me/

Si vous avez des améliorations à y apporter, n'hésitez pas à nous en faire part. Le meilleur moyen étant de proposer une (ou plusieurs) pull request sur le `projet github`__\. Bien que nous encouragions la diffusion de ce texte, et que nous mettions cette traduction à disposition librement, nous ne sommes bien sûr pas les détenteurs des droits du texte original. Référez-vous en à l'auteur original pour toute utilisation que vous voudriez en faire.

.. __ : https://github.com/MaNDRaXe/ingenieurs-grincheux

----------------------------------

Soin et alimentation des ingénieurs informatique (ou pourquoi les ingénieurs sont grincheux)
============================================================================================

Il n'y a pas si longtemps, Jenna Bilotta a écrit un excellent article intitulé "How designers and engineers can play nice" [1]_ (NdT: Comment faire travailler main dans la main designers et développeurs), dans lequel elle aborde les
façons de faire travailler ensemble plus productivement les designers et les ingénieurs. Ayant été confronté aux mêmes soucis en travaillant avec des designers (mais aussi avec des ingénieurs lorsque j'étais du côté interface utilisateur), j'ai apprécié l'approche pragmatique qu'elle suggère. Il est toujours bénéfique de respecter les méthodes de travail des autres intervenants et de comprendre leur façon de penser lorsque l'on travaille ensemble.

Elle préconise notamment aux ingénieurs de ne pas dire "non" si vite. Cela m'a interpellé et m'a trotté dans la tête un moment. Ma première réaction a été "mais vous ne comprenez pas pourquoi nous disons non !". Puis un million d'autres justifications me sont venues à l'esprit. En fait, elle a raison. Nous disons "non" très vite et pas seulement aux designers, mais à tout. Cela m'a amené à réfléchir à la psychologie des ingénieurs informatique et à ce qui fait que nous fonctionnons comme nous le faisons.


Notre réputation
================

Jouons carte sur table, les développeurs ont généralement la réputation d'être arrogants, désagréables et lunatiques. Nous avons aussi la réputation de dire "non", de débattre de détails insignifiants et de prétendre savoir mieux faire le travail de n'importe qui d'autre mieux qu'eux. En général cette réputation est justifiée. C'est exactement ce que nous faisons presque tous les jours, tout comme nous codons tout en surveillant Twitter et Hacker News (NdT : site d'information concernant le développement informatique).

(Note : Certains diront que ce n'est pas vrai de tous les développeurs et ils auront raison. Il y a un petit nombre de développeurs pour qui tout ou partie de ce qui vient d'être dit est faux. Mais s'il vous plaît, avant de descendre en bas de cet article et poster un commentaire pour me dire à quel point tout cela est stupide, continuez la lecture.)

Les réputations ne se font pas aléatoirement, elles sont le fruit de l'expérience des gens. Ce qui me dérange dans cette réputation est que je connais personnellement de nombreux développeurs et qu'ils aiment généralement s'amuser, sont ouverts à la discussion (si il ne s'agit pas de sujet dogmatique) et sont d'une compagnie agréable. Ils font partie des gens avec qui l'on a envie de passer du temps hors du boulot. Alors comment ce fait-il que dans un environnement professionnel une autre personnalité apparaisse ?


Créatifs, pas ouvriers
======================

J'ai une théorie. Cette théorie est que les développeurs se perçoivent d'une façon très différente de la façon dont les perçoivent ceux avec qui ils travaillent. J'en suis arrivé à cette conclusion après plus d'une décennie de travail dans l'industrie logicielle au sein de grandes et petites entreprises. Les entreprises (chefs de produit, designers, et managers) ont tendance à voir les développeurs comme des ouvriers. C'est le travail du chef de produit d'imaginer quoi fabriquer, le travail du designer de le rendre esthétique et le travail de l'ingénieur de construire l'aboutissement de leurs réflexions. Concrètement, les développeurs sont vus comme les exécutants de cette industrie.

Il s'agit de quelque chose à propos duquel mon tout premier responsable m'a mis en garde. Lorsque la première entreprise dans laquelle j'ai travaillé a fermé, nous avons eu une discussion franche concernant ma carrière. Bien que nous n'ayons pas toujours été en accord, il m'a donné un excellent conseil (que je paraphrase ici) :

	*Nicholas, tu vaux mieux que ton code. Quelle que soit la suite de tes aventures, assure-toi de ne pas être un simple exécutant. N'accepte pas un poste où l'on te dit exactement ce que tu dois faire et comment le faire. Tu as besoin de travailler dans un environnement qui apprécie tes propositions autant que ta capacité à les réaliser.*

Il avait tout à fait raison. De nombreuses sociétés veulent des exécutants, ils veulent des programmeurs et des ouvriers qui marchent au pas et restent dans le rang. À vrai dire je dirais que la plupart des sociétés veulent ça, qu'elles soient grandes ou petites. Je ne pourrais dénombrer la quantité de start-ups qui m'ont contacté pour m'offrir d'être associé en échange du développement de la vision du fondateur. Sous entendu : nous savons déjà exactement ce que nous voulons faire, nous avons juste besoin de quelqu'un pour l'exécuter.

Et c'est bien là que se situe le noeud du problème : les développeurs ne sont pas des ouvriers. Les développeurs sont des créateurs. Construire quelque chose c'est ce que vous faites lorsque vous achetez un meuble chez Ikea et que vous le ramenez à la maison. Les instructions de montage sont écrites sur un papier et si vous les suivez étape par étape, vous obtiendrez la si jolie petite table que vous désiriez tant. Créer est un tout autre processus qui donne naissance à quelque chose sans indication ni instruction. Cela consiste à partir d'une feuille blanche pour aboutir à une toile de maître. Les développeurs ne se mettent pas au développement parce qu'ils veulent que quelqu'un leur dise ce qu'ils doivent faire, ils se mettent au développement parce qu'ils ont découvert qu'ils pouvaient créer des choses utiles. Chaque développeur tombe amoureux du développement parce qu'il a fait un jour un petit programme utile et qu'il y est devenu accro.

Dans le triumvirat du logiciel constitué des chefs de produit, des designers et des développeurs, il n'y a que des développeurs que l'on attend qu'ils fassent taire leur esprit créatif et se contentent de produire. Les développeurs ne sont pas stupides, ils le voient bien et se mettent à éprouver du ressentiment. Les développeurs veulent faire partie du processus créatif et cela leur est refusé. En fin de compte vous vous retrouvez avec la personnalité typique des développeurs agrémentée de mauvaise humeur.


Mais alors quel est le problème ?
=================================

Les chefs de produits sont des gens intéressants. Leurs idées ainsi que leur capacité à comprendre le marché sont impressionnants. Ils ont aussi une certaine tendance à croire que leurs idées sont totalement abouties alors qu'en réalité il y a des trous si grands que l'on pourrait y faire passer des trains complets. Je le dis avec beaucoup d'affection, car j'ai de nombreux amis chefs de produit, mais ils savent bien ce que je pense car je le leur ai déjà dit de vive voix à un moment ou un autre. Il ne s'agit pas là d'une critique des chefs de produit, c'est juste dans leur nature. Leur travail est créatif et les idées n'apparaissent jamais totalement abouties. Mais c'est bien l'un des éléments qui rend les développeurs grincheux.

Les développeurs aussi bien que les chefs de produits ont tendance à croire, à tort, que des spécifications et prérequis équivalent à un manuel de montage de chez Ikea. Dans les faits ces documents contiennent rarement assez d'informations pour concrètement construire le produit et ne sont généralement qu'un point de départ. Et cela pose un problème crucial au développeur.

Pour comprendre le problème, imaginez-vous devoir construire une maison. Quelqu'un a décidé qu'il voulait construire une maison sur un certain terrain. La maison va avoir deux étages et un garage. Il y a même un croquis de la façade gribouillé sur un coin de nappe. Cette personne vient vous voir avec ces informations et son coin de nappe et vous dit "Ça devrait te suffire pour commencer à construire ?". Êtes-vous capable de commencer la construction ?

Normalement, vous ne devriez pas pouvoir commencer à construire la maison avec ces éléments-là. Vous ne connaissez pas la superficie, vous ne disposez pas des plans intérieurs, vous ne connaissez même pas le code d'urbanisme à respecter pour la construction d'une maison. Il n'y a vraiment pas assez d'information pour commencer, ne serait-ce qu'à creuser les fondations. À ce moment vous allez dire à votre client qu'il est inconscient et doit savoir exactement ce qu'il veut. Maintenant, imaginez que vous ne puissiez pas le faire car quelqu'un a déterminé une date de livraison que vous êtes responsable de tenir.

"Hé bien", dit le client, "pourquoi ne commencez-vous donc pas à construire et je vous fournirai les détails au fur et à mesure. Comme ça on ne perd pas de temps."

Vous savez qu'il vous manque des informations pour commencer la construction, mais que continuer à questionner le client ne vous fournira pas plus d'éléments dans l'immédiat. Que faites-vous ? Vous commencez à faire des suppositions.

L'adage "when you ASSUME, you make an ASS of U and ME" (NdT: jeu de mots non transposable sur les termes écrits en majuscule qui se traduirait littéralement par "en faisant des suppositions, tu fais de nous deux des imbéciles"), est on ne peut plus vrai. Les suppositions sont dangereuses et souvent fausses. Cependant sans faire de suppositions, vous ne pouvez avancer. Alors c'est ce que vous faites. Vous commencez par supposer que ce que vous savez est vrai, la maison aura deux étages et un garage. Le garage devrait-il être mitoyen ou indépendant? Quelle taille devrait-il faire ? Bon, disons qu'il est indépendant et qu'il puisse contenir une voiture. Cela signifie que vous pouvez commencer le garage comme une structure indépendante et que quand il y aura plus de détails sur la maison vous pourrez continuer à côté du garage.

Après une semaine de travail sur le garage, votre client revient avec plus de détails. En fait la maison doit avoir trois étages (Ouf ! Heureusement que vous n'avez pas commencé par là) et elle aura huit salles de bain. Il n'y a pas plus d'informations concernant le garage, mais la maison sera peinte en bleu. Vous supposez logiquement que le garage indépendant sera également peint en bleu et vous vous y attelez.

Quelques jours plus tard, le garage est presque terminé. Vous êtes plutôt satisfait du résultat avec le peu d'informations dont vous disposiez. Vous êtes maintenant prêt à attaquer la maison lorsque le client revient avec plus de détails. Le garage devra en fait contenir 2 voitures et doit être mitoyen. Cela vous fend le coeur car vous venez juste d'achever une belle construction mais qu'il faut tout raser à la pelleteuse afin de construire ce qui est réellement demandé. Pire encore, il vous reste maintenant moins de temps pour accomplir le projet complet, et cela vous rend grincheux.

Si cette analogie vous semble farfelue, c'est que vous n'avez probablement jamais travaillé en tant que développeur. Nous sommes vraiment confrontés à ce genre de situation chaque jour. Nous essayons de faire avancer les projets en faisant appel à nos capacités de création pour finir par nous rendre compte que nous ne pouvons pas deviner ce que les gens ont en tête et que nous nous trompons à propos de ce que nous devons réellement bâtir. Et pourtant si nous ne le faisions pas nous devrions rester à attendre car personne n'aime le modèle de développement en cascade.

Dans presque toutes les autres industries de fabrication, il est convenu que tous les besoins et détails sont discutés en amont et entérinés avant le début de la fabrication. Sauf dans le logiciel. Dans le logiciel, il n'y a "pas assez de temps" pour mettre au point tous les éléments à l'avance. L'importance d'avancer nous est martelée dès le premier jour. Du coup, les ingénieurs apprennent à remplir les blancs laissés par les chefs de produit afin de faire avancer le projet. Les chefs de produit ont bien sûr la réputation de changer souvent d'avis, ce qui signifie que les suppositions des ingénieurs sont souvent invalidées au cours de la vie du projet.

Est-il surprenant que les développeurs aient tendance à s'user rapidement et à changer fréquemment d'emploi ?


Priorités numéro un
===================

Le changement de contexte est l'ennemi de tout créatif. Une fois plongé dans un mode créatif, "le flux" comme certains l'appellent, le fait d'être dérangé pour se focaliser sur autre chose interrompt totalement le processus. Oui, écrire du code est un processus créatif. C'est à la fois logique et créatif. Nous n'écrivons pas simplement du code, nous le forgeons.

Il semble communément admis chez les gens qui gèrent le temps de travail de développeurs qu'il est facile de passer d'une tâche à une autre. Après tout, comme certains m'ont déjà dit, du travail c'est du travail. Vous l'orientez dans la direction nécessaire comme un canon et feu. Bien sûr c'est totalement erroné. Si vous consacrez beaucoup de temps à une tâche et qu'il vous est demandé de la laisser de côté pour faire autre chose, il n'est pas simple d'y revenir et de reprendre là ou vous en étiez. Cela nécessite un temps de ré-acclimatation en revenant sur la première tâche pour se remettre dans le contexte, et c'est là le coût du changement de contexte. Même si la nouvelle tâche ne demande que quelques minutes, c'est suffisant pour interrompre le flux et cela rend les développeurs moins productifs.

Il s'agit là de l'une des choses qui rend les développeurs le plus grincheux : changer constamment les priorités. Si quelque chose est prioritaire un jour et qu'autre chose l'est le lendemain, cela signifie immanquablement un changement de contexte. Les créatifs n'aiment pas être interrompus avant d'avoir fini, c'est pourquoi les développeurs sont capables de travailler jusqu'à l'aube pour terminer ce qu'ils sont en train de faire. Interrompre le flux nous rend moins productif.

Les vraies priorités ne changent pas, elles sont figées. La fréquence à laquelle les gens au dessus de nous changent d'avis est incroyablement frustrant pour les développeurs. Nous sommes, la plupart du temps, prêt à monter au front pourvu que l'on nous indique la direction à suivre. Mais si vous nous dites un jour que l'on construit une maison puis le lendemain que l'on construit une voiture, il faut vous attendre à quelques dissensions dans les rangs.


Le défaut des développeurs
==========================

Les développeurs sont mis en position difficile tous les jours, mais nous ne sommes tout de même pas des victimes, même si les plus mélodramatiques d'entre nous ont tendance à agir comme tels. Si nous sommes grincheux c'est en partie à cause de nous-mêmes et de quelque chose qui est profondément ancré en la majorité des développeurs. Nous sommes affligés d'un défaut tragique : nous surestimons nos connaissances et nos capacités.

Ce défaut se manifeste de plusieurs manières. La plus fréquente apparaît dans les estimations de temps. Presque tous les ingénieurs que je connais sous-estiment systématiquement le temps qu'il leur sera nécessaire pour accomplir une tâche ou une série de tâches. Seuls les meilleurs des meilleurs sont capables de fournir une estimation de temps précise et de s'y tenir, alors que les autres se trompent parfois d'un facteur 2 voir plus. Le problème est qu'en tant que créatifs, les développeurs n'arrivent pas à prévoir les problèmes qu'ils vont rencontrer.

Même si de nombreux développeurs se plaignent que les chefs de produit changent d'avis, presque aucun n'en tient compte dans ses estimations. Aucun temps n'est prévu pour les réunions permettant de détailler les spécifications ou de faire des changements. Les bugs ? Notre code est parfait et ne comporte jamais de bugs, alors pas besoin de s'en préoccuper (et puis après tout la Q&A soulèvera bien ce que nous pourrions avoir raté). Certains des autres développeurs dont nous pourrions avoir besoin seront absents ? Pas de soucis, nous trouverons bien quelqu'un pour compenser.

En cumulant tout cela on en arrive très rapidement à ne pas tenir les délais de livraison, et pourtant je n'ai pas encore comptabilisé la raison principale à nos retards de livraison : la non prise en compte du temps d'apprentissage. Cela nous ramène directement à notre défaut. Nous pensons que nous savons déjà comment accomplir la tâche qui nous est demandée alors que très souvent elle inclut des choses que nous n'avons jamais faites. Les estimations partent d'une hypothèse de parfaite connaissance, comme lorsque vous avez le manuel Ikea et n'avez qu'à vous mettre au travail. En réalité, de nombreuses tâches nous demandent de faire des choses que nous n'avons jamais faites auparavant.

Au cours de leurs études d'informatique, les ingénieurs se voient inculquer un sentiment de sécurité tout à fait erroné. Ils en sortent en pensant qu'ils comprennent les logiciels et le processus de développement de logiciel alors qu'en fait, ils ne savent presque rien. Dans mon premier emploi, j'étais ce jeune diplômé arrogant expliquant à tout le monde qu'ils s'y prenaient mal. Ce n'est que plusieurs années après que j'ai enfin compris que je ne savais rien.

Les cours d'informatique durant les études ne vous préparent pas à affronter les problèmes auxquels vous allez être confrontés dans votre vie professionnelle. Ils vous fournissent la connaissance d'un large éventail de concepts afin que vous ne soyez pas totalement désemparés lorsque vous les rencontrerez dans votre travail. Vous y apprenez ce que sont des variables, des fonctions et des objets car ce sont des choses que vous allez rencontrer tout le temps. Vous y apprenez les bases de données et le requétage bien que les formes normales qui vous sont inculquées soient presque totalement inutiles. Vous passez un temps incroyable sur les algorithmes de tri et les structures de données, ce qui est très éloigné de votre activité lorsque vous codez dans votre vie professionnelle. En résumé, les programmes d'informatique vous fournissent les solutions à des problèmes que vous ne rencontrerez pas dans votre activité professionnelle. Si j'ai besoin de trier quelque chose aujourd'hui, j'utilise la méthode sort() (NdT : tri en français). Si j'ai besoin d'une queue ou d'une liste chaînée, j'emploie l'implémentation native du langage que j'utilise. Ces problèmes sont déjà résolus.

Nous sortons donc des études en pensant que nous savons tout faire alors qu'en réalité nous ne savons faire que ce qui a déjà été fait. En fait, nous connaissons une petite partie de ce qui à déjà été fait. Et pourtant nous nous comportons comme si nous connaissions tout, supposant ainsi une connaissance parfaite, et fournissant des estimations de temps qui sont bien trop courtes car nous ne prenons pas en compte l'apprentissage.

Une autre partie du problème est nichée dans nos fragiles egos. Nous avons peur que si nous donnons une estimation "trop longue", nous baissions dans l'estime des gens. Ils nous disent que les "bons développeurs" sont ceux qui travaillent le plus vite, et nous acquiesçons. J'ai toujours été fasciné lorsqu'une estimation est faite sur un projet et qu'un non développeur revient et dit que celle-ci est trop longue. Pour commencer, comme je l'ai mentionné plus haut, elle est déjà probablement trop courte à cause de notre défaut. Ensuite, comment un non développeur pourrait bien savoir combien de temps sera nécessaire pour implémenter quelque chose ? Et cela nous conduit à un autre problème. 


J'ai déjà codé
==============

Peu de phrases ont le pouvoir d'énerver un ingénieur plus que "J'ai déjà codé". Qu'elle vienne d'un chef de produit, d'un designer ou d'un manager, cette phrase adressée à un ingénieur n'amènera rien de mieux que du dédain. J'imagine que LeBron James me trouverait tout à fait comique, si je venais lui donner des conseils sur la tactique, sous prétexte que j'ai joué au basket dans la cour de récréation (NdT: LeBron James est un célèbre basketteur de NBA). Les développeurs subissent cela tout le temps.

Voici quelques énormités énoncées par des non-développeurs :

- Je ne comprends pas en quoi c'est si compliqué. Ce ne sont que quelques lignes de code. (Techniquement, n'importe quel développement ne consiste qu'en quelques lignes de code ; cela n'en fait pas un développement facile pour autant).
- Untel nous dit que cela peut être fait en x jours. (Ceci signifie que Untel a l'expérience sur le problème et a une vision claire de la solution. Moi non ; je dois commencer par me mettre à niveau)
- Que peut-on faire pour rendre ça plus rapide ? Est-ce qu'il vous faut plus de développeurs ? (Or, ajouter plus de développeurs sur un problème ne fait souvent qu'empirer les choses. La seule façon de développer quelque chose plus vite, c'est de développer quelque chose de plus petit).

La pire chose que vous puissiez faire à un ingénieur, c'est lui dire que vous avez déjà développé. C'est un peu différent pour quelqu'un qui a réellement été ingénieur dans sa carrière. Dans ce cas, la personne dispose d'une crédibilité naturelle, mais limitée dans le temps (disons 5 ans ; au delà, tout aura changé). Mais quelqu'un qui n'a jamais développé professionnellement, ferait mieux de garder pour lui ses talents de bidouilleur, plutôt que de s'en servir pour donner son avis sur un développement.

(Soyons honnêtes, les designers sont également touchés par le problème. Chacun se pense expert en design car tout le monde aime les jolies choses. Ça ne fait pas de nous des experts pour designer quoi que ce soit).


Plus de cuistots
================

Les développeurs sont en permanence confrontés au problème d'avoir trop de plats sur le feu. Comme nous sous-estimons le temps nécessaire pour finir une tâche, la plupart des développements sont en retard. Cela vaut aussi bien pour les grandes que les petites entreprises, tout le monde a ce problème. Être en retard mécontente la hiérarchie et aboutit à la conclusion qu'il n'y a pas assez de développeurs. Engagez plus de développeurs, disent-ils, et cela améliorera les choses.

Dans certains cas ajouter des ingénieurs fonctionnera. Dans la plupart des cas, cela ne fera qu'empirer le problème. Il est assez difficile de faire communiquer des gens créatifs entre eux, ajouter des développeurs ne fait qu'amplifier le problème. Les développeurs n'ont pas le droit d'être à court de travail en général. Si la hiérarchie découvre que des ingénieurs sont inactifs, elle a tendance à leur créer du travail.

Cela m'est arrivé de façon quasi caricaturale il y a quelques années. Nous concevions la nouvelle page d'accueil de Yahoo, la reconstruisant complètement avec un nombre réduit de gens. Il s'agissait en fait d'une situation idéale où un petit nombre d'entre nous pouvions nous focaliser sur l'architecture à partir de laquelle la future page serait construite. La conception était terminée et nous étions prêt à développer le prototype quand tout à coup on nous a donné huit développeurs. Notre plan de marche ? Ces développeurs devaient immédiatement commencer à écrire du code pour la nouvelle page d'accueil. Sacré casse-tête étant donné que l'architecture n'existait pas encore. Mais les ingénieurs ne pouvaient pas rester sans travail, ils avaient été assignés au projet et devaient commencer à faire quelque chose. Le problème classique de la poule et de l'oeuf.

Dans un monde idéal, nous aurions pu réaliser un prototype de l'architecture et alors reçu des ingénieurs supplémentaires pour nous aider à l'implémentation. Dans cette situation nous étions coincés. Ce que nous avons finalement fait est que nous avons utilisé l'architecture existante d'un autre projet à laquelle nous avons mise une façade simulant l'existence de l'architecture que nous avions conçue. Les développeurs ont ainsi pu commencer leur travail et nous avons pu travailler à la construction de l'architecture cible en parallèle. C'était une très mauvaise solution à un très mauvais problème et cela a fini par se retourner contre nous lorsque les développeurs ont atteint les limites de la façade que nous avions mise en place avec des fonctionnalités qui auraient du être implémentées dans la nouvelle architecture mais qui n'existaient pas encore. J'ai finalement du dire au manager qu'à moins de nous donner le temps de construire la véritable architecture le château de carte que nous avions bâti allait s'effondrer.

Avoir trop d'ingénieurs sur un projet est un sérieux problème. Ajouter des ingénieurs suppose qu'il existe des tâches à accomplir qui peuvent être parallélisées, alors qu'en réalité le nombre de tâches parallélisables sur un projet est faible et limité. Lorsqu'il y a plus d'ingénieurs que nécessaires sur un projet, le temps de développement effectif diminue pour faire de la planification, de la synchronisation et de la coordination. Pour revenir à ma métaphore précédente, vous ne pouvez bâtir le second étage tant que le rez-de-chaussée n'est pas terminé. De nombreuses tâche dans un projet de développement sont en fait séquentielles et ajouter des ingénieurs n'accélère donc pas les choses. Ou comme le disait souvent l'un de mes précédents collègues, "je m'en fous du nombre de femmes que vous me donnez, cela prend toujours neuf mois pour faire un bébé."

Une vraie mauvaise humeur
=========================

Si je résume, sans assez d'informations, avec des prérequis qui changent, un socle de connaissances pas suffisamment solide pour faire le travail aisément, et l'obligation de baser notre travail sur des spéculations erronées, nous trouvons toujours le moyen de venir au travail tous les jours. Étant des gens créatifs, nous pouvons nous en accommoder parce que nous savons qu'un jour des personnes utiliseront le fruit de notre travail. Voici ce qui fait avancer les ingénieurs plus que tout autre chose : l'idée que des personnes que nous ne connaissons pas seront affectées par notre travail. Que vous travailliez sur un site web visité par des millions de personnes par jour, ou bien sur un système de point de vente pour restaurants, savoir que cela aura de l'impact sur la vie des gens constitue un puissant stimulant

.. html :: <blockquote class="twitter-tweet"><p>I can&#8217;t state this enough: Programmers don&#8217;t burn out on hard work, they burn out on change-with-the-wind directives and not &#8216;shipping&#8217;.</p><p>&mdash; Mark Berry (@markab) <a href="https://twitter.com/markab/status/181452969391292417" data-datetime="2012-03-18T18:52:13+00:00">March 18, 2012</a></p></blockquote><p><script src="http://platform.twitter.com/widgets.js" charset="utf-8"></script></p>

**Traduction** : *"Je ne le dirai jamais assez : un ingénieur ne s'épuise pas à cause d'un travail trop dur, il s'épuise à cause des changements de direction incessants, ainsi que sur le fait de ne pas livrer."*

Quand il y a des retards à cause de changement d'avis, nous devenons grincheux. Incroyablement grincheux. Notre objectif de proposer le fruit de notre travail aux gens s'en trouve différé, et c'est démoralisant. Et pourtant, un développeur n'a rien d'un perfectionniste. Nous sommes souvent partant pour sortir quelque chose de juste bien, plutôt que continuer à travailler sur quelque chose de mieux, mais qui ne sort pas. Nous aimons construire des petites choses afin de les sortir rapidement, pour plus tard pouvoir les combiner ensemble en quelque chose de plus grand. Pourquoi ? Parce que c'est ainsi que nous pouvons toucher les gens.

Maintenant, nous savons tous que les retards font partie intégrante de l'industrie logicielle. Les ingénieurs travailleront comme des malades si leur estimation de temps est dépassée, afin d'essayer, et de parvenir à faire fonctionner leur produit. Les ingénieurs ne détestent pas le dur labeur et les horaires à rallonge ; nous détestons ne pas régler les problèmes.


Quels remerciements ?
=====================

En tant que développeur, notre travail se déroule selon un rythme très différent des autres. Par exemple, ce n'est pas un designer ou un chef de produit qui devra se lever au milieu de la nuit parce que quelque chose est cassé en production (bien que j'ai connu des chefs de produit qui tenaient à être appelés lorsque cela arrivait). Une fois j'étais sur le point de partir de chez moi avec mon rendez-vous (NdT : rendez-vous galant) lorsque j'ai reçu un appel du travail à propos d'un problème en production. Elle s'est assise et a attendu patiemment durant une heure alors que j'essayais frénétiquement de régler le problème. Elle a fini par partir (et je ne peux l'en blâmer) me laissant à mon travail avec mes collègues compatissant à mon malheur sur IRC.

Pourtant vous entendrez rarement des ingénieurs se plaindre des horaires à rallonge ou de devoir se lever au milieu de la nuit à cause d'un problème en production. Le logiciel est notre bébé et nous aimons en prendre soin. Cela signifie que s'il faut le nourrir au milieu de la nuit, nous le faisons. Si il a besoin d'un peu plus d'attention pendant le week-end, nous le faisons aussi et tout cela avec le sourire car notre création grandit.

Les développeurs sont heureux quand ils mettent la touche finale aux derniers octets du code d'une tâche. Je n'ai jamais vu un développeur aussi joyeux que quand il envoie un email pour dire qu'il a fini quelque chose et que c'est prêt à être testé. Pourtant cette joie se volatilise rapidement lorsqu'au cours des dix minutes qui suivent, les rapports de bugs sont envoyés concernant son tout nouveau bébé.

Essayez d'imaginer cela une seconde. Vous avez travaillé pendant une journée, une semaine ou plusieurs semaines sur quelque chose et vous venez de le terminer. Vous êtes fier car vous avez accompli la tâche que l'on vous avait confié, vous avez probablement appris des choses que vous ne connaissiez pas auparavant. Tout ce à quoi vous aspirez c'est de prendre un peu de temps pour admirer votre travail. Peut-être même que quelqu'un vous dise "bon boulot". Et qu'obtenez vous ? Des bugs. Telle chose ne fonctionne pas, telle autre chose n'est pas à sa place et ainsi de suite. Notre bonne humeur s'envole aussi vite que nous nous attelons à réparer ce qui ne va pas.


Pourquoi nous disons "Non"
==========================

Compte tenu de tout ce que j'ai déjà mentionné, voici les raisons classiques pour lesquelles les ingénieurs disent non (ou bien semblent grincheux):

- La demande est venue tardivement au cours du développement et il n'y a pas assez de temps pour s'adapter avant la date de livraison.
- La demande annule une ou plusieurs hypothèses qui ont été faites dès le début du processus pour avancer le projet.
- La demande va à l'encontre d'une ou plusieurs demandes précédentes.
- La demande augmente la quantité de travail qui doit être fait avant la livraison.
- Nous sommes tellement épuisés que toute demande est perçue comme une tonne de travail supplémentaire et nous ne voulons simplement pas en supporter plus.

Gardez à l'esprit que toutes ces raisons, exceptée la dernière, sont liées au rapport qu'entretient l'ingénieur et la date de livraison de son projet. Nous voulons que les tâches se terminent, et la seule façon d'y parvenir, c'est de ne pas les changer pendant que nous travaillons dessus. Quand un changement survient, c'est là que nous devenons réellement grincheux, et que le "non" arrive, sortant de nos bouches avant même que vous ayez fini votre phrase.


Soin et alimentation
====================

Alors, comment gérez-vous ces grincheux pourtant nécessaires dans votre entreprise ?

Revoyons un instant ce qui fait avancer les ingénieurs :

- Être créatif
- Résoudre des problèmes
- Avoir une incidence sur la vie des gens

Notez une absente dans cette liste. L'argent. Donner bêtement de l'argent à un ingénieur ne le satisfera que rarement. Cela fait cliché, mais ça n'a rien à voir avec l'argent. L'argent permet de s'amuser, mais ce qui nous intéresse vraiment c'est le code et la création. Lorsque nous pouvons le faire dans un environnement sain, nous sommes heureux, et pour très longtemps.

Alors, comment allez-vous créer un environnement sain pour les ingénieurs ?


Travailler transversalement
===========================

Les ingénieurs logiciels sont créatifs, à l'instar des chefs de produit, et des designers, c'est pourquoi vous devriez veiller à les inclure dans le processus de création. Les ingénieurs constituent des atouts considérables lors des sessions de brainstorming et pour revoir les conceptions initiales. Donnez à chaque ingénieur l'opportunité de rencontrer l'équipe créative et de travailler directement avec elle (pas nécessairement tous en même temps). Pour faire court, insérez l'ingénieur le plus tôt possible dans le processus de création. Aucun ingénieur n'aime découvrir les spécifications et les maquettes jetées sur un mur, sans les comprendre.

Les ingénieurs sont très logiques. Ainsi, en étant dans ces réunions préliminaires afin de saisir d'où viennent les besoins, ils peuvent permettre d'écarter directement un certain nombre de problèmes. Quand les ingénieurs se sentent comme des ouvriers, ils posent des questions et cela ralentit le processus. Lorsque les ingénieurs sont co-créateurs, il y a moins de questions et donc moins de retards par la suite dans le processus.

De plus, les ingénieurs sont souvent très en avance en termes de connaissance de ce qui est possible. Si vous prenez les développeurs d'interfaces, nous savons ce que les navigateurs peuvent faire bien avant les chefs de produit ou les designers. Quand nous partageons ce savoir, nous donnons en fait à tous de nouvelles idées sur comment construire un projet, partant de ce qu'il est possible de faire. Imaginez si vous essayez de créer un site de partage de photo, sans savoir que vous pouvez maintenant effectuer un glisser-déposer de fichiers depuis votre bureau vers le navigateur, afin d'envoyer le fichier au serveur [2]_ ? Sans cette information, imaginez à quel point le produit final s'en trouverait modifié.

Donc, invitez les ingénieurs dans le processus de création, le plus tôt possible. Laissez-les vous faire un retour et vous donner des informations sur ce qu'il est possible de faire. Moins notre conduite nous est dictée, plus nous sommes à l'écoute et heureux dans notre travail. Nous donner le sentiment d'avoir contribué à la création du produit est le seul moyen d'y arriver vraiment.


Aménager un environnement créatif
=================================

Pour faire suite au thème des développeurs vus comme des créatifs, essayez de nous offrir des opportunités d'être créatifs. Il y a une bonne raison si les hackdays et hackweeks (NdT : journées ou semaines de bidouillage, i.e. activité de développement libre regroupant les différents métiers de l'industrie logicielle) sont si populaires ; c'est parce qu'il s'agit de l'échappatoire créatif qui permet aux développeurs de recharger les batteries et redécouvrir leur amour pour le code. Ces événements de bidouillage sont des moments pendant lesquels les développeurs peuvent être complètement créatifs, car libérés des contraintes de leur travail quotidien.

Un hack day chaque trimestre est suffisant pour enthousiasmer les gens. Vous voulez que les gens soient encore plus excités ? Donner un thème au hack day. Donnez des récompenses au plus créatif, à celui qui a le plus de chances de passer en production et ainsi de suite. L'objectif est d'alimenter la créativité des développeurs afin qu'en revenant à leur poste, ils se soient rafraîchis les idées et soient de nouveau prêts à contribuer.

Gardez à l'esprit que les développeurs ne sont pas uniques à cet égard. Tout le monde a besoin de temps pour être créatif. D'après mon expérience, les chefs de produit et les designers ont tendance à l'obtenir plus fréquemment. Ils ont du temps pour des conférences ou des ateliers hors du bureau alors que les développeurs ont tendance à être oubliés.

D'ailleurs, les événements de bidouillage ne sont pas le seul moyen de faire cela, mais ils sont le meilleur moyen de commencer. Vous pouvez aussi allumer la flamme de la créativité en envoyant les ingénieurs à des conférences leur permettant d'améliorer leurs compétences. Permettre aux développeurs d'acheter des livres qui contribuent à leur savoir sur les deniers de la société. Donner l'opportunité aux développeurs d'exprimer leurs idées à propos des projets sur lesquels ils travaillent. Google donne à ses ingénieurs les fameux 20% de leur temps pour travailler à des projets personnels. Tout cela participe grandement à établir une excellente relation avec vos ingénieurs.


Encouragez les temps de repos
=============================

Étant donné le volume horaire et les exercices de concentration que nous faisons en général, les développeurs ont besoin de faire des pauses. Malheureusement, nous ne sommes pas très doués pour planifier cela. Nous sommes si pris dans le processus que nous oublions de prendre des vacances. Durant les cinq premières années de ma carrière, je pense avoir pris 7 jours de congés. Je ne sais pas pourquoi, mais nous ne sommes pas très bons pour prendre le temps de décompresser. C'est un problème.

L'usure du développeur a cela de singulier que nous avons l'habitude de passer outre. Quand l'usure devient vraiment trop pénible, nous partons, à la recherche de repos. Le pire c'est que les développeurs ne vous diront probablement jamais qu'ils approchent de ce point ; nous sommes trop fiers pour cela. Dans ma dernière équipe, j'ai dit aux développeurs que dès la première fois où ils se sentent frustrés ils doivent venir me voir et m'en parler. Je ne voulais pas qu'ils attendent et que cela devienne si fort que la seule façon d'en échapper soit de partir. Je ne voulais pas qu'ils partent, je voulais qu'ils soient heureux et la seule façon pour moi d'y parvenir était de savoir quand ils commençaient à ne plus l'être.

Incitez les ingénieurs à prendre du repos. Votre société donne des congés, alors assurez-vous que les développeurs utilisent ces jours de vacances pendant l'année. Une fois tous les 4 à 5 mois au minimum. Les managers sont les mieux placés pour gérer cela car ils connaissent les agendas des projets.

Lorsque les ingénieurs prennent des jours à intervalle régulier, cela restaure leur côté créatif en les sortant de la rigueur nécessaire au respect des dates de livraison. Oui, il est possible que nous passions une partie de notre temps de repos à coder, mais il s'agit de nos propres créations et de ce fait c'est assez différent de ce que l'on fait au travail. C'est un élément important pour se changer les idées et se préparer pour la prochaine bataille.


Laissez-les coder
=================

Aussi ironique que cela puisse paraître, de nombreuses sociétés recrutent des développeurs mais ne les laissent pas vraiment coder. Au lieu de cela leurs journées sont remplies de réunions inutiles qui brident la productivité. En général, les développeurs sont plus productifs lorsqu'ils peuvent coder pendant au moins 4 heures d'affilée sans interruption.

Il est difficile de rentrer dans un bon flux de développement lorsque l'on sait que l'on a une réunion dans une heure ou deux, cela vous trotte dans la tête pendant que vous codez. Il est incroyablement improductif de coder pendant une heure, s'arrêter pendant une heure, coder pendant une heure, s'arrêter pendant une heure, etc. Vous ne pouvez rentrer dans le flux et à peine commencé vous arrêter. Le cerveau des développeurs doit basculer dans le bon état d'esprit pour coder et cette bascule prend du temps.

Assurez vous que vos développeurs ont chaque jour une plage ininterrompue d'au moins quatre heures dédiée au développement. C'est là le secret pour que le travail avance plus vite. Cela semble assez logique : si les gens font habituellement une journée de huit heures, au moins la moitié de leur temps devrait être allouée à l'activité principale. Je m'étais rendu compte que j'étais plus productif entre 13h et 17h. Je savais que si j'avais ce créneau chaque jour je pouvais facilement accomplir mes tâches. Quand ce créneau commençait à être interrompu par des réunions, je savais que je ne produirais pas beaucoup.

Tâchez aussi d'avoir au moins une journée sans réunion par semaine. Pas même de stand-up quotidien (NdT : courte réunion quotidienne au cours de laquelle les participants à un projet disent ce qu'ils sont en train de faire ; cette réunion a lieu debout afin d'en limiter la durée, d'où le nom). Contentez-vous de laisser aux développeurs le soin de gérer leur temps par eux-même ce jour-là et de faire ce qui doit l'être. Il est absolument incroyable tout ce que l'on peut faire en une journée lorsqu'il n'y a aucune interruption. À une certaine période de ma carrière, mon responsable m'a imposé de travailler de chez moi deux jours par semaine parce que j'étais constamment interrompu lorsque j'étais au bureau. Résultat : je terminais mon travail très vite.


Exprimer votre satisfaction
===========================

Il s'agit là de quelque chose qui peut être mis en oeuvre immédiatement et qui est vraiment efficace. J'ai mentionné précédemment la frustration de suer pour terminer une tâche et de ne recevoir comme retour que des rapports de bug. En tant que développeurs nous avons rarement l'opportunité de nous enfoncer dans notre fauteuil, admirer le résultat de notre travail et recevoir une tape dans le dos de quelqu'un.

Quand un développeur termine une tâche, surtout une longue, un petit mot pour dire merci aura un très grand effet. Un simple "Hé, merci d'avoir terminé. On va jeter un oeil" fera disparaître la position défensive qui apparaît typiquement lorsque les rapports de bugs commencent à arriver. Se sentir apprécié est important pour les développeurs car la plupart des retours que nous recevons sont négatifs, sous la forme de bugs, de problèmes d'exploitation ou autre. Un peu de retour positif rend le reste moins pesant.

Si vous voulez faire encore mieux, décidez d'une récompense qui est attribuée chaque trimestre au développeur qui a eu le plus gros impact ou qui a le plus amélioré les choses ou quoi que ce soit d'autre. La récompense ne doit pas nécessairement être quelque chose d'important ou désirable comme un iPad (même si nous accepterions avec plaisir cela ainsi que d'autres gadgets), cela peut-être un petit trophée et un email à toute l'équipe ou le département qui reconnait l'effort.

Et s'il vous plaît, lorsque vous remerciez les gens pour leur travail, n'oubliez pas les développeurs. J'ai assisté à de nombreuses réunions sur de nombreux projets lors desquelles les gens remercient ouvertement les équipes produits ou les designers pour leur travail sur le projet sans mentionner les ingénieurs dont le sang, la sueur et les larmes ont produit le travail concret. Le succès ou l'échec de chaque produit est le résultat du travail des trois groupes, aucun ne pourrait le faire seul. Assurez-vous que votre entreprise exprime toujours sa reconnaissance envers toute l'équipe et pas seulement une partie.


Conclusion
==========

Nous, les développeurs, sommes une espèce intéressante. Nous sommes dotés d'une personnalité particulière, et désirons vraiment faire les choses du mieux possible. Si vous arrêtez de nous traiter comme des exécutants et commencez à nous traiter comme faisant partie du processus créatif, vous obtiendrez probablement plus et bien plus vite. Les équipes dans lesquelles j'ai travaillé ont toutes connu des frictions à divers degrés par manque de compréhension de l'état d'esprit des développeurs et de ce qui les motive. J'espère sincèrement que cet article permettra une meilleure communication entre les ingénieurs et ceux qui travaillent avec. Ce n'est vraiment pas si difficile. Nous voulons tous faire partie de la solution plutôt que d'être une abeille ouvrière.


Références
==========

.. [1] http://www.designstaff.org/articles/how-designers-and-engineers-can-play-nice-2011-12-22.html
.. [2] http://www.nczonline.net/blog/2012/05/08/working-with-files-in-javascript-part-1/
