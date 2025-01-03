# Lipsync-Unity

This repository contains a unity project that shows the Talky Walky avatar, which is connected with Lipsync. Additionally it can be connected to an animation if needed.

In order to run the project, Unity must be installed from the official [unity webpage](https://unity.com/products).
The project can than be added and opened through the Unity Hub.

It will open with an empty scene. The provided SampleScene can be found in the asset folder under scenes and can be opened with a double-click.

<img width="659" alt="image" src="https://github.com/user-attachments/assets/30b6d87e-e344-498d-a501-8d5f0ea04a28" />

## LipSync:

In the provided scene the Talky Walky avatar is already connected to the Lipsync Tool "uLipSync" with a predefined audio File.
To start the Lipsync in this option, simply press the play button on top of Unity:

<img width="748" alt="image" src="https://github.com/user-attachments/assets/ce57ed65-63c6-4767-8543-3e8a93d00dfd" />

uLipSync is a powerful tool, that can be changed and customized according to your needs. To understand more details, we recommend to follow the [YouTube Tutorial from ReForge Mode](https://www.youtube.com/watch?v=k5CtTsIKwE4) to get the basic understanding.

## LipSync via Microfon:

In order to change the input audio to the Microfon, the uLipSync Element needs to be selected and a new "U LipSync Microphone (Script)" Component needs to be added.

<img width="956" alt="image" src="https://github.com/user-attachments/assets/dcf0a530-5145-4186-ac82-3f85f9c11aab" />

Afterwards the audio input needs to be set to none.

<img width="297" alt="image" src="https://github.com/user-attachments/assets/8b1737ac-9818-4ddf-86fd-cad2eab37047" />

Again, it can be tested and played by pressing the play button.

More details are provided in the mentioned YouTube Tutorial.

## Animation:

To activate an animation for the avatar, the Talky Walky needs to be selected in the scene and its Controller has to be changed to the wished Animation Controller
(provided example "dancing")

<img width="328" alt="image" src="https://github.com/user-attachments/assets/fae54aa7-c60c-412f-b374-3286407094f0" />

If wished, the animation can be changed by double-clicking the Controller in the assets overview. The existing animation was downloaded from [mixamo](https://www.mixamo.com/#/).

<img width="662" alt="image" src="https://github.com/user-attachments/assets/5aaa6fd9-5b15-4a87-8b11-022ae6ab6b30" />

New animations can be added as fbx-Files by drag and drop into the asset folder.
These animations can then be applied and connected in the controller by drag and drop from the asset folder into the space above.
Please note, that the animations need to be connected through arrows in order to be played.

Again, the animations can be played by pressing the play button on top of the Unity Tool.
