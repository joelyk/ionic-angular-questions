# ionic-angular-questions

### Questions sur Ionic

1. **Qu'est-ce que Ionic ?**
   - Ionic est un framework open-source utilisé pour développer des applications mobiles hybrides en utilisant des technologies web comme HTML, CSS et JavaScript.

2. **Quels sont les principaux avantages d'utiliser Ionic ?**
   - Réutilisation du code : un même code pour Android, iOS et le web.
   - Accès aux fonctionnalités natives des appareils via des plugins.
   - Une grande communauté et de nombreuses ressources disponibles.

3. **Quelle est la commande pour créer un nouveau projet Ionic ?**
   - `ionic start myApp blank`

4. **Comment lancer une application Ionic dans un navigateur pour le développement ?**
   - `ionic serve`

### Questions sur Angular

1. **Qu'est-ce qu'Angular ?**
   - Angular est un framework open-source développé par Google pour créer des applications web dynamiques en utilisant TypeScript.

2. **Quels sont les principaux concepts d'Angular ?**
   - Composants, Services, Modules, Directives, Pipes, Routage.

3. **Quelle est la commande pour générer un nouveau composant Angular ?**
   - `ng generate component nom-du-composant` ou `ng g c nom-du-composant`

4. **Comment lancer une application Angular en mode développement ?**
   - `ng serve`

### Questions sur Cordova

1. **Qu'est-ce que Cordova ?**
   - Apache Cordova est une plateforme permettant de construire des applications mobiles en utilisant des technologies web standard et d'accéder aux fonctionnalités natives des appareils via des plugins.

2. **Quelle est la commande pour ajouter une plateforme (par exemple, Android) à un projet Cordova ?**
   - `cordova platform add android`

3. **Comment lancer une application Cordova sur un appareil ou un émulateur Android ?**
   - `cordova run android`

4. **Quelle est la commande pour installer un plugin Cordova (par exemple, le plugin caméra) ?**
   - `cordova plugin add cordova-plugin-camera`

### Questions sur Capacitor

1. **Qu'est-ce que Capacitor ?**
   - Capacitor est un outil moderne de création de ponts entre le code web et les fonctionnalités natives des appareils, créé par l'équipe derrière Ionic.

2. **Quelle est la différence principale entre Cordova et Capacitor ?**
   - Capacitor est conçu pour être plus moderne et offre une meilleure intégration avec les applications web modernes et les Progressive Web Apps (PWAs), tandis que Cordova est plus ancien et a une approche plus traditionnelle.

3. **Quelle est la commande pour ajouter une plateforme (par exemple, Android) dans Capacitor ?**
   - `npx cap add android`

4. **Comment synchroniser les changements dans le code web avec le projet natif en utilisant Capacitor ?**
   - `npx cap sync`

### Questions de vérification de commandes spécifiques

1. **Quelle commande utiliseriez-vous pour construire une application Ionic pour la production ?**
   - `ionic build --prod`

2. **Comment ajouter un plugin Cordova spécifique dans un projet Ionic ?**
   - `ionic cordova plugin add nom-du-plugin`

3. **Quelle commande permet de mettre à jour les dépendances d’un projet Angular ?**
   - `ng update`

4. **Quelle est la commande pour ouvrir l'application Capacitor dans Android Studio ?**
   - `npx cap open android`


### Questions supplementaires sur Ionic

1. **Qu'est-ce que Ionic ?**
   - Ionic est un framework open-source utilisé pour développer des applications mobiles hybrides en utilisant des technologies web comme HTML, CSS et JavaScript.

2. **Quels sont les principaux avantages d'utiliser Ionic ?**
   - Réutilisation du code : un même code pour Android, iOS et le web.
   - Accès aux fonctionnalités natives des appareils via des plugins.
   - Une grande communauté et de nombreuses ressources disponibles.

3. **Quelle est la commande pour créer un nouveau projet Ionic ?**
   - `ionic start myApp blank`

4. **Comment lancer une application Ionic dans un navigateur pour le développement ?**
   - `ionic serve`

5. **Quels sont les principaux composants UI fournis par Ionic ?**
   - Boutons (Buttons), Listes (Lists), Cartes (Cards), Modals, Popovers, Sliders, et Tabs.

6. **Comment ajouter une plateforme (par exemple, Android) à un projet Ionic avec Capacitor ?**
   - `ionic capacitor add android`

7. **Quelle est la commande pour générer une nouvelle page dans un projet Ionic Angular ?**
   - `ionic generate page nom-de-la-page` ou `ionic g page nom-de-la-page`

8. **Comment lancer une application Ionic sur un appareil ou un émulateur Android ?**
   - `ionic capacitor run android`

9. **Quelle commande utiliseriez-vous pour construire une application Ionic pour la production ?**
   - `ionic build --prod`

10. **Comment ajouter un plugin Cordova spécifique dans un projet Ionic ?**
    - `ionic cordova plugin add nom-du-plugin`

11. **Quelle est la commande pour ouvrir l'application Ionic dans Android Studio en utilisant Capacitor ?**
    - `ionic capacitor open android`

12. **Qu'est-ce qu'Ionic Storage et pourquoi est-il utilisé ?**
    - Ionic Storage est une solution de stockage clé-valeur facile à utiliser pour les applications Ionic, permettant de stocker des données localement sur l'appareil de l'utilisateur.

13. **Comment installer Ionic CLI (Command Line Interface) globalement sur votre machine ?**
    - `npm install -g @ionic/cli`

14. **Quelle commande permet de voir toutes les informations sur le projet Ionic actuel, comme les dépendances et les versions des plateformes ?**
    - `ionic info`

15. **Comment intégrer Ionic avec une API REST ?**
    - Utiliser le service HttpClient d'Angular pour faire des requêtes HTTP vers l'API REST et manipuler les données dans l'application.

16. **Comment utiliser un thème personnalisé dans un projet Ionic ?**
    - Modifier le fichier `variables.scss` pour définir des variables CSS personnalisées, puis appliquer ces variables à vos composants Ionic.

17. **Quelle commande permet de déployer une application Ionic sur le web ?**
    - `ionic build --prod` suivi de `npx cap copy` et `npx cap sync`

18. **Quels sont les outils et services complémentaires fournis par Ionic ?**
    - Ionic Appflow (CI/CD), Ionic Studio (IDE), Capacitor (accès aux API natives), et PWA Toolkit.

19. **Comment gérer la navigation entre les pages dans une application Ionic ?**
    - Utiliser le module de routage d'Angular (`RouterModule`) et configurer les routes dans `app-routing.module.ts`.

20. **Quelle est la différence entre Ionic et Cordova ?**
    - Ionic est un framework pour développer des applications mobiles hybrides avec des composants UI et des outils modernes, tandis que Cordova est une plateforme permettant d'accéder aux fonctionnalités natives des appareils via des plugins. Ionic peut utiliser Cordova ou Capacitor pour accéder aux fonctionnalités natives.

---------------------------------
Bien sûr, voici les questions et réponses en français.

### 1. Qu'est-ce que le Framework Ionic ?
Ionic est un framework HTML5 qui permet aux développeurs web de créer des applications mobiles hybrides. Les applications hybrides sont des mini-pages web qui fonctionnent dans une enveloppe web au sein des applications et ont accès aux performances natives de l'appareil.

C'est un SDK HTML5 robuste pour créer des applications mobiles en utilisant HTML, CSS et JavaScript. Le framework Ionic se concentre sur l'esthétique du design de l'application et l'interactivité de l'interface utilisateur. Ionic est idéal pour le front-end de votre application. Il est disponible sous une licence MIT et peut être utilisé à des fins personnelles et commerciales.

### 2. Quelle est la différence entre PhoneGap, Cordova et Ionic ?
- **Cordova** : Cordova est un framework JavaScript pour créer des applications qui interagissent avec le matériel de l'appareil. Cordova ne peut pas créer d'interactivité UI pour les applications mobiles car il repose sur HTML5, CSS6 et Sencha. Cependant, il fonctionne en conjonction avec d'autres technologies web utilisées pour créer des applications mobiles. Apache Cordova est un autre nom pour Cordova.
- **PhoneGap** : PhoneGap est une technologie développée par Adobe Systems. Elle peut être utilisée pour construire des applications mobiles par toute personne ayant des connaissances de base en CSS, HTML et JavaScript. PhoneGap est une version modifiée d'Apache Cordova qui ajoute des fonctionnalités supplémentaires au framework de base Cordova.
- **Ionic** : Le framework Ionic est utilisé pour créer des applications mobiles multiplateformes en utilisant des technologies web comme CSS et HTML. Il a été publié en 2013 et est basé sur AngularJS et Apache Cordova.

### 3. Qui a développé le framework Ionic ?
Le framework Ionic a été développé par Max Lynch, Ben Sperry et Adam Bradley pour Drifty Co. en 2013.

### 4. Quelle est la différence entre la polymérisation ionique et la polymérisation par radicaux libres ?
- **Polymérisation ionique** : C'est une polymérisation en chaîne où le centre contient des ions et des paires d'ions. Elle nécessite moins d'énergie d'activation que la polymérisation radicalaire.
- **Polymérisation par radicaux libres** : Les polymérisations créées par l'ajout de composants de construction à radicaux libres sont connues sous le nom de polymérisations par radicaux libres. Les initiateurs et co-initiators sont utilisés dans la polymérisation radicalaire. C'est la seule méthode pour obtenir des polymères et des matériaux composites divers.

### 5. Listez quelques applications populaires créées avec le framework Ionic ?
Voici une liste de quelques applications créées avec le framework Ionic :
- Pacifica : Thérapie comportementale cognitive
- TD Trading : Application de trading d'actions
- Sworkit : Plan d'entraînement et de fitness
- MarketWatch : Actualités sur la bourse et les affaires
- ChefSteps : Tutoriels et outils de cuisine
- Nationwide : Services d'assurance et financiers
- JustWatch : Moteur de recherche de streaming
- Untappd : Réseau social de découverte et d'enregistrement
- National Museum of African American History and Culture : Musée national d'histoire et de culture afro-américaine
- Crypto change : Suivi des crypto-monnaies

### 6. Comment utiliser les services/fournisseurs dans Ionic ?
Dans le framework Ionic, les services sont essentiels car ils fournissent des informations à notre application et nous aident dans diverses tâches. Le framework Ionic inclut des protocoles comme le moniteur de connectivité, les alertes simples, les données, Google Maps, et d'autres. Lors de la conception d'un service, il est important de :
1. Importer le service.
2. Ajouter un fournisseur.
3. L'injecter dans la classe.

Il est nécessaire d'importer les services dans les classes qui les utiliseront. Lorsqu'un service est injecté, il ajoute une nouvelle variable membre qui peut être accédée partout dans la classe.

### 7. Combien de types de stockage sont disponibles dans le framework Ionic ?
Le stockage dans le framework Ionic est une façon simple de stocker des clés, des valeurs et des objets JSON. Différents types de moteurs sont utilisés dans ce stockage. Le stockage pour les applications web sera probablement IndexedDB, WebSQL et le stockage local. Le framework Ionic offre diverses options de stockage, dont certaines sont :
- Stockage local HTML5
- Stockage de cookies et de sessions
- IndexedDB
- WebSQL
- PouchDB
- Stockage de service Web/API
- Stockage Cordova.

### 8. Listez quelques avantages et inconvénients du framework Ionic ?
**Avantages du framework Ionic** :
- Facile à apprendre
- Documentation simple
- Basé sur AngularJS
- Interface utilisateur
- Multiplateforme

**Inconvénients du framework Ionic** :
- Performances
- Sécurité
- Risque pour les premiers utilisateurs
- Pas adapté aux jeux vidéo
- Fonctionnalité native limitée

### 9. Quelles sont les nouvelles fonctionnalités incluses dans Ionic 2 ?
Le framework Ionic 2 est supérieur au framework Ionic 1 pour plusieurs raisons. Voici quelques-unes des fonctionnalités incluses dans la création du framework Ionic 2 :
- Contrairement à Ionic 1 qui utilise des contrôleurs, le framework Ionic 2 utilise des classes.
- Chaque composant dans Ionic 2 a son propre dossier et fichier de classe.
- Les pages, les fournisseurs, les onglets, les pipelines, les composants et les directives peuvent tous être créés automatiquement avec Ionic 2.
- La navigation adopte une approche beaucoup plus native.
- Ionic 2 n'est rien d'autre que du JavaScript ordinaire.

### 10. Qu'est-ce que l'Ionic CLI ?
Le CLI original d'Ionic, ou interface en ligne de commande, est un outil essentiel pour le développement d'applications Ionic. Il combine une variété d'outils dans un tableau de bord unifié. Démarrer, créer, publier et exécuter sont quelques-unes des fonctions essentielles pour le développement Ionic. Il a également des fonctions comme l'émulation d'informations, utiles dans certaines circonstances. Il est en charge des constructions et des déploiements dans le cloud, ainsi que de la gestion de votre abonnement Ionic Pro.

Voici les questions et réponses en français, bien traduites et révisées :

### 11. Quelles sont les fonctionnalités du Framework Ionic ?

Les fonctionnalités suivantes sont offertes par le Framework Ionic :

- **Multiplateforme** : Avec une seule base de code, l'application peut être déployée sur plusieurs appareils, notamment Android, iOS natif, les ordinateurs de bureau et le web en tant qu'application web dynamique. En conséquence, les applications Ionic peuvent être créées une fois mais exécutées partout.
- **Basé sur les standards web** : Le framework Ionic est construit avec des API web modernes et est fourni avec des applications web conformes aux normes de l'industrie, notamment HTML, CSS et JavaScript (comme les éléments personnalisés et le Shadow DOM). Par conséquent, les éléments Ionic ont une API standardisée, permettant aux applications Ionic de fonctionner sur diverses plateformes.
- **Aide à créer de beaux designs** : En utilisant le framework Ionic, les utilisateurs peuvent construire une application claire, simple et efficace. L'application Ionic dispose d'éléments prédéfinis, de typographies, de paradigmes intrigants et d'un design de base magnifique.
- **Plugin Cordova** : Il offre une API JavaScript pour accéder aux fonctionnalités natives de l'appareil.
- **Licence** : Le Framework Ionic est un projet ouvert et accessible avec une licence MIT. Cela signifie qu'il peut être utilisé à des fins personnelles et commerciales sans frais.
- **Ionic CLI** : L'interface de ligne de commande Ionic, ou Command Line Interface, est un service qui fournit une variété de commandes utiles aux concepteurs Ionic. Elle permet de démarrer, développer, exécuter et émuler des applications Ionic.
- **Compatibilité du framework** : Angular était étroitement lié aux éditions précédentes d'Ionic. Ionic v4 a été réorganisé pour fonctionner comme une bibliothèque web indépendante avec prise en charge des frameworks JavaScript les plus modernes. Il fonctionne également avec la majorité des frameworks front-end.
- **Composants JavaScript** : Il combine les capacités de JavaScript avec les éléments CSS pour garantir que tous les aspects du mobile que HTML et CSS seuls ne peuvent pas gérer sont couverts.
- **Angular** : La popularité du framework Ionic peut être attribuée à Angular. Bien que les éléments de base puissent être utilisés seuls, le pack Angular facilite l'intégration avec l'environnement Angular. Le pack Angular contient toutes les fonctionnalités attendues par les concepteurs Angular, ainsi qu'une intégration avec les bibliothèques principales d'Angular.

### 2.Est-il possible d'utiliser Firebase avec le framework Ionic ?

Oui, il est possible d'utiliser Firebase avec le framework Ionic. Firebase fournit une suite de services backend qui peuvent être facilement intégrés dans les applications Ionic pour ajouter des fonctionnalités comme l'authentification, la base de données en temps réel, le stockage, les notifications push, et bien plus encore.

Voici les étapes générales pour intégrer Firebase dans une application Ionic :

a. **Créer un projet Firebase** :
   - Accédez à la console Firebase.
   - Créez un nouveau projet ou utilisez un projet existant.

b. **Ajouter Firebase à votre application Ionic** :
   - Dans la console Firebase, ajoutez une nouvelle application (web) et suivez les instructions pour obtenir la configuration Firebase (code de configuration avec apiKey, authDomain, etc.).

c. **Installer Firebase et AngularFire** :
   - AngularFire est la bibliothèque officielle Angular pour Firebase.
   - Exécutez les commandes suivantes pour installer Firebase et AngularFire dans votre projet Ionic :
     ```
     npm install firebase @angular/fire
     ```

d. **Configurer Firebase dans votre application Ionic** :
   - Ajoutez la configuration Firebase dans votre module Angular principal (souvent `app.module.ts`).
   - Importez les modules nécessaires et configurez-les avec vos informations de configuration Firebase :
     ```
     import { NgModule } from '@angular/core';
     import { BrowserModule } from '@angular/platform-browser';
     import { IonicModule, IonicRouteStrategy } from '@ionic/angular';
     import { RouteReuseStrategy } from '@angular/router';
     import { AppComponent } from './app.component';
     import { AppRoutingModule } from './app-routing.module';
     import { AngularFireModule } from '@angular/fire';
     import { AngularFireAuthModule } from '@angular/fire/auth';
     import { AngularFirestoreModule } from '@angular/fire/firestore';
     import { environment } from '../environments/environment';

     @NgModule({
       declarations: [AppComponent],
       entryComponents: [],
       imports: [
         BrowserModule,
         IonicModule.forRoot(),
         AppRoutingModule,
         AngularFireModule.initializeApp(environment.firebase),
         AngularFireAuthModule,
         AngularFirestoreModule,
       ],
       providers: [{ provide: RouteReuseStrategy, useClass: IonicRouteStrategy }],
       bootstrap: [AppComponent],
     })
     export class AppModule {}
     ```

5. **Utiliser les services Firebase dans votre application** :
   - Par exemple, pour l'authentification, vous pouvez injecter `AngularFireAuth` dans vos composants ou services et utiliser ses méthodes pour enregistrer, connecter et gérer les utilisateurs.
     ```
     import { Component } from '@angular/core';
     import { AngularFireAuth } from '@angular/fire/auth';
     import firebase from 'firebase/app';

     @Component({
       selector: 'app-login',
       templateUrl: './login.component.html',
       styleUrls: ['./login.component.scss'],
     })
     export class LoginComponent {
       constructor(public auth: AngularFireAuth) {}

       login() {
         this.auth.signInWithPopup(new firebase.auth.GoogleAuthProvider());
       }

       logout() {
         this.auth.signOut();
       }
     }
     ```

Ainsi je peux dire : En utilisant Firebase avec le framework Ionic, vous pouvez rapidement ajouter des fonctionnalités puissantes à votre application sans avoir à gérer une infrastructure backend complexe. Firebase et Ionic fonctionnent bien ensemble et permettent de créer des applications robustes et évolutives.

### 3. Quelles sont les applications natives, hybrides et web mobiles ?

- **Applications natives** : Les applications natives sont conçues pour des appareils spécifiques, comme les smartphones et les tablettes. Elles peuvent être téléchargées et installées directement sur l'appareil via une boutique d'applications. Elles sont toujours présentes sur le téléphone et peuvent être accessibles via des raccourcis sur l'écran d'accueil. Ces applications peuvent être utilisées hors ligne et tirent parti du système de notifications de l'appareil. Quelques exemples incluent la caméra, Collage-Maker, Google Maps, Facebook et d'autres applications natives bien connues.
- **Applications web mobiles** : Ce sont des applications activées par Internet avec des caractéristiques spécifiques aux mobiles. Les applications web mobiles sont accessibles via des navigateurs web mobiles. Elles n'ont pas besoin d'être téléchargées ou installées sur votre appareil.
- **Applications hybrides** : Ce sont des applications qui combinent des fonctionnalités des applications natives et web. Elles peuvent être installées sur un smartphone comme toute autre application. Elles sont comparables aux applications natives en ce sens qu'elles sont créées en utilisant des technologies web comme HTML, CSS et JavaScript. Elles sont populaires car elles permettent aux développeurs d'écrire une seule base de code pour une application mobile et de la distribuer sur plusieurs plateformes.

### 4. Comment pouvez-vous tester vos applications Ionic ?

Les applications Ionic v1 sont conçues avec AngularJS. Deux des nombreux frameworks et bibliothèques de test disponibles avec Angular sont Jasmine et le pilote de test Karma. Ces frameworks peuvent être utilisés pour créer une suite de tests pour les applications Ionic. Les applications Ionic peuvent être évaluées de quatre manières : sur un site WebKit sur un PC, dans un émulateur iOS ou Android, dans un site Web Chrome sur votre mobile ou en tant qu'application native sur votre téléphone.

Ionic-CLI inclut également une fonctionnalité de rechargement continu qui permet aux utilisateurs de tester leur application sur la page Web. Par exemple, la ligne de commande ionic est utilisée pour exécuter l'application sur presque n'importe quel site Web. Nous pouvons utiliser les outils de développement Chrome ou Mozilla Firefox avec Firebug pour déboguer et explorer les applications Ionic.

### 5. ### Quels sont les différents événements du cycle de vie des pages dans Ionic ?

Ionic utilise les événements du cycle de vie d'Angular. Voici les événements du cycle de vie :

- **ngOnInit** : C'est un événement unique qui se produit lors de la configuration du composant. Il peut être utilisé pour créer des membres locaux et effectuer des appels de service ponctuels.
- **ngOnDestroy** : Cet événement est déclenché juste avant qu'Angular ne détruise la vue. Il est utile pour des tâches comme le nettoyage et la désinscription des observables.
- **ionViewWillEnter** : Cet événement est appelé lorsque le composant qui est en cours de routage va être animé pour apparaître à l'écran.
- **ionViewDidEnter** : Cet événement est déclenché lorsque le composant qui est en cours de routage a terminé son animation.
- **ionViewWillLeave** : Cet événement est déclenché lorsque le composant en cours de routage va être animé pour quitter l'écran.
- **ionViewDidLeave** : Cet événement est déclenché lorsque le composant qui est en cours de routage a terminé son animation.

### Divers événements du cycle de vie des pages

Il existe quelques autres événements du cycle de vie qui permettent d'empêcher les utilisateurs d'accéder indésirablement à certaines pages.

- **ionViewCanEnter** : Il est appelé avant d'accéder à une vue et permet de contrôler si l'utilisateur peut accéder à la vue.
- **ionViewCanLeave** : Cette fonctionnalité est activée avant qu'un utilisateur puisse quitter une vue, permettant de décider si la vue peut être quittée ou non.

  
### 6. Qu'est-ce qu'une WebView ?

Les applications Ionic utilisent les standards web, y compris HTML, CSS et JavaScript. Ces applications web sont rendues en utilisant des Web Views, qui sont des navigateurs web plein écran et haute performance.

Dans la vue web actuelle, il y a plusieurs API HTML5 intégrées pour les fonctionnalités matérielles, telles qu'une caméra, Bluetooth, la géolocalisation, les systèmes de capteurs et l'audio. Parfois, il peut également nécessiter l'accès à des API spécifiques à la plateforme. Les API matérielles peuvent être atteintes via une couche de pont dans le framework Ionic, ce qui est souvent réalisé en utilisant des plugins originaux qui exposent des API JavaScript.

### 17. Qu'est-ce que l'élément <ion-app> ?

L'élément <ion-app> est utilisé pour contenir toute l'application Ionic. Il ne doit y avoir qu'un seul élément <ion-app> et divers éléments Ionic tels que les en-têtes, les pieds de page, les menus, le contenu, etc., doivent être inclus dans le projet Ionic. Chacun de ces éléments est enveloppé dans le composant <ion-app> lorsqu'il est affiché.

**Exemple :**

```
<ion-app>
  <ion-header>
    //code
  </ion-header>
  <ion-content>
    //code
  </ion-content

>
</ion-app>
```

### 8. Expliquez un composant ion-grid

Le système de grille Ionic est un système de flexbox mobile qui peut être utilisé pour personnaliser une mise en page. Une grille, des rangées et des colonnes sont les trois aspects principaux de la grille Ionic. La grille Ionic est un style à 12 colonnes avec une variété de points de rupture en fonction de la taille de l'écran.

Les points clés suivants doivent être retenus lors de l'utilisation de la grille Ionic :

- Les grilles sont utilisées pour connecter les rangées et les colonnes. L'attribut fixed définit la largeur par résolution d'écran, mais il occupe toute la largeur de son conteneur.
- Les rangées sont des collections horizontales de colonnes, seules les colonnes doivent être des enfants directs des rangées. Seules les colonnes doivent être des enfants immédiats des rangées, car c'est là que nous plaçons notre contenu.
- Les paramètres de taille déterminent le nombre de colonnes à utiliser parmi les 12 de base par rangée. Par conséquent, une colonne peut avoir un attribut size="4" pour occuper 1/3 de la grille.
- Lorsqu'aucune mesure n'est fournie pour une colonne, elle sera automatiquement divisée en largeurs égales.

### 9. Comment accéder aux fonctionnalités natives du téléphone, comme la caméra, dans les applications Ionic ?

Par défaut, Ionic ne dispose pas d'une API de caméra. Comme le modèle de plugin d'Ionic est basé sur Cordova, nous pouvons utiliser des plugins Cordova dans notre projet. L'équipe Ionic a mis en place un ensemble d'extensions Cordova contenant des wrappers Angular, disponibles sur ngCordova. Pour utiliser les plugins Cordova, nous devons exécuter la commande Ionic `install plugin name`.

Il peut également être nécessaire d'inclure le module Angular du plugin dans l'application Angular dans certains cas. Nous pouvons même utiliser l'API de la caméra en utilisant le `cordova-plugin-camera`, disponible sur GitHub, pour utiliser la caméra d'un téléphone mobile dans une application Ionic. Ce plugin fournit une entité universelle `navigator.camera` au système qui inclut une API pour prendre des photos et choisir des images dans la bibliothèque de photos du système.

### 10. Comment utiliser les observables dans Ionic ?

L'observable est une classe exportée par la bibliothèque RxJS. La bibliothèque RxJS fournit des observables qui ne sont pas spécifiques à Ionic ou Angular. Les promesses sont similaires aux observables, mais les observables ont beaucoup plus de fonctionnalités. Plutôt que de résoudre une seule valeur, ils peuvent gérer plusieurs valeurs simultanément. Vous pouvez même mettre à jour les données incluses dans un observable en vous abonnant à celui-ci.

Les observables sont "paresseux" dans le sens où ils ne sont pas exécutés tant qu'ils ne sont pas abonnés. Une variété d'opérations peut être utilisée pour modifier les observables et renvoyer un nouvel observable. Vous pouvez même créer votre propre observable.

