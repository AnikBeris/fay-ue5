```markdown
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

- [Ce projet est un projet open-source complet de digital human basé sur UE, qui peut être utilisé avec le framework Fay pour réaliser divers scénarios d'application : animateur virtuel, vente en direct, guide d'achat, assistant vocal, assistant vocal à distance, interaction avec des digital humans, recruteur digital et évaluation psychologique, Jarvis, Her](https://github.com/xszyou/Fay)

- Pour rejoindre le groupe de discussion, veuillez suivre le compte officiel : fay数字人. Adresse de la documentation : [​‌metahuman(ue) - 飞书云文档](https://qqk9ntwbcit.feishu.cn/wiki/N33FwegdxiRXzCkZlH2czjwvnrg)

# Démarrage du digital human UE
| | |
|-------------:|:-------------|
| **ID du cours**     | `course-1775792095810` |
| **Auteur**          | `郭泽斌` |
| **Version**         | `1.0.` |
| **Nombre de chapitres** | `5` |
| **Lecture et modification** | https://player.fay-agent.com |
| **Importer le package du cours** | [Démarrage du digital human UE.zip](<./UE 数字人启动.zip>) |

## Couverture

![Couverture du cours Démarrage du digital human UE](<./images/course1/cover.png>)

## Table des matières

> 1. Configuration requise pour la machine
> 2. Installation et démarrage du framework Fay
> 3. Activation du microphone et de l'éveil, désactivation des haut-parleurs
> 4. Téléchargement et exécution du package de démarrage du digital human UE
> 5. Vérification de la connexion et test de dialogue

---

## Section 1 : Configuration requise pour la machine

![Support de cours](<./images/course1/section-01-01.png>)

> [!NOTE]
> `Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 2050, processeur i7 de 7e génération, 16 Go de RAM, 100 Go de disque dur, système d'exploitation Windows 10 ou supérieur.`
> 
> `Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 2050, processeur i7 de 7e génération, 16 Go de RAM, 100 Go de disque dur, système d'exploitation Windows 10 ou supérieur.`

---

## Section 2 : Installation et démarrage du framework Fay

![Support de cours](<./images/course1/section-02-01.png>)

La première étape pour démarrer le digital human UE est d'installer et de démarrer le framework Fay.

Fay est le noyau du système digital human présenté ici. Il est responsable des fonctions clés telles que la reconnaissance vocale, la génération de dialogues et la synthèse vocale.

Veuillez d'abord suivre le lien vers la documentation officielle fourni dans le bloc de code à droite pour télécharger et installer Fay. La documentation officielle contient des instructions complètes sur les dépendances requises et les étapes d'installation. Veuillez suivre ces instructions à la lettre.

Une fois l'installation terminée, ouvrez l'interface principale de Fay. Vous verrez une console simple, avec un menu à gauche contenant des entrées pour des fonctionnalités telles que Messages, Personnages, et MCP.

Sur la page d'accueil de Fay, dans le coin inférieur gauche, se trouve un bouton d'alimentation rond et vert bien visible. Cliquez sur ce bouton pour démarrer les services principaux de Fay en un seul clic.

Une fois le démarrage réussi, le voyant d'état de Fay s'allumera, indiquant que le système est opérationnel et prêt à se connecter au digital human UE.

> [!NOTE]
> Documentation officielle du framework Fay
> Veuillez suivre les instructions du lien ci-dessous pour télécharger, installer et démarrer Fay :
> 
> https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc
> 
> Une fois l'installation terminée, cliquez sur le bouton rond vert en bas à gauche de la page d'accueil de Fay pour démarrer les services Fay.

---

## Section 3 : Activation du microphone et de l'éveil, désactivation des haut-parleurs

![Support de cours](<./images/course1/section-03-01.png>)

Une fois Fay démarré, l'étape suivante essentielle consiste à s'assurer que le microphone est activé, que les haut-parleurs sont désactivés et que la fonction d'éveil est activée.

Le modèle de digital human UE présenté aujourd'hui ne dispose pas d'un module de capture sonore indépendant. Il dépend donc du framework Fay installé sur la machine locale. Cependant, il possède un module de lecture sonore indépendant, qui jouera l'audio synthétisé par Fay, mais cet audio doit être lu sur la même machine.

Si la fonction d'éveil de Fay est désactivée et que vous ne disposez pas d'un matériel de capture sonore professionnel, Fay pourrait capter les sons émis par le digital human lui-même, ce qui entraînerait une boucle d'écho et nuirait gravement à l'expérience de dialogue.

Une fois la configuration terminée, vous pouvez essayer de dire dans le microphone : "Bonjour, es-tu là ?" pour vérifier si Fay reçoit correctement votre voix.

---

## Section 4 : Téléchargement et exécution du package de démarrage du digital human UE

![Support de cours](<./images/course1/section-04-01.png>)

Une fois les préparatifs du côté de Fay terminés, nous devons télécharger et exécuter le package de démarrage du digital human UE.

Veuillez télécharger la dernière version du package de démarrage du digital human UE à l'adresse suivante. Une fois le téléchargement terminé, décompressez l'archive dans un répertoire distinct, puis double-cliquez sur le fichier exécutable (exe) contenu dans le dossier.

Après le démarrage du package, le digital human UE apparaîtra dans une fenêtre distincte. Vous verrez une figure virtuelle vêtue d'une tenue professionnelle blanche, debout sur une scène.

Une fois le digital human démarré, il tentera automatiquement de se connecter au service Fay déjà en cours d'exécution sur votre machine locale. Ce processus de connexion est entièrement automatisé, vous n'avez pas besoin de configurer manuellement le réseau ou les adresses. Cette conception simplifie grandement le processus de déploiement, permettant ainsi aux utilisateurs non techniques de se familiariser rapidement avec le système, tout en réduisant les obstacles à la mise en place d'un système de digital human complet.

> [!NOTE]
> Adresse de téléchargement du package de démarrage du digital human UE :
> 
> Après téléchargement, veuillez décompresser l'archive et double-cliquer sur le fichier exécutable (exe) contenu dans le dossier.
> 
> Une fois le digital human démarré, il se connectera automatiquement au service Fay en cours d'exécution sur la machine locale.
> 
> https://pan.baidu.com/s/1olc-Jd9rH-PcWkdBK2Hc6Q?pwd=kwyd

---

## Section 5 : Vérification de la connexion et test de dialogue

![Support de cours](<./images/course1/section-05-01.png>)

La dernière étape consiste à vérifier si la connexion entre le digital human UE et Fay a été établie avec succès, et à effectuer un test de dialogue complet.

Après le démarrage du digital human UE, retournez à l'interface de gestion de Fay pour vérifier. Dans le coin supérieur gauche, à l'emplacement du logo Fay, vous verrez plusieurs voyants d'état. Si le deuxième voyant s'allume, cela signifie que le digital human UE s'est connecté avec succès au service Fay, et que la communication bidirectionnelle est entièrement opérationnelle.

Une fois la connexion confirmée, vous pouvez saluer le digital human via le microphone. Essayez de dire : "Bonjour, peux-tu te présenter ?" et observez la réaction du digital human.

Si vous voyez le digital human bouger ses lèvres et changer d'expression, et que vous entendez une réponse vocale claire dans la fenêtre d'exécution du digital human UE, félicitations ! Vous avez réussi à démarrer et connecter le digital human UE.

À ce stade, le processus de démarrage du digital human UE est entièrement terminé. Vous disposez désormais d'un partenaire digital capable d'écouter, de parler et d'interagir. Vous pouvez maintenant explorer davantage de scénarios d'application intéressants.

---
---

# Édition du projet digital human UE
| | |
|:-------------|:-------------|
| **ID du cours**     | `course-1775804088429` |
| **Auteur**          | `郭泽斌` |
| **Version**         | `1.0.0` |
| **Nombre de chapitres** | `11` |
| **Lecture et modification** | https://player.fay-agent.com |
| **Importer le package du cours** | [Édition du projet digital human UE.zip](<./UE 数字人工程编辑.zip>) |

## Couverture

![Couverture du cours Édition du projet digital human UE](<./images/course2/cover.png>)

## Table des matières

> 1. Configuration requise pour la machine
> 2. Installation et démarrage du framework Fay
> 3. Activation du microphone et de l'éveil, désactivation des haut-parleurs
> 4. Installation d'Epic Games Launcher
> 5. Installation du moteur UE 5.6
> 6. Téléchargement et décompression du package du projet digital human UE
> 7. Installation des plugins
> 8. Démarrage du projet
> 9. Vérification des plugins
> 10. Aperçu du projet en cours d'exécution
> 11. Vérification de la connexion et test de dialogue

---

## Section 1 : Configuration requise pour la machine
```

Voici la traduction en français selon vos règles :

---

![讲义](<./images/course2/section-01-01.png>)

> [!NOTE]
> `Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 3060, processeur i7 de 10e génération, 32 Go de RAM, 200 Go de disque dur, système d'exploitation Windows 10 ou supérieur.`
> 
> `Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 3060, processeur i7 de 10e génération, 32 Go de RAM, 200 Go de disque dur, système d'exploitation Windows 10 ou supérieur.`

---

## Section 2 : Installer et lancer le framework Fay

![讲义](<./images/course2/section-02-01.png>)

La première étape pour démarrer le Metahuman dans UE consiste à installer et lancer le framework Fay.

Fay est le framework central qui pilote cette solution de Metahuman. Il est responsable de la reconnaissance vocale, de la génération de dialogues et de la synthèse vocale.

Veuillez d'abord télécharger et installer Fay en suivant l'URL de la documentation officielle fournie dans le bloc de code à droite. La documentation officielle contient une description complète des dépendances requises et des étapes d'installation. Suivez attentivement les instructions.

Une fois l'installation terminée, ouvrez l'interface principale de Fay. Vous verrez une page de console simple, avec un menu à gauche contenant des entrées pour les fonctionnalités telles que Messages, Personnage, MCP, etc.

Sur la page d'accueil de Fay, un bouton vert circulaire bien visible se trouve en bas à gauche. Cliquez sur ce bouton pour démarrer les services principaux de Fay en un seul clic.

Une fois le démarrage réussi, le voyant d'état de Fay s'allumera, indiquant que le système est en fonctionnement et prêt à se connecter au Metahuman dans UE.

> [!NOTE]
> Documentation officielle du framework Fay pour Metahumans
> 
> Veuillez suivre les instructions à l'adresse suivante pour télécharger, installer et démarrer Fay :
> 
> https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc
> 
> Une fois l'installation terminée, cliquez sur le bouton vert circulaire en bas à gauche de la page d'accueil de Fay pour démarrer les services de Fay.

---

## Section 3 : Activer le microphone, désactiver le haut-parleur et activer le réveil

![讲义](<./images/course2/section-03-01.png>)

Une fois Fay lancé, l'étape suivante, très importante, consiste à vérifier que le microphone est activé, que le haut-parleur est désactivé et que la fonction de réveil est activée. 

Le modèle de Metahuman présenté aujourd'hui ne dispose pas de module de capture audio indépendant. Il dépend donc de Fay sur la machine locale. Cependant, il possède un module de lecture audio indépendant qui jouera l'audio généré par Fay. Cet audio doit néanmoins être lu sur la même machine.

Si la fonction de réveil de Fay est désactivée et que vous ne disposez pas de matériel de capture audio professionnel, Fay risque de capter les sons émis par le Metahuman lui-même, ce qui entraînera une boucle d'écho et dégradera considérablement l'expérience de dialogue.

Une fois la configuration terminée, vous pouvez essayer de dire dans le microphone : "Bonjour, es-tu là ?", pour vérifier si Fay peut recevoir correctement votre voix.

---

## Section 4 : Installer Epic Games Launcher

![讲义](<./images/course2/section-04-01.png>)

Ensuite, rendez-vous sur le site officiel d'UE : https://www.epicgames.com pour télécharger l'installateur Epic Games Launcher et terminer son installation.

> 
> 
> Site officiel d'UE : https://www.epicgames.com
> 
> 

---

## Section 5 : Installer le moteur UE 5.6

![讲义](<./images/course2/section-05-01.png>)

Ensuite, ouvrez Epic Games Launcher, sélectionnez la section "Unreal Engine" à gauche, puis choisissez "Bibliothèque" dans la barre supérieure. Cliquez sur le bouton "+" à côté de la version du moteur, puis sélectionnez la version 5.6 dans le menu déroulant. Cliquez sur "Installer" et attendez la fin de l'installation.

> 
> Remarque : Dans l'exemple illustré, la version 5.6 n'apparaît pas car elle est déjà installée.
> 

---

## Section 6 : Télécharger et décompresser le package du projet Metahuman UE

![讲义](<./images/course2/section-06-01.png>)

Ensuite, nous devons télécharger et démarrer le package du projet Metahuman UE.

Veuillez télécharger la dernière version du package de projet Metahuman UE à l'adresse suivante. Une fois le téléchargement terminé, décompressez l'archive dans un répertoire dédié.

> 
> https://pan.baidu.com/s/1aApeAiIwGNvPXxR-gBj_MQ?pwd=q2jw
> 

---

## Section 7 : Installer les plugins

Une fois le moteur 5.6 installé, vous pouvez rechercher et installer les plugins illustrés via Epic Games Launcher. Vous pouvez également demander les packages de plugins au personnel de la communauté Fay Metahuman. Décompressez les plugins dans le répertoire "plugins" du projet Metahuman.

---

## Section 8 : Lancer le projet

![讲义](<./images/course2/section-08-01.png>)

Cliquez sur le fichier uproject dans le répertoire du projet et attendez que le lancement soit terminé. Assurez-vous d'avoir au moins 100 Go d'espace libre sur le disque C, sinon le chargement risque d'échouer.

---

## Section 9 : Vérifier les plugins

![讲义](<./images/course2/section-09-01.png>)

Une fois le projet lancé, cliquez sur le menu "Outils", sélectionnez "Plugins", puis "Installés". Assurez-vous que les 4 plugins précédemment installés sont bien activés.

---

## Section 10 : Exécuter un aperçu du projet

![讲义](<./images/course2/section-10-01.png>)

Après avoir fermé la fenêtre des plugins, cliquez sur le bouton "Exécuter" en haut. Vous verrez alors le Metahuman en mode aperçu. Le Metahuman se connectera automatiquement à Fay.

---

## Section 11 : Vérifier la connexion et tester un dialogue

![讲义](<./images/course2/section-11-01.png>)

La dernière étape consiste à vérifier si la connexion entre le Metahuman UE et Fay a bien été établie, puis à effectuer un test de dialogue complet.

Une fois le Metahuman UE lancé, revenez à l'interface de gestion de Fay. En haut à gauche, à côté du logo Fay, vous verrez plusieurs voyants d'état. Si le deuxième voyant est allumé, cela signifie que le Metahuman UE est connecté avec succès au service Fay et que le lien de communication bidirectionnel est entièrement établi.

Une fois la connexion confirmée, vous pouvez saluer le Metahuman via le microphone. Essayez de dire : "Bonjour, peux-tu te présenter ?" et observez la réaction du Metahuman.

Si vous voyez le Metahuman bouger ses lèvres et changer d'expression, et que vous entendez une réponse vocale claire dans la fenêtre d'exécution du Metahuman UE, félicitations ! Vous avez réussi à démarrer et connecter le Metahuman UE.

À ce stade, le processus de démarrage du Metahuman UE est entièrement terminé. Vous disposez désormais d'un partenaire numérique capable d'écouter, de parler et d'interagir. Vous pouvez maintenant explorer davantage de scénarios d'application intéressants.

---
---

# Groupe de discussion UE (pour obtenir gratuitement des plugins et échanger tranquillement)
![交流群](<./images/1280X1280.JPEG>)