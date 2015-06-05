![](https://cloud.githubusercontent.com/assets/110953/7877439/6a69d03e-0590-11e5-9fac-c614246606de.png) 
## Polymer & Firebase


## Instalación

`` npm install && bower install ``

Abre una cuenta en [Firebase](https://www.firebase.com/) 

Crea una nueva APP. ejemplo: `` <your-app-name>.firebaseio.com `` 

Dentro de la APP de Firebase busca la opción de **Login & Auth**, posterior busca la pestaña de **GitHub**

Te pedirá crees una APP dentro de [GitHub](https://github.com/settings/applications), busca la pestaña con el nombre **Developer Application** y posterior crear una APP en GitHub.

1. **Application Name** coloca el nombre de tu nueva APP
2. **Homepage URL** coloca el nombre de tu APP en Firebase, `` <your-app>.firebaseio.com ``
3. **Authorization callback URL** coloca el callback de tu APP en Firebase, `` https://auth.firebase.com/v2/<your-app>/auth/github/callback ``

Toma el **Client ID** y el **Client Secret** que se genera al crear tu APP en GitHub.

Los copias y pegas dentro de tu APP en Firebase

Dentro del proyecto de Polymer-Firebase, dirigite a **/elements/app.html** e introduce el nombre de tu APP Firebase.

`` this.globals.firebase = <your-app>; ``

Finalizar usa [Gulp](http://gulpjs.com/)

`` gulp serve ``

Siguiendo estos simples paso el proyecto funcionará. Cualquier duda puedes contactarme. 
