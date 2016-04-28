TITLE: Gestion de contenu Web et CMS
MENUTITLE: Web & CMS
AUTHOR: Freddy Limpens
LANGUAGE: fr

# Rappels sur Internet, le Web et HTML
## Le web
[video]( https://player.vimeo.com/video/138623497 ){: .lien_video } 
Le web, c'est sans doute l'application informatique qui a rencontré le plus grand succès.
C'est une utilisation particulière  d'internet. Il a été inventé par Tim Berners Lee au début des années 90. C'est d'abord un moyen de communication entre personnes qui permet de s'échanger des informations décrites dans des documents . Il est fréquent de constater une confusion entre Internet et le Web. Or, si le web utilise Internet, il n'est pas la seule application à le faire, le mail par exemple est un autre service qui utilise Internet. Socialement, le web a pris une place considérable dans nos vies. Sur cette application au départ très simple se sont bâties d'autres applications dans tous les domaines d'activités : pour le commerce, le marketing, la recherche d'emploi, le travail à distance et la collaboration... C'est un vecteur important de développement économique aujourd'hui. C'est aussi par des applications web que l'état et les administrations offrent leurs services aux citoyens. C'est encore par les applications sociales du web que nous communiquons dans notre vie privée. Maîtriser les technologies du web est important pour comprendre les enjeux, saisir des opportunités, éviter des pièges... Naviguer sur le web fait aujourd'hui partie du quotidien de chacun d'entre nous. Ce chapitre propose d'en expliquer le fonctionnement pour nous permettre d'avoir des comportements responsables et de garder la maîtrise de ce que nous faisons.

[video]( https://player.vimeo.com/video/138623515 ){: .lien_video } 

Alors, qu'est-ce réellement  que le web ? Le Web est avant tout un service qui permet de s'échanger des ressources. Celles-ci peuvent être très variées et prendre de nombreuses formes. Dans un premier temps, nous considérerons pour simplifier que ce sont uniquement des documents qui contiennent soit du texte soit des images.
Le succès du web est sans doute lié à la notion de document hypertexte. C'est à dire la possibilité d'intégrer à l'intérieur d'un document des liens, qui sont des parties de texte cliquables permettant d'accéder à d'autres ressources.
Cela a été rendu possible grâce à l'utilisation du fameux langage HTML - Hyper Text Markup Language - inventé par Tim Berners Lee en 1991.
L'ensemble des documents ainsi que les liens qui les relient forment alors un réseau de documents. Cette multitude de liens a fait naître l'image bien connue de la toile d'araignée. En anglais : le web

```activité
// question: 159977  name: La toile et ses fils
::La toile et ses fils::[html]<p>Dans l'image du web représentée par une toile d'araignée, les fils sont \:</p>{
	=<p>des liens</p>
	~<p><strong id\="docs-internal-guid-566566e9-d108-1f1b-8d6f-529e33dacd53" style\="font-weight\: normal;"><span style\="font-size\: 14.666666666666666px; font-family\: Arial; color\: \#434343; background-color\: transparent; font-weight\: 400; font-style\: normal; font-variant\: normal; text-decoration\: none; vertical-align\: baseline; white-space\: pre-wrap;">des câbles du réseau internet</span></strong></p>
}


// question: 159978  name: La toile et ses noeuds
::La toile et ses noeuds::[html]<p>Dans l'image du web représentée par une toile d'araignée, les nœuds sont \:</p>{
	=<p>des ressources</p>
	~<p><span style\="font-weight\: normal;"><span style\="font-size\: 14.666666666666666px; font-family\: Arial; color\: \#434343; background-color\: transparent; font-weight\: 400; font-style\: normal; font-variant\: normal; text-decoration\: none; vertical-align\: baseline; white-space\: pre-wrap;">des ordinateurs</span></span></p>
}

// question: 159983  name: Les échanges sur le web
::Les échanges sur le web::[html]<p>Que s'échangent les ordinateurs sur le Web ?</p>{
	~%33.33333%<p>Des ressources</p>
	~%33.33333%<p>Des images</p>
	~%33.33333%<p>Des textes</p>
	####<p>Les trois !</p>\n<p>Dans ce contexte du web, le mot ressource désigne à la fois des textes, des images, des sons, ... C'est ce mot qu'on retrouve dans la signification de l'acronyme URL \: Uniform Resource Locator</p>
}
```

```activité-avancée
::Tim Berners-Lee::[html]<div>
	<p>En vous aidant par exemple de cette ressource : </p>
	<p>
	<a target="_blank" href="http://home.web.cern.ch/fr/topics/birth-web">http://home.web.cern.ch/fr/topics/birth-web</a>
	</p>
	<p>Faites quelques recherches sur <b>Tim Berners-Lee</b> et l'origine du web et répondez aux questions suivantes :
</p>
      <ol>
        <li>Quelle était la spécialité professionnelle de Tim Berners-Lee ?</li>
        <li>Que contenait le premier site web ?</li>
        <li>En quelle année a-t-il été créé ?</li>
      </ol>
    </div>
{####<p>Contrairement à ce qu'on pourrait imaginer, Tim Berners-Lee n'était pas informaticien mais <b>physicien</b>. Il était chercheur en physique nucléaire au CERN dans les années 80. Son objectif était de faciliter le transfert de connaissance dans la communauté scientifique internationale.</p><p>Le premier site réellement opérationnel décrivait les principales caractéristiques du web et expliquait comment accéder aux documents d'autres personnes et comment configurer son propre serveur.</p><p>Les travaux ont démarré en 1989, le premier site a été mis en ligne en <b>1991</b> mais c'est en 1993 que le premier navigateur au sens ou nous les manipulons aujourd'hui est apparu.</p>}
```
 

```activité-avancée
::Qui dirige le Web ?::[html]
<p>Le 30 avril 1993, le CERN annonce que le « World Wide Web » sera <b>libre d'utilisation</b> pour tout le monde.</p>
<div class="editor-indent" style="margin-left: 30px;"><i>Ressources :<br /></i></div>
<ul>
<li><a target="_blank" href="http://fr.wikipedia.org/wiki/Site_web">http://fr.wikipedia.org/wiki/Site_web</a>,</li>
<li><a target="_blank" href="http://home.web.cern.ch/fr/topics/birth-web/licensing-web">http://home.web.cern.ch/fr/topics/birth-web/licensing-web</a></li>
</ul>
<p>Le web n'appartient à personne, en revanche chaque site est sous la responsabilité d'un auteur (le rédacteur des pages) et d'un hébergeur (le propriétaire du serveur). Les seules lois qui le régissent sont les lois sur la diffusion de contenu dans des média, comme par exemple dans la presse ou l'audiovisuel. <br />Si des contenus inappropriés, insultants, diffamants, ... font l'objet d'une plainte, l'auteur est responsable et l'hébergeur est tenu de les effacer. Aucun contenu ne se retrouve donc <i>a priori</i> sans responsable, il se trouve toujours hébergé sur un serveur avec un numéro IP officiel et donc une identité physique répertoriée. <br />Évidemment, dans la pratique, certains serveurs peuvent être physiquement dans des pays où les autorités sont très laxistes, et les contenus s'en trouvent quasi intouchables. Le web n'a pas de frontière, la localisation géographique d'un serveur n'a aucune conséquence sur son accessibilité, les internautes que nous sommes n'avons en général pas conscience du lieu où est hébergé le site que nous consultons, pourtant les lois en vigueur ne sont pas les mêmes dans tous les pays. <br />Par exemple <b>Wikileaks</b> est interdit d'hébergement sur des serveurs américains, mais a trouvé des pays qui acceptent de l'héberger.</p>
<div class="editor-indent" style="margin-left: 30px;"><i><b>Questions</b></i></div>
<ol>
<li>Qu'est-ce que Wikileaks ?</li>
<li>Qui en est le fondateur ?</li>
<li>Exprimez-vous en quelques lignes sur votre position citoyenne (intérêt, légalité, ...) de ce genre de sites.</li>
</ol>
{####<p id="docs-internal-guid-3fe28ae3-d61d-dc88-8eea-c34984c1d971"><b>WikiLeaks</b> (wikileaks.org) est une<a href="https://fr.wikipedia.org/wiki/Association_%C3%A0_but_non_lucratif"> </a><span>association à but non lucratif</span> dont le<span> site web</span><span> lanceur d'alertes</span> publie des documents ainsi que des analyses politiques et sociales. Sa raison d'être est de donner une audience aux<span> fuites d'information</span>, tout en protégeant ses sources.</p>
<p dir="ltr">( ref : <a target="_blank" href="https://fr.wikipedia.org/wiki/WikiLeaks">https://fr.wikipedia.org/wiki/WikiLeaks</a>)</p>
<p dir="ltr"></p>
<p dir="ltr">Le fondateur est <b>Julian Assange.</b></p>
</body>}

````


## Clients et serveurs

### Le modèle client/serveur
[video](https://player.vimeo.com/video/138623558){: .lien_video}
Le Web, et bien d'autres applications d'internet, fonctionnent selon un modèle très simple : le modèle client/serveur.

Celui-ci peut s'illustrer par un petit exemple du quotidien. Dans la vie de tous les jours, si je me promène en ville et que j'ai envie d'un café ou d'une boisson rafraîchissante, j'entre dans une brasserie et j'interpelle un serveur. S'engagent alors des échanges, qui suivent un protocole assez convenu dans une langue commune.

Dès que je lui ai passé ma commande, il s'empresse de me faire savoir qu'il a compris et vient me servir à condition évidemment qu'il ait à sa disposition ce que je lui ai demandé. Si je demande un pneu de vélo ou les œuvres complètes de Karl Marx, ou simplement une marque de bière qu'il ne possède pas, il me répondra gentiment qu'il ne peut pas répondre à ma demande.Dans tous les autres cas, il va s'empresser de me servir et dès qu'il aura fini, il sera à nouveau disponible pour d'autres clients ou une nouvelle demande de ma part. En l'absence de clients, le serveur attend patiemment que quelqu'un l'interpelle.

Sur Internet, les clients et les serveurs sont toujours des programmes qui s'exécutent sur des ordinateurs. Nous avons décidé de représenter les serveurs par des tours et les clients par des ordinateurs portables afin d'être plus clairs, mais il va de soi que n'importe quel type d'ordinateur peut potentiellement jouer le rôle de client ou de serveur.

Dans le cadre du web, les clients sont les navigateurs qui nous permettent d'accéder à des sites constitués de ressources hébergées par des serveurs . Ils respectent pour leurs échanges un langage et des règles communes qu'on appelle le protocole `http` pour hypertext transfer protocol. Chaque ressource fait l'objet d'un échange demande/retour entre le client et le serveur. Certaines demandes n'aboutissent pas, quand  la ressource demandée n'existe pas par exemple. Ce sont les fameuses erreurs 404.

### Les clients
[video](https://player.vimeo.com/video/138623609){: .lien_video}

**Les clients**
**Le client quant à lui, émet les requêtes vers le serveur et réceptionne les ressources qui sont envoyées en réponse. Les clients que nous utilisons sont les navigateurs web.Ce sont donc des logiciels qui s'exécutent sur nos propres machines sous notre contrôle.**

Il en existe des centaines mais les plus connus du grand public sont Firefox, Chrome, Safari, Opera ou Internet Explorer.

**D'autres clients moins connus sont pourtant les plus actifs sur le web. Il s'agit des programmes robots des moteurs de recherche, sorte de mini navigateurs automatiques.**

Une remarque importante doit être signalée. Le terme naviguer peut prêter à confusion. **Si vous nous avez bien entendu, les clients ne se déplacent pas chez le serveur. Ce sont plutôt les ressources qui sont copiées du serveur vers le client** à travers le réseau.
**Cela signifie donc que lorsque vous visitez un site web, le serveur envoie une copie des pages que vous demandez et votre navigateur vous les présente.**

### Les serveurs

**Les serveurs** 
[video](https://player.vimeo.com/video/138623583){: .lien_video}

Un serveur est un logiciel (un programme) qui s'exécute sur une machine le plus souvent 24/24 et 7/7 et attend qu'un client l'interpelle, par exemple c'est le cas du serveur web www.univ-lille.fr qui distribue les ressources du site de l'université de Lille. Dans ces journaux, de nombreuses informations à propos des clients sont mémorisées : leur adresse IP, des dates de visites, la ressource demandée... Notons que, l'envoi d'une ressource, est en fait l' envoi d'une copie de la ressource, l'original restant disponible pour d'autres requêtes identiques. En plus de ce service de distribution, le serveur garde l' historique de toutes les requêtes qui lui ont été adressées dans des journaux d'activité : les logs en anglais. Ces journaux sont autant de traces que nous laissons et qui peuvent être analysées et exploitées.
Son rôle est de distribuer les ressources dont il dispose, c'est-à-dire qui sont stockées sur ses disques, aux clients qui les demandent . 

```activité
// question: 268  name: Erreur 404!
::Erreur 404!::[html]<p>Que signifie le code d'erreur 404 dans le protocole HTTP</p>{
	~<p>La ressource a été déplacée sur un autre serveur</p>
	=<p>La ressource n’existe pas sur le serveur</p>#<p>Votre réponse est correcte.</p> 
	~<p>Le client de peut pas communiquer avec le serveur</p>
	####<p>L'erreur 404 apparaît lorsque la ressource demandée n'existe pas sur le serveur. Cela se produit en général lorsqu'il y a une 'faute' dans l'url ou lorsque le gestionnaire du site a déplacé, supprimé ou renommé une ressource. L'url devient alors invalide.</p> 
}


// question: 270  name: le meilleur Navigateur
::le meilleur Navigateur::[html]<p>Avec quel navigateur peut-on accéder au plus grand nombre de sites ?</p>{
	~<p>Firefox</p>
	~<p>Internet Explorer</p>
	~<p>Chrome</p>
	~<p>Safari</p>
	=<p>Tous</p>#<p>Votre réponse est correcte.</p> 
	####<p>Tous les navigateurs sont équivalents de ce point de vue, seuls leur rapidité, leurs fonctionnalités avancées ou leur ergonomie les différencient.</p> 
}


// question: 273  name: Les clients
::Les clients::[html]<p>Qu'est-ce qu'un client web ?</p>{
	~%33.33333%<p>Tout logiciel qui demande des ressources à un serveur web</p>
	~%33.33333%<p>un navigateur</p>
	~%33.33333%<p>un robot de moteur de recherche</p>
	~<p>une page HTML</p>
}


// question: 271  name: Les logs c'est quoi ?
::Les logs c'est quoi ?::[html]<p>Qu'est-ce qu'un fichier de logs d'un serveur web ?</p>{
	~la liste des noms des gens qui ont consulté le site hébergé sur le serveur#non, sur la plupart des sites nous n'envoyons pas nos noms, les logs conservent les traces des requêtes effectuées par les clients repérés par leur adresse IP ainsi que toutes les activités du serveur dans un journal 
	=un journal des activités du serveur#Oui, bravo 
	~la liste de toutes les ressources stockées sur ce serveur#Non, les logs conservent le journal des activités du serveur 
	####<p>Voici ci dessous quelques lignes extraites d'un journal (log) d'un serveur Web. Chaque ligne correspond à une requête d'un client. Les lignes ont été "anonymisées" \: nous avons remplacé les adresses IP des clients par 127.0.0.1.  </p><p> </p><p>Sur cette ligne vous avez l'adresse IP (anonymisée) du client, suivi de la date et l'heure de la requête et entre guillemets la requête adressée ("GET /polys/...") qui signifie " donne-moi la ressource "/poly/...etc". On voit également le code 200 signalant que la requête a bien été traitée sans erreur et aussi les caractéristiques du client \:  C'est ici le robot du moteur de recherche bing.</p><p><br /><code>127.0.0.1 - - [22/Sep/2015\:08\:22\:48 +0200] "GET /polys/access-1997/node66.html HTTP/1.1" 200 2257 "-" "Mozilla/5.0 (compatible; bingbot/2.0; +http\://www.bing.com/bingbot.htm)"</code></p><p> </p><p>L'exemple suivant est intéressant car il montre une suite de 5 requêtes. La première est un celle d'un document contenant des liens vers d'autres ressources (feuilles de style CSS et images au format PNG). Les 5 requêtes sont enchaînées car le navigateur (ici Safari) a immédiatement demandé au serveur les ressources nécessaires pour afficher une page web complète.</p><p>    <br /><code>127.0.0.1 - - [22/Sep/2015\:08\:19\:57 +0200] "GET /\~torre/Football/Confrontations/Ajaccio-Clermont.php HTTP/1.1" 200 4836 "https\://www.google.fr/" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/42.0.2311.135 Safari/537.36 Edge/12.10240" </code><br /><code>127.0.0.1 - - [22/Sep/2015\:08\:19\:57 +0200] "GET /\~torre/include/css/ft-v3.css HTTP/1.1" 200 6692 "http\://www.grappa.univ-lille3.fr/\~torre/Football/Confrontations/Ajaccio-Clermont.php" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/42.0.2311.135 Safari/537.36 Edge/12.10240"</code><br /><code>127.0.0.1 - - [22/Sep/2015\:08\:19\:57 +0200] "GET /\~torre/include/css/ft-print-v3.css HTTP/1.1" 200 2231 "http\://www.grappa.univ-lille3.fr/\~torre/Football/Confrontations/Ajaccio-Clermont.php" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/42.0.2311.135 Safari/537.36 Edge/12.10240"</code><br /><code>127.0.0.1 - - [22/Sep/2015\:08\:19\:57 +0200] "GET /\~torre/Images/valid-html5.png HTTP/1.1" 200 1723 "http\://www.grappa.univ-lille3.fr/\~torre/Football/Confrontations/Ajaccio-Clermont.php" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/42.0.2311.135 Safari/537.36 Edge/12.10240"</code><br /><code>127.0.0.1 - - [22/Sep/2015\:08\:19\:57 +0200] "GET /\~torre/Images/FabienTorre.png HTTP/1.1" 200 478 "http\://www.grappa.univ-lille3.fr/\~torre/Football/Confrontations/Ajaccio-Clermont.php" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/42.0.2311.135 Safari/537.36 Edge/12.10240"</code></p><p>Un dernier petit exemple pour les hackers \:-). On peut lire avec un peu d'expérience ou de sagacité que la ressource (ici /FAQ-LaTeX/12.3.html) a été demandée depuis une page web (indiquée après le code de succès 200 et la taille de 7444 de cette ressource) qui est une adresse sur les serveurs de Google. En regardant mieux encore, on peut même lire que c'est à la suite d'une recherche à propos de "FAQ-LaTeX"... C'est en partie grâce à cette indication de provenance qu'on peut rémunérer les sites qui font de la publicité vers d'autres sites...</p><p><br /><code>127.0.0.1 - - [22/Sep/2015\:08\:22\:30 +0200] "GET /FAQ-LaTeX/12.3.html HTTP/1.1" 200 7444 "http\://www.google.fr/url?sa\=t&rct\=j&q\=&esrc\=s&source\=web&cd\=1&ved\=0CCQQFjAAahUKEwjo6IWtgIrIAhVFOxQKHdjEDfw&url\=http%3A%2F%2Fwww.grappa.univ-lille3.fr%2FFAQ-LaTeX%2F12.3.html&usg\=AFQjCNEtHaKlFbotxdHj6bxRzpkDN3NwkA" "Mozilla/5.0 (Windows NT 6.1; WOW64; rv\:24.0) Gecko/20100101 Firefox/24.0"</code><br /><br /></p> 
}


// question: 269  name: Les protocoles
::Les protocoles::[html]<p>Par quel protocole les clients et serveurs dialoguent-ils ? <br></br></p>{
	~<p>HTML<br></p>
	=<p><span style\="font-weight\:normal;"><span style\="font-size\:14.666666666666666px;font-family\:Arial;color\:\#434343;background-color\:transparent;font-weight\:400;font-style\:normal;font-variant\:normal;text-decoration\:none;vertical-align\:baseline;white-space\:pre-wrap;">HTTP</span></span></p>#Votre réponse est correcte. 
}


// question: 272  name: La distribution
::La distribution::[html]<p>Quand un serveur a envoyé une image à un client, il doit attendre que ce client l'ait rendue avant de la distribuer à un autre client.</p>{TRUE####<p>Cette notion de "rendre" une ressource n'a pas de sens, à chaque fois les ressources sont copiées et ce sont des copies qui sont envoyées, ...</p><p>Le serveur conserve toujours ses ressources et peut en faire autant de copies que nécessaire.</p> }


````

## Exemple et récapitulatif

[video]( https://player.vimeo.com/video/138623678 ){: .lien_video } 

### Exemple

Commençons par un exemple très simple pour comprendre le mécanisme de base. Si à l'aide d'un client web tel que Firefox, je saisis l'adresse :

```
 http://culturenumerique.univ-lille3.fr/PageExemple
```

Que se passe -t-il ?

Mon client interprète ma saisie comme l'interrogation par le protocole `http` du serveur situé sur la machine `culturenumerique.univ-lille3.fr` pour lui demander la ressource `/PageExemple`

Comme nous l'avons vu précédemment, l'adresse `IP` de ma machine sera nécessaire pour communiquer avec le serveur. Mais mon navigateur va également réunir un certain nombre d'autres informations disponibles sur ma machine (informations que nous verrons plus loin) et les joindre à la requête envoyée au serveur qui héberge la ressource. 
Le serveur reçoit cette requête, la comprend car elle est formulée selon les règles définies dans ce fameux protocole `http`, norme utilisée pour que les clients web et les serveurs web puissent communiquer.


Une part du succès du web repose sur le fait que `http` est utilisé par TOUS les serveurs web et TOUS les clients WEB, quels qu'ils soient et leur permet donc de dialoguer et de s 'échanger des informations.

Le serveur fait alors une copie de la ressource demandée et la renvoie au client, celui-ci n'a plus qu'à afficher le contenu de la ressource dans la fenêtre du navigateur.

Notons qu'une adresse du type : `http://culturenumerique.univ-lille3.fr/PageExemple`
s'appelle une URL pour Uniform Resource Locator, c'est-à-dire en français l'adresse d'une ressource. Le mot uniform suggère une convention d'écriture de ces adresses et une uniformisation de l'écriture de ces adresses. Il est important de noter que cette URL contient à la fois le nom du serveur (la machine `culturenumerique.univ-lille3.fr` dans notre exemple) qui héberge la ressource ET le nom de la ressource sur ce serveur (ici `/PageExemple`).

### Récapitulatif

Retenons dans un premier temps les notions suivantes :

- le web permet à des clients d'accéder à des copies de ressources hébergées sur des serveurs.
- les ressources sont toutes repérées par des URLs.
- les ressources de type texte sont décrites dans un langage normalisé, le `html` qui permet de créer des hyperliens pour faciliter notre navigation.
- les programmes appelés serveurs (on ne les « voit » pas) et clients (les navigateurs) parlent tous la même langue : le protocole `http`.
- comme pour beaucoup de communications sur internet, ces échanges entre client et serveurs ne sont pas confidentiels, et le protocole ne peut même pas garantir que les clients et les serveurs sont bien ceux qu'ils annoncent être.

Une évolution du protocole `http` remédie à ces problèmes en ajoutant le cryptage des communications pour assurer la confidentialité, et l'authentification des protagonistes dans ces échanges.C'est le protocole `https`.

En conclusion, dès que vous transmettez des données confidentielles veillez bien à la présence du petit verrou qui indique l'utilisation du protocole `https`.

```activité
// question: 274  name: Composition d'une URL
::Composition d'une URL::[html]<p>Quelles informations sont indiquées dans une URL ?</p>{
	~%33.33333%<p>le nom du serveur</p>
	~%33.33333%<p>le nom d'une ressource</p>
	~%33.33333%<p>le protocole utilisé</p>
	~<p>si la ressource est une image ou un texte</p>
	~<p>l’adresse du client</p>
	####<p>URL \: Unified Ressource Locator, soit en français \: l'adresse d'une ressource. Elle contient évidemment \:</p><ul><li>le non du serveur sur laquelle elle est stockée</li><li>le nom de la ressource \: le nom du fichier et le 'chemin' (dossier/sousdossier/) pour y accéder</li><li>le protocole utilisé, pour le Web \: http\:// ou https\://</li></ul><p>Elle ne précise pas le type de la ressource et elle est évidemment indépendante de l'adresse des éventuels clients qui feraient une requête...</p> 
}


// question: 275  name: HTTP vs HTTPS
::HTTP vs HTTPS::[html]<p>Quelle est la différence entre HTTP et HTTPS ? Grâce à HTTPS \:</p>{
	~<p>mes communications avec le serveur sont cachées</p>
	~%50%<p>le contenu de mes communications avec le serveur est crypté</p>
	~%50%<p>je peux m’assurer que le serveur est celui auquel je veux m’adresser</p>
	####<p>Le protocole https a 2 fonctions majeures. Il permet \:</p><ul><li>de crypter les échanges (requêtes/réponses) par exemple des mots de passe ou des codes de Carte Banquaire, seul le destinataire pourra les décrypter</li><li>d'authentifier les serveurs, par exemple pour éviter qu'un site pirate cherche à se faire passer pour le site d'une banque</li></ul> 
}


// question: 276  name: Les balises HTML
::Les balises HTML::[html]<p>Quel est le rôle des balises en HTML ?</p>{
	~%50%<p>de délimiter des parties de texte</p>
	~%50%<p>de décrire la structure des documents</p>
	~<p>de signaler aux internautes des pages dangereuses</p>
	~<p>d'accélérer internet</p>
}


// question: 277  name: Les informations échangées entre clients et serveurs
::Les informations échangées entre clients et serveurs::[html]<p>Quelles autres informations que l’URL peuvent être échangées dans un échange entre un client et un serveur Web ?</p>{
	~%33.33333%<p>l’adresse IP du client</p>
	~%33.33333%<p>le nom du navigateur web \: firefox, opera, internet explorer, ….</p>
	~%33.33333%<p>la page présentée dans le navigateur au moment où la requête est effectuée</p>
	####<p>l’IP est toujours nécessaire pour indiquer au destinataire à qui il doit répondre. Mais potentiellement les 3 informations peuvent être échangées, et bien d'autres encore !</p> 
}


// question: 278  name: Une page web
::Une page web::[html]<p>Quand on regarde une page web, toutes les informations viennent du même serveur.</p>{
	~<p>oui</p><p> </p>
	=<p>non</p>#<p>Votre réponse est correcte.</p> 
	####<p>Une page Web est souvent constituée de plusieurs ressources. Chaque ressource fait l'objet d'un échange entre le client et un serveur, pas forcément toujours le même !</p> 
}


// question: 279  name: Une URL
::Une URL::[html]<p>Qu'est-ce qu'une URL ?</p>{
	~<p>une ressource</p>
	=<p>l'adresse d'une ressource</p>#<p>Votre réponse est correcte.</p> 
	~<p>un fichier</p>
}


````

## HTML

### HTML: contenu, structure, liens
[video]( https://player.vimeo.com/video/138623721 ){: .lien_video } 
Allons maintenant voir plus en détail le fonctionnement ; le langage `html` a plusieurs caractéristiques très intéressantes. Nous avons vu qu'il permettait d'introduire des hyperliens dans un document, mais il possède d'autres atouts.


C'est un langage de description de document , c'est à dire qu'il permet d'expliquer comment le document est construit et donc comment un logiciel comme un navigateur peut l'afficher. Concrètement, `html` permet d'ajouter au contenu texte des éléments de structure du type : ce paragraphe est un titre, celui-là est un sous-titre, cet  est une légende, ce mot doit être mis en exergue...
Cette distinction contenu/structure est essentielle, elle est présente dans de nombreux domaine et nous y reviendrons souvent. La structure permet d'ajouter du sens aux parties de textes et à l'aide de règles de résentation de rendre une page `html` affichable sur de nombreux types d'écrans. Le navigateur calcule alors la présentation adaptée, par exemple pour une tablette, un smartphone ou un grand écran d'ordinateur.

En français la traduction de `html` est : langage de balisage pour documents hypertexte. Les balises vont indiquer la structure du document en titres, paragraphes etc ainsi que des liens vers d'autres ressources du Web. Les documents sont donc des textes décrivant des documents hypertexte. Mais que fait ensuite le client, le navigateur avec ce document hypertexte qu'il vient de recevoir ?

Grâce à la description faite du document et en fonction de ses capacités le navigateur va pouvoir recomposer le document et vous l'afficher. Les pages web que votre navigateur affiche sont des textes avec le plus souvent des images, formant un document complet. En fait ce document est réalisé par l'assemblage de nombreuses ressources. En effet, le langage `html` permet également de spécifier l'insertion d'images (ou d'autres ressources) à différents endroits d'un document. Les images ne sont pas à proprement parler insérées dans le document principal, mais un balisage indique qu'à cet endroit il faudra insérer une image.

### Rassembler les ressources
[video]( https://player.vimeo.com/video/138623756 ){: .lien_video } 

Rappelons qu'une page affichée dans votre navigateur est en fait un assemblage de nombreuses ressources. Il faut donc dans un premier temps les rassembler.

Une image est une ressource au même titre que les autres documents. Elle est donc désignée par une URL. Notez bien que ce mécanisme d'URLs permet de désigner des images dans les pages web comme autant de ressources indépendantes. En conséquence, les images ne se trouvent pas forcément sur le même serveur que le document principal.

Examinons alors plus en détail ce qui se passe lorsque je clique sur un lien qui pointe vers une ressource de type texte mais qui cette fois contient des liens vers des images, ce que nous faisons tous les jours et qui constitue l'essentiel des pages que nous consultons. Le début du processus est rigoureusement identique à l'exemple précédent, mais au moment du calcul du résultat, (i.e. de l'affichage de la page Web par le navigateur), le client rencontre dans la description de sa page, un lien vers une ressource image . Il ne peut pas afficher cette image directement puisque le fichier n'est pas inclus , seul le lien vers cette ressource est spécifié.

Alors, sans rien nous demander , il effectue une autre requête (identique à la précédente mais avec l'url de l'image) pour obtenir cette ressource. La réponse à cette requête est une copie du fichier image indiqué. Le client peut alors l'intégrer à l'affichage de la page.

Ce processus se répète autant de fois qu'il y a d'images dans le document et ce, quelles que soient leurs tailles.

Cette remarque prendra tout son sens lorsque nous nous intéresserons aux traces que nous laissons et à la préservation de notre vie privée.


### Mise en forme
[video]( https://player.vimeo.com/video/138623826 ){: .lien_video } 

Revenons maintenant à l'affichage de la page dans mon navigateur.

Le document que le client/navigateur reçoit contient du texte et des images (en lien) et il est structuré .

Mais a priori aucune indication n'est donnée pour définir comment les éléments doivent être affichés.

Un titre doit-il être en rouge, en noir, en gras, de quelle taille, aligné à gauche ou centré ?

Or, tous les fichiers étant décrit dans une norme commune , le langage HTML , tous les navigateurs proposent une mise en forme par défaut de chacun des éléments possibles d'un document.

Cette mise en forme est généralement basique et pas très esthétique mais elle permet de proposer sur n'importe quelle machine un affichage du contenu.

Lorsque nous surfons tous les jours, nous voyons bien qu'au contraire, les sites proposent des affichages très graphiques beaucoup plus sophistiqués que l'affichage par défaut.

C'est l'utilisation de feuilles de styles qui sont associées au document qui permet cela. Une feuille de styles définit les règles de présentation d'un document.

Ces feuilles de styles, qui constituent à nouveau une ressource avec leur propre url redéfinissent l'affichage des différents éléments de contenu en utilisant par exemple une charte graphique aux couleurs de l'organisation responsable du site.

Concrètement, dans le fichier du document principal, un lien particulier vers une ressource/feuille de style, déclenche pour le navigateur une requête pour obtenir cette feuille de style qui sera utilisée à la place des styles par défaut.

Le triptyque structure/contenu/présentation est fondamental pour la compréhension de ce qu'est un document numérique.

Il est réalisé par le couple HTML/feuilles de style sur le Web.

Mais une bonne utilisation du traitement de texte passe également par la maîtrise de cette décomposition en 3 parties.

```activité

// Question vide de type description (sans {}) pour présenter le support des questions suivantes
::Exercice::[html]
<p>Rendez-vous sur la page <a target="_blank" href="http://culturenumerique.univ-lille3.fr/activitesWeb/html/">http://culturenumerique.univ-lille3.fr/activitesWeb/html/</a> <br />Lisez, observez, gardez les pages ouvertes dans des onglets, puis répondez aux questions du quizz suivant </p>


// question: 283  name: Au delà du contenu
::Au delà du contenu::[html]<p>Pourquoi peut-on créer facilement une table des matières ou construire la liste des liens d’un document HTML ?</p>{}


// question: 282  name: Comprendre les balises
::Comprendre les balises::[markdown]Nous vous avons expliqué que les balises `<section>... </section>` servaient à délimiter les parties, les balises `<h1> ... </h1>` délimitent les titres de premier niveaux, à votre avis que signifient les balises `<p> ... </p>` ?{}


// question: 280  name: Repérer la feuille de styles
::Repérer la feuille de styles::[html]<p>Comparez les codes sources des 2 premières pages, seule une ligne supplémentaire a été insérée, elle précise l'utilisation d'une feuille de styles pour l'affichage du contenu. Indiquez le numéro de la ligne qui a changé et recopiez-la également.</p>{}


// question: 284  name: Décrire un document
::Décrire un document::[html]<p>Pourquoi s’échanger une description de document plutôt qu’un document lui-même est plus adéquat au Web ?</p>{
	~%33.33333%<p>tous les clients n’ont pas la même capacité d’affichage</p>
	~%33.33333%<p>la description contient plus d’informations \: structure + contenu</p>
	~%33.33333%<p>la structure permet d'ajouter du sens (ceci est un titre, etc...) explicitement.</p>
}


// question: 281  name: Exemple de mise en forme
::Exemple de mise en forme::[html]<p>Observez la mise en forme du titre principal dans la deuxième version et indiquez les caractéristiques d'affichage qui ont été choisies dans cette feuille de styles (ce qui change par rapport à la première version).</p>{
	~%25%la typo (la police de caractères)
	~l'ordre des mots a été changé
	~%25%la couleur des caractères
	~%25%l'alignement du paragraphe
	~%25%les caractères ont été transformés en majuscule
	~l'orthographe a été modifié
	####<p>Une feuille de styles ne peut pas changer l'ordre des mots ou l'orthographe, cela reviendrait à changer le contenu, seules les caractéristiques graphiques sont possibles, ici la police, la couleur, l'alignement et la 'casse' des caractères (ils sont affichés en majuscule).</p> 
}


// question: 286  name: Les feuilles de style
::Les feuilles de style::[html]<p>Une feuille de style...</p>{
	~<p>décrit le contenu d'un document HTML</p>
	~%50%<p>permet de décrire la présentation graphique d'un document</p>
	~%50%<p>décrit par exemple la couleur du texte, la taille des marges</p>
	~<p>coordonne automatiquement les couleurs d'une page web</p>
	~<p>contrôle si on écrit comme Flaubert ou Blazac</p>
}


// question: 285  name: Structure et contenu
::Structure et contenu::[html]<p>Le langage HTML permet de décrire des documents en indiquant leur structure et leur contenu. Comment la structure est-elle décrite ?</p>{
	=<p>Par un balisage du texte</p>#Votre réponse est correcte. 
	~<p>Par des couleurs et du gras ou la taille des caractères</p>
}


// question: 288  name: Une page Web
::Une page Web::[html]<p>Pour qu’un client affiche une page Web,...</p>{
	~<p>une seule requête vers un unique serveur suffit toujours</p>
	~<p>parfois plusieurs requêtes sont nécessaires mais toujours vers le même serveur</p>
	=<p>parfois plusieurs requêtes vers plusieurs serveurs sont nécessaires</p>#Votre réponse est correcte. 
}


// question: 287  name: Expressivité de HTML
::Expressivité de HTML::[html]<p>Le langage HTML permet de représenter une image.</p>{TRUE#<p>Les images ne sont pas décrites en HTML. HTML ne permet que d'indiquer qu'à un certain endroit dans un document, se trouve une image. 
####[html]En HTML, les images sont représentées dans un format qui leur est propre. Elles sont soit <a href="https://fr.wikipedia.org/wiki/Image_matricielle" target="_blank">matricielles</a> ou <a href="https://fr.wikipedia.org/wiki/Image_vectorielle" target="_blank">vectorielles</a>.</p><ul><li>Les images matricielles décrivent une image comme un assemblage de points de couleur, généralement dans un rectangle de dimensions données par des nombres de points en largeur et en hauteur. Les formats de représentation de ces images matricielles utilisées sur le web sont par exemple le <a href="https://fr.wikipedia.org/wiki/Graphics_Interchange_Format" target="_blank">GIF</a>, le <a href="https://fr.wikipedia.org/wiki/Portable_Network_Graphics" target="_blank">PNG</a>, le <a href="https://fr.wikipedia.org/wiki/JPEG" target="_blank">JPEG</a>.</li><li>Les images vectorielles sont la description d'une image par des formes et des opérations géométriques. Le format <a href="https://fr.wikipedia.org/wiki/Scalable_Vector_Graphics" target="_blank">SVG</a> est utilisé sur le web. Peu d'autres le sont. </li></ul>}
```

```activité-avancée
::Activité sur les serveurs::[markdown]
Rendez-vous sur la page :
(pageServeurs.html)[http://culturenumerique.univ-lille3.fr/activitesWeb/html/pageServeurs.html]
Lisez, observez et répondez aux questions posées...
{}
````

# 2. Reprise des bases en HTML/CSS

L'objectif de ces 3 séances est de reprendre les bases de HTML/CSS déjà vues dans les précédents cours. 

##Enoncé

Reprenez le document [template_doc.html](https://github.com/freddylimpens/Cours_CMS_Web/blob/master/template_doc.html) dans le dépôt de fichier avec la feuille de style css associée [style_0.css](https://github.com/freddylimpens/Cours_CMS_Web/blob/master/style_0.css). L'objectif de cet exercice est de modifier le code HTML ainsi que le code CSS pour que ce document soit le plus proche possible du document inclus [test.pdf](https://github.com/freddylimpens/Cours_CMS_Web/blob/master/media/test.pdf). 

##Remarques/Aides

Outre l'apparence générale du document (couleurs, bordures, etc) la structure évolue un tout petit peu vers un affichage à 2 colomnes, ce qui implique de modifier également la structure (HTML) du document. 

## Ressources suggérées:

- [inline block](http://learnlayout.com/inline-block.html)
- [css floats](http://www.w3schools.com/css/css_float.asp)
- [discussion sur les avantages de chaque approche](http://stackoverflow.com/questions/15172520/advantages-of-using-displayinline-block-vs-floatleft-in-css)

# 3. Création d'une carte de visite en ligne

Sur la base des fichiers [one_page_image_bg.html](https://github.com/freddylimpens/Cours_CMS_Web/blob/master/one_page_image_bg.html) et [one_page_image_bg.css](https://github.com/freddylimpens/Cours_CMS_Web/blob/master/one_page_image_bg.css) qui utilisent l'image [media/chemin_brumeux.JPG](https://github.com/freddylimpens/Cours_CMS_Web/blob/master/media/chemin_brumeux.JPG), réalisez votre propre "business card" en ligne. 

Le petit paragraphe de texte vous présentera succintement, et vous ajouterez une photo (ou image) sur le côté de ce texte (réutilisation de l'affichage double colonne vu précedemment).

Le principe de ce code HTML repose sur les différentes propriétés codées par la règle "position" de CSS, en particulier cet exemple couvre les interactions et les comportements générés par les propriétées:

- `position: fixed` : qui permet de placer de manière fixe (sans déplacement avec le scroll) par rapport au "viewport", i.e la fenêtre du navigateur; ici c'est la `<div id="bg">` qui est placée de cette manière afin de fonctionner comme un "canevas" sur lequel se positionnera l'image
- `position: absolute`: qui permet de placer un élément par rapport à la position de l'élément conteneur, ici l'image par rapport à la `<div id="bg">`. Notez aussi l'usage de `margin:auto` pour centre l'image.
- `position: relative`:  qui permet de placer un élément relativement par rapport à sa position normale; ici c'est le bloc `wrap_page` qui contient le texte qui naturellement se placera dans le coin en haut à gauche, et qui est légèrement recentré à l'aide des propriétés `margin` . NOtez aussi le positionnement en "altitude" avec `z-index` qui nécessite un élément "positionné" pour être effectif.

**Références:**

- http://www.w3schools.com/css/css_positioning.asp
- http://www.w3schools.com/css/css_margin.asp
- http://www.w3schools.com/cssref/pr_pos_z-index.asp

# 4. 