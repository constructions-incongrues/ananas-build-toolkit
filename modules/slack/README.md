#### Module : slack

TODO : Présentation du module.

##### Installation

Ajoutez les lignes suivantes au fichier ```build.xml``` du projet, aux endroits indiqués :
   
Après l'import du module toolkit :
 ```xml
 <import file="${toolkit.basedir}/modules/slack/module.xml" />
 ```

Dans la *target* ```setprofile``` :
```xml
<property file="${toolkit.basedir}/modules/slack/build.properties" />
```

Si besoin, surchargez les directives de configuration par défaut du module dans votre profil de configuration.

##### TODO : Directives de configuration

* **slack.directivename** (défaut : *valeur*) : description

##### TODO : Les tâches et leurs paramètres

* **slack.taskname** : (toolkit phase : *configure|build|review|migrate|sync*) : description
    * **parameter.name** (défaut : valeur) : description
