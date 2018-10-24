# QuestionAnswers_Week1Day3
Answers to homework questions


1. Android Platform layers (Explain the re architecture for Android 8.0)

 - At the lowest level Android runs on linux operating system which provides all the drivers, kernels to control the hardware.
 - On top of that we have hardware abstraction layer to provide convenient access to hardware api.
 - On top of the hardware abstraction there are C/C++ libraries to provide higher level APIs to the hardware on the device.
 - On top of all this comes Java API Framework to create apps which can work together with Hardware Abstraction Layer and native libraries to cerate functionality.
 - At the highest level we have the apps themselves which are already build on Java. For example: phone, email etc.

2. Android components (Explain the use of each)

- Activities - Activites have views to display the GUI interface of the app to the user.
- Broadcast/Receivers - These are used to send or receive intents throughout the android infrastructure to do certain intercations with other apps etc.
- Services - Services are long term background processes running on the device.
- Content Providers - These provide data to your app. As well as save/provide your app's data.

3. Lint 

Android Lint performs check on your project to see if there are any potential bugs or if you forgot something as a developer

4. Build process in Android

During build process the compilers take all the code, assets and dependency libraries and make executable files out of them. Then the APK managers signs the compiled project with your own key to create a produciton version of the app ready to publish to google store.

5. Dalvik vs ART

ART is the newer version of project compiler which compilers the whole project. From what I gather, Dalvik was compiling parts of the code as they were needed, whereas ART would compile the whole project ahead of time and therefore ART is slower to install but runs faster and puts lesser load on the hardware.
