# OBS-VideoStream
Setting up Video stream for FORK

# Checklist Equipment
 - Q2n Camera
 - SD Card
 - LAN cables, LONG CABLES
 - Router                       
 - Switch x 2 
 - Several Laptops
 - Memory Stick with software
 - HDMI Cables, Several
 - HDMI to VGA converters, Several, just in case
 - Microphone at location
 - Audio Mixing Table
 - Extra 1.5 V AA Batteries for the Q2N
 - Clicker
 - Micro USB cable for the camera

# Software Links

On the Render Server

> Newtek tools
https://www.newtek.com/ndi/tools/#download-tools

> OBS Studio
https://cdn-fastly.obsproject.com/downloads/OBS-Studio-22.0.2-Full-Installer-x64.exe

On the Client: 

> OBS Studio
> NewTek tools

On the client for the webcam

> OBS Studio
> NewTek tools
> Q2n Driver
https://www.zoom.co.jp/sites/default/files/products/downloads/software/E_Q2n_WebCamDriver_win_v1.0.0.4.zip

# Setup Strategy

See Diagram on Screen Setup:
See Diagram on Network Setup:
See Diagram on Floor Setup:

Screenshot:


# How to configure OBS
Setup the Camera First 
Install the OBS Software from link above, Install the newtek tools from above, RESTART.
Launch the OBS software, as administrator

# SetupPowerpoint


- Start the OBS as administrator

> OBS Select Display capture: 
> Select output 
Blank screen ? Go to problems


# Setup of the Camera
- Make sure it is on a stable platform
- Make sure it can see the Presenter ( or some of the crouwd )
- Attach Micro USB cable to the computer and the camera:
    The Camera should now Automatically boot up with a USB Sign
        If it does not: Press the PLAY button on the camera
    Select webcam mode: Press the RED "record" button
    The camera should now be availble in the device manager as well as to be added in the OBS Studio
- In the ods studio Select TOOLS - > NDI output settings. Tick box main output: Give it a name like "Q2N Audio stuff"

    
# Setup of Render machine
- Load image of "stream starting soon"
Link to Image:
- Setup Scene Transition (STUDIO) 
- Setup input: 
    - connect Camera Trough NDI input: 



# things to test

 - Different Coding Schemes
 - Skype Setup
 - Multipule Audio Setup

# Things to do

- Create several Scenes
- Meeting with marieke
- Completing things to test
- Doing a full test run 1.0
- Creating Network Diagram
- Floor Diagram
- Creating Screen Setup 
- Finishing documentation : 
    - Adding screenshots : Dum Dum Version
    - Adding backup of software on Nextcloud

# Possible Problems

The Q2n Camera Shuts off Randomly
 - Did you make sure it has the firmware update? It needs to be V1.1 or higher
 - Make sure the Computer you're attaching it to has the software installed. It should pop up in the device manger 

The Display gives a Blank Screen
Option 1:
https://www.quora.com/How-do-I-fix-a-display-capture-that-only-displays-and-records-a-black-screen-in-OBS
Option 2:
you did not start the Obs as administrator

# OBS Settings

Download the jason file in the respetorie and import it in OBS by clicking in the top bar on scene collection and press import
Dubble click on the cameras to check if the right came is being used if not select right camera

For the hardware check if aux cable is plugged in and is on at the split box at the poduim and on the control pannel(it is marked aux)
Also for the microphone you will see a split box with all the audio plugs called €ordial remove the plug of the microphone and plug in the
plug of the mixpanel(plug in main out links) and plug the microphone in the mixpanel also put in power and the cabel to the usb.
There also is a HDMI cable at the speaker that is the beamer (WARNING DO NOT LET IT GO TO SLEEP MODE IT WILL NOT GO ON AGAIN)
