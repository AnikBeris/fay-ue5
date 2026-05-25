<p align="center">
  <strong>-------> |</strong>
  <a href="/LanguageReadme/README.md">中文</a> |
  <a href="/LanguageReadme/README.ru.md">Russian</a> |
  <a href="/LanguageReadme/README.en.md">English</a> |
  <a href="/LanguageReadme/README.fr.md">Français</a>
  <strong>| <-------</strong>
</p>

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-blue?style=flat&logo=github)](https://github.com/xszyou)
[![License](https://img.shields.io/badge/License-purple?style=flat&logo=github)](https://github.com/xszyou/fay-ue5/blob/main/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/xszyou?style=flat&logo=github&label=Stars&color=orange)](https://github.com/xszyou)

</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./images/icon.png" alt="Fay">
    <img alt="Project Logo" src="./images/icon.png" alt="Fay" width="256" height="auto">
  </picture>
    <h1>FAY</h1>
    <h2>UE5 Digital Human Project (Metahuman)</h2>
</div>

---

- [Ce projet est un projet open source complet de digital human sous UE, qui peut être utilisé avec le framework Fay digital human pour réaliser divers scénarios d'application : animateurs virtuels, vendeurs en direct, guides d'achat de produits, assistants vocaux, assistants vocaux à distance, interactions avec des humains numériques, recruteurs numériques et évaluations psychologiques, Jarvis, Her](https://github.com/xszyou/Fay)

- Pour rejoindre le groupe de discussion, veuillez suivre le compte public : fay数字人, adresse du document : [​‌metahuman(ue) - 飞书云文档](https://qqk9ntwbcit.feishu.cn/wiki/N33FwegdxiRXzCkZlH2czjwvnrg)

# Démarrage du digital human UE
| | |
|-------------:|:-------------|
| **ID du cours** | `course-1775792095810` |
| **Auteur**       | `郭泽斌` |
| **Version**      | `1.0.` |
| **Nombre de chapitres** | `5` |
| **Lecture et modification** | https://player.fay-agent.com |
| **Importer le package de cours** | [Démarrage du digital human UE.zip](<../UE 数字人启动.zip>) |

## Couverture

![Couverture du démarrage du digital human UE](<../images/course1/cover.png>)

## Table des matières

> 1. Configuration requise de la machine  
> 2. Installation et démarrage du framework Fay  
> 3. Activation du microphone et réveil, désactivation du haut-parleur  
> 4. Téléchargement et exécution du package de démarrage du digital human UE  
> 5. Vérification de la connexion et test de dialogue  

---

## Section 1 : Configuration requise de la machine

![Support de cours](<../images/course1/section-01-01.png>)

> [!NOTE]
> `Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 2050, processeur i7 de 7e génération, 16 Go de RAM, 100 Go de disque dur, système d'exploitation Windows 10 ou supérieur.`
> 
> `Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 2050, processeur i7 de 7e génération, 16 Go de RAM, 100 Go de disque dur, système d'exploitation Windows 10 ou supérieur.`

---

## Section 2 : Installation et démarrage du framework Fay

![Support de cours](<../images/course1/section-02-01.png>)

La première étape pour démarrer le digital human UE consiste à installer et à démarrer le framework Fay.

Fay est le cadre de base de la solution de digital human présentée ici. Il est responsable du traitement de la reconnaissance vocale, de la génération de dialogue et de la synthèse vocale, entre autres étapes clés.

Veuillez d'abord suivre l'URL du document officiel fourni dans le bloc de code à droite pour télécharger et installer Fay. Le document officiel contient une description complète des dépendances nécessaires et des étapes d'installation. Veuillez suivre les instructions avec soin.

Une fois l'installation terminée, ouvrez l'interface principale de Fay. Vous verrez une page de console simple, avec un menu sur la gauche contenant des entrées pour les messages, les personnages, MCP, etc.

Sur la page d'accueil de Fay, en bas à gauche, se trouve un bouton vert circulaire bien visible. Cliquez sur ce bouton pour démarrer les services principaux de Fay en un seul clic.

Une fois le démarrage réussi, le voyant d'état de Fay s'allumera, indiquant que le système est en fonctionnement et prêt à se connecter au digital human UE.

> [!NOTE]
> Documentation officielle du framework Fay digital human  
> Veuillez suivre les instructions de l'URL ci-dessous pour télécharger, installer et démarrer Fay :  
> 
> https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc  
> 
> Une fois l'installation terminée, cliquez sur le bouton vert circulaire en bas à gauche de la page d'accueil de Fay pour démarrer les services Fay.

---

## Section 3 : Activation du microphone et réveil, désactivation du haut-parleur

![Support de cours](<../images/course1/section-03-01.png>)

Une fois Fay démarré, la prochaine étape essentielle consiste à vérifier que le microphone est activé, que le haut-parleur est désactivé et que le réveil est activé.  
Le modèle de digital human UE présenté aujourd'hui ne dispose pas d'un module de capture audio indépendant. Il dépend donc du matériel local pour Fay. Cependant, il dispose d'un module de lecture audio indépendant qui jouera l'audio synthétisé par Fay. Cet audio doit toutefois être lu sur la même machine.  

Si la fonction de réveil de Fay est désactivée et que vous ne disposez pas de matériel de capture audio professionnel, Fay pourrait capturer les sons émis par le digital human lui-même, provoquant une boucle d'écho qui nuirait gravement à l'expérience de dialogue.  

Une fois la configuration terminée, vous pouvez essayer de dire dans le microphone "Bonjour, êtes-vous là ?" pour vérifier si Fay peut recevoir correctement votre voix.

---

## Section 4 : Téléchargement et exécution du package de démarrage du digital human UE

![Support de cours](<../images/course1/section-04-01.png>)

Une fois les préparatifs du côté Fay terminés, nous devons télécharger et démarrer le package de démarrage du digital human UE.  

Veuillez télécharger la dernière version du package de démarrage du digital human UE à l'URL suivante. Une fois le téléchargement terminé, décompressez l'archive dans un répertoire distinct, puis double-cliquez sur le fichier exécutable (.exe) inclus.  

Une fois le package démarré, le digital human UE apparaîtra dans une fenêtre distincte. Vous verrez une figure virtuelle vêtue d'un costume blanc se tenir sur une scène.  

Après le démarrage, le digital human tentera automatiquement de se connecter au service Fay en cours d'exécution sur la machine locale. Ce processus de connexion est entièrement automatisé, vous n'aurez pas besoin de configurer manuellement des réseaux ou des adresses. Cette conception simplifie considérablement le processus de déploiement, permettant aux utilisateurs non techniques de se familiariser rapidement avec le système et de réduire les obstacles à la mise en place d'un système complet de digital human.  

> [!NOTE]
> Adresse de téléchargement du package de démarrage du digital human UE  
> 
> Une fois téléchargé, décompressez l'archive et double-cliquez sur le fichier exécutable (.exe) inclus.  
> Le digital human se connectera automatiquement au service Fay en cours d'exécution sur la machine locale.  
> 
> https://pan.baidu.com/s/1olc-Jd9rH-PcWkdBK2Hc6Q?pwd=kwyd

---

## Section 5 : Vérification de la connexion et test de dialogue

![Support de cours](<../images/course1/section-05-01.png>)

La dernière étape consiste à vérifier si le digital human UE est correctement connecté à Fay et à effectuer un test de dialogue complet.  

Une fois le digital human UE démarré, retournez à l'interface de gestion de Fay pour vérifier. Dans le coin supérieur gauche, à l'emplacement du logo Fay, vous verrez plusieurs voyants d'état. Si le deuxième voyant est allumé, cela signifie que le digital human UE est connecté avec succès au service Fay, et que la communication entre les deux systèmes est pleinement établie.  

Après avoir confirmé la connexion, vous pouvez parler dans le microphone pour saluer le digital human. Essayez de dire : "Bonjour, pouvez-vous vous présenter ?" et observez la réaction du digital human.  

Si vous voyez le digital human changer d'expression et de mouvement des lèvres, et que vous entendez une réponse vocale claire dans la fenêtre de fonctionnement du digital human UE, félicitations, vous avez réussi à démarrer et connecter le digital human UE !  

À ce stade, le processus de démarrage du digital human UE est entièrement terminé. Vous disposez maintenant d'un partenaire digital capable d'écouter, de parler et d'interagir. Vous pouvez commencer à explorer davantage de scénarios d'application intéressants.

---
---

# Édition du projet digital human UE
| | |
|:-------------|:-------------|
| **ID du cours**     | `course-1775804088429` |
| **Auteur**       | `郭泽斌` |
| **Version**       | `1.0.0` |
| **Nombre de chapitres** | `11` |
| **Lecture et modification** | https://player.fay-agent.com |
| **Importer le package de cours** | [Édition du projet digital human UE.zip](<../UE 数字人工程编辑.zip>) |

## Couverture

![Couverture de l'édition du projet digital human UE](<../images/course2/cover.png>)

## Table des matières

> 1. Configuration requise de la machine  
> 2. Installation et démarrage du framework Fay  
> 3. Activation du microphone et réveil, désactivation du haut-parleur  
> 4. Installation de Epic Games Launcher  
> 5. Installation de Unreal Engine 5.6  
> 6. Téléchargement et décompression du package de projet digital human UE  
> 7. Installation des plugins  
> 8. Démarrage du projet  
> 9. Vérification des plugins  
> 10. Aperçu du projet en cours d'exécution  
> 11. Vérification de la connexion et test de dialogue  

---

## Section 1 : Configuration requise de la machine

![讲义](<../images/course2/section-01-01.png>)

> [!NOTE]
> `Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 3060, processeur i7 de 10e génération, 32 Go de RAM, 200 Go de disque dur, système d'exploitation Windows 10 ou supérieur.`
> 
> `Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 3060, processeur i7 de 10e génération, 32 Go de RAM, 200 Go de disque dur, système d'exploitation Windows 10 ou supérieur.`

---

## Section 2 : Installer et démarrer le framework Fay

![讲义](<../images/course2/section-02-01.png>)

La première étape pour démarrer un Metahuman dans UE consiste à installer et démarrer le framework Fay.

Fay est le framework central de la solution numérique humaine présentée ici. Il gère des étapes clés comme la reconnaissance vocale, la génération de dialogues et la synthèse vocale.

Veuillez d'abord télécharger et installer Fay en suivant l'URL de la documentation officielle fournie dans le bloc de code à droite. La documentation officielle contient une description complète des dépendances nécessaires et des étapes d'installation. Suivez attentivement les instructions.

Une fois l'installation terminée, ouvrez l'interface principale de Fay. Vous verrez une page de console simple, avec un menu à gauche contenant des entrées pour des fonctionnalités telles que Messages, Personnages et MCP.

En bas à gauche de la page d'accueil de Fay, un bouton vert circulaire bien visible permet d'allumer le système. Cliquez sur ce bouton pour démarrer les services centraux de Fay en un clic.

Une fois le démarrage réussi, le voyant d'état de Fay s'allumera, indiquant que le système est opérationnel et prêt à se connecter au Metahuman d'UE.

> [!NOTE]
> Documentation officielle du framework Fay pour les Metahumans
> 
> Veuillez suivre les instructions à l'URL suivante pour télécharger, installer et démarrer Fay :
> 
> https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc
> 
> Une fois l'installation terminée, cliquez sur le bouton vert circulaire en bas à gauche de la page d'accueil de Fay pour démarrer le service Fay.

---

## Section 3 : Activer le microphone, désactiver le haut-parleur et activer l'éveil

![讲义](<../images/course2/section-03-01.png>)

Après avoir démarré Fay, l'étape suivante essentielle consiste à s'assurer que le microphone est activé, que le haut-parleur est désactivé et que la fonction d'éveil est activée.

Le modèle numérique humain UE présenté aujourd'hui ne dispose pas de module de captation sonore indépendant. Il dépend donc de Fay installé sur la machine locale. Cependant, il dispose d'un module de lecture sonore indépendant pour diffuser l'audio généré par Fay, mais cet audio doit également être lu sur la même machine.

Si la fonction d'éveil de Fay est désactivée et que vous n'avez pas de matériel de captation sonore professionnel, Fay pourrait capter les sons émis par le Metahuman lui-même, ce qui entraînerait une boucle d'écho et perturberait gravement l'expérience de dialogue.

Une fois la configuration terminée, vous pouvez essayer de dire dans le microphone : "Bonjour, es-tu là ?" pour vérifier si Fay peut recevoir correctement votre voix.

---

## Section 4 : Installer Epic Games Launcher

![讲义](<../images/course2/section-04-01.png>)

Ensuite, rendez-vous sur le site officiel d'UE : https://www.epicgames.com pour télécharger l'installateur Epic et terminer l'installation.

> 
> 
> Site officiel d'UE : https://www.epicgames.com
> 
> 

---

## Section 5 : Installer le moteur Unreal Engine 5.6

![讲义](<../images/course2/section-05-01.png>)

Ensuite, ouvrez Epic Games Launcher, sélectionnez la section "Unreal Engine" à gauche, puis choisissez "Bibliothèque" dans la barre supérieure. Cliquez sur le bouton "+" à côté de la version du moteur, sélectionnez la version 5.6 dans le menu déroulant, cliquez sur "Installer" et attendez la fin de l'installation.

> 
> Remarque : La version 5.6 n'apparaît pas dans l'illustration de l'auteur car elle est déjà installée.
> 

---

## Section 6 : Télécharger et extraire le package de projet numérique UE

![讲义](<../images/course2/section-06-01.png>)

Ensuite, nous devons télécharger et démarrer le package de projet numérique UE.

Veuillez télécharger la dernière version du package de projet numérique UE à l'URL suivante. Une fois le téléchargement terminé, extrayez l'archive dans un répertoire distinct pour une utilisation ultérieure.

> 
> https://pan.baidu.com/s/1aApeAiIwGNvPXxR-gBj_MQ?pwd=q2jw
> 

---

## Section 7 : Installer les plugins

Une fois le moteur 5.6 installé, vous pouvez rechercher et installer les plugins illustrés dans Epic Games Launcher. Vous pouvez également demander les fichiers des plugins à l'équipe de la communauté Fay Metahuman. Extrayez les plugins dans le répertoire "plugins" du projet numérique.

---

## Section 8 : Démarrer le projet

![讲义](<../images/course2/section-08-01.png>)

Cliquez sur le fichier uproject dans le répertoire et attendez que le démarrage soit terminé. Assurez-vous de disposer d'au moins 100 Go d'espace libre sur le disque C, sinon le chargement risque d'échouer.

---

## Section 9 : Vérifier les plugins

![讲义](<../images/course2/section-09-01.png>)

Une fois le projet démarré, cliquez sur le menu "Outils", sélectionnez "Plugins", puis "Installés". Assurez-vous que les 4 plugins récemment installés sont bien activés.

---

## Section 10 : Exécuter un aperçu du projet

![讲义](<../images/course2/section-10-01.png>)

Après avoir fermé la fenêtre des plugins, cliquez sur le bouton "Exécuter" en haut. Vous verrez alors le Metahuman en mode aperçu. Le Metahuman se connectera automatiquement à Fay.

---

## Section 11 : Vérifier la connexion et tester le dialogue

![讲义](<../images/course2/section-11-01.png>)

La dernière étape consiste à vérifier si la connexion entre le Metahuman UE et Fay a été correctement établie et à effectuer un test de dialogue complet.

Une fois le Metahuman UE démarré, retournez à l'interface de gestion de Fay pour vérifier. En haut à gauche, à l'emplacement du logo Fay, vous verrez plusieurs voyants d'état. Si le deuxième voyant est allumé, cela signifie que le Metahuman UE est connecté avec succès au service Fay et que le lien de communication bidirectionnel est entièrement établi.

Après avoir confirmé que la connexion est réussie, vous pouvez saluer le Metahuman via le microphone. Essayez de dire : "Bonjour, peux-tu te présenter ?" et observez la réaction du Metahuman.

Si vous voyez le Metahuman bouger les lèvres et changer d'expression, et que vous entendez une réponse vocale claire dans la fenêtre d'exécution du Metahuman UE, félicitations, vous avez réussi à démarrer et connecter le Metahuman UE !

À ce stade, tout le processus de démarrage du Metahuman UE est terminé. Vous avez maintenant un partenaire numérique capable d'écouter, de parler et d'interagir. Vous pouvez commencer à explorer de nombreux scénarios d'application intéressants.

---
---

# Groupe de discussion UE (pour obtenir gratuitement des plugins et échanger tranquillement)
![交流群](<../images/1280X1280.JPEG>)