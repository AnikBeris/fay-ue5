```html
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./images/icon.png" alt="Fay">
    <img alt="Project Logo" src="./images/icon.png" alt="Fay" width="256" height="auto">
  </picture>
    <h1>FAY</h1>
    <h3>UE5 Digital Human Project (Metahuman)</h3>
</div>

[This project is a complete open-source UE digital human project that can be used with the Fay digital human framework to implement various application scenarios: virtual anchors, live product promotion, product guides, voice assistants, remote voice assistants, digital human interaction, digital human interviewers and psychological evaluations, Jarvis, Her](https://github.com/xszyou/Fay).

(To join the user group, please follow the official account: Fay Digital Human. Documentation is available at: [metahuman(ue) - Feishu Docs](https://qqk9ntwbcit.feishu.cn/wiki/N33FwegdxiRXzCkZlH2czjwvnrg))

# UE Digital Human Startup

- Course ID: course-1775792095810
- Author: Guo Zebin
- Version: 1.0.0
- Number of Chapters: 5
- Play and Modify: https://player.fay-agent.com/
- Import Course Package: UE Digital Human Startup.zip

## Cover

![UE Digital Human Startup Cover](<images/course1/cover.png>)

## Table of Contents

1. Machine Requirements  
2. Install and Launch Fay Framework  
3. Enable Microphone and Wake-Up, Disable Speaker  
4. Download and Run UE Digital Human Runtime Package  
5. Verify Connection and Test Interaction  

## Section 1: Machine Requirements

![Slide](<images/course1/section-01-01.png>)

This tutorial requires a host configuration of at least: RTX 2050 GPU, 7th Gen i7 CPU, 16GB RAM, 100GB storage, and Windows 10 or above.

```
This tutorial requires a host configuration of at least: RTX 2050 GPU, 7th Gen i7 CPU, 16GB RAM, 100GB storage, and Windows 10 or above.
```

## Section 2: Install and Launch Fay Framework

![Slide](<images/course1/section-02-01.png>)

The first step to launching the UE digital human is to install and start the Fay framework.

Fay is the core driving framework of this digital human solution, responsible for handling key processes such as speech recognition, dialogue generation, and speech synthesis.

Please follow the official documentation link provided in the code block on the right to complete the download and installation of Fay. The official documentation contains comprehensive details on environment dependencies and installation steps. Please follow the instructions carefully.

Once installed, open the main interface of Fay. You will see a simple console page, with a left-side menu containing entries for Messages, Personas, MCP, and other features.

On the Fay homepage, there is a prominent green circular power button in the bottom left corner. Click this button to start the core services of Fay with one click.

Once started successfully, the status indicator light on Fay will turn on, indicating that the system is operational and ready to interface with the UE digital human.

```
# Fay Digital Human Framework Official Documentation
# Please follow the instructions at the following URL to complete the download, installation, and startup of Fay

https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc

# After installation, click the green circular button on the bottom left of the Fay homepage to start the Fay service.
```

## Section 3: Enable Microphone and Wake-Up, Disable Speaker

![Slide](<images/course1/section-03-01.png>)

After starting Fay, the next critical step is to ensure that the microphone is enabled, the speaker is disabled, and the wake-up feature is turned on. 

The UE digital human model demonstrated today does not have an independent audio capture module and relies on Fay running on the local machine for this purpose. However, it does have an independent audio playback module that plays the audio synthesized by Fay. This audio must also be on the same machine.

If the wake-up function in Fay is turned off and you do not have professional audio capture hardware, Fay might pick up the sound emitted by the digital human itself, causing an echo loop that severely affects the interaction experience.

After completing the configuration, you can try speaking into the microphone and saying, "Hello, are you there?" to verify whether Fay can correctly receive your voice.

## Section 4: Download and Run UE Digital Human Runtime Package

![Slide](<images/course1/section-04-01.png>)

Once the preparations on the Fay side are complete, the next step is to download and launch the UE digital human runtime package.

Please download the latest version of the UE digital human runtime package from the following URL. After downloading, extract the compressed file to a separate directory, and then double-click the executable file (.exe) to run it.

After the runtime package starts, the UE digital human will appear in a separate window. You will see a virtual figure dressed in a white professional outfit standing on a stage.

Once the digital human is launched, it will automatically attempt to connect to the locally running Fay service. The entire connection process is automated, and you do not need to manually configure any network settings or addresses. This automatic connection design greatly simplifies the deployment process, allowing non-technical users to get started quickly and lowering the barrier to setting up a complete digital human system.

```
# UE Digital Human Runtime Package Download Link
# After downloading, extract the file and double-click the executable file to run it.
# The digital human will automatically connect to the locally running Fay service after startup.

https://pan.baidu.com/s/1olc-Jd9rH-PcWkdBK2Hc6Q?pwd=kwyd
```

## Section 5: Verify Connection and Test Interaction

![Slide](<images/course1/section-05-01.png>)

The final step is to verify whether the connection between the UE digital human and Fay is successful and to conduct a complete interaction test.

After starting the UE digital human, return to the Fay management interface to check. In the top-left corner near the Fay logo, you will see several status indicator lights. If the second light is on, it means that the UE digital human has successfully connected to the Fay service, and the communication link between the two systems has been fully established.

Once the connection is confirmed, you can greet the digital human through the microphone. Try saying: "Hello, please introduce yourself," and observe the digital human's response.

If you see the digital human display lip movements and facial expressions, and you hear clear audio responses from the UE digital human's runtime window, congratulations! You have successfully completed the startup and integration of the UE digital human.

At this point, the entire UE digital human startup process is complete. You now have a digital human companion that can listen, speak, and interact. You can start exploring more exciting application scenarios.

# UE Digital Human Project Editing

- Course ID: course-1775804088429
- Author: Guo Zebin
- Version: 1.0.0
- Number of Chapters: 11
- Play and Modify: https://player.fay-agent.com/
- Import Course Package: UE Digital Human Project Editing.zip

## Cover

![UE Digital Human Project Editing Cover](<images/course2/cover.png>)

## Table of Contents

1. Machine Requirements  
2. Install and Launch Fay Framework  
3. Enable Microphone and Wake-Up, Disable Speaker  
4. Install Epic Games Launcher  
5. Install UE 5.6 Engine  
6. Download and Extract UE Digital Human Project Package  
7. Install Plugins  
8. Launch Project  
9. Check Plugins  
10. Run Project Preview  
11. Verify Connection and Test Interaction  

## Section 1: Machine Requirements

![Slide](<images/course2/section-01-01.png>)

This tutorial requires a host configuration of at least: RTX 3060 GPU, 10th Gen i7 CPU, 32GB RAM, 200GB storage, and Windows 10 or above.

```
This tutorial requires a host configuration of at least: RTX 3060 GPU, 10th Gen i7 CPU, 32GB RAM, 200GB storage, and Windows 10 or above.
```

## Section 2: Install and Launch Fay Framework

![Slide](<images/course2/section-02-01.png>)

The first step to launching the UE digital human is to install and start the Fay framework.

Fay is the core driving framework of this digital human solution, responsible for handling key processes such as speech recognition, dialogue generation, and speech synthesis.

Please follow the official documentation link provided in the code block on the right to complete the download and installation of Fay. The official documentation contains comprehensive details on environment dependencies and installation steps. Please follow the instructions carefully.

Once installed, open the main interface of Fay. You will see a simple console page, with a left-side menu containing entries for Messages, Personas, MCP, and other features.

On the Fay homepage, there is a prominent green circular power button in the bottom left corner. Click this button to start the core services of Fay with one click.

Once started successfully, the status indicator light on Fay will turn on, indicating that the system is operational and ready to interface with the UE digital human.

```
# Fay Digital Human Framework Official Documentation
# Please follow the instructions at the following URL to complete the download, installation, and startup of Fay

https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc

# After installation, click the green circular button on the bottom left of the Fay homepage to start the Fay service.
```

## Section 3: Enable Microphone and Wake-Up, Disable Speaker

![Lecture](<images/course2/section-03-01.png>)

After Fay has been successfully launched, the next critical step is to ensure that the microphone is turned on, the speaker is muted, and the wake-up function is enabled.  
The UE digital human model demonstrated today does not have an independent audio capture module and relies on Fay running on the local machine. However, it does have an independent audio playback module that plays the audio synthesized by Fay, but this audio must still be played on the same machine.  
If the wake-up function of Fay is disabled and you do not have professional audio capture hardware, Fay might pick up the sound emitted by the digital human itself, causing an echo loop that severely affects the conversation experience.  

Once the configuration is complete, you can try speaking into the microphone and saying, "Hello, are you there?" to verify whether Fay can correctly receive your voice.

---

## Section 4: Installing the Epic Games Launcher

![Lecture](<images/course2/section-04-01.png>)

Next, go to the UE official website at https://www.epicgames.com/ to download the Epic Installer and complete the installation.

```
UE official website: https://www.epicgames.com/
```

---

## Section 5: Installing Unreal Engine 5.6

![Lecture](<images/course2/section-05-01.png>)

Next, open the Epic Games Launcher, select the "Unreal Engine" tab on the left, then choose "Library" from the top menu. Click the "+" button next to the engine version, select version 5.6 from the dropdown menu in the engine block, and click "Install." Wait for the installation to complete.

```
Note: The author’s illustration does not show version 5.6 because it has already been installed.
```

---

## Section 6: Downloading and Extracting the UE Digital Human Project Package

![Lecture](<images/course2/section-06-01.png>)

Next, we need to download and launch the UE Digital Human project package.

Please download the latest version of the UE Digital Human project package from the following link. After downloading, extract the compressed file to a separate directory for later use.

```
https://pan.baidu.com/s/1aApeAiIwGNvPXxR-gBj_MQ?pwd=q2jw
```

---

## Section 7: Installing Plugins

After installing the 5.6 engine, search for and install the plugins shown in the image via the Epic Games Launcher. Alternatively, you can request the plugin package from the Fay Digital Human community staff. Extract the plugins into the `plugins` directory of the digital human project.

---

## Section 8: Launching the Project

![Lecture](<images/course2/section-08-01.png>)

Click the `uproject` file in the directory and wait for the project to launch. Make sure that your C drive has at least 100GB of free space; otherwise, the loading process may fail.

---

## Section 9: Checking the Plugins

![Lecture](<images/course2/section-09-01.png>)

After the project launches, click the "Tools" menu, select "Plugins," and then go to the "Installed" section. Ensure that the four plugins you installed earlier are enabled.

---

## Section 10: Running the Project Preview

![Lecture](<images/course2/section-10-01.png>)

After closing the plugin window, click the "Play" button at the top. You should see the digital human running in preview mode. The digital human will automatically connect to Fay.

---

## Section 11: Verifying the Connection and Testing the Conversation

![Lecture](<images/course2/section-11-01.png>)

The final step is to verify whether the connection between the UE Digital Human and Fay has been successfully established and to conduct a complete conversation test.

After launching the UE Digital Human, return to Fay's management interface to check the connection. In the top-left corner, near the Fay logo, you will see several status indicators. If the second indicator light is on, it means that the UE Digital Human has successfully connected to the Fay service, and the two-way communication link has been fully established.

Once the connection is confirmed, you can greet the digital human through the microphone. Try saying, "Hello, please introduce yourself," and observe the digital human's response.

If you see the digital human's mouth and facial expressions change and hear a clear voice response from the UE Digital Human's running window, congratulations! You have successfully completed the setup and integration of the UE Digital Human.

At this point, the entire setup process for the UE Digital Human is complete. You now have a digital human companion that can listen, speak, and interact. You can start exploring more interesting application scenarios.

---

# UE Special Interest Group (Free Plugins and Quiet Discussions)
![Group](<images/1280X1280.JPEG>)
