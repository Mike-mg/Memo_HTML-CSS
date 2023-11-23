# Memo HTML-CSS

## ***__Introduction au HTML__***  

- ### ***Qu’est-ce que le HTML ?***  

  - #### Qu’est-ce que le HTML ?

    - Le HTML ( HyperText Markup Language ), est utilisé pour mettre en page un site web.  

      - [Lien vers la page des références des éléments HTML](https://developer.mozilla.org/fr/docs/Web/HTML/Element)

- ### ***HTML, un langage en constante évolution***  

  - #### HTML, un langage en constante évolution

    - Le W3C ( Wolrd wide Web Consortium ), est l’organisme chargé de la standardisation et de la compatibilité des technologies du web.  

      - [Site du W3C](https://www.w3.org/) <a id="W3C"></a>

- ### ***HTML, un langage côté client***  

  - #### HTML, un langage côté client

    - Le « côté client » couvre toutes les opérations effectuées par une application ou un site web au sein d’un navigateur.  
    - Le langage HTML est donc un langage « côté client ». C’est le navigateur de l’utilisateur qui interprète le HTML.  
    - Les pages d’un site web sont transmises sous forme de code HTML brut au navigateur, qui va l’interpréter pour afficher son contenu sur l’écran.  
    - Cette partie du développement d’un site web est appelée « développement frontend », faisant référence à la partie création de l’interface utilisateur, au côté visuel d’un site ou d’une application web. HTML sert à définir la structure et l’organisation des pages.  

##
## ***__Syntaxe générale de HTML__***  

- ### ***Syntaxe générale du code HTML***  

  - #### Syntaxe générale du code HTML  

    - Le code HTML est un langage de balisage hypertexte : il se construit à l’aide de balises, qui sont entourées par deux chevrons « < » et « > ».  
    - Ces balises peuvent également prendre en charge des attributs, qui, eux, permettront de donner plus de précision sur la façon dont la balise doit être interprétée.  

    - Les balises HTML minimal  

      ```HTML
      <!DOCTYPE html>
      <html lang="fr">
        <head> ... </head>
        <body> ... </body>
      </html>
      ```  

    - Les balises sont « répétées ». En HTML, la grande majorité des balises fonctionnent par paires et sont composées d’une balise d’ouverture et une balise de fermeture.  
    - La balise de fermeture est identique à la balise d’ouverture si ce n’est qu’elle contient un slash (« / ») juste après le chevron ouvrant.  

      - Exemple :  
      
        ```HTML
        <head> ... </head>
        ```

    - Il existe cependant des balises qui n’ont pas besoin de balise fermante, on les appelle balises auto-fermantes ou orphelines.  
    - Le code HTML commence toujours avec la balise suivante :  

      ```HTML
      <!DOCTYPE html>
      ``` 

        - Cette balise permet de spécifier au navigateur le type de document HTML utilisé. Il est donc crucial de toujours inclure cette balise au début de votre code HTML.  

    - La balise ***\<html>*** que l’on appelle aussi l’élément racine du document HTML marque le début du document HTML.  

      ```HTML
      <html> ... </html>
      ``` 

    - La balise ***\<head>*** inclut toutes les informations qui ne s’affichent pas directement dans la page web, mais qui sont utiles pour le bon fonctionnement du code, ainsi que pour les moteurs de recherche.  
      
      ```HTML
      <head> ... </head>
      ```  

        - La balise ***\<head>*** est essentielle, Elle s’imbrique entre la balise d’ouverture ***\<html>*** et de fermeture ***\</html>***.  

    - La balise ***\<body>*** définit l’ensemble des éléments qui vont être visibles sur la page tels que les titres, le texte, les images ou encore les formulaires.  

      ```HTML
      <body> ... </body>
      ``` 

        - La balise ***\<body>*** est essentielle, Elle s’imbrique entre la balise d’ouverture ***\<html>*** et de fermeture ***\</html>***.

- ### ***Balises structurelles en HTML***  

  - #### Balises structurelles en HTML

    - La balise ***\<div>***  

      - La balise ***\<div>*** est la balise la plus couramment utilisée pour placer du contenu sur une page web, elle va permettre de diviser la page web en différents espaces et donc de la structurer de manière organisée.  

        ```HTML
        <div> ... </div>
        ``` 
         
    - La balise ***\<nav>***  

      - Délimite la partie de la page dans laquelle nous allons pouvoir trouver les liens qui conduisent les autres pages du site web. Il s’agit de la balise de navigation où l’on pourra retrouver le menu principal du site.  

        ```HTML
        <nav> ... </nav>
        ``` 

    - La balise ***\<header>***  

      - Dans le ***\<header>***, se compose généralement du titre, d’un texte d’introduction ou encore une bannière, c’est ici que vous placerez les éléments qui permettront d’identifier la thématique de votre page web.  

        ```HTML
        <header> ... </header>
        ``` 

    - La balise ***\<footer>***  

      - Dans le pied page ***\<footer>*** on retrouvera le menu de bas de page, les pages légales et les informations relatives aux droits d’auteur, sera intégré dans la balise.  

        ```HTML
        <footer> ... </footer>
        ``` 

    - La balise ***\<section>***  

      - La balise ***\<section>*** est utiliser pour regrouper les éléments d’une même thématique dans un conteneur dédié, elle permet de découper le contenu par thématique pour mieux organiser le contenu sur la page.  
        
        ```HTML
        <section> ... </section>
        ``` 

    - La balise ***\<article>***  

      - La balise ***\<article>*** est utilisée pour délimiter une section dont le contenu est autonome, comme des articles de blog, des produits ou encore des commentaires.  

        ```HTML
        <article> ... </article>
        ``` 

    - La balise ***\<aside>***  

      - la balise ***\<aside>*** sert à définir un contenu « à côté » d’un contenu principal. Ce contenu à part est souvent lié de manière indirecte au contenu principal. On l’utilise pour les encarts publicitaires ou encore les articles connexes.  

        ```HTML
        <aside> ... </aside>
        ``` 

##
## ***__L'organisation du texte__***  

  - ### ***Éléments d’organisation du texte en HTML***  

    - #### Éléments d’organisation du texte en HTML

      - Il existe plusieurs niveaux de balises de titres, allant du ***\<h1>*** jusqu'au ***\<h6>***. Les balises ont des tailles et des styles de police différents, ce qui permet de les différencier visuellement. Ainsi, le titre principal de la page est inséré dans la balise ***\<h1>***, tandis que les balises ***\<h2>*** à ***\<h6>*** sont utilisées pour les sous-titres.  

 
        ```HTML
        <h1> ... </h1>  
        <h2> ... </h2>  
        <h3> ... </h3>  
        <h4> ... </h4>  
        <h5> ... </h5>  
        <h6> ... </h6> 
        ``` 

      - La balise \<p>  

          - Les balises ***\<p>*** sont utilisées en HTML pour délimiter un paragraphe de texte, elle permet d'ajouter des sauts de ligne entre les différents paragraphes.  

            ```HTML
            <p> ... </p>
            ``` 

      - Les balises \<ul> et \<ol>  

        - La balise ***\<ul>*** permet de créer une liste d'éléments sans ordre particulier. Chaque item est précédé d'un point (ou autre symbole), et il n'y a pas de numérotation. Ce type de liste est idéal pour présenter des informations qui ne sont pas liées entre elles.  

          ```HTML
          <ul> ... </ul>
          ``` 

        - la balise ***\<ol>*** permet de créer une liste ordonnée, où chaque item est numéroté. Cette liste est très utile pour présenter des informations qui ont un ordre ou une hiérarchie, comme les étapes d'un processus.  

          ```HTML
          <ol> ... </ol>
          ``` 

            - Ces éléments apportent une structure visuelle à l'information.  
            - Ceci qui est crucial pour la lisibilité de la page.  
            - Il est possible d'ajouter des sous-listes à l'intérieur d'une liste principale, il faut ajouter une liste imbriquée dans une autre liste.  

      - Les balises ***\<li>***, il est également important de noter que, à l'intérieur de ces deux balises, chaque élément de la liste est inscrit dans une balise ***\<li>***.

        - Exemple avec la balise ***\<ul>*** :  

          
          ```HTML
          <ul>
            <li> ... </li>  
            <li> ... </li>  
            <li> ... </li>  
            <li> ... </li>
          </ul>
          ```

        - Exemple avec la balise ***\<ol>*** :  

          ```HTML
          <ol>
            <li> ... </li>  
            <li> ... </li>  
            <li> ... </li>  
            <li> ... </li>
          </ol>
          ```

- ### ***Mise en forme du texte en HTML***  

  - #### Mise en forme du texte en HTML  

    - une balise block est une balise qui crée un nouveau bloc de contenu sur la page web. Cela signifie que tout le contenu compris entre la balise d'ouverture et la balise de fermeture sera affiché comme un bloc distinct.  
    - Les exemples les plus courants de balises block incluent les balises ***\<div>***, ***\<p>***, ***\<ul>***, ***\<ol>***, ***\<h1>*** à ***\<h6>*** et ***\<blockquote>***.  
    - Les balises inline sont souvent utilisées pour formater le texte ou pour ajouter des éléments en ligne, tels que des liens hypertextes, des images ou des boutons. Les exemples les plus courants de balises inline incluent les balises ***\<a>***, ***\<img>***, ***\<span>*** et ***\<button>***.  
    - Lors de la création d'une page web, il est important de considérer la mise en forme, le HTML a plusieurs balises qui permettent de mettre en évidence certains mots ou texte.
    - Les balises ***\<b>*** et ***\<strong>*** permettent de faire apparaître le contenu en gras.

      - la balise ***\<b>*** sert uniquement à la mise en forme.
        
        ```HTML
        <b> ... </b>
        ```

      - la balise ***\<strong>*** indique que le mot ou la phrase a une importance particulière.

        ```HTML
        <strong> ... </strong>
        ```

    - Les balises ***\<i>*** et ***\<em>*** permettent de faire apparaître le contenu en italique.

      - la balise ***\<i>*** sert uniquement à la mise en forme.
          
        ```HTML
        <i> ... </i>
        ```

      - la balise ***\<em>*** est préférée pour mettre en valeur un mot ou une phrase bien précise.  

        ```HTML
        <em> ... </em>
        ```

    - la balise ***\<mark>*** permet de faire ressortir visuellement une partie de texte en la surlignant avec une couleur de fond différente.  
          
      ```HTML
      <mark> ... </mark>
      ```

    - la balise ***\<small>*** est utilisée pour formater du texte en réduisant sa taille. Elle peut être utilisée pour indiquer des notes de bas de page, des légendes, des crédits ou des informations supplémentaires qui ne sont pas essentielles à la compréhension du contenu principal de la page.

      ```HTML
      <small> ... </small>
      ```

- ### ***Placement du texte en HTML***  

  - #### Placement du texte en HTML

    - Les balises ***\<br>*** et ***\<hr>*** sont utilisées en HTML pour insérer des sauts de ligne et des séparateurs horizontaux dans le texte.

      - La balise ***\<br>*** est utilisée pour insérer un saut de ligne simple.  

        ```HTML
        <br />
        ```

      - La balise ***\<hr>*** est utilisée pour insérer une ligne horizontale pour séparer le texte.  

        ```HTML
        <hr />
        ```

    - La balise ***\<blockquote>*** permet de citer du texte dans une page web. Elle est très utile pour citer des extraits de texte provenant d'autres sources, comme des livres, des articles de journaux, des discours ou des entrevues.  

      ```HTML
      <blockquote> ... </blockquote>
      ```

    - La balise ***\<span>*** est utilisée pour définir du texte ou éléments HTML avec une mise en forme particulière. Elle est souvent utilisée pour appliquer des styles spécifiques à une partie d'un bloc de texte sans affecter le reste du texte.  

      ```HTML
      <span> ... </span>
      ```

##
## ***__Un langage hypertexte__***

  - ### ***Lier des éléments grâce à l’hypertexte***  

    - #### Lier des éléments grâce à l’hypertexte

      - Un lien hypertexte est un élément interactif d’une page web.
      - Cela permet à l’utilisateur qui clique dessus de naviguer entre différents contenus.
      - Les liens hypertextes peuvent prendre différents formats commes par exemple.

        - Du texte  
        - Des images  
        - Des boutons  

      - La balise ***\<a>*** (ancre ou anchor en anglais) est la balise utilisée pour créer des hyperliens en HTML qui comporte différents attributs. 

        ```HTML
        <a> ... </a>
        ```

  - ### ***Créer des liens hypertextes en HTML***  

    - #### Créer des liens hypertextes en HTML
      
      - ***L’attribut href***  

        - L’attribut href contient le lien vers lequel vous souhaitez rediriger l’utilisateur, il peut accueillir n’importe quel schéma d’URL si il est pris en charge par les navigateurs web. Cet attribut est un attribut essentiel de la balise ***\<a>***.  
        - Il peut s’agir :  
          
            - D’un lien interne vers une autre page du même site web  
            - Vers une autre section d’une même page web  
            - Un lien externe vers un autre site  
            - Un lien de téléchargement  
            - Un lien de courriel  

        - Créer des liens hypertextes en HTML  

          ```HTML
          <a href="www.google.com">Site Google</a>
          ```
          
            - Ne pas oublier de placer l'URL entre guillemets (“”).  

        - Créer un lien interne  

          - Insérer dans l'attribut ***href*** le chemin d’accès relatif ou absolu vers le document HTML de la page.
            
            ```HTML
            <a href="Accueil.html">Accueil</a>
            ```

        - Créer un lien vers un endroit de la même page <a id="ancre"></a>

          - Cela permet de créer un lien sur un endroit précis d’une page comme une section, c'est ce qui s’appelle créer une ancre.  
          - Il faut donner un attribut “id” à l’élément que l’on souhaite lier.
          - On va attribuer à l’attribut “href” de la balise de lien l’id de cet élément précédé du signe dièse (#).

            - Balise HTML de l'ancre  
            
              ```HTML
              <section id="projects"> ... \</section>
              ```
              
              - Lien vers l'ancre HTML
              
                ```HTML
                <a href="#projects">Ancre de la section</a>
                ```

        - Créer un lien courriel  

          - Pour créer un lien courriel, il suffit d’utiliser le schéma d’URL mailto  

            ```HTML
            <a href=”mailto:username@exemple.com”>Contactez-nous</a>
            ```

        - Créer un lien vers un document  

          - Pour créer un lien vers un document, il suffit d’ajouter le chemin d’accès vers ce document à l’attribut href du lien  

            ```HTML
            <a href=”/fichier/doc.pdf”>Fichier_PDF</a>
            ```
    
  - ### ***Autres attributs de la balise \<a>***  

    - #### Autres attributs de la balise  

      - L’attribut ***target***  

        - Il va permettre de préciser au navigateur où ouvrir le lien sur lequel l’utilisateur a cliqué. La façon la plus courante de l’utiliser est en lui passant la valeur “_blank” pour ouvrir le lien dans un nouvel onglet ou dans une nouvelle fenêtre. Cependant, il existe d'autres valeurs possibles pour l'attribut "target", comme "_self" pour ouvrir le lien dans la même fenêtre ou "_parent" pour ouvrir le lien dans le cadre parent de la fenêtre en cours
        
          ```HTML
          <a href="/HTML/contact.html" target="_blank">Contactez-nous</a>
          ```

      - L’attribut ***dowload***  

        - L'attribut "download" est un élément HTML qui permet à un visiteur de télécharger un fichier associé à une page web

          ```HTML
          <a href=”mon-fichier.pdf” download>Télécharger mon fichier PDF</a>
          ```
        
      - L’attribut ***title***  

        - L'attribut “title” est un attribut universel, c’est-à-dire qu’il est pris en charge par l’ensemble des balises HTML. Néanmoins, il s’avère particulièrement utile associé à la balise ***\<a>***. Cet attribut permet de donner des informations supplémentaires sur le lien, qui vont s’afficher sous la forme d’info-bulle lorsque l’utilisateur passera la souris dessus
        
          ```HTML
          <a href="Taches.html" title="Toutes les taches">Taches à faire</a>
          ```

##
## ***__Le multimédia en HTML__***

  - ### ***Introduction aux balises multimédia en HTML***  

    - #### Introduction aux balises multimédia en HTML

      - Qu’est-ce qu’un fichier multimédia ?  

        - Un fichier multimédia est défini comme un fichier informatique qui a la capacité de contenir plusieurs types de médias  

      - Intégrer des images avec les balises ***\<img>*** et ***\<picture>***  

        - Il existe 2 méthodes qui permettent d’afficher des fichiers image sur une page web : l’utilisation de la balise ***\<img>*** et celle de la balise ***\<picture>***

        - La balise ***\<img>***  

          - La balise ***\<img>*** permet d’intégrer une image à une page web depuis un dossier en local ou depuis une URL spécifique. Il s’agit d’une balise autofermante, qui ne nécessite pas l’utilisation d’une balise de fermeture dédiée  

          - Elle prend un attribut obligatoire : l’attribut src, qui sert à spécifier l’URL ou le chemin d’accès vers l’image que l’on souhaite ajouter à notre page web  

          - L’attribut alt est un autre attribut courant de la balise ***\<img>***. Il permet d’associer un texte à l’image, dit alternatif, qui s’affiche en cas d’erreur de chargement du fichier  

            ```HTML
            <img src="picture.png” alt=”Img picture”>
            ```

        - La balise ***\<picture>***  

          - Elle va permettre de définir plusieurs sources, c’est-à-dire plusieurs images différentes  
          
          - Chaque image est définie dans une balise ***\<source>*** contenue dans la balise ***\<picture>***  

          - Chaque image s’affiche si, et seulement si, elle remplit certaines conditions qui sont définies grâce aux attributs de la balise ***\<source>***  

            Exemple :  

              ```HTML
              <picture>
                <source media="(min-width:1200px)" srcset="grande-image.jpg">`  
                <source media="(min-width:800px)" srcset="image-moyenne.jpg">`  
                <img src="petit-image.jpg" alt="Flowers" style="width:auto;">`  
              </picture>
              ```

      - La balise ***\<source>*** nous permet de définir dans l’attribut srcset les sources des différentes images  

      - L’attribut ***media*** sert à spécifier les tailles d’écran à utiliser pour les images  
        
        - Si l'écran a une largeur supérieure à 1 200px, la page web affichera le fichier « grande-image.jpg »  

        - Si l’écran a une largeur comprise entre 800px et 1200px, alors l’image « image-moyenne.jpg » sera affichée  

        - Si l'écran a une largeur inférieure à 800px, la source choisie sera le fichier « petit-image.jpg »

          - Les formats AVIF et WebP sont les formats qui offrent les meilleures performances, ils optimisent la vitesse de chargement des images et donc de la page web

      - La balise ***\<video>***  

        - La balise ***\<video>*** permet de partager du contenu de manière ludique et immersive, assure une meilleure compréhension de l’information en la rendant dynamique  

          ```HTML
          <video src=”./assets/mavideo.mp4” controls>
          ```

            - Elle peut être utilisée seule ou couplée avec la balise ***\<source>***, si il est est nécessaire de définir plusieurs sources vidéo en fonction des préférences de l’utilisateur ou pour maximiser la compatibilité avec les différents navigateurs  

              ```HTML
              <video controls>
                <source  src=”./assets/mavideo.webm” type=”video/webm”>
                <source  src=”./assets/mavideo.mp4” type=”video/mp4”>  
              </video>
              ```
        
          - L’attribut ***controls*** permet d’afficher les options de contrôle de la vidéo : le bouton de lecture, de pause et de gestion du volume audio  

          - Un attribut ***type***, va permettre de préciser au navigateur le type de fichier dont il s’agit (ici, une vidéo) et le format de ce fichier (dans notre exemple, un fichier mp4 et un fichier webM)
      
      - La balise ***\<audio>***  

        - La balise ***\<audio>***, permet l’immersion de l’utilisateur avec la possibilité d’intégrer de l’audio à votre page web. la balise présente les mêmes caractéristiques d’utilisation que la balise ***\<video>***  

          ```HTML
          <audio controls src=”./assets/mon-audio.mp3”>
          ```

            - Avec plusieurs sources  

              ```HTML
              <audio controls>
                <source src="audio.mp3" type="audio/mpeg">
                <source src="audio.ogg" type="audio/ogg">
                <source src="audio.wav" type="audio/wav">
              </audio>
              ```

        - Nous allons préférer l’utilisation de fichiers MP3 pour optimiser la compatibilité avec l’ensemble des navigateurs web  

  - ### ***Aller plus loin avec les balises multimédia : les balises de contenu intégré***  

    - #### Aller plus loin avec les balises multimédia : les balises de contenu intégré  

      - La balise ***\<iframe>***  

        - Cette balise permet d’intégrer à la page web du contenu externe qui sera traité de manière totalement indépendante  

          ```HTML
          <iframe width="560" height="315" src="source_vers_contenu">Video</iframe>
          ```

      - La balise ***\<embed>***  

        - Cette permet également d’intégrer du contenu externe à la page web. la différence c’est que la balise ***\<embed>*** est surtout utilisée pour l’intégration de plug-ins  

          ```HTML
          <embed src="mon_fichier.pdf" width="500" height="375" type="application/pdf">
          ```

      - La balise ***\<object>***  

        - Les balises ***\<iframe>*** et ***\<embed>*** permettent d’intégrer une grande variété de contenus PDF, SVG, plug-ins, applets et évidemment des fichiers multimédia  
        
        - La balise ***\<object>*** offre une plus grande flexibilité et une plus grande compatibilité de son contenu avec l’ensemble des navigateurs  

          ```HTML
          <object data="snippet.html" width="500" height="200">Object</object>
          ```

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

      ```CSS
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
          
          - ***propriété : valeur***

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

          ```HTML
          <link rel=”stylesheet” href=”styles/style.css”>
          ```

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

      - Les IDs sont utilisés pour cibler des éléments HTML spécifiques sur lesquels on veut effectuer des actions particulières, souvent avec JavaScript. Pour créer un ID, on utilise le dièse (#) suivi du nom de l'ID  [Voir exemple](#ancre)

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
        
        ```CSS
        a:visited {
          color: grey;
        }
        ```

      - L'état " active " s'active lorsque l'utilisateur est en train de cliquer sur le lien  
        
        ```CSS
        a:active {
        color: black;
        }
        ```

      - L'état " hover " s'applique lorsque le curseur de la souris survole le lien  
        
        ```CSS
        a:hover {
        color: red;
        text-decoration: none;
        }
        ```

      - L'état " focus " est activé lorsque le curseur du clavier est positionné sur le lien, généralement en utilisant la touche " tab "  
        
        ```CSS
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

    - Les CSS permettent de personnaliser l'apparence du texte  
    
    - Les éléments de mise en forme comprennent la police, la taille, la couleur, le soulignement, le surlignage, l'alignement et la justification, ainsi que l'ajout d'espaces et d'interlignes  

      | Proprietes                  | Exemple                       | Notes                                                             |
      | :-------------------------: | :---------------------------: |:----------------------------------------------------------------: |
      | Couleur                     | color                         | La couleur à appliquer au texte.                                  |
      | Fond                        | background-color              | La couleur de fond y compris le texte.                            |
      | Police                      | font-*, etc.                  | Propriétés de la police : fontes, tailles, italique, gras, etc.   |
      | Mise en forme et alignement | text-*, etc.                  | Propriétés du texte : Soulignement, surlignage, alignement, etc.  |
      |Interligne et espacement     | line-*, letter-*, word-*, etc.| Espaces entre chaque lettre, mot et ligne de texte, etc.               |

  - #### Couleurs  

    - La propriété ***color*** ajoute des couleurs dans les textes  

    - Les methodes de la notation en hexadécimale et la notation RGB sont les plus optimisés car elles peuvent représenter 16,7 millions de couleurs  

      | Proprietes    | Exemple         | Notes                                                                                                                                                   |
      | :-----------: | :-------------: |:------------------------------------------------------------------------------------------------------------------------------------------------------: |
      | Mots-clés     | blue            | C’est une référence qui pointe sur une couleur, Il existe 147 noms prédéfinis en anglais                                                                |
      | Hexadécimale  | #0000FF         | Un dièse suivi de 3 paires de digits indiquant respectivement la quantité de rouge, de vert et de bleu                                                  |
      | RGB           | rgb(0, 0, 255)  | La valeur est représentée en 3 couleurs décimales, indiquant respectivement la quantité de rouge, de vert et de bleu. Ces proportions allant de 0 à 255 |  

        - Exemple :  

          ```CSS
          .keyword {
          color: red;
          }

          /* Rouge = FF, Vert = 00, Bleu = 00 */  
          .hexa {  
          color: #FF0000;
          }

          .rgb {
          color: rgb(255, 0, 0);
          }          
          ```


  - #### Propriétés dédiées aux polices de caractères FONT-*  

    - La propriété ***font-family*** sert à définir une police de caractères. Elle se présente sous la forme d’une liste de noms de polices ***séparées par une virgule***, et ***classées par ordre de préférence***  

      - Pour assurer une bonne interprétation des polices génériques par les navigateurs, il est recommandé de les mentionner en dernière position après les noms de polices spécifiques  

        - ***Il est important de noter que les noms de polices composés de plusieurs mots doivent être placés entre guillemets comme pour la police "Times New Roman"***  

          - ***Il existe quelques polices de caractères génériques communes sur les navigateurs internet telles que “Serif”, “Sans-serif”, “Monospace”, “cursive”, “fantasy”, “system-ui”, “emoji”, “math” et “fangsong”, car elles sont installées sur la plupart des ordinateurs. Les polices génériques doivent être utilisées en dernière position dans la liste de font-family***  

          - Exemple :  

            ```CSS
            .famille1 {
            font-family: Futura, Verdana, sans-serif;
            }

            .famille2 {
              font-family: "Times new roman", Times, serif;
            }
            
            .famille3 {
              font-family: "Courier New", Courier, monospace;
            }

            ```

    - La propriété ***font-weight*** offre la possibilité de modifier l’épaisseur ou la graisse d’une police  

      - La valeur par défaut est normal, qui est le poids de police standard  

      - Il existe plusieurs autres valeurs possibles pour cette propriété, telles que ***lighter*** ou ***bolder*** qui définit la graisse d’un cran moins gras ou plus gras que son parent  

        - Il est important de retenir que la valeur ***400*** est équivalente à ***normal*** et la valeur ***700*** est équivalente à ***bold***  

        - Exemple :  

          ```CSS
          /* Arial accepte facilement plusieurs graisses */
          p {
          font-family: arial;
          }

          /* similaire à font-weight: 400 */
          .texte-normal {
          font-weight: normal;
          }

          /* similaire à font-weight: 700 */
          .texte-gras {
          font-weight: bold;
          }

          .texte-tres-gras {
          font-weight: 900;
          }
          ```

    - La propriété ***font-size*** permet de modifier la taille des polices, Cette propriété comprend 4 types de valeurs, telles que la longueur, le mot-clé, le pourcentage et la globale  

      - La valeur spécifiée par longueur peut être exprimée en plusieurs unités, nous utiliserons ici le ***px*** (pixels)

      - La valeur par mot-clé correspond à des valeurs prédéfinies, il en existe 8. Par exemple “xx-small” correspond à la moitié de la taille par défaut du navigateur, ou encore “large” correspond à 10 % de plus. La valeur en pourcentage donne une proportionnalité par rapport à la valeur de l’élément parent, et enfin la valeur globale qui permet de gérer l’héritage ou la réinitialisation comme par exemple “inherit”, “initial”, “revert” et “unset”  

      - Exemple :  

        ```CSS
        body {
        font-family: Arial;

        /* Taille absolue */
        font-size: 12px;
        }

        p {
        margin: 0;
        }

        /* Tailles relatives au parent, ici le body à 12px */
        .p1 {
        font-size: smaller;
        }

        .p2 {
        font-size: larger; 
        }
        
        /* Tailles par mots-clés dépendants des paramètres du navigateur */
        .p3 {
        font-size: xx-small;
        } /* 50% */
        
        .p4 {
        font-size: x-small;
        } /* 75% */
        
        .p5 {
        font-size: small;
        } /* 85% */
        
        .p6 {
        font-size: medium; 
        } /* 100% */
        
        .p7 {
        font-size: large;
        } /* 120% */
        
        .p8 {
        font-size: x-large;
        } /* 150% */
        
        .p9 {
        font-size: xx-large; 
        } /* 200% */

        .p10 {
        font-size: xxx-large;
        } /* 400% */
        
        /* tailles en pourcentage, proportionnelles au parent, donc le body */
        .p11 {
        font-size: 70%;
        }
        
        .p12 {
        font-size: 150%; 
        } /* ignore l'héritage, prends la valeur par défaut du navigateur */
        
        .p13 {
        font-size: initial;
        }
        ```

    - La propriété ***font-style*** permet de modifier l’inclinaison des polices. Cette propriété comprend 2 types de valeurs, telles que le mot-clé et la globale  

      - La valeur spécifiée par mot-clé correspond à deux valeurs prédéfinies, “italic” et “oblique”  
      
      - À la différence d’”italic”, “oblique” force la police à se rendre italique même si elle n’a pas été conçue pour cela  
      
      - La valeur globale qui permet de gérer l’héritage ou la réinitialisation comme à travers ***“inherit”***, ***“initial”***, ***“revert”*** et ***“unset”***  

        - Exemple :  

          ```CSS
          .p1 {
          font-style: italic;
          }
          ```

  - #### Alignements et compositions de textes  

    - La propriété ***text-align*** permet de gérer l’alignement du texte sur l’axe des abscisses (X). Cette propriété comprend plusieurs types de valeurs  

      - La valeur spécifiée par mot-clé correspond à quatre valeurs prédéfinies (***left***, ***center***, ***right*** et ***justify***)  

      - Il existe également une propriété “vertical-align” pour aligner les éléments sur l’axe des ordonnées (Y), mais elle est généralement utilisée avec les tableaux (***\<table>***)  

      - Exemple :  

        ```CSS
        body {
        width: 400px;
        }

        p {
        padding: 10px;
        border: 1px solid blue;
        }

        .p-left {
        text-align: left;
        }

        .p-right {
        text-align: right;
        }

        .p-center {
        text-align: center;
        }

        .p-justify {
        text-align: justify;
        }
        ```

    - La propriété ***text-decoration*** permet d’ajouter des décorations à un texte avec comme valeurs principales et il est possible de combiner plusieurs valeurs pour avoir une composition visuelle spécifique

      - ***underline*** qui permet d’ajouter un trait de soulignement au texte  
      - ***overline*** qui ajoute un trait au-dessus du texte  
      - ***line-through*** qui permet de barrer un texte  

        - Exemple :  

          ```CSS
          body {
          font-size: 20px;
          }

          .sans-soulignement {
          text-decoration: none;
          }
          
          .avec-soulignement {
          text-decoration: underline;
          }
          
          .avec-surlignement {
          text-decoration: overline;	
          }
          
          .avec-surlignement-soulignement {
          text-decoration: underline overline;
          }
          
          .trait-barre {
          text-decoration: line-through;
          }
          
          .pointilles {
          /* souligné + pointillé + couleur rouge */
          text-decoration: underline dashed red;
          }
          ```

    - La propriété text-transform permet de transformer un texte    

        - ***uppercase*** qui met le texte en majuscule  
        - ***lowercase*** qui met le texte en minuscule  
        - ***capitalize*** qui met une majuscule à la première lettre de chaque mot d’un texte  
        - ***globale*** permet de gérer l’héritage ou la réinitialisation comme par exemple ***“inherit”***, ***“initial”***, ***“revert”*** et ***“unset”***

        - Exemple :  

          ```CSS
          span {
          font-weight: bold;
          color: blue;
          }

          .maj {
          text-transform: uppercase;
          }
          
          .min {
          text-transform: lowercase;
          }
          
          .cap {
          text-transform: capitalize;
          }
          ```

    - Plusieurs propriétés permettent de gérer les interlignes et les espaces dans les textes

      - ***line-height*** permet de spécifier l’espace entre chaque ligne  
      - ***letter-spacing*** définit l’espace entre les différents caractères du texte  
      - ***word-spacing*** définit l’espace entre les différents mots du texte

        - Exemple :  

          ```CSS
          p {
          font-family: arial, sans-serif;
          font-size: 16px;
          border: 1px solid blue;
          }

          .container {
          width: 400px;
          }

          /* hauteur en pixel, mais possible aussi en pourcentage */          
          .hauteur-de-ligne {
          line-height: 30px;
          }

          /* largeur en pixel */
          .espace-de-lettres-positif {
          letter-spacing: 5px;
          }
          
          /* largeur en pixel, et valeurs négatives possibles pour serrer davantage les lettres */
          .espace-de-lettres-negatif {
          letter-spacing: -1px;
          }
          
          .espace-de-mots-positif {
          word-spacing: 15px;
          }
          
          .espace-de-mots-negatif {
          word-spacing: -2px;
          }
          ```

      - Il existe beaucoup de mise en forme des textes en CSS, voici quelques-unes des autres propriétés fréquemment utilisées qu’il est intéressant de connaître

          | Propriété     | Notes                                                                                                                               |
          | :-----------: | :---------------------------------------------------------------------------------------------------------------------------------: |
          | word-break    |Gère la césure des mots, donc très pratique lorsqu’un mot est très long et qu’il risque de « traverser » un cadre limité en largeur  |
          | hyphens       | Spécifie comment les mots peuvent être coupés en fin de ligne                                                                       |
          | overflow-wrap | Tronque une ligne pour empêcher un débordement, ou empêche la césure de celle-ci                                                    |
          | text-shadow   | Ajoute des ombres au texte                                                                                                          |
          | opacity       | Définit la transparence d’un élément, de 0 à 1. Cette valeur s’applique à l’ensemble de l’élément et de ses enfants                 |

- ### ***Un peu plus loin dans la mise en forme et la composition des textes***

  - #### Couleurs et leur opacité  

    - Voici un tableau qui présente les méthodes d’affichage des couleurs avec leur opacité, et d’autres méthodes moins connues  

    | Méthode             | Exemple                       |  Notes |
    | :-----------------: | :---------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
    | Hexadécimale alpha  | #0000FFFF                     | Fonctionne comme l’hexadécimale simple, à la différence qu’on ajoute 2 digits pour gérer la couche alpha permettant de gérer la transparence allant de 00 (transparent) à FF (opaque). Il y a maintenant 8 digits pour définir une couleur                              |
    | RGBA                | rgb(0, 0, 255, 1)             | RGBA = Red Green Blue alpha. Fonctionne comme le RGB, à la différence que la couche supplémentaire alpha permet de gérer la transparence sur la proportion 0 à 1, ainsi 0 est transparent, 0,5 représente 50 % de transparence et 1 une opacité complète.               |
    | HSL                 | hsl(240, 100 %, 50 %)         | HSL = Hue Saturation Lightness. Valeur basée sur la teinte (H, de 0 à 360), la saturation (S de 0 à 100 %) et la lumière (L de 0) 100 %). L’utilisation est plus complexe, mais la palette de couleur est plus précise.                                                 |
    | HSLA                | hsl(240, 100 %, 50 %, 1)      | HSLA = Hue Saturation Lightness Alpha. Fonctionne comme le HSL, à la différence que la couche supplémentaire alpha permet de gérer la transparence sur la proportion 0 à 1. Ainsi, 0 est transparent, 0,5 représente 50 % de transparence et 1 une opacité complète.    |
    | HSV                 | hsv(240, 100 %, 100 %)        | HSV = Hue Saturation Value. Valeur basée sur la teinte (H, de 0 à 360), la saturation (S de 0 à 100 %) et la lumière (L de 0) 100 %). Unité de mesure utilisée pour la peinture ou l’encre, car elle représente mieux les couleurs pour les humains que la valeur RVB.  |
    | CMYK                | cmyk(100 %, 100 %, 0 %, 0 %)  | CMYK = Cyan, Magenta, Jaune et Noir (CMJN en français). Unité utilisée pour le tirage papier, tel que les imprimantes. Les couleurs sont une combinaison de cyan, magenta, jaune et noir.                                                                               |
    | HWB                 | hwb(240, 0 %, 0 %)            | HWB = Hue, Whiteness, Blackness. Teinte, blancheur et noirceur. Cette unité de couleur devrait être prise en charge en CSS4                                                                                                                                             |
    
      - Il existe d’autres méthodes de couleur telles que LAB, un système de coordonnées rectangulaire avec un axe central de luminosité. LCH avec le même axe que LAB, mais utilisant des coordonnées polaires chroma et teintes donnant des coordonnées polaires cylindriques, OKLAB, OKLCH, les espaces coloriques prédéfinis tels que sRGB color space,  display-p3 color, a98-rgb color, prophoto-rgb color, et bien d’autres encore que l’on peut retrouver sur le site du W3  

  - #### Unités de mesure des caractères  

    - L’unité rem s’appuie sur la taille de la police de l’élément racine du document. Ainsi, 1 rem correspond à la taille de police définie par défaut dans les paramètres du navigateur, qui est généralement de 16 px. L’unité de mesure 10 rem sera alors équivalente à 160 px  

      - Exemple :  

          ```CSS
          html {
            font-size: 62,5%; /* Soit 10px */
          }
          
          .paraph_1 {
          font-size: 1.6rem; /* Soit 16px */
          }

          .paraph_2 {
          font-size: 1.9rem; /* Soit 19px */
          }
          ```

          - Depuis l’apparition de l’unité rem, l’unité em est moins utilisée, car elle avait le défaut d’agir par héritage et d’être relative au parent. Ainsi, si nous imbriquons plusieurs balises ayant la même taille de police, les éléments enfants vont grossir davantage

  - #### Polices téléchargeables  

    - La première solution consiste à utiliser un service tiers tel que Google Fonts qui est un service d’hébergement de polices de caractères libres de droits, téléchargeables et utilisables gratuitement, que nous pouvons visualiser et choisir sur ce lien : [Google Fonts](https://fonts.google.com/)  

      - Exemple :  

        ```HTML
        <!DOCTYPE html>
        <html>
        <head>

        <!-- Code à copier/coller depuis la page https://fonts.google.com/specimen/Ruluko -->
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Ruluko&display=swap" rel="stylesheet">
        
        <style>
        h1 {
        /* Ruluko n’a pas d’empattement, elle est donc de la famille sans-serif */
        font-family: 'Ruluko', sans-serif;
        }
        </style>

        </head>

        <body>
          <h1>Titre écrit avec la police Ruluko</h1>
        </body>
        </html>
        ```
  
  - #### Utiliser des fontes personnelles  

    - La directive @font-face permet de définir une police de caractère spécifique pour une page web. 
    
    - Cette police peut être chargée depuis un serveur local ou distant, et il existe différents formats de fichiers possibles, tels que .ttf (TrueType), .otf (OpenType), .woff, .woff2, .otc, eot (embedded OpenType), .svg, .svgz

    - Voici un exemple avec la police Roboto que vous pouvez télécharger et décompresser dans un dossier nommé “fonts”

      - Pour utiliser ce fichier, vous devez d’abord 
      
        - Déclarer la directive @font-face en spécifiant la propriété ***font-famil***y, qui sera attribuée à la valeur Roboto. 
        
        - Vous devez ajouter ensuite la propriété ***src*** avec la valeur ***“url”*** et ***“format”***, qui spécifie les différents formats de fichiers présents dans le dossier “fonts”.
        
        - Le navigateur choisira le fichier correspondant en fonction de son système. Une fois la directive déclarée, vous pouvez utiliser la propriété font-family sur les éléments HTML pour appliquer la police Roboto et jouer avec les propriétés de poids et de taille pour personnaliser son apparence

            ```HTML
            <!DOCTYPE html>
            <html>
              <head>
                <style>
                  @font-face {
                  font-family: 'Roboto';
                  src: url('./fonts/Roboto-Regular.woff2') format('woff2'),
                  url('./fonts/Robot-Regular.ttf') format('truetype');
                  }

                  body {
                  font-size: 22px;
                  }
                  
                  span {
                  font-family: 'Roboto', sans-serif;
                  font-weight: 700;
                  }
                </style>
              </head>
              <body>
              <p>Exemple avec <span>la police Roboto</span></p>
              </body>
            </html>
            ```

            - Découvrez toutes les propriétés disponibles pour la directive @font-face en consultant la documentation [MDN Web](https://developer.mozilla.org/fr/docs/Web/CSS/@font-face)
  
  - #### Documentations officielles  

    - Vous pouvez utiliser des polices de caractères à distance, sans avoir besoin d’héberger les polices sur votre serveur avec les sites suivants :

      - [Google Fonts](https://fonts.google.com/) : fonts open source, que nous pouvons utiliser gratuitement à des fins personnelles ou commerciales.

      - [CDN](https://www.cdnfonts.com/) : fonts avec diverses licences d’utilisation qu’il faut bien lire avant utilisation.

    - Autres sites utiles :

      - [CSS Fonts](https://www.cssfontstack.com/) : vous pouvez voir la liste des polices web considérées comme “sûres”. Ce site affiche des statistiques de disponibilité en fonction de la police générique et du système d’exploitation.

      - [Code Couleur](https://www.code-couleur.com/) : obtenir des codes hexadécimaux et rvb, et obtenir des palettes de couleurs à partir de photos.

      - [RapidTables](https://www.rapidtables.com/convert/color/index.html) : convertir les couleurs en hexadécimal, RGB, HSV, HSL.

    - Il est important de noter que les navigateurs ne réagissent pas tous de la même manière sur certaines fonctionnalités CSS, et ceci, indépendamment du système d’exploitation. Il est donc essentiel de vérifier la compatibilité des propriétés, soit sur MDM Web Docs de Mozilla ou le site [Can I use](https://caniuse.com/)

##
## ***__La structuration logique en HTML5 et le modèle de boîtes en CSS3__***

- ### ***Structure logique en HTML5***  

  - #### Structure logique en HTML5  

    - HTML5 améliore la structure et la compréhension des pages web. Les éléments sémantiques d'HTML5 décrivent explicitement le rôle et la structure des différentes parties d'une page  

      - La balise ***\<header>*** sert à définir l'en-tête d'une page web ou d'une section dans une page  
      
        - Il est utilisé pour regrouper des informations d'introduction ou de navigation, Elle peut contenir des éléments tels que :
        
          - Des titres
          - Des logos
          - Des menus de navigation 
          - Ou des informations de contact

        - La balise est de type ***"container"***, elle doit être ouverte et fermée  

          Exemple :  

            ```HTML
            <!DOCTYPE html>
            <html>
              <head>
                <title>Ma Page</title>
              </head>
              <body>
                <header>
                  <!-- Logo -->
                  <a href="index.html"><img src="logo.png" alt="Logo"></a>
                  <!-- Navigation -->
                </header>
                <main>
                  <!-- Contenu principal de la page -->
                </main>
                <footer>
                  <!-- Pied de page -->
                </footer>
              </body>
            </html>
            ```

      - La balise ***\<nav>*** représente une section de navigation dans une page web  
        
        - Il est utilisé pour regrouper les liens de navigation principaux, tels que les liens vers les pages internes d'un site web ou les liens vers des ressources externes  

        - La balise de type ***"container"*** ; elle est donc doit être ouverte puis fermée  

        - Pour améliorer l'accessibilité, ajoutez un attribut ***aria-label*** à l'élément ***\<nav>*** avec une description claire de la section de navigation  
        
          - Exemple :  
          
            ```HTML
            <nav aria-label="Menu principal"> ... </nav>
            ```
          
          - Autre exemple :  

            ```HTML
            <header>
              <h1>Titre du site</h1>
              <nav aria-label="Menu principal">
                <ul>
                  <li><a href="index.html">Accueil</a></li>
                  <li><a href="apropos.html">À propos</a></li>
                  <li><a href="contact.html">Contact</a></li>
                </ul>
              </nav>
            </header>
            ```

              - Dans cet exemple, l'élément ***\<nav>*** est utilisé pour créer un menu de navigation principal à l'intérieur de l'en-tête ***\<header>***  

      - La balise ***\<main>*** représente le contenu principal d'une page web et est de type ***“container”***  
        
        - Elle doit être utilisé une seule fois par page pour englober le contenu principal. Pour améliorer l'accessibilité, ajoutez un attribut ***role*** avec la valeur ***"main"*** à l'élément ***\<main>***

        - L'élément ***\<main>*** est généralement placé après l'en-tête ***\<header>*** et la navigation ***\<nav>***, et avant le pied de page ***\<footer>*** 

          - Exemple :  

            ```HTML
            <main role="main">

              <article>
                <h2>Titre de l'article</h2>
                <p>Contenu de l'article...</p>
              </article>
              
              <section>
                  <h2>Titre de la section</h2>
                  <p>Contenu de la section...</p>
              </section>

            </main>
            ```

      - La balise ***\<article>*** représente une section indépendante et autonome de contenu dans une page web et est utilisé pour englober des éléments tels que :  
      
        - Les articles de blog  
        - Les actualités  
        - Les commentaires  
        - Ou contenu qui pourrait être réutilisé ou distribué séparément du reste de la page  
        
          -  Les balises ***\<article>*** peuvent être incluses à l'intérieur d'autres éléments sémantiques, tels que ***\<main>***, ***\<section>*** ou même d'autres éléments ***\<article>***  

          - Les éléments ***\<header>*** et ***\<footer>*** peuvent être utilisés à l'intérieur d'un ***\<article>*** pour décrire le contenu de l'article  
          
            - Par exemple :  
            
              - Un ***\<header>*** à l'intérieur d'un ***\<article>*** peut contenir le titre et les informations sur l'auteur  
              
              - Un ***\<footer>*** peut inclure des liens vers des articles connexes, des balises ou des informations de copyright.

              - Ajouter des éléments de titre ***\<h1>*** à ***\<h6>*** structure le contenu de l'article  

        - Exemple :  

          ```HTML
          <!DOCTYPE html>
          <html lang="fr">
            <head>
            <!-- tête de la page -->
            </head> 
            <body>
              <header>
              <!-- En-tête de la page -->
              </header>
              <main role="main">
                <article>
                  <header>
                    <h1>Titre de l'article</h1>
                    <p>Auteur : Jane Doe</p>
                    <p>Date : 17 avril 2023</p>
                  </header>

                  <p>Contenu de l'article...</p>
                  <p>Autre paragraphe de l'article...</p>
                  
                  <footer>
                    <p>Tags : HTML5, sémantique, accessibilité</p>
                  </footer>
                </article>
              </main>
              <footer>
              <!-- Pied de page -->
              </footer>
            </body>
          </html>
          ```

      - La balise ***\<section>*** représente une section générique de contenu dans une page web  

        - Elle est utilisé pour regrouper des éléments thématiquement cohérents ou relatifs, généralement accompagnés d'un titre  

        - Chaque ***\<section>*** est accompagnée d'un élément de titre ***\<h1>*** à ***\<h6>***  

        - Elle peut être imbriqué à l'intérieur d'autres éléments sémantiques, tels que ***\<main>***, ***\<article>*** ou d'autres éléments ***\<section>***  

        - Exemple :  

          ```HTML
          <main role="main">

            <section>
              <h2>Introduction</h2>
              <p>Contenu de l'introduction...</p>
            </section>
            
            <section>
              <h2>Chapitre 1</h2>
              <p>Contenu du chapitre 1...</p>
            </section>

            <section>
              <h2>Chapitre 2</h2>
              <p>Contenu du chapitre 2...</p>
            </section>
          
          </main>
          ```

      - La balise ***\<aside>*** représente une section de contenu qui est tangentielle ou indirectement liée au contenu principal de la page  

        - Il est souvent utilisé pour englober des éléments tels que :

          - Les barres latérales  
          - Les encadrés  
          - Les publicités  
          - Les biographies d'auteurs  
          - Du contenu qui peuvent être considérés comme séparés du contenu principal  

        - Exemple :  

          ```HTML
          <main role="main">
            <article>
            <!-- Contenu principal de l'article -->
            </article>

            <aside>
              <h3>À propos de l'auteur</h3>
              
              <p>Jane Doe est une développeuse web spécialisée dans les technologies front-end et  
              l'accessibilité.</p>
              
              <h3>Articles connexes</h3>

              <ul>
                <li><a href="#">Titre de l'article connexe 1</a></li>
                <li><a href="#">Titre de l'article connexe 2</a></li>
                <li><a href="#">Titre de l'article connexe 3</a></li>
              </ul>
            </aside>
          </main>
          ```

        - Elle peut être imbriqué à l'intérieur d'autres éléments sémantiques, tels que ***\<main>***, ***\<article>*** ou d'autres éléments ***\<section>***  

      - La balise ***\<footer>*** peut être imbriqué à l'intérieur d'autres éléments sémantiques, tels que ***\<main>***, ***\<article>*** ou ***\<section>***

        - Exemple :  

          ```HTML
          <body>
            <header>
            <!-- Contenu de l’en-tête de la page -->
            </header>
            
            <main>
            <!-- Contenu principal de la page -->        
            </main>

            <footer>
              <p>&copy; 2023 Tous droits réservés. Conçu par Jane Doe.</p>
              <nav>
              <ul>
              <li><a href="#">Accueil</a></li>
              <li><a href="#">À propos</a></li>
              <li><a href="#">Contact</a></li>
              <li><a href="#">Mentions légales</a></li>
              </ul>
              </nav>
            </footer>
          </body>
          ```

- ### ***Modèle de boîtes en CSS3***  

  - #### Modèle de boîtes en CSS3

    - Le modèle de boîtes (box model) en CSS3 est un concept fondamental. Chaque élément est considéré comme une boîte rectangulaire  

    - Le modèle de boîtes est composé de plusieurs parties : 
    
      - ***Le contenu***  

        - Représente le contenu. Il est possible d’augmenter sa zone en hauteur avec la propriété “height” et sa largeur avec la propriété “width”  

      - ***Le padding*** (marge intérieure)  

        - C’est une zone entourant le contenu. La propriété “padding” permet de modifier l’épaisseur de celui-ci  

      - ***La bordure***  

        - La bordure entoure le contenu ainsi que le padding. La propriété “border” permet de modifier sa taille à l’image de padding, mais également son style  
      
      - ***La marge*** extérieure (margin)  

        - la marge englobe toutes les autres boîtes CSS d’un bloc. C’est la propriété “margin” qui permet de paramétrer les valeurs des quatre côtés  

          - Exemple en image :  
          
            ![Block CSS](/Pictures/struc_bloc_css_1.png)


            - Quelques exemple de code :  

              ```CSS
              .box {
              margin: 10px 50px 20px 0;
              }
              ```

                - le bloc box à “margin-top” à 10px, “margin-right” à 50px, “margin-bottom” à 20px et “margin-left” à 0px  

              ```CSS
              .box {
              width: 250px;
              height: 100px;
              padding : 10px;
              margin: 10px;
              border: 5px solid black;
              }
              ```

                - Si on ne renseigne qu’une valeur, cela signifie que les quatre côtés du bloc défini auront la même valeur  

    - ***Les Unités de mesures CSS***

      - Les unités les plus courantes sont les pixels (px)  
        - Les pixels sont une unité de mesure absolue
      
      - Les em  
      
      - Les rem  
      
      - Les pourcentages (%)  

        - Les em, rem et pourcentages sont des unités relatives

      - Les unités rem sont basées sur la taille de la police de l'élément racine (généralement l'élément ***\<html>***)

        - Rappel : 

          ```CSS
          html {
            font-size: 62,5% /* Soit une police à 10px */
          }

          p {
            font-size: 1.2rem /* soit le paragraphe sera de 12px */
          }

          a {
            font-size: 2rem /* soit le lien sera de 20px */
          }
          
          ```

      - Une autre unité de mesure est le vw (viewport width), qui représente un pourcentage de la largeur de la fenêtre d'affichage. Ainsi, 1vw correspond à 1 % de la largeur de la fenêtre d'affichage  

    - ***Box-sizing***

      - La propriété CSS box-sizing permet de contrôler la manière dont les dimensions d'un élément sont calculées. Elle détermine si les marges intérieures (padding) et les bordures doivent être incluses dans la largeur et la hauteur totales ou non  

        - Les valeurs courantes sont content-box (par défaut) et border-box  

          - ***Le content-box***  

            - La largeur et la hauteur spécifiées pour un élément sont uniquement appliquées au contenu de l'élément. Les bordures et le padding sont ajoutés en plus de ces dimensions

          - ***Le border-box***  

            - La largeur et la hauteur spécifiées pour un élément incluent le padding et les bordures  

      - Exmeple :  

        ```HTML
        <!DOCTYPE html>
        <html>
          <head>
            <meta charset="utf-8" />
            <style>
            .box {
            width: 200px;
            height: 200px;
            border: 10px solid #000;
            padding: 20px;
            margin: 20px;
            }

            .content-box {
            box-sizing: content-box;
            background-color: #f1f1f1;
            }
            .border-box {
            box-sizing: border-box;
            background-color: #e1e1e1;
            }
            </style>
          </head>
          <body>
            <div class="box content-box">content-box</div>
            <div class="box border-box">border-box</div>
          </body>
        </html>
        ```
    - ***Overflow***

      - La propriété CSS ***overflow*** détermine comment le contenu qui dépasse les dimensions d'un élément est géré et les valeurs courantes sont :  
      
        - Visibles (par défaut)  
          - Le contenu qui dépasse les dimensions de l'élément sera visible et s'étendra au-delà des limites de l'élément.  
        - Hidden  
          - Le contenu qui dépasse les dimensions de l'élément sera masqué et ne sera pas visible.  
        - Scroll  
          - Des barres de défilement seront toujours affichées pour l'élément, même si le contenu ne dépasse pas les dimensions.
        - Auto  
          - des barres de défilement seront affichées uniquement si le contenu dépasse les dimensions de l'élément.  

          - Exemple :  

            ```HTML
            <!DOCTYPE html>
            <html>
              <head>
                <meta charset="utf-8" />
                <style>
                  .overflow-example {
                  width: 200px;
                  height: 200px;
                  overflow: auto;
                  border: 1px solid #000;
                  }
                </style>
              </head>
              <body>
                <div class="overflow-example">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ut felis et sapien bibendum cursus. Etiam congue fringilla venenatis. Praesent vitae leo at nunc vehicula fermentum vitae ut odio.
                </div>
              </body>
            </html>
            ```

    - ***Éléments en ligne et display: inline-block***  

      -  les éléments en ligne sont disposés horizontalement, côte à côte, et n'occupent que l'espace nécessaire pour leur contenu.    
      - Les éléments en ligne ne respectent pas les propriétés width et height, et les marges horizontales (gauche et droite) contrôlent l'espacement entre les éléments.  
      - Les éléments en ligne prennent en compte les propriétés padding, border et margin (à l'exception des marges supérieure et inférieure, qui n'affectent pas l'espacement vertical).  
      - La hauteur d'un élément en ligne est déterminée par la hauteur de la ligne (line-height) et son contenu.  
      - La propriété ***display: inline-block*** permet aux éléments d'avoir des dimensions spécifiées (largeur et hauteur) tout en conservant leur positionnement sur une même ligne.

    - Exemple :  

      ```HTML
      <!DOCTYPE html>
      <html>
        <head>
          <meta charset="utf-8" />
          <style>
            ul {
            list-style-type: none;
            background-color: #f1f1f1;
            padding: 10px;
            }

            li {
            display: inline;
            }
            
            a {
            display: inline-block;
            text-decoration: none;
            color: black;
            background-color: #f1f1f1;
            padding: 10px 20px;
            margin: 5px;
            }
            
            a:hover {
            background-color: #e1e1e1;
            }
          </style>
        </head>
        <body>
          <ul>
            <li><a href="#">Accueil</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
          </ul>
        </body>
      </html>
      ```





##
## ***____*** Theme

- ### ****** (grand titre)

  - #### (petit titre)
