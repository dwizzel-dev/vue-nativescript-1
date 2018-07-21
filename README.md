# Vuejs Nativescript

> A Vuejs Nativescript test

## Build Setup

``` bash
# install command line
yarn global add @vue/cli

# install missing libs
yarn global add @vue/cli-init

# install nativescript
yarn global add nativescript

# install jest cli
yarn global add jest-cli

# jest small command
jest --showConfig
jest --clearCache




# dev installed 
@powershell -NoProfile -ExecutionPolicy unrestricted -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin

choco install googlechrome -y

choco install nodejs-lts -y

choco install jdk8 -y

choco install android-sdk -y

# will install platform, tools, etc... for android-25
.\sdkmanager "platform-tools" "platforms;android-25" "build-tools;27.0.3" "extras;android;m2repository" "extras;google;m2repository"
.\sdkmanager "emulator" 
.\sdkmanager "system-images;android-25;google_apis;x86"

# start android studio
  # start sdk manager
  - change the path of the sdk C:\Android\android-sdk
    - suppose to have Android 7.1.1 (Nougat) 
      - Android SDK platform 25
      - Google API x86 Atom system image

  # start avd manager
  - device definition, next--
  - select system image nougat api 25, next--
  - graphics: hardware, change mem, camera, netwok, etc... 

  suppose to create file in C:\Users\{username}\.android\avd\{devicename}

# start the emulator, important: not the one from tool
# pick one from the utils 
.\avdmanager.bat list avd 
.\emulator.exe -avd {emulatorname}




# after all install
tns doctor







```
