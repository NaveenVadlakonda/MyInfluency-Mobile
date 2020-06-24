##Running the Project:
Make sure you have Node(and npm), python, JDK, and Android Studio/XCode installed

npm install -g react-native-cli

Enter the project in Android Studio/XCode, build, and you should be able to run it on an emulator.

If some permissions are failing when restarting the node server try:
cd android && gradlew clean && cd ..
then reload the app
