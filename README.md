# CrossBeer
CrossBeer


# Environement Installation


## Ubuntu 14.04 LTS
$ apt-get install nodejs npm adb


$ npm install -g cordova
$ npm install -g bower
$ npm install -g gulb

### Android
#### Download the Android SDK (http://developer.android.com/sdk/index.html)
tar -xvzf android-sdk_rXX-linux.tgz && mv android-sdk-linux /opt/

#### Install Java
$ apt-get install sun-java8-jdk

$ nano ~/.bashrc 
export PATH=${PATH}:~/android-sdk-linux/tools
export PATH=${PATH}:~/android-sdk-linux/platform-tools 


# Create Cordova project
$ cordova create crossbeer io.cross.beer

# Get components
$ bower install