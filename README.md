# phonegap_dt
Development Template application based on the PhoneGap

To work with this project you need to:

1) Install NodeJS from http://nodejs.org/.
Detailed instruction can be found here https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager#windows.

2) Install PhoneGap.
sudo npm install -g phonegap

3) Install android SDK.

4) For Windows: Add environmental vaiable ANDROID_HOME that point to correct location of the android SDK on your PC.  Include the SDK's tools and platform-tools directories in your PATH: "%ANDROID_HOME%\tools;%ANDROID_HOME%\platform-tools;"
For Linux: Edit .bsashrc.sh file and add config there:
#Export path to Android SDK location:
export ANDROID_HOME=/home/dimas/android-sdk-linux
export PATH=${PATH}:${CATALINA_HOME}/tools
export PATH=${PATH}:${CATALINA_HOME}/platforms

