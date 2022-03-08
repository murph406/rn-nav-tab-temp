# This Template React Native Application #

[Template] Use it or not. I wont be offended.

### Application Information###

* This application is built with React Native frameworks. 
* [React Native](https://reactnative.dev)

### Development Environment MacOs Setup  ###

* Install Node.js Globally --> `brew install node` 
* Install Watchman Globally --> `brew install watchman` 
* Install Java JRE and JDK Globally 
    * `brew tap AdoptOpenJDK/openjdk` 
    * `brew install adoptopenjdk8` 
* Set up Xcode 
    * `sudo gem install cocoapods` 
* Set up Android Studio
    *  Open Preferences --> Appearance & Behavior --> System Settings --> Android SDK
    *  ✅ Hide Obsolete Packages Box and Show package Details Box
    *  Apply Android SDK Platform 28 && Intel x86 Atom_64 System Image or Google APIs Intel x86 Atom System Image
    *  Create new virtual device
* Set up Environment Variables 
    * `cd ~/` 
    * `touch ~/.bash_profile;` 
    * `open -e .bash_profile` 
    * Paste Code --> 
    `export ANDROID_HOME=$HOME/Library/Android/sdk  
    export ANDROID_HOME=$HOME/Library/Android/sdk 
    export PATH=$PATH:$ANDROID_HOME/emulator 
    export PATH=$PATH:$ANDROID_HOME/tools 
    export PATH=$PATH:$ANDROID_HOME/tools/bin 
    export PATH=$PATH:$ANDROID_HOME/platform-tools`

### Running Project ###

* Clone Project
* In project directory run `yarn`
* In project directory run `yarn ios` to start project on Ios device

### Dependencies ###
* [react-native-uuid](https://github.com/eugenehp/react-native-uuid)
* [react-native-unimodules](https://docs.expo.io/bare/installing-unimodules/)
* [react-navigation](https://reactnavigation.org)
* [expo-camera](https://docs.expo.io/versions/latest/sdk/camera/)

