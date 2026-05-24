```html
<p align="center">
  <strong>-------></strong>
  <a href="/README.md">中文</a> |
  <a href="/README.ru.md">Russian</a> |
  <a href="/README.en.md">English</a> |
  <a href="/README.fr.md">Français</a>
  <strong><-------</strong>
</p>

---

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./images/icon.png" alt="Fay">
    <img alt="Project Logo" src="./images/icon.png" alt="Fay" width="256" height="auto">
  </picture>
    <h1>FAY</h1>
    <h3>UE5 Projet numérique humain (Metahuman)</h3>
</div>

[Ce projet est un projet open-source complet pour les humains numériques UE, qui peut être utilisé avec le framework Fay pour réaliser divers scénarios d'application : animateur virtuel, vente en direct, guide d'achat, assistant vocal, assistant vocal à distance, interaction avec des humains numériques, recruteur numérique et évaluation psychologique, Jarvis, Her](https://github.com/xszyou/Fay).

(Pour rejoindre le groupe de discussion, veuillez suivre le compte officiel : fay数字人, documentation disponible ici : [​‌metahuman(ue) - 飞书云文档](https://qqk9ntwbcit.feishu.cn/wiki/N33FwegdxiRXzCkZlH2czjwvnrg))

# Démarrage de l'humain numérique UE

- ID du cours : course-1775792095810
- Auteur : 郭泽斌
- Version : 1.0.0
- Nombre de chapitres : 5
- Lecture et modification : https://player.fay-agent.com/
- Importer le package de cours : [Démarrage de l'humain numérique UE.zip](<UE 数字人启动.zip>)

## Couverture

![Couverture Démarrage de l'humain numérique UE](<images/course1/cover.png>)

## Sommaire

1. Configuration requise
2. Installer et démarrer le framework Fay
3. Activer le microphone et le réveil, désactiver le haut-parleur
4. Télécharger et exécuter le package de l'humain numérique UE
5. Vérifier la connexion et tester la conversation

## Section 1 : Configuration requise

![Document](<images/course1/section-01-01.png>)

Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 2050, processeur i7 de 7e génération, 16 Go de RAM, 100 Go de disque dur, système d'exploitation Windows 10 ou supérieur.

```
Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 2050, processeur i7 de 7e génération, 16 Go de RAM, 100 Go de disque dur, système d'exploitation Windows 10 ou supérieur.
```

## Section 2 : Installer et démarrer le framework Fay

![Document](<images/course1/section-02-01.png>)

La première étape pour démarrer l'humain numérique UE consiste à installer et démarrer le framework Fay.

Fay est le cadre moteur principal de cette solution humaine numérique. Il est responsable du traitement de la reconnaissance vocale, de la génération de dialogue et de la synthèse vocale.

Veuillez d'abord suivre l'URL de la documentation officielle fournie dans le bloc de code à droite pour télécharger et installer Fay. La documentation officielle contient des explications complètes sur les dépendances environnementales et les étapes d'installation. Veuillez suivre attentivement les instructions.

Une fois l'installation terminée, ouvrez l'interface principale de Fay. Vous verrez une page de console simple, avec un menu à gauche contenant des entrées pour Messages, Personnalités, MCP, etc.

Sur la page d'accueil de Fay, un bouton d'alimentation vert circulaire bien visible se trouve en bas à gauche. Cliquez sur ce bouton pour démarrer les services principaux de Fay en un clic.

Une fois le démarrage réussi, le voyant d'état de Fay s'allumera, indiquant que le système est en cours d'exécution et prêt à se connecter à l'humain numérique UE.

```
# Documentation officielle du framework Fay
# Veuillez suivre les instructions de l'URL ci-dessous pour télécharger, installer et démarrer Fay

https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc

# Une fois l'installation terminée, cliquez sur le bouton vert circulaire en bas à gauche de la page d'accueil de Fay pour démarrer les services Fay.
```

## Section 3 : Activer le microphone et le réveil, désactiver le haut-parleur

![Document](<images/course1/section-03-01.png>)

Une fois Fay démarré, la prochaine étape essentielle consiste à s'assurer que le microphone est activé, que le haut-parleur est désactivé et que la fonction de réveil est activée.

Le modèle numérique humain UE présenté aujourd'hui ne dispose pas d'un module de capture sonore indépendant. Il dépend du Fay installé sur la machine locale. Cependant, il dispose d'un module de lecture sonore indépendant, qui jouera l'audio synthétisé par Fay, mais cet audio doit toujours être lu sur la même machine.

Si la fonction de réveil de Fay est désactivée et que vous n'avez pas de matériel de capture sonore professionnel, Fay pourrait capter le son émis par l'humain numérique lui-même, provoquant une boucle d'écho qui affecterait gravement l'expérience de la conversation.

Une fois la configuration terminée, vous pouvez essayer de dire dans le microphone : "Bonjour, es-tu là ?" pour vérifier si Fay peut recevoir votre voix correctement.

## Section 4 : Télécharger et exécuter le package de l'humain numérique UE

![Document](<images/course1/section-04-01.png>)

Une fois les préparatifs du côté de Fay terminés, nous devons télécharger et démarrer le package de l'humain numérique UE.

Veuillez télécharger la dernière version du package de l'humain numérique UE à l'URL suivante. Une fois le téléchargement terminé, décompressez l'archive dans un répertoire distinct, puis double-cliquez pour exécuter le fichier exécutable (exe) qu'elle contient.

Une fois le package lancé, l'humain numérique UE apparaîtra dans une fenêtre distincte. Vous verrez une figure virtuelle vêtue d'une tenue professionnelle blanche se tenir sur une scène.

Une fois l'humain numérique démarré, il tentera automatiquement de se connecter au service Fay en cours d'exécution sur la machine locale. Ce processus de connexion est entièrement automatique, vous n'avez pas besoin de configurer manuellement les réseaux ou les adresses. Ce design de connexion automatique simplifie considérablement le processus de déploiement, permettant même aux utilisateurs non techniques de se familiariser rapidement avec le système, réduisant ainsi la barrière à l'entrée pour la mise en place d'un système humain numérique complet.

```
# Adresse de téléchargement du package de l'humain numérique UE
# Après le téléchargement, veuillez décompresser et double-cliquer sur le fichier exécutable (exe) pour le lancer
# Une fois démarré, l'humain numérique se connectera automatiquement au service Fay en cours d'exécution sur la machine locale

 https://pan.baidu.com/s/1olc-Jd9rH-PcWkdBK2Hc6Q?pwd=kwyd
```

## Section 5 : Vérifier la connexion et tester la conversation

![Document](<images/course1/section-05-01.png>)

La dernière étape consiste à vérifier si la connexion entre l'humain numérique UE et Fay a été établie avec succès, puis à effectuer un test de conversation complet.

Une fois l'humain numérique UE démarré, retournez à l'interface de gestion de Fay pour vérifier. Dans le coin supérieur gauche, à l'emplacement du logo Fay, vous verrez plusieurs voyants d'état. Si le deuxième voyant est allumé, cela signifie que l'humain numérique UE s'est connecté avec succès au service Fay, et que le lien de communication bidirectionnel est complètement établi.

Après avoir confirmé que la connexion est réussie, vous pouvez saluer l'humain numérique via le microphone. Essayez de dire : "Bonjour, peux-tu te présenter ?" et observez la réaction de l'humain numérique.

Si vous voyez des changements dans les expressions faciales et les mouvements des lèvres de l'humain numérique, et que vous entendez une réponse vocale claire dans la fenêtre de l'humain numérique UE, félicitations, vous avez réussi à démarrer et connecter l'humain numérique UE !

À ce stade, le processus de démarrage de l'humain numérique UE est entièrement terminé. Vous disposez maintenant d'un partenaire numérique capable d'écouter, de parler et d'interagir. Vous pouvez désormais explorer de nombreux scénarios d'application intéressants.

# Édition du projet humain numérique UE

- ID du cours : course-1775804088429
- Auteur : 郭泽斌
- Version : 1.0.0
- Nombre de chapitres : 11
- Lecture et modification : https://player.fay-agent.com/
- Importer le package de cours : UE 数字人工程编辑.zip

## Couverture

![Couverture Édition du projet humain numérique UE](<images/course2/cover.png>)

## Sommaire

1. Configuration requise
2. Installer et démarrer le framework Fay
3. Activer le microphone et le réveil, désactiver le haut-parleur
4. Installer Epic Games Launcher
5. Installer le moteur UE 5.6
6. Télécharger et décompresser le package du projet humain numérique UE
7. Installer les plugins
8. Démarrer le projet
9. Vérifier les plugins
10. Prévisualiser le projet
11. Vérifier la connexion et tester la conversation

## Section 1 : Configuration requise

![Document](<images/course2/section-01-01.png>)

Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 3060, processeur i7 de 10e génération, 32 Go de RAM, 200 Go de disque dur, système d'exploitation Windows 10 ou supérieur.

```
Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 3060, processeur i7 de 10e génération, 32 Go de RAM, 200 Go de disque dur, système d'exploitation Windows 10 ou supérieur.
```

## Section 2 : Installer et démarrer le framework Fay

![Document](<images/course2/section-02-01.png>)

La première étape pour démarrer l'humain numérique UE consiste à installer et démarrer le framework Fay.

Fay est le cadre moteur principal de cette solution humaine numérique. Il est responsable du traitement de la reconnaissance vocale, de la génération de dialogue et de la synthèse vocale.

Veuillez d'abord suivre l'URL de la documentation officielle fournie dans le bloc de code à droite pour télécharger et installer Fay. La documentation officielle contient des explications complètes sur les dépendances environnementales et les étapes d'installation. Veuillez suivre attentivement les instructions.

Une fois l'installation terminée, ouvrez l'interface principale de Fay. Vous verrez une page de console simple, avec un menu à gauche contenant des entrées pour Messages, Personnalités, MCP, etc.

Sur la page d'accueil de Fay, un bouton d'alimentation vert circulaire bien visible se trouve en bas à gauche. Cliquez sur ce bouton pour démarrer les services principaux de Fay en un clic.

Une fois le démarrage réussi, le voyant d'état de Fay s'allumera, indiquant que le système est en cours d'exécution et prêt à se connecter à l'humain numérique UE.

```
# Documentation officielle du framework Fay
# Veuillez suivre les instructions de l'URL ci-dessous pour télécharger, installer et démarrer Fay

https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc
```

# Une fois l'installation terminée, cliquez sur le bouton vert circulaire en bas à gauche de la page d'accueil de Fay pour démarrer le service Fay.
```

## Section 3 : Activer le microphone, réveiller Fay et désactiver les haut-parleurs

![Cours](<images/course2/section-03-01.png>)

Une fois Fay démarré, l'étape suivante, essentielle, consiste à vérifier que le microphone est activé, les haut-parleurs désactivés, et la fonction de réveil activée.  
Le modèle numérique UE présenté aujourd'hui n'a pas de module de capture audio indépendant. Il dépend donc de Fay installé sur la machine locale. Cependant, il dispose d'un module de lecture audio indépendant qui joue les fichiers audio générés par Fay, mais ces fichiers doivent également être lus sur la même machine.  
Si la fonction de réveil de Fay est désactivée et que vous ne disposez pas d'un matériel de capture audio professionnel, Fay pourrait capter les sons émis par le personnage numérique lui-même, ce qui entraînerait une boucle d'écho et perturberait gravement l'expérience de conversation.

Une fois la configuration terminée, vous pouvez essayer de dire dans le microphone : "Bonjour, es-tu là ?" pour vérifier si Fay peut recevoir votre voix correctement.

## Section 4 : Installer Epic Games Launcher

![Cours](<images/course2/section-04-01.png>)

Ensuite, rendez-vous sur le site officiel de l'UE : https://www.epicgames.com/ pour télécharger l'installateur Epic Games et terminer l'installation.

```
Site officiel de l'UE : https://www.epicgames.com/
```

## Section 5 : Installer le moteur Unreal Engine 5.6

![Cours](<images/course2/section-05-01.png>)

Ensuite, ouvrez Epic Games Launcher, sélectionnez l'onglet "Unreal Engine" dans la barre latérale gauche, puis cliquez sur "Bibliothèque" dans la barre supérieure. Cliquez sur le bouton "+" à côté de la version du moteur, sélectionnez la version 5.6 dans le menu déroulant, puis cliquez sur "Installer" et attendez la fin de l'installation.

```
Note : La version 5.6 n'apparaît pas dans les captures d'écran car elle est déjà installée.
```

## Section 6 : Télécharger et extraire le package de projet numérique UE

![Cours](<images/course2/section-06-01.png>)

Ensuite, nous devons télécharger et lancer le package de projet numérique UE.

Veuillez télécharger la dernière version du package de projet numérique UE à l'adresse suivante. Une fois le téléchargement terminé, extrayez le fichier compressé dans un répertoire distinct pour une utilisation ultérieure.

```
https://pan.baidu.com/s/1aApeAiIwGNvPXxR-gBj_MQ?pwd=q2jw
```

## Section 7 : Installer les plugins

Une fois le moteur 5.6 installé, vous pouvez rechercher et installer les plugins montrés dans l'image via Epic Games Launcher. Vous pouvez également demander le package de plugins à l'équipe de la communauté Fay. Extrayez les plugins dans le répertoire "plugins" du projet numérique.

## Section 8 : Lancer le projet

![Cours](<images/course2/section-08-01.png>)

Cliquez sur le fichier uproject dans le répertoire et attendez que le lancement soit terminé. Assurez-vous d'avoir au moins 100 Go d'espace libre sur le disque C, sinon le chargement risque d'échouer.

## Section 9 : Vérifier les plugins

![Cours](<images/course2/section-09-01.png>)

Une fois le projet lancé, cliquez sur le menu "Outils", sélectionnez "Plugins", puis "Installés". Assurez-vous que les quatre plugins mentionnés précédemment sont activés.

## Section 10 : Lancer l'aperçu du projet

![Cours](<images/course2/section-10-01.png>)

Après avoir fermé la fenêtre des plugins, cliquez sur le bouton "Exécuter" en haut. Vous verrez alors le personnage numérique en mode aperçu. Le personnage numérique se connectera automatiquement à Fay.

## Section 11 : Vérifier la connexion et tester une conversation

![Cours](<images/course2/section-11-01.png>)

La dernière étape consiste à vérifier si la connexion entre le personnage numérique UE et Fay a bien été établie et à effectuer un test de conversation complet.

Une fois le personnage numérique UE lancé, retournez à l'interface de gestion de Fay pour vérifier l'état de la connexion. En haut à gauche, à l'emplacement du logo Fay, vous verrez plusieurs voyants d'état. Si le deuxième voyant est allumé, cela signifie que le personnage numérique UE est connecté avec succès au service Fay et que la communication bidirectionnelle est entièrement établie.

Une fois la connexion confirmée, vous pouvez saluer le personnage numérique via le microphone. Essayez de dire : "Bonjour, peux-tu te présenter ?" et observez la réaction du personnage numérique.

Si vous voyez le personnage numérique bouger les lèvres et exprimer des émotions, et que vous entendez une réponse vocale claire dans la fenêtre d'exécution du personnage numérique UE, félicitations ! Vous avez réussi à démarrer et connecter le personnage numérique UE.

À ce stade, le processus de démarrage du personnage numérique UE est entièrement terminé. Vous disposez désormais d'un partenaire numérique capable d'écouter, de parler et d'interagir. Vous pouvez maintenant commencer à explorer davantage de scénarios d'application intéressants.

# Groupe d'échange dédié à UE (obtenez gratuitement les plugins et échangez en toute tranquillité)
![Groupe d'échange](<images/1280X1280.JPEG>)
```
