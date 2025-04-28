### Interactive Installation /w Kinect V1.0, TouchOSC, [ofxMSAFluid](https://github.com/memo/ofxMSAFluid)


## Setup

1. [Download and Install OpenFrameworks](https://openframeworks.cc/download/)
2. Clone this repository in OpenFrameworks/apps/myApps/<repository>
3. Run ./bin/PhantasmInstallation (Linux) or build with 'make'
> [!IMPORTANT]
> When building, make sure you install the following dependencies:
- ofxBeat
- ofxBeatTracking
- ofxGui
- ofxKinect 
- ofxMSACore 
- ofxMSAFluid 
- ofxMSAInteractiveObject 
- ofxOpenCv 
- ofxOsc 
- ofxPostProcessing 
- ofxXmlSettings 
- ofxSimpleGuiToo


## Controls

Scene
'D' HideDebugInfo 
'd' drawFluid
'p' drawParticles
'f' ToggleFullscreen
'r' resetFluid
'g' hideGUI
'alt' changeScene

Kinect 
'>' increaseFarThreshold
'<' decreaseFarthreshold
'+' increaseNearThreshold
'-' decreaseNearThreshold
'w' enableDepthNearValueWhite
'o' openKinect
'c' closeKinect
'arrow_up' changeKinectAngleUp
'arrow_down' changeKinectAngleDown
















