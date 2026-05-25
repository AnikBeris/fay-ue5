
Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 2050, processeur i7 de 7e génération, 16 Go de RAM, 100 Go de disque dur, système d'exploitation Windows 10 ou supérieur.

# Documentation officielle du framework Fay Digital Human
# Veuillez suivre les instructions sur le site suivant pour télécharger, installer et démarrer Fay

https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc

# Une fois l'installation terminée, cliquez sur le bouton circulaire vert en bas à gauche de la page d'accueil de Fay pour démarrer le service Fay.

# Adresse de téléchargement du package de l'humain numérique UE
# Après téléchargement, décompressez et double-cliquez sur le fichier exécutable (exe) pour démarrer
# Une fois démarré, l'humain numérique se connectera automatiquement au service Fay en cours d'exécution sur la machine locale

https://pan.baidu.com/s/1olc-Jd9rH-PcWkdBK2Hc6Q?pwd=kwyd

Ce tutoriel nécessite une configuration minimale de l'hôte : carte graphique RTX 3060, processeur i7 de 10e génération, 32 Go de RAM, 200 Go de disque dur, système d'exploitation Windows 10 ou supérieur.

# Documentation officielle du framework Fay Digital Human
# Veuillez suivre les instructions sur le site suivant pour télécharger, installer et démarrer Fay

https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc


## Section 3 : Activer le microphone, réveiller Fay et désactiver le haut-parleur

![Support de cours](<./images/course2/section-03-01.png>)

Une fois Fay démarré, l'étape suivante, très importante, consiste à s'assurer que le microphone est activé, que le haut-parleur est désactivé et que la fonction de réveil est activée.  
Le modèle numérique humain UE présenté aujourd'hui ne dispose pas de module de capture audio indépendant. Il dépend de Fay installé sur la machine locale. Cependant, il dispose d'un module de lecture audio indépendant, qui joue les fichiers audio générés par Fay, mais ces fichiers doivent toujours être lus sur la même machine.  
Lorsque la fonction de réveil de Fay est désactivée, si vous ne disposez pas de matériel de capture audio professionnel, Fay pourrait capter le son émis par le personnage numérique lui-même, ce qui entraînerait un effet d'écho en boucle et affecterait gravement l'expérience de la conversation.

Une fois la configuration terminée, vous pouvez essayer de dire dans le microphone : 你好，你在吗 (Bonjour, es-tu là ?) pour vérifier si Fay peut recevoir correctement votre voix.

## Section 4 : Installer Epic Games Launcher

![Support de cours](<./images/course2/section-04-01.png>)

Ensuite, rendez-vous sur le site officiel d'Unreal Engine : https://www.epicgames.com/ pour télécharger l'installateur Epic et terminer l'installation.



## Section 5 : Installer Unreal Engine 5.6

![Support de cours](<./images/course2/section-05-01.png>)

Ensuite, ouvrez Epic Games Launcher, sélectionnez l'onglet UnrealEngine sur la gauche, puis cliquez sur Library (Bibliothèque) dans la barre supérieure. Cliquez sur le bouton + à côté de la version du moteur, sélectionnez la version 5.6 dans le menu déroulant qui apparaît sous le bloc du moteur, puis cliquez sur Install (Installer) et attendez que l'installation soit terminée.



## Section 6 : Télécharger et extraire le projet UE Digital Human

![Support de cours](<./images/course2/section-06-01.png>)

Ensuite, nous devons télécharger et lancer le projet UE Digital Human.

Veuillez télécharger la dernière version du projet UE Digital Human à l'adresse suivante. Une fois le téléchargement terminé, extrayez l'archive dans un répertoire distinct pour une utilisation ultérieure.



## Section 7 : Installer les plugins

Une fois le moteur Unreal Engine 5.6 installé, vous pouvez rechercher et installer les plugins illustrés dans Epic Games Launcher. Vous pouvez également demander les fichiers des plugins à l'équipe de la communauté Fay Digital Human. Extrayez les plugins dans le répertoire plugins du projet numérique humain.

## Section 8 : Lancer le projet

![Support de cours](<./images/course2/section-08-01.png>)

Cliquez sur le fichier uproject dans le répertoire et attendez que le lancement soit terminé. Assurez-vous d'avoir au moins 100 Go d'espace libre sur le disque C, sinon le chargement risque d'échouer.

## Section 9 : Vérifier les plugins

![Support de cours](<./images/course2/section-09-01.png>)

Après le lancement du projet, cliquez sur le menu Outils, sélectionnez Plugins, puis Installés. Assurez-vous que les quatre plugins installés précédemment sont bien cochés.

## Section 10 : Exécuter un aperçu du projet

![Support de cours](<./images/course2/section-10-01.png>)

Après avoir fermé la fenêtre des plugins, cliquez sur le bouton Exécuter en haut. Vous verrez le personnage numérique en mode aperçu. Le personnage numérique se connectera automatiquement à Fay.

## Section 11 : Vérifier la connexion et tester une conversation

![Support de cours](<./images/course2/section-11-01.png>)

La dernière étape consiste à vérifier si la connexion entre le personnage numérique UE et Fay est bien établie, puis à effectuer un test de conversation complet.

Une fois le personnage numérique UE lancé, revenez à l'interface de gestion de Fay pour vérifier. Dans le coin supérieur gauche, à l'emplacement du logo Fay, vous verrez plusieurs voyants d'état. Si le deuxième voyant est allumé, cela signifie que le personnage numérique UE est connecté avec succès au service Fay, et que la communication bidirectionnelle est entièrement établie.

Une fois la connexion confirmée, vous pouvez saluer le personnage numérique via le microphone. Essayez de dire : 你好，请介绍一下你自己 (Bonjour, peux-tu te présenter ?) et observez la réaction du personnage numérique.

Si vous voyez des mouvements de lèvres et des expressions faciales sur le personnage numérique, et que vous entendez une réponse vocale claire dans la fenêtre d'exécution du personnage numérique UE, félicitations, vous avez réussi à lancer et connecter le personnage numérique UE !

À ce stade, tout le processus de lancement du personnage numérique UE est terminé. Vous disposez désormais d'un partenaire numérique capable d'écouter, de parler et d'interagir. Vous pouvez commencer à explorer de nombreuses applications intéressantes.

# Groupe d'échange dédié à Unreal Engine (obtenez des plugins gratuitement et échangez en toute tranquillité)
![Groupe d'échange](<./images/1280X1280.JPEG>)