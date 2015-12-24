# BuildGradleCommandLine

Build Apk Commnad Line Windows

Install Android sdk
Install Gradle

Run cmd in windows

Check gradle version

> gradle -version

------------------------------------------------------------
Gradle 2.8
------------------------------------------------------------

Build time:   2015-10-20 03:46:36 UTC
Build number: none
Revision:     b463d7980c40d44c4657dc80025275b84a29e31f

Groovy:       2.4.4
Ant:          Apache Ant(TM) version 1.9.3 compiled on December 23 2013
JVM:          1.7.0_75 (Oracle Corporation 24.75-b04)
OS:           Windows 8.1 6.3 amd64 


This root folder project

> gradle wrapper

> gradle build

IF occurred under error 

> Execution failed for task ':app:compileDebugJavaWithJavac'
> Could not find tools.jar
 
Check Windows Environment Varibles (Like this)

>|ANDROID_HOME|D:\Android_IDE\android-sdk-windows |
>|------------|-----------------------------------|
>|JAVA_HOME   |C:\Program Files\Java\jdk1.7.0_75  |


 
