### Cordova demo project for gwt-cordova showcase

#### Building

The project in github does not include temporary stuff used for building, hence you need to run the following commands.

     $ npm install
     $ cordova platform add android
     $ cordova build android
     
 After this you should have the android APK that you can install in your device in the folder `platforms/android/build/outputs/apk/android-debug.apk`
 
 
#### Updating the project

Clone and compile the gwt-cordova showcase project.

     $ git clone https://github.com/manolo/gwt-cordova-showcase.git
     $ cd gwt-cordova-showcase
     $ mvn clean package -Dmaven.test.skip
     
Copy the compilation result in this project

     $ cp -r folder_of_gwt_cordova_showcase/target/gwt-cordova-demo/gwtcordovashowcase www/

 
 
 
