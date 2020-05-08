# SteamVR Template

This github template repository includes a full unity project that is setup and ready to go for SteamVR for use with Oculus
When making a VR unity project for use with SteamVR, to save time you can generate a new github repository from this template and be ready to go!

**Latest Unity version tested: 2019.3.13f1**

# Generating a repository from this template
Go to the top of this repository and click 'Use this template'


Select the owner of the new repository


Enter a name for your new repository


Click create repository.


You will need to rename the unity project within unity to the name of your own VR project but this is simple.


Go to Project Settings -> Player -> Change the text in the fields product name / company name to your own project and company.


This is now ready to use, but you can tryout the example scene by opening an example scene:

```
Assets/SteamVR/InteractionSystem/Samples/Interaction_Example
```

# SteamVR in a new project
Listed here are setup instructions for using SteamVR in a new project.

From the asset store in unity search for "SteamVR"

![Image of asset store](https://raw.githubusercontent.com/KnightVR/SteamVRTemplate/master/Images/SteamVR%20Asset%20Store.PNG)

Install this package and import everything

![Image of importing SteamVR](https://raw.githubusercontent.com/KnightVR/SteamVRTemplate/master/Images/SteamVR%20Import.PNG)

Accept all unity settings changes

![Image of accepting changes](https://raw.githubusercontent.com/KnightVR/SteamVRTemplate/master/Images/SteamVR%20Import%20Changes.PNG)

Go to player settings -> XR Settings -> Enable 'Virtual Reality Supported'


Add Oculus by pressing the plus button and selecting Oculus


Add OpenVR by pressing the plus button and selecting OpenVR


Set 'Stereo Rendering Mode' to 'Multi Pass'

![Image of changing XR settings](https://raw.githubusercontent.com/KnightVR/SteamVRTemplate/master/Images/Player%20Settings.PNG)

Go to Window -> SteamVR Input -> Click 'yes' to use example actions.json

![Image of setting SteamVR Input](https://raw.githubusercontent.com/KnightVR/SteamVRTemplate/master/Images/Copy%20example%20actions.PNG)

SteamVR Input window will appear. Click 'Save and generate'

![Image of generating SteamVR Input](https://raw.githubusercontent.com/KnightVR/SteamVRTemplate/master/Images/Generate%20Inputs.PNG)

This is now ready to use, but you can tryout the example scene by opening an example scene:
```
Assets/SteamVR/InteractionSystem/Samples/Interaction_Example
```

# Run in Virtual Desktop
Virtual Desktop allows you to run almost any game from Oculus Store or Steam VR via WiFi on the Oculus Quest.


Download the Virtual Desktop Streamer application on your computer from [here](https://www.vrdesktop.net/)


Install Virtual Desktop app using [SideQuest](https://sidequestvr.com/setup-howto) [Virtual Desktop App](https://sidequestvr.com/app/16/virtual-desktop)


To run a Unity application that has been built for SteamVR:


Startup the Virtual Desktop steamer (on computer)


Start the Virtual Desktop app (on Quest)


Select the PC in the app


Press the menu button on the left controller to bring up the menu


Click 'Start SteamVR'


Wait for SteamVR to run on the PC then run the application in the build directory of this project


This should run the application in SteamVR which will be streamed straight to the Quest!


# Useful guides
Valve provides guide on using SteamVR [here](https://valvesoftware.github.io/steamvr_unity_plugin/articles/intro.html)

# Unity XR Manager support
If you would like to use Unity's new XR Manager rather than SteamVR then use this [github template repository](https://github.com/KnightVR/XRTemplate) instead.


This also includes a Unity Package that can be imported into any Unity project with some useful prefabs! (See release [here](https://github.com/KnightVR/XRTemplate/releases))


This is neccessary as Unity XR Manager does not support SteamVR. When and if this is added, these two will be joined.
