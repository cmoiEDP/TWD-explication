## Où est le HTML

Le HTML peut etre trouver ici dans le index.html a la racine :

```javascript
// de ici
switch (page) {
      case "landing-page":
        mainPanel.innerHTML = 
// code html
break;
```
cas n2
```javascript
case "nom de la page"
// code html
break;
```

## JavaScript
``` javascript
    const params = new URLSearchParams(window.location.search);
    const page = params.get("page") || "landing-page";
    const mainPanel = document.querySelector(".main_panel");
```

recupere les parametre de l'argument page et affiche la page corespondante, permetant l'utilisation de plusieur page html en une seule 
