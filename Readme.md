# Memo HTML-CSS

## ***__Introduction au HTML__***  

- ### ***Qu’est-ce que le HTML ?***  

  - #### Qu’est-ce que le HTML ?

    - Le HTML ( HyperText Markup Language ), est utilisé pour mettre en page un site web  

      - [Lien vers la page des références des éléments HTML](https://developer.mozilla.org/fr/docs/Web/HTML/Element)

- ### ***HTML, un langage en constante évolution***  

  - #### HTML, un langage en constante évolution

    - Le W3C ( Wolrd wide Web Consortium ), est l’organisme chargé de la standardisation et de la compatibilité des technologies du web  

      - [Site du W3C](https://www.w3.org/) <a id="W3C"></a>

- ### ***HTML, un langage côté client***  

  - #### HTML, un langage côté client

    - Le « côté client » couvre toutes les opérations effectuées par une application ou un site web au sein d’un navigateur  

    - Le langage HTML est donc un langage « côté client ». C’est le navigateur de l’utilisateur qui interprète le HTML  

    - Les pages d’un site web sont transmises sous forme de code HTML brut au navigateur, qui va l’interpréter pour afficher son contenu sur l’écran  

    - Cette partie du développement d’un site web est appelée « développement frontend », faisant référence à la partie création de l’interface utilisateur, au côté visuel d’un site ou d’une application web. HTML sert à définir la structure et l’organisation des pages  

##
## ***__Syntaxe générale de HTML__***  

- ### ***Syntaxe générale du code HTML***  

  - #### Syntaxe générale du code HTML  

    - Le code HTML est un langage de balisage hypertexte : il se construit à l’aide de balises, qui sont entourées par deux chevrons « < » et « > »  

    - Ces balises peuvent également prendre en charge des attributs, qui, eux, permettront de donner plus de précision sur la façon dont la balise doit être interprétée  

    - Les balises HTML minimal  

      `<!DOCTYPE html>`  
      `<html lang="fr">`  
      $\qquad$`<head> ... </head>`  
      $\qquad$`<body> ... </body>`  
      `</html>`  

    - Les balises sont « répétées ». En HTML, la grande majorité des balises fonctionnent par paires et sont composées d’une balise d’ouverture et une balise de fermeture  

    - La balise de fermeture est identique à la balise d’ouverture si ce n’est qu’elle contient un slash (« / ») juste après le chevron ouvrant  
      - Ex : `<head> ... </head>`  

    - Il existe cependant des balises qui n’ont pas besoin de balise fermante, on les appelle balises auto-fermantes ou orphelines  

    - Le code HTML commence toujours avec la balise suivante  

      - `<!DOCTYPE html>`  

        - Cette balise permet de spécifier au navigateur le type de document HTML utilisé. Il est donc crucial de toujours inclure cette balise au début de votre code HTML  

    - La balise ***\<html>*** que l’on appelle aussi l’élément racine du document HTML marque le début du document HTML  

      - `<html> ... </html>`  

    - La balise ***\<head>*** inclut toutes les informations qui ne s’affichent pas directement dans la page web, mais qui sont utiles pour le bon fonctionnement du code, ainsi que pour les moteurs de recherche  
      
      - `<head> ... </head>`  

        - La balise ***\<head>*** est essentielle, Elle s’imbrique entre la balise d’ouverture ***\<html>*** et de fermeture ***\</html>***

    - La balise ***\<body>*** définit l’ensemble des éléments qui vont être visibles sur la page tels que les titres, le texte, les images ou encore les formulaires  

      - `<body> ... </body>`  

        - La balise ***\<body>*** est essentielle, Elle s’imbrique entre la balise d’ouverture ***\<html>*** et de fermeture ***\</html>***

- ### ***Balises structurelles en HTML***  

  - #### Balises structurelles en HTML

    - La balise ***\<div>***  

      - La balise ***\<div>*** est la balise la plus couramment utilisée pour placer du contenu sur une page web, elle va permettre de diviser la page web en différents espaces et donc de la structurer de manière organisée  

        - `<div> ... </div>`  

    - La balise ***\<nav>***  

      - Délimite la partie de la page dans laquelle nous allons pouvoir trouver les liens qui conduisent les autres pages du site web. Il s’agit de la balise de navigation où l’on pourra retrouver le menu principal du site  

        - `<nav> ... </nav>`  

    - La balise ***\<header>***  

      - Dans le ***\<header>***, se compose généralement du titre, d’un texte d’introduction ou encore une bannière, c’est ici que vous placerez les éléments qui permettront d’identifier la thématique de votre page web.  

        - `<header> ... </header>`  

    - La balise ***\<footer>***  

      - Dans le pied page ***\<footer>*** on retrouvera le menu de bas de page, les pages légales et les informations relatives aux droits d’auteur, sera intégré dans la balise  

        - `<footer> ... </footer>`  

    - La balise ***\<section>***  

      - La balise ***\<section>*** est utiliser pour regrouper les éléments d’une même thématique dans un conteneur dédié, elle permet de découper le contenu par thématique pour mieux organiser le contenu sur la page  
        
        - `<section> ... </section>`  

    - La balise ***\<article>***  

      - La balise ***\<article>*** est utilisée pour délimiter une section dont le contenu est autonome, comme des articles de blog, des produits ou encore des commentaires  

        - `<article> ... </article>`  

    - La balise ***\<aside>***  

      - la balise ***\<aside>*** sert à définir un contenu « à côté » d’un contenu principal. Ce contenu à part est souvent lié de manière indirecte au contenu principal. On l’utilise pour les encarts publicitaires ou encore les articles connexes  

        - `<aside> ... </aside>`  

##
## ***__L'organisation du texte__***  

  - ### ***Éléments d’organisation du texte en HTML***  

    - #### Éléments d’organisation du texte en HTML

      - Il existe plusieurs niveaux de balises de titres, allant du ***\<h1>*** jusqu'au ***\<h6>***. Les balises ont des tailles et des styles de police différents, ce qui permet de les différencier visuellement. Ainsi, le titre principal de la page est inséré dans la balise ***\<h1>***, tandis que les balises ***\<h2>*** à ***\<h6>*** sont utilisées pour les sous-titres  

        `<h1> ... </h1>`  
        `<h2> ... </h2>`  
        `<h3> ... </h3>`  
        `<h4> ... </h4>`  
        `<h5> ... </h5>`  
        `<h6> ... </h6>`  

      - La balise \<p>  

          - Les balises ***\<p>*** sont utilisées en HTML pour délimiter un paragraphe de texte, elle permet d'ajouter des sauts de ligne entre les différents paragraphes  

            - `<p> ... </p>`  

      - Les balises \<ul> et \<ol>  

        - La balise ***\<ul>*** permet de créer une liste d'éléments sans ordre particulier. Chaque item est précédé d'un point (ou autre symbole), et il n'y a pas de numérotation. Ce type de liste est idéal pour présenter des informations qui ne sont pas liées entre elles  

          - `<ul> ... </ul>`  

      - la balise ***\<ol>*** permet de créer une liste ordonnée, où chaque item est numéroté. Cette liste est très utile pour présenter des informations qui ont un ordre ou une hiérarchie, comme les étapes d'un processus  

        - `<ol> ... </ol>`  

          - Ces éléments apportent une structure visuelle à l'information  
          - Ceci qui est crucial pour la lisibilité de la page  
          - Il est possible d'ajouter des sous-listes à l'intérieur d'une liste principale, il faut ajouter une liste imbriquée dans une autre liste  

      - Les balises ***\<li>***, il est également important de noter que, à l'intérieur de ces deux balises, chaque élément de la liste est inscrit dans une balise ***\<li>***

        - Exemple avec la balise ***\<ul>***  

          `<ul>`  
          $\qquad$`<li> ... </li>`  
          $\qquad$`<li> ... </li>`  
          $\qquad$`<li> ... </li>`  
          $\qquad$`<li> ... </li>`  
          `</ul>`

        - Exemple avec la balise ***\<ol>***  

          `<ol>`  
          $\qquad$`<li> ... </li>`  
          $\qquad$`<li> ... </li>`  
          $\qquad$`<li> ... </li>`  
          $\qquad$`<li> ... </li>`  
          `</ol>`  

- ### ***Mise en forme du texte en HTML***  

  - #### Mise en forme du texte en HTML  

    - une balise block est une balise qui crée un nouveau bloc de contenu sur la page web. Cela signifie que tout le contenu compris entre la balise d'ouverture et la balise de fermeture sera affiché comme un bloc distinct  

    - Les exemples les plus courants de balises block incluent les balises ***\<div>***, ***\<p>***, ***\<ul>***, ***\<ol>***, ***\<h1>*** à ***\<h6>*** et ***\<blockquote>***  

    - Les balises inline sont souvent utilisées pour formater le texte ou pour ajouter des éléments en ligne, tels que des liens hypertextes, des images ou des boutons. Les exemples les plus courants de balises inline incluent les balises ***\<a>***, ***\<img>***, ***\<span>*** et ***\<button>***  

    - Lors de la création d'une page web, il est important de considérer la mise en forme, le HTML a plusieurs balises qui permettent de mettre en évidence certains mots ou texte

    - Les balises ***\<b>*** et ***\<strong>*** permettent de faire apparaître le contenu en gras

      - la balise ***\<b>*** sert uniquement à la mise en forme
        
        - `<b> ... </b>`  

      - la balise ***\<strong>*** indique que le mot ou la phrase a une importance particulière

        - `<strong> ... </strong>`  

    - Les balises ***\<i>*** et ***\<em>*** permettent de faire apparaître le contenu en italique

      - la balise ***\<i>*** sert uniquement à la mise en forme
          
        - `<i> ... </i>`  

      - la balise ***\<em>*** est préférée pour mettre en valeur un mot ou une phrase bien précise  

          - `<em> ... </em>`  

    - la balise ***\<mark>*** permet de faire ressortir visuellement une partie de texte en la surlignant avec une couleur de fond différente  
          
      - `<mark> ... </mark>`  

    - la balise ***\<small>*** est utilisée pour formater du texte en réduisant sa taille. Elle peut être utilisée pour indiquer des notes de bas de page, des légendes, des crédits ou des informations supplémentaires qui ne sont pas essentielles à la compréhension du contenu principal de la page

      - `<small> ... </small>`  

- ### ***Placement du texte en HTML***  

  - #### Placement du texte en HTML

    - Les balises ***\<br>*** et ***\<hr>*** sont utilisées en HTML pour insérer des sauts de ligne et des séparateurs horizontaux dans le texte

      - La balise ***\<br>*** est utilisée pour insérer un saut de ligne simple  

        - `<br />`  

      - La balise ***\<hr>*** est utilisée pour insérer une ligne horizontale pour séparer le texte  

        - `<hr />`  

    - La balise ***\<blockquote>*** permet de citer du texte dans une page web. Elle est très utile pour citer des extraits de texte provenant d'autres sources, comme des livres, des articles de journaux, des discours ou des entrevues  

      - `<blockquote> ... </blockquote>`  

    - La balise ***\<span>*** est utilisée pour définir du texte ou éléments HTML avec une mise en forme particulière. Elle est souvent utilisée pour appliquer des styles spécifiques à une partie d'un bloc de texte sans affecter le reste du texte  

      - `<span> ... </span>`  

##
## ***__Un langage hypertexte__***

  - ### ***Lier des éléments grâce à l’hypertexte***  

    - #### Lier des éléments grâce à l’hypertexte

      - Un lien hypertexte est un élément interactif d’une page web
      - Cela permet à l’utilisateur qui clique dessus de naviguer entre différents contenus
      - Les liens hypertextes peuvent prendre différents formats commes par exemple

        - Du texte  
        - Des images  
        - Des boutons  

      - La balise ***\<a>*** (ancre ou anchor en anglais) est la balise utilisée pour créer des hyperliens en HTML qui comporte différents attributs 

        - `<a> ... </a>`  

  - ### ***Créer des liens hypertextes en HTML***  

    - #### Créer des liens hypertextes en HTML
      
      - ***L’attribut href***  

        - L’attribut href contient le lien vers lequel vous souhaitez rediriger l’utilisateur, il peut accueillir n’importe quel schéma d’URL si il est pris en charge par les navigateurs web. Cet attribut est un attribut essentiel de la balise ***\<a>***  
        
        - Il peut s’agir  
          
            - D’un lien interne vers une autre page du même site web  
            - Vers une autre section d’une même page web  
            - Un lien externe vers un autre site  
            - Un lien de téléchargement  
            - Un lien de courriel  

        - Créer des liens hypertextes en HTML  

          - `<a href="www.google.com">Site Google</a>`  
          
            - Ne pas oublier de placer l'URL entre guillemets (“”)  

        - Créer un lien interne  

          - Insérer dans l'attribut ***href*** le chemin d’accès relatif ou absolu vers le document HTML de la page
            
            - `<a href="Accueil.html">Accueil</a>`  

        - Créer un lien vers un endroit de la même page 

          - Cela permet de créer un lien sur un endroit précis d’une page comme une section, c'est ce qui s’appelle créer une ancre  
          
          - Il faut donner un attribut “id” à l’élément que l’on souhaite lier
          
          - On va attribuer à l’attribut “href” de la balise de lien l’id de cet élément précédé du signe dièse (#)

            - Exemple  
            
              > `<section id="projects"> ... \</section>`  
              
              - `<a href="#projects">Découvrez nos réalisations</a>`  

        - Créer un lien courriel  

          - Pour créer un lien courriel, il suffit d’utiliser le schéma d’URL mailto  

            - `<a href=”mailto:username@exemple.com”>Contactez-nous</a>`  

        - Créer un lien vers un document  

          - Pour créer un lien vers un document, il suffit d’ajouter le chemin d’accès vers ce document à l’attribut href du lien  

            - `<a href=”/fichier/doc.pdf”>Fichier_PDF</a>`
    

  - ### ***Autres attributs de la balise \<a>***  

    - #### Autres attributs de la balise  

      - L’attribut ***target***  

        - Il va permettre de préciser au navigateur où ouvrir le lien sur lequel l’utilisateur a cliqué. La façon la plus courante de l’utiliser est en lui passant la valeur “_blank” pour ouvrir le lien dans un nouvel onglet ou dans une nouvelle fenêtre. Cependant, il existe d'autres valeurs possibles pour l'attribut "target", comme "_self" pour ouvrir le lien dans la même fenêtre ou "_parent" pour ouvrir le lien dans le cadre parent de la fenêtre en cours
        
          - `<a href="/HTML/contact.html" target="_blank">Contactez-nous</a>`

      - L’attribut ***dowload***  

        - L'attribut "download" est un élément HTML qui permet à un visiteur de télécharger un fichier associé à une page web

          - `<a href=”mon-fichier.pdf” download>Télécharger mon fichier PDF</a>`
        
      - L’attribut ***title***  

        - L'attribut “title” est un attribut universel, c’est-à-dire qu’il est pris en charge par l’ensemble des balises HTML. Néanmoins, il s’avère particulièrement utile associé à la balise ***\<a>***. Cet attribut permet de donner des informations supplémentaires sur le lien, qui vont s’afficher sous la forme d’info-bulle lorsque l’utilisateur passera la souris dessus
        
          - `<a href="Taches.html" title="Toutes les taches">Taches à faire</a>`  

##
## ***__Le multimédia en HTML__***

  - ### ***Introduction aux balises multimédia en HTML***  

    - #### Introduction aux balises multimédia en HTML

      - Qu’est-ce qu’un fichier multimédia ?  

        - Un fichier multimédia est défini comme un fichier informatique qui a la capacité de contenir plusieurs types de médias  

      - Intégrer des images avec les balises \<img> et \<picture>  

        - Il existe 2 méthodes qui permettent d’afficher des fichiers image sur une page web : l’utilisation de la balise ***\<img>*** et celle de la balise ***\<picture>***

        - La balise ***\<img>***  

          - La balise ***\<img>*** permet d’intégrer une image à une page web depuis un dossier en local ou depuis une URL spécifique. Il s’agit d’une balise autofermante, qui ne nécessite pas l’utilisation d’une balise de fermeture dédiée  

          - Elle prend un attribut obligatoire : l’attribut src, qui sert à spécifier l’URL ou le chemin d’accès vers l’image que l’on souhaite ajouter à notre page web  

          - L’attribut alt est un autre attribut courant de la balise ***\<img>***. Il permet d’associer un texte à l’image, dit alternatif, qui s’affiche en cas d’erreur de chargement du fichier  

            - `<img src="picture.png” alt=”Img picture”>`  

        - La balise ***\<picture>***  

          - Elle va permettre de définir plusieurs sources, c’est-à-dire plusieurs images différentes  
          
          - Chaque image est définie dans une balise ***\<source>*** contenue dans la balise ***\<picture>***  

          - Chaque image s’affiche si, et seulement si, elle remplit certaines conditions qui sont définies grâce aux attributs de la balise ***\<source>***  

            Exemple  

              `<picture>`  
              $\qquad$`<source media="(min-width:1200px)" srcset="grande-image.jpg">`  
              $\qquad$`<source media="(min-width:800px)" srcset="image-moyenne.jpg">`  
              $\qquad$`<img src="petit-image.jpg" alt="Flowers" style="width:auto;">`  
              `</picture>`  

      - La balise ***\<source>*** nous permet de définir dans l’attribut srcset les sources des différentes images  

      - L’attribut ***media*** sert à spécifier les tailles d’écran à utiliser pour les images  
        
        - Si l'écran a une largeur supérieure à 1 200px, la page web affichera le fichier « grande-image.jpg »  

        - Si l’écran a une largeur comprise entre 800px et 1200px, alors l’image « image-moyenne.jpg » sera affichée  

        - Si l'écran a une largeur inférieure à 800px, la source choisie sera le fichier « petit-image.jpg »

        > Les formats AVIF et WebP sont les formats qui offrent les meilleures performances, ils optimisent la vitesse de chargement des images et donc de la page web

      - La balise ***\<video>***  

        - La balise ***\<video>*** permet de partager du contenu de manière ludique et immersive, assure une meilleure compréhension de l’information en la rendant dynamique  

          - `<video src=”./assets/mavideo.mp4” controls>`  

            - Elle peut être utilisée seule ou couplée avec la balise ***\<source>***, si il est est nécessaire de définir plusieurs sources vidéo en fonction des préférences de l’utilisateur ou pour maximiser la compatibilité avec les différents navigateurs  

              `<video controls>`  
              $\qquad$`<source  src=”./assets/mavideo.webm” type=”video/webm”>`  
              $\qquad$`<source  src=”./assets/mavideo.mp4” type=”video/mp4”>`  
              `</video>`  
        
          - L’attribut ***controls*** permet d’afficher les options de contrôle de la vidéo : le bouton de lecture, de pause et de gestion du volume audio  

          - Un attribut ***type***, va permettre de préciser au navigateur le type de fichier dont il s’agit (ici, une vidéo) et le format de ce fichier (dans notre exemple, un fichier mp4 et un fichier webM)
      
      - La balise ***\<audio>***  

        - La balise ***\<audio>***, permet l’immersion de l’utilisateur avec la possibilité d’intégrer de l’audio à votre page web. la balise présente les mêmes caractéristiques d’utilisation que la balise ***\<video>***  

          - `<audio controls src=”./assets/mon-audio.mp3”>`  

            - Avec plusieurs sources  

              - `<audio controls>`  
              $\qquad$`<source src="audio.mp3" type="audio/mpeg">`  
              $\qquad$`<source src="audio.ogg" type="audio/ogg">`  
              $\qquad$`<source src="audio.wav" type="audio/wav">`  
              `</audio>`  

        - Nous allons préférer l’utilisation de fichiers MP3 pour optimiser la compatibilité avec l’ensemble des navigateurs web  

  - ### ***Aller plus loin avec les balises multimédia : les balises de contenu intégré***  

    - #### Aller plus loin avec les balises multimédia : les balises de contenu intégré  

      - La balise ***\<iframe>***  

        - Cette balise permet d’intégrer à la page web du contenu externe qui sera traité de manière totalement indépendante  

          - `<iframe width="560" height="315" src="source_vers_contenu">Video</iframe>`  

      - La balise ***\<embed>***  

        - Cette permet également d’intégrer du contenu externe à la page web. la différence c’est que la balise ***\<embed>*** est surtout utilisée pour l’intégration de plug-ins  

          - `<embed src="mon_fichier.pdf" width="500" height="375" type="application/pdf">`  

      - La balise ***\<object>***  

        - Les balises ***\<iframe>*** et ***\<embed>*** permettent d’intégrer une grande variété de contenus PDF, SVG, plug-ins, applets et évidemment des fichiers multimédia  
        
        - La balise ***\<object>*** offre une plus grande flexibilité et une plus grande compatibilité de son contenu avec l’ensemble des navigateurs  

          - `<object data="snippet.html" width="500" height="200">Object</object>`  

            - L’attribut ***data*** fonctionne de manière similaire à l’attribut src et accueille le chemin d’accès de la ressource externe à intégrer à la page web  

        - la balise ***\<object>*** vous permet d’intégrer, de manière flexible et en assurant une compatibilité maximale, une grande variété de contenus externes à votre page web, tout en offrant une alternative pour les navigateurs qui ne prennent pas en charge le contenu intégré  

##
## ***__Introduction au CSS__***

- ### ***Bases de CSS***  

  - #### Origine du CSS  

    - CSS (Cascading Style Sheets), permet de définir des styles pour différents éléments HTML, XHTML ou XML tels que les polices de caractères, les couleurs, les marges, les bordures, les images, les dimensions de blocs, soit tout élément que le navigateur web  

  - #### Intérêt et avantage des CSS  

    - L'utilisation du CSS permet de faciliter grandement la maintenance et la mise à jour d’un site, mais il aide également à améliorer l'accessibilité pour les personnes en situation de handicap  

    - Il est possible de personnaliser l’affichage de chaque élément HTML depuis le navigateur  

    - L'utilisation des CSS est donc essentielle pour un site web esthétique et confortable à lire  

  - #### Fonctionnement et syntaxe des CSS  

    - CSS est un langage basé sur des règles destinées à des éléments HTML ou des groupes d’éléments HTML  

      ```
      /* Ceci est un commentaire non interprété par le navigateur */

      /* le sélecteur de titre h1 */
      h1 {
        /* propriété : valeur */
        font-size: 20px;
        color: blue;
      }

      /* le sélecteur de paragraphe p */
      p {
        text-align: justify;
        color: red;
      }
      ```  

        - Ces règles contiennent un sélecteur, l’élément HTML h1 et l’élément p. On ouvre une accolade où l’on va définir une ou plusieurs déclarations sous la forme d’une paire  
          
          - propriété : valeur

        - Dans l’exemple avec l’élément h1, la première déclaration contient la propriété font-size qui indique la taille de la police de caractères, ayant pour valeur 20px dont l’unité est le pixel  
        
        - La seconde déclaration, color a pour valeur blue, la couleur bleue. L’élément HTML p a un texte justifié, aligné sur les marges gauche et droite et il a une couleur rouge  
        
        - Le point-virgule sert de séparateur entre les différentes déclarations.

  - #### Lier CSS au document HTML  

    - La feuille de style externe est la méthode la plus utilisée pour la présentation des pages web, car elle présente de nombreux avantages  

      - Elle permet une définition unique des styles, qui peut être appliquée à toutes les pages du site  

      - La modification de la feuille de style externe permet une mise à jour facile et rapide de la présentation de toutes les pages du site  

      - l'utilisation d'une feuille de style externe offre une solution efficace et pratique pour la gestion des styles de présentation sur un site web, permettant de garantir une cohérence globale et une maintenance aisée des pages  

      - L’en-tête de la page contient une référence vers le fichier style.css. Cette référence s’effectue à l’aide de la balise ***<link>*** dans la section ***<head>***. L’attribut rel de l’élément link spécifie que le lien est une feuille de style

        - Exemple

          - `<link rel=”stylesheet” href=”styles/style.css”>`  

  - #### Organisation et nommage des fichiers dans un site web  

    - Il est utile de structurer et séparer intelligemment les fichiers CSS de manière à ce qu’ils aient un rôle bien distinct, par exemple  

      | Fichier CSS     | Rôle                                                                |  
      | :-------------: | :-----------------------------------------------------------------: |  
      | style.css       | Styles communs à toutes les pages                                   |  
      | layout.css      | Styles de la mise en page générale de toutes les pages              |  
      | header.css      | Styles pour l’en-tête commun à toutes les pages                     |  
      | footer.css      | Styles pour le pied de page commun à toutes les pages               |  
      | menu.css        | Styles pour le menu commun à toutes les pages                       |  
      | pageX.css       | Styles spécifiques à une page ou un groupe de pages                 |  
      | slider.css      | Styles spécifiques au carrousel d’images commun à toutes les pages  |  
    
      - En structurant et en séparant intelligemment vos fichiers CSS de cette manière, vous pouvez aisément comprendre et gérer les styles de votre site web. Cela peut également faciliter la maintenance et les mises

- ### ***Mise en œuvre des CSS***  

  - #### Utilisation des classes  

    - Les classes sont attribuées à chaque élément HTML, une ou plusieurs classes dont vous avez le loisir de choisir un nom. L’avantage des classes est que vous pouvez cibler n’importe quel élément HTML qui contient la classe comme attribut  

    - Il est important de respecter certaines conventions. La syntaxe d'écriture des classes doit être réalisée avec des caractères alphanumériques uniquement  
    
      - Les lettres (a-z, A-Z)
      - Les chiffres (0-9)
      - Le tiret (-)
      - Le trait de soulignement ou underscore (_)  

    - Il est recommandé d’éviter les noms de classes génériques tels que « div » ou « container », ils peuvent entraîner des conflits avec d’autres classes ou éléments HTML  
    
    - Il est également déconseillé de commencer le nom d’une classe par un chiffre, car certains navigateurs peuvent interpréter cela comme une erreur de syntaxe  

    - Les classes sont dites « case-sensitive » (sensibles à la casse), cela signifie que si vous utilisez une classe appelée « maClasse » dans la feuille de style et que dans la page HTML, vous l’écrivez « maclasse », cette dernière ne sera pas reconnue  

  - #### Utilisation des ID  

    - Lorsqu'on travaille avec les éléments HTML en CSS, il est possible de leur attribuer un identifiant, ou ID, en plus ou à la place des classes. Les IDs fonctionnent de manière similaire aux classes, en ce sens qu'on peut leur appliquer des styles. Toutefois, il existe certaines différences importantes entre les deux  

      - La première différence est que chaque élément HTML ne peut avoir qu'un seul ID, et cet ID doit être unique dans une page HTML. Alors que plusieurs éléments HTML peuvent partager une même classe  

      - La deuxième différence majeure entre les IDs et les classes est que les règles CSS qui utilisent un ID ont la priorité sur les règles qui utilisent une classe. Cela signifie que si un même élément HTML possède à la fois un ID et une classe, les styles appliqués à l'ID auront la priorité sur les styles appliqués à la classe  

      - Les IDs sont utilisés pour cibler des éléments HTML spécifiques sur lesquels on veut effectuer des actions particulières, souvent avec JavaScript. Pour créer un ID, on utilise le dièse (#) suivi du nom de l'ID  

    - Les ID ont la priorité sur les classes. Ainsi, lorsque les attributs ID et classe sont utilisés sur le même élément HTML, c’est l’ID qui applique son style en priorité, indépendamment de l'ordre dans lequel les attributs sont déclarés  

      - L'ID est sensible à la casse, tout comme les classes. La syntaxe d'écriture d'un ID est la même que celle des classes  

  - #### Fonctionnement de l’héritage  

    - Les styles fonctionnent par héritage, ce qui signifie que les règles de styles se combinent et se transmettent de parents à enfants. Cette notion est importante avant de passer à la création d’un site web  

  - #### Mécanisme de cascade et de spécificité  

    - Les sélecteurs CSS sont des instructions utilisées pour cibler des éléments HTML et leur appliquer un style. Lorsque plusieurs sélecteurs s’appliquent à un même élément, CSS repose sur un ensemble de règles qui vont définir l’ordre de préférence d’application des propriétés déclarées dans les sélecteurs  

    - Plus un sélecteur est spécifique, plus sa priorité sera élevée. Par exemple, un sélecteur qui cible un élément par son identifiant (#) est plus spécifique qu'un sélecteur qui cible un élément par sa classe (.), et aura donc une priorité plus élevée. Si deux sélecteurs ont la même spécificité, la règle la plus importante aura la priorité. Les règles importantes ont une priorité plus élevée que les règles non importantes  

    - Une liste d'exemple de principaux sélecteurs par ordre de priorité

        | Sélecteur             | Exemple                       | Priorité        |  
        | :-------------------: | :---------------------------: | :-------------: |  
        | Style en ligne        | \<p style="... !important">   | La plus élevée  |  
        | Style en ligne        | \<p style="...">              |                 |  
        | Sélecteur ID          | #id { ... }                   |                 |  
        | Sélecteur de classe   | .class { ... }                |                 |  
        | Sélecteur d’élément   | p.class { ... }               |                 |  
        | Sélecteur d’élément   | p { ... }                     | La plus basse   |  

        - Il est important de noter que l'utilisation excessive de règles importantes ou de sélecteurs spécifiques peut rendre le code CSS difficile à maintenir et à comprendre

  - #### Mise en forme appliquée sur l’état  

    - Lorsque l'on souhaite appliquer des règles CSS à des éléments HTML en fonction de leur état, plusieurs possibilités existent, Un exemple parfait pour illustrer cette méthode est celui des liens, ou ancres, représentés par la balise ***\<a>***  

      - L'état " visited " s'applique lorsque le lien a été visité précédemment par l'utilisateur  
        
        ```
        a:visited {
          color: grey;
        }
        ```

      - L'état " active " s'active lorsque l'utilisateur est en train de cliquer sur le lien  
        
        ```
        a:active {
        color: black;
        }
        ```

      - L'état " hover " s'applique lorsque le curseur de la souris survole le lien  
        
        ```
        a:hover {
        color: red;
        text-decoration: none;
        }
        ```

      - L'état " focus " est activé lorsque le curseur du clavier est positionné sur le lien, généralement en utilisant la touche " tab "  
        
        ```
        a:focus {
        font-size: 15px;
        color: green;
        }
        ```

    - Nombreuses autres balises HTML sont assujetties à l’utilisation des états dont voici une liste non exhaustive : ***\<button>***, ***\<input>***, ***\<label>***, ***\<div>***, ***\<span>***, ***\<ul>***, ***\<li>***, ***\<img>***. En utilisant des sélecteurs CSS appropriés, il est possible de personnaliser l'apparence de ces éléments en fonction de leur état, pour une expérience utilisateur plus agréable et plus intuitive  

  - #### Ressources et informations  

    - Les CSS sont une norme ouverte et publique développée par le World Wide Web Consortium (W3C), qui est un groupe constitué de représentants des éditeurs de navigateurs et de quelques autres sociétés concernées par les CSS  

      - [La page d’accueil des CSS du W3C](#W3C)

        - Quelques liens utiles

          - [La page d’accueil des CSS de MDN](https://developer.mozilla.org/fr/docs/Learn/CSS)
          - [W3Schools](https://www.w3schools.com/)
          - [CSS-Tricks](https://css-tricks.com/)
          - [CSS Reference](https://cssreference.io/)

    - Il est important de noter que les navigateurs ne réagissent pas tous de la même manière sur certaines fonctionnalités CSS, et ceci, indépendamment du système d’exploitation. Il est donc essentiel de vérifier la compatibilité des propriétés, soit sur MDM Web Docs de Mozilla ou le site Can I use dédié à cette tâche
    
      - [Can I use](https://caniuse.com/)

##
## ***__CSS3 : Le stylage du texte__***  

- ### ***Différents types de propriétés***  

  - #### Différents types de propriétés  

    - Les CSS permettent de personnaliser l'apparence du texte selon les besoins et les préférences de l'utilisateur. Les éléments de mise en forme comprennent la police, la taille, la couleur, le soulignement, le surlignage, l'alignement et la justification, ainsi que l'ajout d'espaces et d'interlignes  

    - La mise en forme de texte est donc un élément clé de la conception web, permettant de créer des pages web visuellement attrayantes et faciles à lire  

      | Proprietes                  | Exemple                       | Notes                                                             |
      | :-------------------------: | :---------------------------: |:----------------------------------------------------------------: |
      | Couleur                     | color                         | La couleur à appliquer au texte.                                  |
      | Fond                        | background-color              | La couleur de fond y compris le texte.                            |
      | Police                      | font-*, etc.                  | Propriétés de la police : fontes, tailles, italique, gras, etc.   |
      | Mise en forme et alignement | text-*, etc.                  | Propriétés du texte : Soulignement, surlignage, alignement, etc.  |
      |Interligne et espacement     | line-*, letter-*, word-*, etc.| Espaces entre chaque lettre, mot et ligne de texte, etc.               |

  - #### Couleurs  

  - #### Propriétés dédiées aux polices de caractères FONT-*  

  - #### Alignements et compositions de textes  

- ### ***Un peu plus loin dans la mise en forme et la composition des textes***

  - #### Couleurs et leur opacité  

  - #### Unités de mesure des caractères  
  
  - #### Polices téléchargeables  
  
  - #### Utiliser des fontes personnelles  
  
  - #### Documentations officielles  
