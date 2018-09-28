# Becode - Animation Css

Réalisation de différents exercices pour apprendre l'**animation en CSS3.**

## Ex.1 | Drill

![Gif of drill](https://github.com/JustineCrenier/becode-animation-css/blob/master/Img/drill.gif)

Animation avec les transitions

```CSS
a:hover{
	transition: all 0.3s ease;
}
```

## Ex.2 | Menu animé

![Gif of menu](https://github.com/JustineCrenier/becode-animation-css/blob/master/Img/menu.gif)

Utilisation des transitions pour créer un menu animé avec la propriété transform.

```CSS
a:hover{
	transform: translateX(0);
	transition: all 0.3s ease;
}
```

## Ex.3 | Star Wars Crawl

[Star Wars Crawl](https://justinecrenier.github.io/Star-Wars-Crawl/)

Utilisation des keyframes.

```CSS
@keyframes crawl{
	0% {
		opacity: 1;
		transform: translate(-50%,-50%) perspective(300px) rotateX(25deg) scale3d(3,3,3) translate3d(0px, 720px, 0px);
	}
	90% {
		opacity: 1;
	}
	100% {
		opacity: 0;
		transform: translate(-50%,-50%) perspective(300px) rotateX(25deg) scale3d(3,3,3) translate3d(0px, -500px, 0px);
	}
}
```

## Ex.4 | Carte animée

![Gif of card](https://github.com/JustineCrenier/becode-animation-css/blob/master/Img/carte.gif)

Mise en pratique des transition et transform pour créer une animation sur une preview d'article.