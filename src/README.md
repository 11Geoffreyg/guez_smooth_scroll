ici se trouvent les fichiers sass qui seront importes dans le style.sass en ecrivant @import "partials/variables" (sans _ ni extention)

ligne de commande pour la compilation:
se placer dans le dossier test
écire sass --watch src:www

src = dossier de source
www = dossier d'origine 

Les fonctions de mixins sont créées avec = et appellées avec +

Pour étendre une class on ecrit @extend %nomDeLaClasse

& est un selecteur de parent

Pour compresser le css 

ligne de commande : sass --watch src:www --style compressed