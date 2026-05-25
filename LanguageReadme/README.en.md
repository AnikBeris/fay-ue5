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

- [This project is a complete UE digital human open-source project that can be paired with the Fay digital human framework to achieve various application scenarios: virtual hosts, live product promotion, product guidance, voice assistants, remote voice assistants, digital human interaction, digital human interviewers and psychological assessments, Jarvis, Her](https://github.com/xszyou/Fay)

- To join the community group, please follow the official account: Fay Digital Human. Documentation address: [​‌metahuman(ue) - Feishu Cloud Document](https://qqk9ntwbcit.feishu.cn/wiki/N33FwegdxiRXzCkZlH2czjwvnrg)

# UE Digital Human Startup
| | |
|-------------:|:-------------|
| **Course ID**     | `course-1775792095810` |
| **Author**       | `Guo Zebin` |
| **Version**       | `1.0.` |
| **Number of Chapters**     | `5` |
| **Play and Modify** | https://player.fay-agent.com |
| **Import Course Package** | [UE Digital Human Startup.zip](<../UE 数字人启动.zip>) |

## Cover

![UE Digital Human Startup Cover](<../images/course1/cover.png>)

## Table of Contents

> 1. Machine Requirements  
> 2. Install and Launch Fay Framework  
> 3. Enable Microphone and Wake-Up, Disable Speaker  
> 4. Download and Run UE Digital Human Package  
> 5. Verify Connection and Conduct Dialogue Test  

---

## Section 1: Machine Requirements

![Lecture](<../images/course1/section-01-01.png>)

> [!NOTE]
> `This tutorial requires a host configuration of at least: RTX 2050 graphics card, 7th-gen i7, 16GB RAM, 100GB hard drive, Windows 10 or higher operating system.`  
> 
> `This tutorial requires a host configuration of at least: RTX 2050 graphics card, 7th-gen i7, 16GB RAM, 100GB hard drive, Windows 10 or higher operating system.`  

---

## Section 2: Install and Launch Fay Framework

![Lecture](<../images/course1/section-02-01.png>)

The first step to launching the UE digital human is installing and launching the Fay framework.

Fay is the core driving framework of this digital human solution, responsible for key processes such as speech recognition, dialogue generation, and speech synthesis.

Please follow the official documentation URL provided in the code block on the right to complete the download and installation of Fay. The official documentation contains complete environment dependency instructions and installation steps. Please strictly follow the requirements.

After installation, open Fay's main interface. You will see a simple console page, with the left menu containing entry points for functions such as messages, personas, and MCP.

On the Fay homepage, there is a prominent green circular power button in the lower-left corner. Click this button to start Fay's core services with one click.

Once successfully started, Fay's status indicator will light up, indicating that the system has entered running mode and is ready to interface with the UE digital human.

> [!NOTE]
> Fay Digital Human Framework Official Documentation  
> Please follow the instructions at the following URL to complete the download, installation, and startup of Fay:  
> 
> https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc  
> 
> After installation, click the green circular button in the lower-left corner of Fay's homepage to start Fay services.

---

## Section 3: Enable Microphone and Wake-Up, Disable Speaker

![Lecture](<../images/course1/section-03-01.png>)

After Fay is successfully started, the next critical step is to ensure that the microphone is enabled, the speaker is disabled, and wake-up is activated.  

The UE digital human model demonstrated today does not have an independent sound pickup module and relies on Fay running on the local machine. However, it does have an independent sound playback module that plays audio synthesized by Fay, which must also run on the same machine.  

If Fay's wake-up function is disabled and you lack professional sound pickup hardware, Fay may pick up the sound emitted by the digital human itself, causing echo loops that severely impact the dialogue experience.

Once the configuration is complete, you can try saying "Hello, are you there?" into the microphone to verify whether Fay can successfully receive your voice.

---

## Section 4: Download and Run UE Digital Human Package

![Lecture](<../images/course1/section-04-01.png>)

After completing the preparations on Fay's side, the next step is to download and launch the UE digital human package.

Please download the latest version of the UE digital human package from the following URL. Once downloaded, extract the compressed package into a separate directory and double-click the executable file within to run it.

After launching the package, the UE digital human will appear in a separate window. You will see a virtual figure dressed in white professional attire standing on a stage.

Once the digital human is started, it will automatically attempt to connect to the locally running Fay service. The entire connection process is completed automatically, and you do not need to manually configure any network settings or addresses. This automatic connection design greatly simplifies the deployment process, allowing non-technical users to quickly get started and lowering the threshold for setting up a complete digital human system.

> [!NOTE]
> UE Digital Human Package Download URL  
> 
> After downloading, extract the package and double-click the executable file within to run it.  
> 
> The digital human will automatically connect to the locally running Fay service upon startup.  
> 
> https://pan.baidu.com/s/1olc-Jd9rH-PcWkdBK2Hc6Q?pwd=kwyd  

---

## Section 5: Verify Connection and Conduct Dialogue Test

![Lecture](<../images/course1/section-05-01.png>)

The final step is to verify whether the UE digital human has successfully connected to Fay and conduct a complete dialogue test.

After starting the UE digital human, return to Fay's management interface to check. At the top left of Fay's logo area, you will see several status indicators—if the second indicator lights up, it means the UE digital human has successfully connected to Fay services, and the communication link between the two sides has been fully established.

Once the connection is confirmed, you can greet the digital human through the microphone. Try saying: "Hello, please introduce yourself," and observe the digital human's response.

If you see the digital human displaying changes in lip movement and facial expressions, and hear clear voice replies from the UE digital human's running window, congratulations! You have successfully completed the startup and integration of the UE digital human.

At this point, the entire UE digital human startup process is complete. You now have a digital human companion that can listen, speak, and interact. You can start exploring more interesting application scenarios.

---
---

# UE Digital Human Project Editing
| | |
|:-------------|:-------------|
| **Course ID**     | `course-1775804088429` |
| **Author**       | `Guo Zebin` |
| **Version**       | `1.0.0` |
| **Number of Chapters**     | `11` |
| **Play and Modify** | https://player.fay-agent.com |
| **Import Course Package** | [UE Digital Human Project Editing.zip](<../UE 数字人工程编辑.zip>) |

## Cover

![UE Digital Human Project Editing Cover](<../images/course2/cover.png>)

## Table of Contents

> 1. Machine Requirements  
> 2. Install and Launch Fay Framework  
> 3. Enable Microphone and Wake-Up, Disable Speaker  
> 4. Install Epic Games Launcher  
> 5. Install UE 5.6 Engine  
> 6. Download and Extract UE Digital Human Project Package  
> 7. Install Plugins  
> 8. Launch Project  
> 9. Check Plugins  
> 10. Run Project Preview  
> 11. Verify Connection and Conduct Dialogue Test  

---

## Section 1: Machine Requirements

![Lecture Notes](<../images/course2/section-01-01.png>)

> [!NOTE]
> `This tutorial requires a host configuration of at least: RTX 3060 GPU, 10th Gen i7, 32GB RAM, 200GB storage, and Windows 10 or higher.`
> 
> `This tutorial requires a host configuration of at least: RTX 3060 GPU, 10th Gen i7, 32GB RAM, 200GB storage, and Windows 10 or higher.`

---

## Section 2: Installing and Launching the Fay Framework

![Lecture Notes](<../images/course2/section-02-01.png>)

The first step to launching the UE digital human is to install and start the Fay framework.

Fay is the core driving framework for this digital human solution, responsible for handling key processes such as speech recognition, dialogue generation, and speech synthesis.

First, follow the official documentation link provided in the code block on the right to download and install Fay. The official documentation includes complete details about environment dependencies and installation steps. Please follow the instructions carefully.

Once the installation is complete, open the main interface of Fay. You will see a simple console page, with a menu on the left that includes entry points for features like Messages, Persona, and MCP.

On the Fay homepage, there is a prominent green circular power button in the lower-left corner. Click this button to start Fay's core services with one click.

Once the startup is successful, Fay's status indicator light will turn on, indicating that the system is now running and ready to interface with the UE digital human.

> [!NOTE]
> Fay Digital Human Framework Official Documentation
> 
> Please follow the instructions at the following URL to complete the download, installation, and startup of Fay:
> 
> https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc
> 
> After installation, click the green circular button on the bottom left of the Fay homepage to start the Fay service.

---

## Section 3: Enabling the Microphone, Wake-Up, and Disabling the Speaker

![Lecture Notes](<../images/course2/section-03-01.png>)

After starting Fay, the next crucial step is to ensure that the microphone is enabled, the speaker is turned off, and the wake-up feature is activated.

The UE digital human model demonstrated today does not have an independent sound pickup module and relies on Fay running on the local machine. However, it does have an independent sound playback module that will play audio synthesized by Fay, but this audio must still be on the same machine.

If Fay's wake-up feature is turned off and you do not have professional sound pickup hardware, Fay might pick up the audio output from the digital human itself, causing an echo loop that severely affects the conversation experience.

After configuring these settings, you can test Fay by speaking into the microphone and saying, "Hello, are you there?" to verify if Fay can receive your voice correctly.

---

## Section 4: Installing the Epic Games Launcher

![Lecture Notes](<../images/course2/section-04-01.png>)

Next, go to the UE official website https://www.epicgames.com to download the Epic Installer and complete the installation.

> 
> 
> UE Official Website: https://www.epicgames.com
> 
> 

---

## Section 5: Installing Unreal Engine 5.6

![Lecture Notes](<../images/course2/section-05-01.png>)

Next, open the Epic Games Launcher, select the "Unreal Engine" tab on the left, then choose "Library" from the top menu. Click the plus sign next to the engine version, select version 5.6 from the dropdown menu that appears below, and click "Install." Wait for the installation to complete.

> 
> Note: The version 5.6 is not shown in the author's illustration because it has already been installed.
> 

---

## Section 6: Downloading and Extracting the UE Digital Human Project Package

![Lecture Notes](<../images/course2/section-06-01.png>)

Next, we need to download and launch the UE Digital Human project package.

Please download the latest version of the UE Digital Human project package from the following URL. Once the download is complete, extract the compressed file to a separate directory for later use.

> 
> https://pan.baidu.com/s/1aApeAiIwGNvPXxR-gBj_MQ?pwd=q2jw
> 

---

## Section 7: Installing Plugins

After installing the 5.6 engine, you can search for and install the plugins shown in the image through the Epic Launcher. Alternatively, you can request the plugin package from the Fay Digital Human community staff. Extract the plugins into the "plugins" directory of the digital human project.

---

## Section 8: Launching the Project

![Lecture Notes](<../images/course2/section-08-01.png>)

Click the uproject file in the directory and wait for the launch to complete. Please ensure that at least 100GB of free space is available on the C drive; otherwise, the loading process may fail.

---

## Section 9: Checking Plugins

![Lecture Notes](<../images/course2/section-09-01.png>)

After launching the project, click on the "Tools" menu, select "Plugins," and then choose "Installed." Ensure that the four plugins you installed earlier are selected.

---

## Section 10: Running the Project Preview

![Lecture Notes](<../images/course2/section-10-01.png>)

After closing the plugin settings, click the "Run" button at the top. You will see the digital human in a preview running state. The digital human will automatically connect to Fay.

---

## Section 11: Verifying Connection and Conducting a Conversation Test

![Lecture Notes](<../images/course2/section-11-01.png>)

The final step is to verify whether the connection between the UE digital human and Fay has been successfully established and to conduct a complete conversation test.

After launching the UE digital human, return to the Fay management interface to check. In the upper-left corner where the Fay logo is located, you will see several status indicator lights. If the second light is on, it means the UE digital human has successfully connected to the Fay service, and the two-way communication link has been fully established.

Once the connection is confirmed, you can greet the digital human through the microphone. Try saying, "Hello, can you introduce yourself?" and observe the digital human's response.

If you see the digital human's mouth and facial expressions change and hear a clear voice response from the UE digital human's running window, congratulations! You have successfully completed the startup and integration of the UE digital human.

At this point, the entire UE digital human startup process is complete. You now have a digital human companion that can listen, speak, and interact. You can start exploring more interesting application scenarios.

---
---

# UE Special Interest Group (Free Plugin Access and Quiet Discussions)
![Group Chat](<../images/1280X1280.JPEG>)