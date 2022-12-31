download advance web view of jasonelle from github orfrom this repository.
extract rar and change name to the name of app
open the app folder in andriod studio
use embeeded jdk
upgrade graddle using run selected steps
change app name in setting.gradle
refactor folder name and rename directory to app name using run refeactor
sycn the project 
change appname in res>values>strings.xml
update versions in build.graddle module file  
	compileSdkVersion 31
    defaultConfig {
        applicationId "com.xyz.android"
        minSdkVersion 22
        // Android 8 is the minimum required for the playstore
        targetSdkVersion 31
sync project
generate app icons and splash screen using appicon.co
replace appicon in app>src>main>res using file explrorer
rename all splash screens to splash.png and copy them to app>src>res
open app>src>res>drawable>launch.xml and change anrdiod src to @drawable/splash under bitmap tag
change splash screen background app>src>res>values>colors.xml <color name="colorLaunchScreen">#ffffff</color>
update the code in assets>file>hello.json 
build project

{
    "$jason": {
        "head": {
            "title": "Title"
        },
        "body": {
            "background": {
                "type": "html",
                "url": "",
                "style": {
                    "background": "#ffffff",
                    "progress": "#000000"
                },
                "action": {
                    "type": "$default"
                }
            }
        }
    }
}
