# Memo HTML-CSS

## __Introduction au HTML__  

__Qu’est-ce que le HTML ?__  

  - Le HTML ( HyperText Markup Language ), est utilisé pour mettre en page un site web  

    - [Lien vers la page des références des éléments HTML](https://developer.mozilla.org/fr/docs/Web/HTML/Element)

__Le W3C__  

  - Le W3C ( Wolrd wide Web Consortium ), est l’organisme chargé de la standardisation et de la compatibilité des technologies du web  

    - [Site du W3C](https://www.w3.org/)  

__Le HTML coté client__  

  - Le « côté client » couvre toutes les opérations effectuées par une application ou un site web au sein d’un navigateur  

  - Le langage HTML est donc un langage « côté client ». C’est le navigateur de l’utilisateur qui interprète le HTML  

  - Les pages d’un site web sont transmises sous forme de code HTML brut au navigateur, qui va l’interpréter pour afficher son contenu sur l’écran  

  - Cette partie du développement d’un site web est appelée « développement frontend », faisant référence à la partie création de l’interface utilisateur, au côté visuel d’un site ou d’une application web. HTML sert à définir la structure et l’organisation des pages  

##
## ***__Syntaxe générale de HTML__***  

- __Les éléments de syntaxes générales du HTML__  

  - Le code HTML est un langage de balisage hypertexte : il se construit à l’aide de balises, qui sont entourées par deux chevrons « < » et « > »  

  - Ces balises peuvent également prendre en charge des attributs, qui, eux, permettront de donner plus de précision sur la façon dont la balise doit être interprétée  

  - Les balises HTML minimal  

    ```  
    <!DOCTYPE html>  
    <html lang="fr">  
    <head> ... </head>  
    <body> ... </body>  
    </html>  
    ```  

  - Les balises sont « répétées ». En HTML, la grande majorité des balises fonctionnent par paires et sont composées d’une balise d’ouverture et une balise de fermeture  

  - La balise de fermeture est identique à la balise d’ouverture si ce n’est qu’elle contient un slash (« / ») juste après le chevron ouvrant  
    - Ex : `<head> ... </head>`  

  - Il existe cependant des balises qui n’ont pas besoin de balise fermante : on les appelle balises auto-fermantes ou orphelines  

- __Desciption de la syntaxe des balises HTML minimal__  

  - Le code HTML commence toujours avec la balise suivante  
    - `<!DOCTYPE html>`  

      - Cette balise permet de spécifier au navigateur le type de document HTML utilisé. Il est donc crucial de toujours inclure cette balise au début de votre code HTML  

  - La balise ***\<html>*** que l’on appelle aussi l’élément racine du document HTML marque le début du document HTML  

    - `<html> ... </html>`  

  - La balise ***\<head>*** inclut toutes les informations qui ne s’affichent pas directement dans la page web, mais qui sont utiles pour le bon fonctionnement du code, ainsi que pour les moteurs de recherche  
    
    - `<head> ... </head>`  

  - La balise ***\<body>*** définit l’ensemble des éléments qui vont être visibles sur la page tels que les titres, le texte, les images ou encore les formulaires  

    - `<body> ... </body>`  

  ```
  - Les balises <head> et <body> sont deux autres balises essentielles
  
  - Elles s’imbriquent entre la balise d’ouverture <html> et de fermeture </html>
  ```  

- __Les balises structurelles en HTML__  

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
## ***__Organiser son texte__***  

- __Les balises \<h1> à \<h6>__  

  - Il existe plusieurs niveaux de balises de titres, allant du ***\<h1>*** jusqu'au ***\<h6>***. Les balises ont des tailles et des styles de police différents, ce qui permet de les différencier visuellement. Ainsi, le titre principal de la page est inséré dans la balise ***\<h1>***, tandis que les balises ***\<h2>*** à ***\<h6>*** sont utilisées pour les sous-titres  

    ```
    <h1> ... </h1>  
    <h2> ... </h2>  
    <h3> ... </h3>  
    <h4> ... </h4>  
    <h5> ... </h5>  
    <h6> ... </h6>  
    ```  

- __La balise \<p>__  

    - Les balises ***\<p>*** sont utilisées en HTML pour délimiter un paragraphe de texte, elle permet d'ajouter des sauts de ligne entre les différents paragraphes  

      - `<p> ... </p>`  

- Les balises \<ul> et \<ol>  

  - La balise ***\<ul>*** permet de créer une liste d'éléments sans ordre particulier. Chaque item est précédé d'un point (ou autre symbole), et il n'y a pas de numérotation. Ce type de liste est idéal pour présenter des informations qui ne sont pas liées entre elles  

      - `<ul> ... </ul>`  

    - la balise ***\<ol>*** permet de créer une liste ordonnée, où chaque item est numéroté. Cette liste est très utile pour présenter des informations qui ont un ordre ou une hiérarchie, comme les étapes d'un processus  

      - `<ol> ... </ol>`  

      ```
      Ces éléments apportent une structure visuelle à l'information
      ceci qui est crucial pour la lisibilité de la page  
      ```
      
      ```
      Il est possible d'ajouter des sous-listes à l'intérieur d'une liste principale.
      Il faut ajouter une liste imbriquée dans une autre liste
      ```

    - Les balises ***\<li>***, il est également important de noter que, à l'intérieur de ces deux balises, chaque élément de la liste est inscrit dans une balise ***\<li>***

        - Exemple avec la balise ***\<ul>***  

          ```
          <ul>  
          <li> ... </li>  
          <li> ... </li>  
          <li> ... </li>  
          <li> ... </li>  
          </ul>  
          ```

        - Exemple avec la balise ***\<ol>***  

          ```
          <ol>  
          <li> ... </li>  
          <li> ... </li>  
          <li> ... </li>  
          <li> ... </li>  
          </ol>  
          ```

- __Les balises block et les balises inline__  

    - une balise block est une balise qui crée un nouveau bloc de contenu sur la page web. Cela signifie que tout le contenu compris entre la balise d'ouverture et la balise de fermeture sera affiché comme un bloc distinct  

    - Les exemples les plus courants de balises block incluent les balises ***\<div>***, ***\<p>***, ***\<ul>***, ***\<ol>***, ***\<h1>*** à ***\<h6>*** et ***\<blockquote>***  

    - Les balises inline sont souvent utilisées pour formater le texte ou pour ajouter des éléments en ligne, tels que des liens hypertextes, des images ou des boutons. Les exemples les plus courants de balises inline incluent les balises ***\<a>***, ***\<img>***, ***\<span>*** et ***\<button>***  

- __Le formatage du texte__  

    ```
    Lors de la création d'une page web, il est important de considérer la mise en forme
    Le HTML offre plusieurs balises qui permettent de mettre en évidence certains mots
    ```  

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

---

6. __Le placement du texte en HTML__  

    - Les balises ***\<br>*** et ***\<hr>*** sont utilisées en HTML pour insérer des sauts de ligne et des séparateurs horizontaux dans le texte

      - La balise ***\<br>*** est utilisée pour insérer un saut de ligne simple  

        - `<br />`  

      - La balise ***\<hr>*** est utilisée pour insérer une ligne horizontale pour séparer le texte  

        - `<hr />`  

    - La balise ***\<blockquote>*** permet de citer du texte dans une page web. Elle est très utile pour citer des extraits de texte provenant d'autres sources, comme des livres, des articles de journaux, des discours ou des entrevues  

      - `<blockquote> ... </blockquote>`  

    - La balise ***\<span>*** est utilisée pour définir du texte ou éléments HTML avec une mise en forme particulière. Elle est souvent utilisée pour appliquer des styles spécifiques à une partie d'un bloc de texte sans affecter le reste du texte  

      - `<span> ... </span>`  

---
---
---

## ***__Le langage hypertexte__***

  - ***Les liens hypertextes***  

    ```
    - Un lien hypertexte est un élément interactif d’une page web

    - Cela permet à l’utilisateur qui clique dessus de naviguer entre différents contenus
    
    - Les liens hypertextes peuvent prendre différents formats commes par exemple
      
      * Du texte
      * Des images
      * Des boutons
    ```  

    - La balise ***\<a>*** (ancre ou anchor en anglais) est la balise utilisée pour créer des hyperliens en HTML qui comporte différents attributs 

      - `<a> ... </a>`  
      
  - ***L’attribut href***  

    ```
    - L’attribut href contient le lien vers lequel vous souhaitez rediriger l’utilisateur
    
    - Il peut s’agir
      
          * D’un lien interne vers une autre page du même site web 
          * Vers une autre section d’une même page web
          * Un lien externe vers un autre site
          * Un lien de téléchargement
          * Un lien de courriel
        
    - Cet attribut est un attribut essentiel de la balise <a>
    
    - Il peut accueillir n’importe quel schéma d’URL 
          
          * Si il est pris en charge par les navigateurs web
    ```  

    - ***Créer un lien vers une autre page web***  

        - `<a href="www.google.com">Site Google</a>`  
          
          - Ne pas oublier de placer l'URL entre guillemets (“”)  

    - ***Créer un lien interne***  

        - Insérer dans l'attribut ***href*** le chemin d’accès relatif ou absolu vers le document HTML de la page
          
          - `<a href="Accueil.html">Accueil</a>`  

    - ***Créer un lien vers un endroit de la même page***  

        ```
        - Cela permet de créer un lien sur un endroit précis d’une page comme une section
        
        - C’est ce qui s’appelle créer une ancre. 
        
        - Il faut donner un attribut “id” à l’élément que l’on souhaite lier
        
        - On va attribuer à l’attribut “href” de la balise de lien l’id de cet élément précédé du signe dièse (#)
        ```

        - Exemple  
        
          ```
          <section id="projects"> ... \</section>
          ```
          
          - `<a href="#projects">Découvrez nos réalisations</a>`  

    - ***Créer un lien courriel***  

        - Pour créer un lien courriel, il suffit d’utiliser le schéma d’URL mailto  

          - `<a href=”mailto:username@exemple.com”>Contactez-nous</a>`  

    - ***Créer un lien vers un document***  

        - Pour créer un lien vers un document, il suffit d’ajouter le chemin d’accès vers ce document à l’attribut href du lien  

          - `<a href=”/fichier/doc.pdf”>Fichier_PDF</a>`
    
  - L’attribut ***target***  

    ```
    Il va permettre de préciser au navigateur où ouvrir le lien sur lequel l’utilisateur a cliqué. La façon la plus courante de l’utiliser est en lui passant la valeur “_blank” pour ouvrir le lien dans un nouvel onglet ou dans une nouvelle fenêtre. Cependant, il existe d'autres valeurs possibles pour l'attribut "target", comme "_self" pour ouvrir le lien dans la même fenêtre ou "_parent" pour ouvrir le lien dans le cadre parent de la fenêtre en cours
    ```
      - Exemple
        - `<a href="/HTML/contact.html" target="_blank">Contactez-nous</a>`

  - L’attribut ***dowload***  

    ```
    L'attribut "download" est un élément HTML qui permet à un visiteur de télécharger un fichier associé à une page web
    ```
      - Exemple
        - `<a href=”mon-fichier.pdf” download>Télécharger mon fichier PDF</a>`
        
  - L’attribut ***title***  

    ```
    L'attribut “title” est un attribut universel, c’est-à-dire qu’il est pris en charge par l’ensemble des balises HTML. Néanmoins, il s’avère particulièrement utile associé à la balise <a>. Cet attribut permet de donner des informations supplémentaires sur le lien, qui vont s’afficher sous la forme d’info-bulle lorsque l’utilisateur passera la souris dessus
    ```
      - Exemple
        - `<a href="Taches.html" title="Toutes les taches">Taches à faire</a>`  

---
---
---
---

## ***__Le multimédia en HTML__***


  - ***Introduction aux balises multimédia en HTML***  

    ```
    - Qu’est-ce qu’un fichier multimédia ?  

    - un fichier multimédia est défini comme un fichier informatique qui a la capacité de contenir plusieurs types de médias

    ```  

  - ***Intégrer des images avec les balises \<img> et \<picture>***  

    ```
    - Il existe 2 méthodes qui permettent d’afficher des fichiers image sur une page web : l’utilisation de la balise <img> et celle de la balise <picture>
    ```  

    - La balise ***\<img>***  

      ```
      - La balise <img> permet d’intégrer une image à une page web depuis un dossier en local ou depuis une URL spécifique. Il s’agit d’une balise autofermante, qui ne nécessite pas l’utilisation d’une balise de fermeture dédiée  

      - Elle prend un attribut obligatoire : l’attribut src, qui sert à spécifier l’URL ou le chemin d’accès vers l’image que l’on souhaite ajouter à notre page web  

      - L’attribut alt est un autre attribut courant de la balise <img>. Il permet d’associer un texte à l’image, dit alternatif, qui s’affiche en cas d’erreur de chargement du fichier  
      ```

      - Exemple  

        - `<img src="picture.png” alt=”Img picture”>`  

    - La balise ***\<picture>***  

      ```

      ```

      - Exemple  

        - ``
