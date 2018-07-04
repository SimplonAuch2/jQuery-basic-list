# jquery-basic-list

Vous devez utilisez la librairie jQuery et Bootstrap:

http://api.jquery.com/
https://getbootstrap.com/

### 1. Afficher les données ci-dessus sous forme de liste dans une page *HTML*.



```javascript
var books = [
{
  title: 'CSS: The Definitive Guide',
  author: 'Eric Meyer',
  link: 'http://shop.oreilly.com/product/0636920012726.do',
  type: 'css'
},
{
  title: 'CSS Development with CSS3',
  author: 'Zachary Kingston',
  link: 'http://shop.oreilly.com/product/0636920057970.do',
  type: 'css'
},
{
  title: 'You Don\'t Know JS: Up & Going',
  author: 'Kyle Simpson',
  link: 'http://shop.oreilly.com/product/0636920039303.do',
  type: 'js'
},
{
  title: 'Programming JavaScript Applications',
  author: 'Eric Elliott',
  link: 'http://shop.oreilly.com/product/0636920033141.do',
  type: 'js'
},
{
  title: 'Modern JavaScript',
  author: 'unknown',
  link: 'http://www.oreilly.com/web-platform/free/modern-javascript.csp',
  type: 'js'
}
] ;
```


### 2. Ajouter 2 boutons intitulés JS et CSS dans la page *HTML* qui permettent de filtrer, respectivement, les livres de type *CSS* et *JS*.

### 3. Transformer la ```var books``` en fichier *JSON* et utiliser *Ajax* pour afficher les données.

Exemple de synthaxe *Ajax*


```
$.ajax({
    url:'cheminJSON',
	data: {
		task: 'get',
	}

}).done(function() {

    alert( "success" );

}).fail(function() {

    alert( "error" );

}).always(function() {

    alert( "complete" );

});
```
