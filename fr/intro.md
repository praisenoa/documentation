<p align="center">
	<a href="https://dreamvo.com"><img src="../images/logo.png" alt="Dreamvo" width="580"></a>
</p>
<h3 align="center">Reprenez le contrôle de vos vidéos</h3>
<p align="center">Dreamvo est une plateforme de partage de vidéo décentralisée qui met en avant l'expérience utilisateur.</p>

---

Dreamvo est un projet de plateforme de vidéo décentralisée gratuite et open source. Le projet a pour but de créer une alternative à YouTube qui offrirait une autre vision du partage, du visionnage et de la gestion de son contenu audiovisuel sur le web. Il s'agit d'une plateforme destinée à un large public et pas seulement à un public francophone.

## La décentralisation, le futur du partage de vidéo ?
Le principe de la décentralisation repose sur la possibilité de contribution des utilisateurs. Dans ce contexte précis, décentraliser les vidéos permet d'éviter de dépenser des énormes sommes dans des serveurs et de profiter de la puissance du réseau P2P.

<a href="https://github.com/Chocobozzz/PeerTube">PeerTube</a> est une plateforme de vidéo décentralisée et sponsorisée par Framasoft, un organisme à but non lucratif qui promeut, diffuse et développe la culture libre en général ainsi que des logiciels libres. L'objectif du projet PeerTube est de proposer une alternative à YouTube en créant un réseau de plateformes décentralisées, libres et open source. C'est sur ce projet que nous voulons baser Dreamvo. Nous voulons faire partie des premières plateformes à démocratiser le partage de vidéo décentralisé.

La problèmatique qu'a voulu soulever PeerTube c'est que nous ne pouvons pas créer d'alternatives de streaming vidéo <a href="https://en.wikipedia.org/wiki/Free_and_open-source_software">FOSS</a> à YouTube, Dailymotion, Vimeo ... avec un logiciel centralisé. Une organisation seule peut ne pas avoir assez d'argent pour payer la bande passante et le stockage vidéo nécessaires à un tel projet.

Nous avons donc besoin d'un réseau de serveurs décentralisé qui <a href="http://www.commentcamarche.net/faq/19276-seeders-et-leechers">seedent</a> des vidéos (comme Diaspora par exemple). Mais ce n'est pas suffisant car une vidéo pourrait devenir célèbre et surcharger le serveur. C'est la raison pour laquelle nous devons utiliser un protocole P2P pour limiter la charge du serveur. Grâce à WebTorrent, nous pouvons faire du P2P directement dans le navigateur web. Cela veut dire qu'un utilisateur peut seeder une vidéo simplement en la regardant depuis son navigateur, c'est comme si vous partagiez le flux vidéo que vous téléchargiez en regardant une vidéo sur YouTube à quelqu'un d'autre qui regarde la même vidéo en même temps. Même si personne ne regarde une vidéo, elle reste accessible via le serveur principal via le <a href="http://getright.com/seedtorrent.html">protocole WebSeed</a>. La décentralisation permet également de migrer sur une autre plateforme sans devoir réuploader toutes ses vidéos puisqu'elles sont déjà disponibles à l'importation depuis le réseau P2P.

<p align="center"><img src="../images/screen2.png" alt="" /></p>

Actuellement, PeerTube est encore en développement mais contient de nombreuses fonctionnalités que l'on retrouve habituellement comme des sous-titres, un algorithme de détection de contenu NSFW, la possibilité d'intégrer le player HTML5 ainsi que de nombreuses fonctionnalités de base que l'on retrouve sur YouTube. PeerTube n'est pas encore prêt à être déployé dans un environnement de production, mais il devrait pouvoir l'être dans les mois à venir.

<p align="center"><img src="../images/screen1.png" alt="" /></p>

## Un modèle économique adapté
Mettre en place un modèle économique solide est important. Il faut générer du profit mais aussi rémunérer les créateurs de contenu, en évitant le recourt à la publicité. Et si l'utilisateur contribuait également financièrement au développement de la plateforme ? Le <a href="https://medium.com/precoil/what-is-the-business-model-for-a-twitch-streamer-f3b9e5351666">modèle économique de Twitch</a> se base sur les abonnements de chaîne, les chaînes répondant à certains critères sont éligibles à un partenariat avec Twitch ce qui leur permet d'activer l'abonnement payant de 4,99€ par mois.

Ce partenariat comprend les avantages suivant :
* Obtient une part des revenus publicitaires générés par toutes les diffusions sur la chaîne.
* Revenu d'abonnement mensuel des spectateurs abonnés.
* Création d'un magasin pour la vente de vêtements personnalisés.
* Système de donations des spectateurs via les bits.

Twitch récupère un pourcentage des revenus générés par les abonnements, et les abonnés ont droit à certains avantages comme des émots personnalisées dans le chat, des badges, des accès privilégiés aux rediffusions ou à certains sites. Grâce à son traffic, aux publicités que les non abonnés regardent, aux abonnements Twitch Turbo ($8,99/mois) et aux taxes d'abonnements de chaînes, la société Twitch génère des centaines de millions de dollars chaque années. Les spectateurs soutiennent financièrement leurs créateurs favoris tout en soutenant la plateforme.

Un autre exemple, <a href="https://www.feedough.com/reddit-make-money-reddit-business-model/">Reddit</a>. Reddit est un forum de discussion dont le modèle économique se base sur la publicité (liens/posts sponsorisés par les utilisateurs ou par Google Adsense) mais également sur leur abonnement premium "Reddit Gold" ($3.99 ou $29.99/mois) qui donne certains avantages : désactiver les annonces (les utilisateurs peuvent désactiver les annonces quand ils le souhaitent), un quota de commentaires par page plus élevé, enregistrer et classer les commentaires où l'utilisateur peut enregistrer le commentaire qu'il / elle aime et peut les classer selon leurs besoins, accéder aux thèmes personnalisés fournis par Reddit. De plus, les membres Reddit Gold peuvent faire évoluer des membres standards en membre Gold en un clic avec une certaine limite.

Ces modèles sont intéressants et adapté à un tel projet, mais il y a une problèmatique : Comment convraincre les spectateurs de migrer vers une nouvelle plateforme tout en sachant qu'ils vont devoir payer pour soutenir leur vidéastes favoris car la publicité, étant moins présente, rapportera moins d'argent ? Nous pensons que la réponse se trouve dans les solutions que nous proposons aux vidéastes et à leur communauté, à savoir des règles plus souples concernant les droits d'auteur, une meilleure gestion de leur contenu, un meilleur contact avec leur communauté, une plateforme qui évolue avec sa communauté ainsi que de nombreuses fonctionnalités pour améliorer l'expérience de chaque utilisateur.

<p align="center"><img src="../images/tweet1.png" alt="" /><br><a href="https://twitter.com/_Amixem/status/953612321707917312">Tweet original</a></p>

## Reprenons le pouvoir avec un modèle économique sain

Avec le modèle économique actuel de YouTube, ce sont les annonceurs qui ont le pouvoir sur la rémunération des créateurs de contenu. C'est très mauvais car à cause de polémiques comme celle autour du YouTuber Logan Paul par exemple, les annonceurs ce sont montrés plus réticents envers YouTube, car ils ne veulent pas que leur image de marque soit assimilée comme étant en accord avec ce type de contenu. YouTube se voit donc dans l'obligation de diminuer les seuils de monétisations et de réstreindre l'accès à celle-ci avec des critères plus précis. C'est l'une des principales raisons pour lesquelles YouTube est en train de devenir obsolète. La communauté doit reprendre le pouvoir au détriment des annonceurs.

## Pourquoi "Dreamvo" ?
Chez les anglophones, "Dreamvo" désigne la possibilité d'enregistrer un rêve pour une vision future, quand un rêve est tellement agréable qu'on a envie de l'enregistrer et le revoir. C'est également un clin d'oeil subtil à <a href="https://github.com/dreamvids">DreamVids</a>, une startup française qui avait pour projet de concurrencer YouTube, et qui a réalisé l'exploit de prouver que c'est possible. La plateforme a fermé fin 2015 après un problème matériel de la part de leur hébergeur, ils avaient prévu de la relancer avec une version V3, elle n'a jamais vu le jour. Cette nouvelle plateforme, en plus d'être décentralisée et open source, apportera aux créateurs et aux spectateurs un outil qui correspond vraiment à leurs besoins.

Les principaux objectifs de Dreamvo sont donc :

- Un meilleur respect de la vie privée avec des comptes anonymes et du chiffrement à [clé publique](https://www.globalsign.fr/fr/centre-information-ssl/cryptographie-cle-publique/)
- Une plateforme pensée [secure by default](https://en.wikipedia.org/wiki/Secure_by_default)
- Des fonctionnalités innovantes permettant de meilleures intéractions avec la communauté
- Un modèle économique en grande partie basé sur les dons et les abonnements
- Mettre davantage en avant le contenu de qualité et la nouveauté
  
## Un projet ambitieux mais réalisable
Bien que le projet peut sembler irréalisable ou trop ambitieux, nous pensons qu'il ne faut simplement pas brûler d'étape. Le grand public n'est peut être pas prêt à se débarrasser de YouTube, mais ça viendra tôt ou tard, qu'on le veuille ou non, et rien ne nous empêche de créer une alternative à ce dernier et de développer un YouTube meilleur petit à petit, sans dépenser des grosses sommes en serveurs ou en marketing. Le premier objectif est de lancer une solution pour tous ceux qui sont directement impactés par la politique actuelle de YouTube, ses principaux défauts, à savoir les droits d'auteur, la censure et la monétisation.

# Contribuer
Vous êtes développeur, journaliste, programmeur, vidéaste ou simple spectateur ? Vous avez tous le pouvoir de contribuer au développement de cette plateforme, vous n'avez pas besoin de savoir coder pour contribuer ! <a href="https://github.com/Chocobozzz/PeerTube/blob/develop/.github/CONTRIBUTING.md">Plus d'infos</a>

Mais avant tout, nous recherchons des développeurs pour composer une équipe. Nous recherchons un web designer UX/UI, des développeurs front et back, ainsi qu'un ou plusieurs sysadmins.

Envoyer une candidature de développeur : *raphael@crvx.fr*
