# HoloDocs
Documentation for the Hololens

Installation can be found [here](https://developer.microsoft.com/en-us/windows/holographic/install_the_tools)
Example building [here](https://developer.microsoft.com/en-us/windows/holographic/holograms_101e)

- Visual Studio with Update 3
- Unity Hololens Technical Version
- HoloLens Emulator(optional)

# Setting up a project
## Setup main camera 
- In the Hierarchy Panel, select Main Camera.
- In the Inspector set its transform position to 0,0,0.
- Find the Clear Flags property, and change the dropdown from Skybox to Solid color.
- Click on the Background field to open a color picker.
- Set R, G, B, and A to 0.
## Setup Deploying
- In Unity select File > Build Settings.
- Select Windows Store in the Platform list and click Switch Platform.
- Set SDK to Universal 10 and Build Type to D3D.
- Check Unity C# Projects.
- Click Add Open Scenes to add the scene.
- Click Player Settings....
- In the Inspector Panel select the Windows Store logo. Then select Publishing Settings.
- In the Capabilities section, select the Microphone and SpatialPerception capabilities.
- Back in the Build Settings window, click Build.

# Credentials 
Usernane: holoTest
Password: dshsholo

# Various Tasks
## Getting IP of HoloLens
Goto Settings>WiFi>Advanced Options>IPv4Address
