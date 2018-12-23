# Project Title
Sample Project for ioic Application

### Prerequisites
1)pre requirements <br>
   * [node-(v8)](https://nodejs.org/en/download/)
   * [Angular-cli(v1.7)](https://www.npmjs.com/package/@angular/cli)
   * [Ionic-(v4)](https://ionicframework.com/docs/intro/installation/)



### Installing

Clone Source code from git hub [Git_Hub_Link](https://github.com/gsrikanth007/sample-project.git). And install npm
```
npm install
```
* It will install all angular, typescript, ionic, cordova plugins
* If you want install any plugin add in package 

### Usefull ionic commands

* ionic generate component
* ionic generate directive
* ionic generate pipe
* ionic generate provider
* ionic generate page Login
* ionic generate page Detail --no-module
* ionic generate page About --constants
* ionic generate pipe MyFilterPipe


### For run the App
* <b>ionic serve</b>
  it will start the app and automatically open in local default browser 
* <b>ionic serve --livereload</b>
 it will start the app and automatically open in locall browser and if add any changes in the code no need to refresh the browser
 
 ### Generate apk or ios file 
 
  #### <u>step-1</u>
 * <b>ionic cordova platform add android</b>
        Adding platform for android
 * <b>ionic cordova platform add ios</b>
    Adding platform for ios 
  #### <u>step-2</u>
  * <b>ionic cordova build android</b>
      it will generate apk file for android
      (***better to delete <b>www</b> folder before ren the command)  
   * <b>ionic cordova build ios</b>
  it will generate Xcode file for ios
  (***better to delete <b>www</b> folder before ren the command) 
   
### To Debug in Emulater
  * <b>ionic cordova emulate android --livereload</b>
      it will generate apk file for android automatically open android emulater
      (***better to delete <b>www</b> folder before ren the command)  
   * <b>ionic cordova emulate ios --livereload</b>
  it will generate Xcode file for ios and automatically open ios emulater
  (***better to delete <b>www</b> folder before ren the command) 
   
