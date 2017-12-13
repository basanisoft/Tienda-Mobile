					MI Tienda Mobile Installation.

1. Install java version 8 in your system.
2. Setup JAVA_HOME(ex: 'c:\program Files\java\jdk1.8'),  Path(ex: '  %JAVA_HOME%\bin')  Variables  in the System environment Variables.
3. Download Latest Android studio from the  developer.android.com
4. Setup ANDROID_HOME (ex: 'D:\Android\sdk') and  in system path (ex: '%ANDROID_HOME%\tools;%ANDROID_HOME\platform-tools').
5. Install node.js from nodejs.org.
6. Run Command prompt as a Administrator. 
7. Run node –v (result should be v9.3.0) so that installation is successful.
8. Run npm install –g  react-native-cli.
9. Donwload  both  graphql server and Mobile, sql file build from the github.
10.  Run .sql file  In your mysql server.
11. In the graphql server build go the config folder and edit fields username, password, database, host according to your server.
12. Now go to command prompt and  run  command 'npm install'.
13. Run  command 'npm start' to start the graphql  server.
14. After successful starting the Graphql server. 
15. Go to the  Tienda\src\const \index.js file and edit the URL to the graphql server URL.(Ex: '192.168.1.9:8088/graphql').
16. Open New Command Prompt and Move to Tienda path and Run command 'npm install'.
17. Then Connect to your mobile to the system and run command 'react-native  run-android'. (Make sure usb debugging is enable in your device).
18.  Second method for testing create a virtual device in Android studio and run simulator. Then the type the same command 'react-native run-android'. So the you can test in simulator.
19. To generate apk move to android folder in command prompt and run the following command 'gradlew assembleRelease --console plain''
20.you will find .apk in the following folder 'android/app/build/outputs/'.
21. That's it  you can run the apk in any Android mobile.
