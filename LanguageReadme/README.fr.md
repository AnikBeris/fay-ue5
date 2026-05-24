```html
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./images/icon.png" alt="Fay">
    <img alt="Project Logo" src="./images/icon.png" alt="Fay" width="256" height="auto">
  </picture>
    <h1>FAY</h1>
    <h3>UE5 数字人工程(Metahuman)</h3>
</div>

[Ce projet est un projet open-source complet pour les personnages numériques UE, qui peut être utilisé avec le framework Fay pour réaliser divers scénarios d'application : animateurs virtuels, démonstrateurs en direct, guides d'achat, assistants vocaux, assistants vocaux à distance, interactions avec des personnages numériques, intervieweurs numériques et évaluations psychologiques, Jarvis, Her](https://github.com/xszyou/Fay).

(Pour rejoindre le groupe de discussion, veuillez suivre le compte public : fay数字人, adresse de la documentation : [​‌metahuman(ue) - 飞书云文档](https://qqk9ntwbcit.feishu.cn/wiki/N33FwegdxiRXzCkZlH2czjwvnrg))

# Démarrage du personnage numérique UE

- ID du cours : course-1775792095810
- Auteur : 郭泽斌
- Version : 1.0.0
- Nombre de chapitres : 5
- Lecture et modification : https://player.fay-agent.com/
- Importer le package de cours : UE 数字人启动.zip

## Couverture

![Couverture du cours Démarrage du personnage numérique UE](<images/course1/cover.png>)

## Table des matières

1. Exigences matérielles
2. Installation et démarrage du framework Fay
3. Activer le microphone et le réveil, désactiver le haut-parleur
4. Télécharger et exécuter le package de démarrage du personnage numérique UE
5. Vérification de la connexion et test de dialogue

## Section 1 : Exigences matérielles

![Document](<images/course1/section-01-01.png>)

Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 2050, processeur i7 de 7e génération, 16 Go de RAM, 100 Go de disque dur et système d'exploitation Windows 10 ou supérieur.

```
Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 2050, processeur i7 de 7e génération, 16 Go de RAM, 100 Go de disque dur et système d'exploitation Windows 10 ou supérieur.
```

## Section 2 : Installation et démarrage du framework Fay

![Document](<images/course1/section-02-01.png>)

La première étape pour démarrer le personnage numérique UE consiste à installer et démarrer le framework Fay.

Fay est le moteur principal de cette solution de personnage numérique, responsable des étapes clés telles que la reconnaissance vocale, la génération de dialogue et la synthèse vocale.

Veuillez d'abord suivre l'URL de la documentation officielle fournie dans le bloc de code à droite pour télécharger et installer Fay. La documentation officielle contient une description complète des dépendances requises et des étapes d'installation. Veuillez suivre les instructions attentivement.

Une fois l'installation terminée, ouvrez l'interface principale de Fay. Vous verrez une page de console simple, avec un menu à gauche contenant des entrées pour les messages, les paramètres de personnage, MCP, etc.

Sur la page d'accueil de Fay, en bas à gauche, se trouve un bouton d'alimentation rond et vert bien visible. Cliquez sur ce bouton pour démarrer les services principaux de Fay en un seul clic.

Une fois le démarrage réussi, le voyant d'état de Fay s'allumera, indiquant que le système est en cours d'exécution et prêt à se connecter au personnage numérique UE.

```
# Documentation officielle du framework Fay
# Veuillez suivre les instructions sur l'URL ci-dessous pour télécharger, installer et démarrer Fay

https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc

# Une fois l'installation terminée, cliquez sur le bouton rond vert en bas à gauche de la page d'accueil de Fay pour démarrer le service Fay.
```

## Section 3 : Activer le microphone et le réveil, désactiver le haut-parleur

![Document](<images/course1/section-03-01.png>)

Une fois Fay démarré, la prochaine étape cruciale consiste à s'assurer que le microphone est activé, que le haut-parleur est désactivé et que la fonction de réveil est activée.  
Le modèle de personnage numérique UE présenté aujourd'hui ne dispose pas d'un module de captation audio indépendant. Il dépend du Fay local pour la captation audio. Cependant, il dispose d'un module de lecture audio indépendant qui jouera l'audio synthétisé par Fay, mais cet audio doit toujours être lu sur la même machine.  

Après avoir désactivé la fonction de réveil de Fay, si vous n'avez pas de matériel de captation audio professionnel, Fay pourrait capter à nouveau le son émis par le personnage numérique lui-même, provoquant une boucle d'écho qui perturberait gravement l'expérience de dialogue.

Une fois la configuration terminée, vous pouvez essayer de dire dans le microphone : "Bonjour, es-tu là ?" pour vérifier si Fay peut recevoir votre voix correctement.

## Section 4 : Télécharger et exécuter le package de démarrage du personnage numérique UE

![Document](<images/course1/section-04-01.png>)

Une fois la préparation côté Fay terminée, nous devons maintenant télécharger et démarrer le package de démarrage du personnage numérique UE.

Veuillez télécharger la dernière version du package de démarrage du personnage numérique UE à l'URL suivante. Une fois le téléchargement terminé, décompressez l'archive dans un répertoire distinct, puis double-cliquez sur le fichier exécutable .exe inclus.

Une fois le package démarré, le personnage numérique UE apparaîtra dans une fenêtre distincte. Vous verrez une figure virtuelle vêtue d'une tenue professionnelle blanche se tenir sur une scène.

Après le démarrage du personnage numérique, il tentera automatiquement de se connecter au service Fay déjà en cours d'exécution localement. Ce processus de connexion est entièrement automatique, et vous n'avez pas besoin de configurer manuellement le réseau ou les adresses. Ce design de connexion automatique simplifie grandement le processus de déploiement, permettant aux utilisateurs non techniques de s'y mettre rapidement et de réduire la barrière à l'installation d'un système de personnage numérique complet.

```
# Adresse de téléchargement du package de démarrage du personnage numérique UE
# Après téléchargement, veuillez décompresser et double-cliquer sur le fichier exécutable .exe inclus
# Une fois démarré, le personnage numérique se connectera automatiquement au service Fay en cours d'exécution localement

 https://pan.baidu.com/s/1olc-Jd9rH-PcWkdBK2Hc6Q?pwd=kwyd
```

## Section 5 : Vérification de la connexion et test de dialogue

![Document](<images/course1/section-05-01.png>)

La dernière étape consiste à vérifier si la connexion entre le personnage numérique UE et Fay a été établie avec succès, puis à effectuer un test de dialogue complet.

Après le démarrage du personnage numérique UE, retournez à l'interface de gestion de Fay pour vérifier. Dans le coin supérieur gauche, à l'emplacement du logo Fay, vous verrez plusieurs voyants d'état. Si le deuxième voyant est allumé, cela signifie que le personnage numérique UE s'est connecté avec succès au service Fay et que le lien de communication bidirectionnel est entièrement établi.

Une fois la connexion confirmée, vous pouvez saluer le personnage numérique via le microphone. Essayez de dire : "Bonjour, peux-tu te présenter ?" et observez la réaction du personnage numérique.

Si vous voyez le personnage numérique effectuer des mouvements de bouche et des expressions faciales, et que vous entendez une réponse vocale claire dans la fenêtre d'exécution du personnage numérique UE, félicitations, vous avez réussi à démarrer et connecter le personnage numérique UE !

À ce stade, le processus de démarrage du personnage numérique UE est entièrement terminé. Vous avez maintenant un partenaire numérique capable d'écouter, de parler et d'interagir. Vous pouvez commencer à explorer davantage de scénarios d'application intéressants.

# Édition du projet de personnage numérique UE

- ID du cours : course-1775804088429
- Auteur : 郭泽斌
- Version : 1.0.0
- Nombre de chapitres : 11
- Lecture et modification : https://player.fay-agent.com/
- Importer le package de cours : UE 数字人工程编辑.zip

## Couverture

![Couverture du cours Édition du projet de personnage numérique UE](<images/course2/cover.png>)

## Table des matières

1. Exigences matérielles
2. Installation et démarrage du framework Fay
3. Activer le microphone et le réveil, désactiver le haut-parleur
4. Installer Epic Games Launcher
5. Installer Unreal Engine 5.6
6. Télécharger et décompresser le package du projet de personnage numérique UE
7. Installer les plugins
8. Démarrer le projet
9. Vérifier les plugins
10. Aperçu du projet en cours d'exécution
11. Vérification de la connexion et test de dialogue

## Section 1 : Exigences matérielles

![Document](<images/course2/section-01-01.png>)

Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 3060, processeur i7 de 10e génération, 32 Go de RAM, 200 Go de disque dur et système d'exploitation Windows 10 ou supérieur.

```
Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 3060, processeur i7 de 10e génération, 32 Go de RAM, 200 Go de disque dur et système d'exploitation Windows 10 ou supérieur.
```

## Section 2 : Installation et démarrage du framework Fay

![Document](<images/course2/section-02-01.png>)

La première étape pour démarrer le personnage numérique UE consiste à installer et démarrer le framework Fay.

Fay est le moteur principal de cette solution de personnage numérique, responsable des étapes clés telles que la reconnaissance vocale, la génération de dialogue et la synthèse vocale.

Veuillez d'abord suivre l'URL de la documentation officielle fournie dans le bloc de code à droite pour télécharger et installer Fay. La documentation officielle contient une description complète des dépendances requises et des étapes d'installation. Veuillez suivre les instructions attentivement.

Une fois l'installation terminée, ouvrez l'interface principale de Fay. Vous verrez une page de console simple, avec un menu à gauche contenant des entrées pour les messages, les paramètres de personnage, MCP, etc.

Sur la page d'accueil de Fay, en bas à gauche, se trouve un bouton d'alimentation rond et vert bien visible. Cliquez sur ce bouton pour démarrer les services principaux de Fay en un seul clic.

Une fois le démarrage réussi, le voyant d'état de Fay s'allumera, indiquant que le système est en cours d'exécution et prêt à se connecter au personnage numérique UE.

```
# Documentation officielle du framework Fay
# Veuillez suivre les instructions sur l'URL ci-dessous pour télécharger, installer et démarrer Fay

https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc

# Une fois l'installation terminée, cliquez sur le bouton rond vert en bas à gauche de la page d'accueil de Fay pour démarrer le service Fay.
```

### ![讲义](<images/course2/section-03-01.png>)

Une fois que Fay est lancé, l'étape suivante, très importante, consiste à vérifier que le microphone est activé, que le haut-parleur est désactivé et que la fonction de réveil est activée.  
Le modèle numérique présenté aujourd'hui dans UE ne dispose pas d'un module de captation sonore indépendant. Il dépend donc de Fay installé sur la machine locale. Cependant, il dispose d'un module de lecture audio indépendant, qui joue les fichiers audio générés par Fay. Ces fichiers audio doivent néanmoins être lus sur la même machine.  
Si la fonction de réveil de Fay est désactivée et que vous ne disposez pas d'un matériel de captation sonore professionnel, Fay pourrait capter les sons émis par le personnage numérique lui-même, ce qui entraînerait un effet de boucle d'écho et nuirait gravement à l'expérience de dialogue.  

Une fois la configuration terminée, vous pouvez essayer de dire dans le microphone : "Bonjour, es-tu là ?" pour vérifier si Fay peut recevoir votre voix correctement.

---

## Section 4 : Installer l'Epic Games Launcher

![讲义](<images/course2/section-04-01.png>)

Ensuite, rendez-vous sur le site officiel d'UE : https://www.epicgames.com/ pour télécharger l'installateur Epic et terminez l'installation.

```
Site officiel d'UE : https://www.epicgames.com/
```

---

## Section 5 : Installer le moteur UE 5.6

![讲义](<images/course2/section-05-01.png>)

Ensuite, ouvrez l'Epic Games Launcher, sélectionnez l'onglet "Unreal Engine" à gauche, puis allez dans l'onglet "Library" en haut. Cliquez sur le bouton "+" à côté de la version du moteur, choisissez la version 5.6 dans le menu déroulant qui apparaît sous le bloc du moteur, puis cliquez sur "Installer" et attendez que l'installation soit terminée.

```
Note : Dans l'illustration de l'auteur, la version 5.6 n'apparaît pas car elle est déjà installée.
```

---

## Section 6 : Télécharger et extraire le projet UE Digital Human

![讲义](<images/course2/section-06-01.png>)

Ensuite, nous devons télécharger et lancer le projet UE Digital Human.

Veuillez télécharger la dernière version du projet UE Digital Human à l'adresse suivante. Une fois le téléchargement terminé, extrayez l'archive dans un répertoire distinct pour l'utiliser ultérieurement.

```
https://pan.baidu.com/s/1aApeAiIwGNvPXxR-gBj_MQ?pwd=q2jw
```

---

## Section 7 : Installer les plugins

Une fois le moteur 5.6 installé, vous pouvez rechercher et installer les plugins illustrés dans l'Epic Games Launcher. Vous pouvez également demander les fichiers des plugins à l'équipe de la communauté Fay Digital Human. Extrayez les plugins dans le répertoire "plugins" du projet Digital Human.

---

## Section 8 : Lancer le projet

![讲义](<images/course2/section-08-01.png>)

Cliquez sur le fichier uproject dans le répertoire et attendez que le lancement soit terminé. Assurez-vous d'avoir au moins 100 Go d'espace libre sur le disque C, sinon le chargement risque d'échouer.

---

## Section 9 : Vérifier les plugins

![讲义](<images/course2/section-09-01.png>)

Après le lancement du projet, cliquez sur le menu "Outils", sélectionnez "Plugins", puis allez dans l'onglet "Installés". Assurez-vous que les 4 plugins mentionnés précédemment sont activés.

---

## Section 10 : Exécuter un aperçu du projet

![讲义](<images/course2/section-10-01.png>)

Après avoir fermé la fenêtre des plugins, cliquez sur le bouton "Play" en haut. Vous verrez alors le personnage numérique en mode aperçu. Le personnage numérique se connectera automatiquement à Fay.

---

## Section 11 : Vérifier la connexion et tester le dialogue

![讲义](<images/course2/section-11-01.png>)

La dernière étape consiste à vérifier si la connexion entre le personnage numérique UE et Fay est réussie, et à effectuer un test de dialogue complet.

Une fois le personnage numérique UE lancé, retournez à l'interface de gestion de Fay pour vérifier. Dans le coin supérieur gauche, à côté du logo Fay, vous verrez plusieurs voyants d'état. Si le deuxième voyant s'allume, cela signifie que le personnage numérique UE est connecté avec succès au service Fay, et que la communication bidirectionnelle est entièrement établie.

Une fois la connexion confirmée, vous pouvez saluer le personnage numérique via le microphone. Essayez de dire : "Bonjour, peux-tu te présenter ?" et observez la réaction du personnage numérique.

Si vous voyez des mouvements de lèvres et des expressions faciales sur le personnage numérique, et que vous entendez une réponse vocale claire dans la fenêtre d'exécution du personnage numérique UE, félicitations ! Vous avez réussi à lancer et connecter le personnage numérique UE.

À ce stade, tout le processus de lancement du personnage numérique UE est terminé. Vous disposez maintenant d'un partenaire numérique capable d'écouter, de parler et d'interagir. Vous pouvez désormais explorer de nombreux scénarios d'application intéressants.

---

# Groupe de discussion dédié à UE (pour obtenir gratuitement les plugins et échanger tranquillement)  
![交流群](<images/1280X1280.JPEG>)
