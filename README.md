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

> gradlew build

	:app:preBuild UP-TO-DATE
	:app:preDebugBuild UP-TO-DATE
	:app:checkDebugManifest
	:app:preReleaseBuild UP-TO-DATE
	:app:prepareComAndroidSupportAppcompatV72311Library UP-TO-DATE
	:app:prepareComAndroidSupportSupportV42311Library UP-TO-DATE
	:app:prepareDebugDependencies
	:app:compileDebugAidl UP-TO-DATE
	:app:compileDebugRenderscript UP-TO-DATE
	:app:generateDebugBuildConfig UP-TO-DATE
	:app:generateDebugAssets UP-TO-DATE
	:app:mergeDebugAssets UP-TO-DATE
	:app:generateDebugResValues UP-TO-DATE
	:app:generateDebugResources UP-TO-DATE
	:app:mergeDebugResources UP-TO-DATE
	:app:processDebugManifest UP-TO-DATE
	:app:processDebugResources UP-TO-DATE
	:app:generateDebugSources UP-TO-DATE
	:app:compileDebugJavaWithJavac UP-TO-DATE
	:app:compileDebugNdk UP-TO-DATE
	:app:compileDebugSources UP-TO-DATE
	:app:transformClassesWithDexForDebug UP-TO-DATE
	:app:mergeDebugJniLibFolders UP-TO-DATE
	:app:transformNative_libsWithMergeJniLibsForDebug UP-TO-DATE
	:app:processDebugJavaRes UP-TO-DATE
	:app:transformResourcesWithMergeJavaResForDebug UP-TO-DATE
	:app:validateDebugSigning
	:app:packageDebug UP-TO-DATE
	:app:zipalignDebug UP-TO-DATE
	:app:assembleDebug UP-TO-DATE
	:app:checkReleaseManifest
	:app:prepareReleaseDependencies
	:app:compileReleaseAidl UP-TO-DATE
	:app:compileReleaseRenderscript UP-TO-DATE
	:app:generateReleaseBuildConfig UP-TO-DATE
	:app:generateReleaseAssets UP-TO-DATE
	:app:mergeReleaseAssets UP-TO-DATE
	:app:generateReleaseResValues UP-TO-DATE
	:app:generateReleaseResources UP-TO-DATE
	:app:mergeReleaseResources UP-TO-DATE
	:app:processReleaseManifest UP-TO-DATE
	:app:processReleaseResources UP-TO-DATE
	:app:generateReleaseSources UP-TO-DATE
	:app:compileReleaseJavaWithJavac UP-TO-DATE
	:app:compileReleaseNdk UP-TO-DATE
	:app:compileReleaseSources UP-TO-DATE
	:app:lintVitalRelease
	:app:transformClassesWithDexForRelease UP-TO-DATE
	:app:mergeReleaseJniLibFolders UP-TO-DATE
	:app:transformNative_libsWithMergeJniLibsForRelease UP-TO-DATE
	:app:processReleaseJavaRes UP-TO-DATE
	:app:transformResourcesWithMergeJavaResForRelease UP-TO-DATE
	:app:packageRelease UP-TO-DATE
	:app:assembleRelease
	:app:assemble
	:app:compileLint
	:app:lint
	Wrote HTML report to file:///D:/My%20Projects/android/sample/BuildGradleCommnadLine/app/build/outputs/lint-results.html
	Wrote XML report to file:///D:/My%20Projects/android/sample/BuildGradleCommnadLine/app/build/outputs/lint-results.xml
	Lint found 0 errors and 2 warnings
	:app:preDebugUnitTestBuild UP-TO-DATE
	:app:prepareDebugUnitTestDependencies
	:app:compileDebugUnitTestJavaWithJavac UP-TO-DATE
	:app:processDebugUnitTestJavaRes UP-TO-DATE
	:app:compileDebugUnitTestSources UP-TO-DATE
	:app:mockableAndroidJar UP-TO-DATE
	:app:assembleDebugUnitTest UP-TO-DATE
	:app:testDebugUnitTest UP-TO-DATE
	:app:preReleaseUnitTestBuild UP-TO-DATE
	:app:prepareReleaseUnitTestDependencies
	:app:compileReleaseUnitTestJavaWithJavac UP-TO-DATE
	:app:processReleaseUnitTestJavaRes UP-TO-DATE
	:app:compileReleaseUnitTestSources UP-TO-DATE
	:app:assembleReleaseUnitTest UP-TO-DATE
	:app:testReleaseUnitTest UP-TO-DATE
	:app:test UP-TO-DATE
	:app:check
	:app:build

	BUILD SUCCESSFUL

	Total time: 1 mins 9.796 secs

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


 
