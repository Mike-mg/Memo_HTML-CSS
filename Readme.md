# Memo HTML-CSS

## ***__Introduction__***  

### Qu’est-ce que le HTML ?  

- Le HTML ( HyperText Markup Language ), est utilisé pour mettre en page une site web  

---  

### Le W3C  

- Le W3C ( Wolrd wide Web Consortium ), est l’organisme chargé de la standardisation et de la compatibilité des technologies du web  

  - [Site du W3C](https://www.w3.org/)  

---  

### Le HTML coté client  

- Le « côté client » couvre toutes les opérations effectuées par une application ou un site web au sein d’un navigateur  

- Le langage HTML est donc un langage « côté client ». C’est le navigateur de l’utilisateur qui interprète le HTML  

- Les pages d’un site web sont transmises sous forme de code HTML brut au navigateur, qui va l’interpréter pour afficher son contenu sur l’écran  

- Cette partie du développement d’un site web est appelée « développement frontend », faisant référence à la partie création de l’interface utilisateur, au côté visuel d’un site ou d’une application web. HTML sert à définir la structure et l’organisation des pages  

---  
---  
---  

## ***__La syntaxe minimal__***  

### La syntaxe minimal du code HTML  

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
### Desciption de la syntaxe des balises HTML minimal  

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

### __La balise ***\<div>***__  

- La balise ***\<div>*** est la balise la plus couramment utilisée pour placer du contenu sur une page web, elle va permettre de diviser la page web en différents espaces et donc de la structurer de manière organisée  
  - `<div> ... </div>`  

### __La balise ***\<nav>***__  

- Délimite la partie de la page dans laquelle nous allons pouvoir trouver les liens qui conduisent les autres pages du site web. Il s’agit de la balise de navigation où l’on pourra retrouver le menu principal du site  

  - `<nav> ... </nav>`  

### __La balise ***\<header>***__  

- Dans le ***\<header>***, se compose généralement du titre, d’un texte d’introduction ou encore une bannière, c’est ici que vous placerez les éléments qui permettront d’identifier la thématique de votre page web.  

  - `<header> ... </header>`  

### __La balise ***\<footer>***__  

- Dans le pied page ***\<footer>*** on retrouvera le menu de bas de page, les pages légales et les informations relatives aux droits d’auteur, sera intégré dans la balise  
  - `<footer> ... </footer>`  

### __La balise ***\<section>***__  
- La balise ***\<section>*** est utiliser pour regrouper les éléments d’une même thématique dans un conteneur dédié, elle permet de découper le contenu par thématique pour mieux organiser le contenu sur la page  
  
  - `<section> ... </section>`  

### __La balise ***\<article>***__  

- La balise ***\<article>*** est utilisée pour délimiter une section dont le contenu est autonome, comme des articles de blog, des produits ou encore des commentaires  

  - `<article> ... </article>`  

### __La balise ***\<aside>***__  
- la balise ***\<aside>*** sert à définir un contenu « à côté » d’un contenu principal. Ce contenu à part est souvent lié de manière indirecte au contenu principal. On l’utilise pour les encarts publicitaires ou encore les articles connexes  

  - `<aside> ... </aside>`  

---  
---  
---  

## ***__Organiser son texte__***

### __Le texte__

En cours ...