Prerequisites:

* Unreal Engine >= 4.9
* `git clone --recursive https://github.com/cboulay/SimpleUE4PSMove.git`

Setup

* Follow the instructions [here](https://github.com/cboulay/psmove-ue4/wiki) for setting up the PSMove controller to work with your PC.
* Right click on SimpleUE4PSMove.uproject and choose "Generate Visual Studio project files"
* Open the solution and build
* Once the project is loaded, make sure the HMD is in view of its tracker, the PSMove is in view of its tracker, and press Preview-in-VR.

Default button assignments

* Trigger generates vibration (to do: scale vibration with trigger magnitude)
* Move button resets the yaw
* Circle changes the sphere LED colour (hold still during colour calibration)