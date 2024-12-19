## Désolé madame, mais j'ai séparé mon code donc je vous envoie directement le lien de mon github


## J'ai ajouté deux commandes le package.json pour aller plus vite

```json
"scripts": {
    "sass": "sass assets/css/style.scss style.css --watch",
    "build": "sass assets/css/style.scss style.css --style compressed"
},
```


### La première sert pour que à chaque fois qu'on modifie le scss , ca recompile automatiquement le fichier style.css, il faudra donc faire :

```
npm run sass
```

### La deuxième sert pour que à chaque fois qu'on modifie le scss , ca recompile automatiquement le fichier style.css en version compressée, il faudra donc faire :

```
npm run build
```