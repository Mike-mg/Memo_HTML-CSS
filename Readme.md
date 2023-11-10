# Memo HTML-CSS

## ***__Introduction__***  

1. Qu’est-ce que le HTML ?  

    - Le HTML ( HyperText Markup Language ), est utilisé pour mettre en page une site web  

      - [Lien vers la page des références des éléments HTML](https://developer.mozilla.org/fr/docs/Web/HTML/Element)

---  

2. Le W3C  

    - Le W3C ( Wolrd wide Web Consortium ), est l’organisme chargé de la standardisation et de la compatibilité des technologies du web  

      - [Site du W3C](https://www.w3.org/)  

---  

3. Le HTML coté client  

    - Le « côté client » couvre toutes les opérations effectuées par une application ou un site web au sein d’un navigateur  

    - Le langage HTML est donc un langage « côté client ». C’est le navigateur de l’utilisateur qui interprète le HTML  

    - Les pages d’un site web sont transmises sous forme de code HTML brut au navigateur, qui va l’interpréter pour afficher son contenu sur l’écran  

    - Cette partie du développement d’un site web est appelée « développement frontend », faisant référence à la partie création de l’interface utilisateur, au côté visuel d’un site ou d’une application web. HTML sert à définir la structure et l’organisation des pages  

---  
---  
---  

## ***__La syntaxe minimal__***  

1. La syntaxe minimal du code HTML  

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

---  

#### 2. Desciption de la syntaxe des balises HTML minimal  

- Le code HTML commence toujours avec la balise suivante  
  - `<!DOCTYPE html>`  

    - Cette balise permet de spécifier au navigateur le type de document HTML utilisé. Il est donc crucial de toujours inclure cette balise au début de votre code HTML  

- La balise ***\<html>*** que l’on appelle aussi l’élément racine du document HTML marque le début du document HTML  
  - `<html> ... </html>`  

- La balise ***\<head>*** inclut toutes les informations qui ne s’affichent pas directement dans la page web, mais qui sont utiles pour le bon fonctionnement du code, ainsi que pour les moteurs de recherche  
  - `<head> ... </head>`  

- La balise ***\<body>*** définit l’ensemble des éléments qui vont être visibles sur la page tels que les titres, le texte, les images ou encore les formulaires  
  - `<body> ... </body>`  

> Les balises \<head> et \<body>, qui sont deux autres balises essentielles de tout document HTML, viennent s’imbriquer entre la balise d’ouverture \<html> et la balise de fermeture \</html>  
---  
---  
---  
## ***__Les balises structurelles en HTML__***  

1. __La balise ***\<div>***__  

    - La balise ***\<div>*** est la balise la plus couramment utilisée pour placer du contenu sur une page web, elle va permettre de diviser la page web en différents espaces et donc de la structurer de manière organisée  
      - `<div> ... </div>`  

---  

2. __La balise ***\<nav>***__  

    - Délimite la partie de la page dans laquelle nous allons pouvoir trouver les liens qui conduisent les autres pages du site web. Il s’agit de la balise de navigation où l’on pourra retrouver le menu principal du site  

      - `<nav> ... </nav>`  

---  

3. __La balise ***\<header>***__  

    - Dans le ***\<header>***, se compose généralement du titre, d’un texte d’introduction ou encore une bannière, c’est ici que vous placerez les éléments qui permettront d’identifier la thématique de votre page web.  

      - `<header> ... </header>`  

---  

4. __La balise ***\<footer>***__  

    - Dans le pied page ***\<footer>*** on retrouvera le menu de bas de page, les pages légales et les informations relatives aux droits d’auteur, sera intégré dans la balise  

      - `<footer> ... </footer>`  

---  

5. __La balise ***\<section>***__  

    - La balise ***\<section>*** est utiliser pour regrouper les éléments d’une même thématique dans un conteneur dédié, elle permet de découper le contenu par thématique pour mieux organiser le contenu sur la page  
      
      - `<section> ... </section>`  

---  

6. __La balise ***\<article>***__  

    - La balise ***\<article>*** est utilisée pour délimiter une section dont le contenu est autonome, comme des articles de blog, des produits ou encore des commentaires  

      - `<article> ... </article>`  

---  

7. __La balise ***\<aside>***__  

    - la balise ***\<aside>*** sert à définir un contenu « à côté » d’un contenu principal. Ce contenu à part est souvent lié de manière indirecte au contenu principal. On l’utilise pour les encarts publicitaires ou encore les articles connexes  

      - `<aside> ... </aside>`  

---  
---  
---  

## ***__Organiser son texte__***  

1. __Les balises ***\<h1> à \<h6>***__  

    - Il existe plusieurs niveaux de balises de titres, allant du ***\<h1>*** jusqu'au ***\<h6>***. Les balises ont des tailles et des styles de police différents, ce qui permet de les différencier visuellement. Ainsi, le titre principal de la page est inséré dans la balise ***\<h1>***, tandis que les balises ***\<h2>*** à ***\<h6>*** sont utilisées pour les sous-titres  

---

2. __La balise ***\<p>***__  

    - Les balises ***\<p>*** sont utilisées en HTML pour délimiter un paragraphe de texte, elle permet d'ajouter des sauts de ligne entre les différents paragraphes  

      - `<h1> ... </h1>`
      - `<h2> ... </h2>`
      - `<h3> ... </h3>`
      - `<h4> ... </h4>`
      - `<h5> ... </h5>`
      - `<h6> ... </h6>`

---

3. __Les balises ***\<ul> et \<ol>***__  

    - La balise ***\<ul>*** permet de créer une liste d'éléments sans ordre particulier. Chaque item est précédé d'un point (ou autre symbole), et il n'y a pas de numérotation. Ce type de liste est idéal pour présenter des informations qui ne sont pas liées entre elles  

      - `<ul> ... </ul>`

    - la balise ***\<ol>*** permet de créer une liste ordonnée, où chaque item est numéroté. Cette liste est très utile pour présenter des informations qui ont un ordre ou une hiérarchie, comme les étapes d'un processus  

      - `<ol> ... </ol>`

      > Ces éléments apportent une structure visuelle à l'information, ce qui est crucial pour la lisibilité de la page  

      > Il est possible d'ajouter des sous-listes à l'intérieur d'une liste principale. Pour cela, il faut ajouter une liste imbriquée dans une autre liste, qui sera alors indentée et affichée avec un symbole différent  

    - Les balises ***\<li>***, il est également important de noter que, à l'intérieur de ces deux balises, chaque élément de la liste est inscrit dans une balise ***\<li>***

        - Exemple avec la balise ***\<ul>***  

          ```  
          <ul>  
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
          </ol>  
          ```  

---

4. __Les balises block et les balises inline__  

    - une balise block est une balise qui crée un nouveau bloc de contenu sur la page web. Cela signifie que tout le contenu compris entre la balise d'ouverture et la balise de fermeture sera affiché comme un bloc distinct  

    - Les exemples les plus courants de balises block incluent les balises ***\<div>***, ***\<p>***, ***\<ul>***, ***\<ol>***, ***\<h1>*** à ***\<h6>*** et ***\<blockquote>***  

    - Les balises inline sont souvent utilisées pour formater le texte ou pour ajouter des éléments en ligne, tels que des liens hypertextes, des images ou des boutons. Les exemples les plus courants de balises inline incluent les balises ***\<a>***, ***\<img>***, ***\<span>*** et ***\<button>***  

---

5. __Le formatage du texte__  

    > Lors de la création d'une page web, il est important de considérer la mise en forme du texte pour une présentation visuellement attrayante et facile à lire. Le HTML offre plusieurs balises qui permettent de mettre en évidence certains mots ou certaines phrases sans avoir recours à un fichier CSS  

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

En cours ...