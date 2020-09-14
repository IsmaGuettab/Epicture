
Créer 3 components  :
a
1 component Title
1 component Form
1 component Weather

Dans le component title , créer une class Title qui  va uniquement afficher 2 titre d'accroche pour votre appli.
Dans le component Form, On va créer deux champs et un boutton (un formulaire quoi) un champ avec le nom City et un autre champ avec le nom Country.

Dans le fichier App.js on aura la classe principale, c'est ici que l'on fera tout nos appels de des différents component.

Dans ce même fichier, créer un state qui va  contenir les différentes variables que nous voulons rechercher dans l'API. (ici Temperature, Humidity ,ville, pays, Condiditions)
les variables auront pour valeurs par défaut undefined.

Créer une méthode GetWeather avec async qui va nous permettre de récupérer ce qu'on a mis dans les champs, faire notre appel APi etc..
Elle prend en paramètre une variable Event. 

Récuperer ce qu'on a tapé dans les champs dans des variables.

Faire notre appel API avec Fetch (vous utiliserez Axios de votre côté.) Await
Mettre le tout en JSON avec .json() 

Mettre le tout dans le state grâce à setState.

Grâce à la méthode Render Appelez dans l'ordre les component Title Form et Weather.

Dans les balises des différents appels de component, mettre les attributs ou méthode  à utiliser.
Pour <Form> mettre dedans [Nom de méthode] => [Nom qu'elle aura dans le component "vue"]
Dans la balise weather mettre votre state en paramètre c'est à dire : [Le state] => [Le nom qu'il aura dans le component météo]

Maintenant à vous d'utiliser les props dans vos component.

appli finie.
