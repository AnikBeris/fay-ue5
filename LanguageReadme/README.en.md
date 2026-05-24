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
    <h3>UE5 Digital Human Project (Metahuman)</h3>
</div>

[This project is a complete UE digital human open-source project that can be used with the Fay digital human framework to implement various application scenarios: virtual anchors, live product promotion, product guides, voice assistants, remote voice assistants, digital human interaction, digital human interviewers and psychological assessments, Jarvis, Her](https://github.com/xszyou/Fay).

(Join the discussion group by following the official account: Fay Digital Human. Documentation available at: [​‌metahuman(ue) - Feishu Cloud Document](https://qqk9ntwbcit.feishu.cn/wiki/N33FwegdxiRXzCkZlH2czjwvnrg))

# UE Digital Human Startup

- Course ID: course-1775792095810
- Author: Guo Zebin
- Version: 1.0.0
- Chapters: 5
- Play and Edit: https://player.fay-agent.com/
- Import Course Package: [UE Digital Human Startup.zip](<UE Digital Human Startup.zip>)

## Cover

![UE Digital Human Startup Cover](<images/course1/cover.png>)

## Table of Contents

1. Machine Requirements
2. Install and Launch Fay Framework
3. Enable Microphone and Wake-up, Disable Speaker
4. Download and Run UE Digital Human Runtime Package
5. Verify Connection and Test Conversation

## Section 1: Machine Requirements

![Lecture](<images/course1/section-01-01.png>)

This tutorial requires the host configuration to be at least: RTX 2050 GPU, 7th Gen i7 CPU, 16GB RAM, 100GB storage, and Windows 10 or above.

```
This tutorial requires the host configuration to be at least: RTX 2050 GPU, 7th Gen i7 CPU, 16GB RAM, 100GB storage, and Windows 10 or above.
```

## Section 2: Install and Launch Fay Framework

![Lecture](<images/course1/section-02-01.png>)

The first step to launching the UE Digital Human is to install and launch the Fay framework.

Fay is the core driving framework of this digital human solution, responsible for handling key processes such as speech recognition, conversation generation, and speech synthesis.

Please follow the official documentation link provided in the code block on the right to complete the download and installation of Fay. The official documentation includes complete environment dependency instructions and installation steps, so please follow them strictly.

Once the installation is complete, open the main interface of Fay. You will see a simple console page, with the left menu containing entry points for features like Messages, Personas, and MCP.

On the Fay homepage, there is a prominent green circular power button in the bottom left corner. Click this button to start Fay's core services with one click.

Once started successfully, Fay's status indicator will light up, indicating that the system is running and ready to interface with the UE Digital Human.

```
# Fay Digital Human Framework Official Documentation
# Please follow the instructions at the link below to complete the download, installation, and startup of Fay

https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc

# After installation, click the green circular button on the bottom left of the Fay homepage to start the Fay service.
```

## Section 3: Enable Microphone and Wake-up, Disable Speaker

![Lecture](<images/course1/section-03-01.png>)

After starting Fay, the next very important step is to ensure that the microphone is enabled, the speaker is turned off, and the wake-up function is activated.

The UE digital human model demonstrated today does not have an independent audio capture module and relies on the local machine's Fay. However, it does have an independent audio playback module that plays audio synthesized by Fay, but this audio must still be on the same machine.

If Fay's wake-up function is turned off and you do not have professional audio capture hardware, Fay might pick up the sound emitted by the digital human itself, causing an echo loop that severely affects the conversation experience.

Once the configuration is complete, you can try saying "Hello, are you there?" into the microphone to verify if Fay can receive your voice correctly.

## Section 4: Download and Run UE Digital Human Runtime Package

![Lecture](<images/course1/section-04-01.png>)

Once the preparations on the Fay side are complete, the next step is to download and launch the UE Digital Human runtime package.

Please download the latest version of the UE Digital Human runtime package from the following link. After downloading, extract the compressed file to a separate directory, and double-click the executable file within to run it.

Once the runtime package is launched, the UE Digital Human will appear in a separate window. You will see a virtual figure dressed in white professional attire standing on a stage.

After the digital human is launched, it will automatically attempt to connect to the locally running Fay service. The entire connection process is completed automatically, and you do not need to manually configure any network settings or addresses. This automatic connection design greatly simplifies the deployment process, allowing non-technical users to quickly get started and lowering the barrier to setting up a complete digital human system.

```
# UE Digital Human Runtime Package Download Link
# After downloading, extract and double-click the executable file to run
# The digital human will automatically connect to the locally running Fay service after launching

 https://pan.baidu.com/s/1olc-Jd9rH-PcWkdBK2Hc6Q?pwd=kwyd
```

## Section 5: Verify Connection and Test Conversation

![Lecture](<images/course1/section-05-01.png>)

The final step is to verify whether the UE Digital Human is successfully connected to Fay and conduct a complete conversation test.

After launching the UE Digital Human, return to the Fay management interface to check. In the top left corner of Fay's logo position, you will see several status indicators—if the second light is on, it means the UE Digital Human has successfully connected to the Fay service, and the two-way communication link is fully established.

Once the connection is confirmed, you can greet the digital human through the microphone. Try saying: "Hello, can you introduce yourself?" and observe the digital human's response.

If you see the digital human showing lip movements and facial expressions, and hear a clear voice response from the UE Digital Human's runtime window, congratulations! You have successfully completed the startup and integration of the UE Digital Human!

At this point, the entire UE Digital Human startup process is complete. You now have a digital human companion that can listen, speak, and interact. You can start exploring more interesting application scenarios.

# UE Digital Human Project Editing

- Course ID: course-1775804088429
- Author: Guo Zebin
- Version: 1.0.0
- Chapters: 11
- Play and Edit: https://player.fay-agent.com/
- Import Course Package: UE Digital Human Project Editing.zip

## Cover

![UE Digital Human Project Editing Cover](<images/course2/cover.png>)

## Table of Contents

1. Machine Requirements
2. Install and Launch Fay Framework
3. Enable Microphone and Wake-up, Disable Speaker
4. Install Epic Games Launcher
5. Install UE 5.6 Engine
6. Download and Extract UE Digital Human Project Package
7. Install Plugins
8. Launch Project
9. Check Plugins
10. Run Project Preview
11. Verify Connection and Test Conversation

## Section 1: Machine Requirements

![Lecture](<images/course2/section-01-01.png>)

This tutorial requires the host configuration to be at least: RTX 3060 GPU, 10th Gen i7 CPU, 32GB RAM, 200GB storage, and Windows 10 or above.

```
This tutorial requires the host configuration to be at least: RTX 3060 GPU, 10th Gen i7 CPU, 32GB RAM, 200GB storage, and Windows 10 or above.
```

## Section 2: Install and Launch Fay Framework

![Lecture](<images/course2/section-02-01.png>)

The first step to launching the UE Digital Human is to install and launch the Fay framework.

Fay is the core driving framework of this digital human solution, responsible for handling key processes such as speech recognition, conversation generation, and speech synthesis.

Please follow the official documentation link provided in the code block on the right to complete the download and installation of Fay. The official documentation includes complete environment dependency instructions and installation steps, so please follow them strictly.

Once the installation is complete, open the main interface of Fay. You will see a simple console page, with the left menu containing entry points for features like Messages, Personas, and MCP.

On the Fay homepage, there is a prominent green circular power button in the bottom left corner. Click this button to start Fay's core services with one click.

Once started successfully, Fay's status indicator will light up, indicating that the system is running and ready to interface with the UE Digital Human.

```
# Fay Digital Human Framework Official Documentation
# Please follow the instructions at the link below to complete the download, installation, and startup of Fay

https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc
```

# After installation, click the green circular button at the bottom left corner of the Fay homepage to start the Fay service.
```

## Section 3: Enable Microphone, Wake-up Function, and Disable Speaker

![Lecture](<images/course2/section-03-01.png>)

Once Fay has started successfully, the next critical step is to ensure that the microphone is turned on, the speaker is turned off, and the wake-up function is enabled. 

The UE digital human model demonstrated today does not have an independent audio capture module and relies on Fay running on the local machine. However, it does have an independent audio playback module that plays audio synthesized by Fay. This audio must still be played on the same machine.

If the wake-up function in Fay is turned off and you do not have professional audio capture hardware, Fay might pick up the sound emitted by the digital human itself, causing an echo loop that severely impacts the conversation experience.

Once the configuration is complete, you can try speaking into the microphone and say, "Hello, are you there?" to verify whether Fay can successfully receive your voice.

## Section 4: Install Epic Games Launcher

![Lecture](<images/course2/section-04-01.png>)

Next, go to the UE official website https://www.epicgames.com/ to download the Epic Games Launcher and complete the installation.

```
UE official website: https://www.epicgames.com/
```

## Section 5: Install Unreal Engine 5.6

![Lecture](<images/course2/section-05-01.png>)

Next, open the Epic Games Launcher, select the "Unreal Engine" tab on the left, then choose "Library" from the top menu. Click the "+" icon next to the engine version, select version 5.6 from the dropdown menu in the engine block, click "Install," and wait for the installation to complete.

```
Note: The author's illustration does not show version 5.6 because it has already been installed.
```

## Section 6: Download and Extract the UE Digital Human Project Package

![Lecture](<images/course2/section-06-01.png>)

Next, we need to download and launch the UE Digital Human project package.

Please download the latest version of the UE Digital Human project package from the following URL. After downloading, extract the compressed file to a separate directory for later use.

```
https://pan.baidu.com/s/1aApeAiIwGNvPXxR-gBj_MQ?pwd=q2jw
```

## Section 7: Install Plugins

After installing the 5.6 engine, you can search for and install the plugins shown in the image via the Epic Games Launcher. Alternatively, you can request the plugin package from the Fay Digital Human community staff. Extract the plugins into the "plugins" directory of the digital human project.

## Section 8: Launch the Project

![Lecture](<images/course2/section-08-01.png>)

Click the uproject file in the directory and wait for the launch to complete. Make sure your C drive has at least 100GB of free space; otherwise, loading may fail.

## Section 9: Check Plugins

![Lecture](<images/course2/section-09-01.png>)

After the project launches, click the "Tools" menu, select "Plugins," then choose "Installed." Ensure that the four plugins you just installed are enabled.

## Section 10: Run Project Preview

![Lecture](<images/course2/section-10-01.png>)

After confirming the plugins are enabled, click the "Run" button at the top. You will see the digital human in preview mode. The digital human will automatically connect to Fay.

## Section 11: Verify Connection and Conduct a Conversation Test

![Lecture](<images/course2/section-11-01.png>)

The final step is to verify whether the connection between the UE digital human and Fay has been successfully established and conduct a complete conversation test.

After launching the UE digital human, return to the Fay management interface to check. At the top left corner near the Fay logo, you will see several status indicator lights. If the second light is on, it means the UE digital human has successfully connected to the Fay service, and the two-way communication link has been fully established.

Once the connection is confirmed, you can start interacting with the digital human by speaking into the microphone. Try saying, "Hello, please introduce yourself," and observe the digital human's response.

If you see the digital human displaying lip movements and facial expressions, and you hear clear voice responses from the UE digital human's running window, congratulations! You have successfully completed the startup and integration of the UE digital human.

At this point, the entire UE digital human startup process is complete. You now have a digital human companion that can listen, speak, and interact. You can start exploring more interesting application scenarios.

# UE Special Interest Group (Free Plugin Access and Quiet Discussions)
![Group](<images/1280X1280.JPEG>)
