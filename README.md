# phonegap_dt
Development Template application based on the PhoneGap

To work with this project you need to:

1) Install Java 7 or Java 8.

2) Install Ant (one of the latest versions).

3) Install NodeJS from http://nodejs.org/.
Detailed instruction can be found here https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager#windows.

4) Install PhoneGap.
For Linux: sudo npm install -g phonegap 
For Windows: C:\>npm install -g phonegap

5) Install android SDK.

6) For Windows: Add environmental vaiable ANDROID_HOME that point to correct location of the android SDK on your PC.  Include the SDK's tools and platform-tools directories in your PATH: "%ANDROID_HOME%\tools;%ANDROID_HOME%\platform-tools;"
For Linux: Edit .bsashrc.sh file and add config there:
export ANDROID_HOME=/home/dimas/android-sdk-linux
export PATH=${PATH}:${CATALINA_HOME}/tools
export PATH=${PATH}:${CATALINA_HOME}/platforms

7) Reload .bashrc file in Linux:
source ~/.bashrc

8) Configure Android SDK via Manager as described here: 
http://frontendmatters.com/getting-started-mobile-app-development-phonegap-yeoman-angularjs-ionic/

Usefull commands:
android - runs Android SDK Manager
android avd - runds Android Virtual Device manager
phonegap run android - runs application on android platform
phonegap emulate android - emulates application on android platform


9) We will use Yeoman to help with the scaffolding, Grunt to help with automated task, and Bower to take care of front-end packages.
To install them use command:
sudo npm install -g yo bower grunt

10) If you want to scaffold AngularJS applications via Yeoman you need to install generator:
sudo npm install -g generator-angular



