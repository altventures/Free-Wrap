1. Download the rar file name Alt-Wrapper.rar
2. Extract the downloaded file and changed it's name to the APP NAME you want.
3. Open the folder in Andriod Studio.
4. Select JDK and upgrade Gradle if required.
5. Change APP NAME in setting.gradle
6. Refactor folder name and rename directory to APP NAME using run refeactor
7. Sycn the project
8. Update android properties in Android Manifest(Module) file and sycn the project
9. Change the web url to yours in assets>file>hello.json 
10. Build the project.

For splash screen and App icon
1. Generate app icons and splash screen using appicon.co
2. Replace appicon in app>src>main>res using file explrorer
3. Rename all splash screens to splash.png and copy them to app>src>res
4. Change splash screen background app>src>res>values>colors.xml <color name="colorLaunchScreen">#ffffff</color>


Our wrapper proviedes following native functionalities
1. Open Whatsapp chat
2. Fetch GPS Location 
3. Share Text 
4. Share Image 
5. Get Contacts 
6. OneSignal SDK
