# SteamVR Template

This github template repository includes a full unity project that is setup and ready to go for SteamVR for use with Oculus
When making a VR unity project for use with SteamVR, to save time you can generate a new github repository from this template and be ready to go!

# Generating a repository from this template
Go to this repositories github [here](www.google.com)
Click 'Use this template'
Select the owner of the new repository
Enter a name for your new repository
Click create repository.
Done!

You will need to rename the unity project within unity to the name of your own VR project but this is simple.
Go to Project Settings -> Player -> Change the text in the fields product name / company name to your own project and company.

# SteamVR in a new project
Listed here are setup instructions for using SteamVR in a new project.

From the asset store in unity search for "SteamVR"
Install this package and import everything
Accept all unity settings changes
Go to player settings -> XR Settings -> Enable 'Virtual Reality Supported'
Add Oculus by pressing the plus button and selecting Oculus
Add OpenVR by pressing the plus button and selecting OpenCV
Set 'Stereo Rendering Mode' to 'Multi Pass'
Go to Window -> SteamVR Input -> Click 'yes' to use example actions.json
SteamVR Input window will appear. Click 'Save and generate'

This is now ready to use, but you can tryout the example scene by opening an example scene:
Assets/SteamVR/InteractionSystem/Samples/Interaction_Example

# Unity XR support
If you would like to use Unity's new XR Manager rather than SteamVR then use this [github template repository](www.google.com) instead.
This also includes a Unity Package that can be imported into any Unity project with some useful prefabs! (See release [here](www.google.com))
This is neccessary as Unity XR Manager does not support SteamVR. When and if this is added, these two will be joined.