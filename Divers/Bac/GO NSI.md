### Le numérique à l'origine de l'émergence de sports nouveaux ?

#### Introduction

Depuis plusieurs siècles, nous connaissons les sports, le sport en général, comme une forme standard, avec un effort physique et un respect de règles bien définies. Ces derniers sont mis en valeurs par de grands tournois internationaux comme les JO.
Pourtant, depuis moins de 40 ans, le numérique couplé au développement d'Internet -> apparition de jeux multijoueurs avec possiblité de jouer à plusieurs et à différents endroits de la planète

**-> Le numérique à l'origine de l'émergence de sports nouveaux ?**

### I. Le développement des jeux multijoueurs puis en réseau

**1) Les origines de l'esport**

L'esport, aussi appelé sport électronique, est né dans les années 80 avec l'appariton des premiers jeux-vidéo en multijoueurs. L'esport est simplement une forme de compétition sur des jeux-vidéo.

Ces origines sont encore récentes.

En 1980, le premier tournoi esport prend place aux Etats-Unis avec le jeu Space Invaders sur Atari. Ce tournoi a rassemblé plus de 10000 personnes.

Puis en 1988, le jeu Netrek apparaît. Ce jeu d'arcade est le premier à s'appuyer sur Internet pour jouer à distance sur des serveurs. EN 1993, Il est qualifié par le magazine Wired comme le "premier jeu de sport en ligne".

-> tournant dans les années 90: le World Wide Web, un système hypertexte développé sur Internet par Tim Berners-Lee et Robert Cailleau au CERN ainsi que le développement d'Internet en général a permis l'apparition rapide de jeux-vidéos multijoueurs en ligne. 

On observe donc le développement de franchises comme Counter-Strike en 2000 ou League of Legends en 2009, encore très populaires. Aujourd'hui, La plupart des jeux-vidéos notamment compétitifs utilisent le protocole UDP au lieu de TCP pour sa vitesse de transmission des données plus rapide.

**2) Deux manières de faire une compétition esport**

Les compétitions d'esport peuvent se dérouler de deux façons

- D'un côté, avec des tournois sur Internet, chaque ordinateur envoie et reçoit les données du serveur par le protocole UDP. Il faut aussi s'appuyer sur des protocoles de routage pour que les données transitent le plus rapidement possible entre l'ordinateur du joueur et le serveur (OSPF !)

- D'un autre, dans les tournois amateurs ou professionels qui se déroulent dans une même salle, aussi appelés LAN, on peut réduire la latence en reliant directement les ordinateurs avec un switch et des câbles Ethernet. Le plus souvent, une topologie de réseau en étoile est utilisée pour des jeux à moins de 10 joueurs (voir graphe). Un routeur est éventuellement connecté au switch pour permettre à chaque ordinateur d'avoir accès à Internet.

![[Pasted image 20220604155726.png]]

Aujourd'hui, c'est ce qui est privilégié pour les compétitions professionnelles car cela réduit la latence et donc réduit le nombre de facteurs pouvant influencer négativement le jeu.

#### II. L'émergence du Web et des plateformes de streaming

Néanmoins, l'essor de l'esport s'est fait uniquement grâce aux services vidéo. Il y a eu dans les années 2000 des tentatives de diffusion des tournois esport sur la télévision. Mais les chaînes TV ont duré la plupart du temps moins de 5 ans.

Le Web a donc pris le relève pour la diffusion de ces évènements. En 2011, Twitch, un service de streaming vidéo en direct spécialisé dans les jeux-vidéo, est créé. Ce site Web s'appuie donc sur deux protocoles :

- HTTP pour récupérer les ressources nécessaires à l'affichage du site web comme les images ou les fichiers HTML. Le client va donc généralement envoyer des requêtes GET au serveur pour récupérer ces données.

- UDP pour recevoir les données du flux vidéo en direct. Le client envoie une requête et le serveur envoie continuellement les paquets nécessaires. En dépit d'une transmission plus rapide des données grâce à UDP, des paquets peuvent être perdus et donc impacter négativement la vidéo si le réseau subit des problèmes.

En 2021, Twitch a cumulé en moyenne 2,84 millions de spectateurs chaque jour. Cette performance dans le domaine de l'esport est l'une des raisons du rachat de Twitch par Amazon pour 970 millions de dollars en 2014.

### Conclusion

Le numérique a permis l'émergence de nouveaux sports : l'esport. C'est un secteur encore jeune et en développement. La France via le Président de la République veut aussi devenir un leader européen de l'esport d'ici 2025 avec une volonté d'accueillir de grands tournois internationaux en vue des JO de Paris.
