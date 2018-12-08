                                                #############################
                                                #	  Flutter Documentation   #
                                                #############################
                            
Flutter is Google's mobile UI framework for crafting high-quality native experiences on iOS and Android in record time
To do work with Flutter follow the instructions:
                            
#1 Install Android Studio and Git on system
#2 Download the following installation bundle to get the latest stable release of the Flutter SDK:
https://storage.googleapis.com/flutter_infra/releases/stable/windows/flutter_windows_v1.0.0-stable.zip
#3 Extract the zip file and place the contained flutter in the desired installation location for the Flutter SDK (eg. C:\src\flutter; do not install Flutter in a directory like C:\Program Files\ that requires elevated privileges)
#4 Locate the file flutter_console.bat inside the flutter directory. Start it by double-clicking
#5 Edit environment variables: Add the full path to flutter\bin
#6 Have to close and reopen any existing console windows for these changes to take effect
#7 Open Git bash in the folder "flatter" and run this command: $ flutter doctor
#8 If any error occurs, then go through the error to solve
#9 Now download Visual Studio Code from: https://code.visualstudio.com/download and install it
#10 After installing launch the Visual Studio Code and go to File -> Preferences -> Extensions and Install + Ractivate the following Extensions: Dart, Flutter, Flutter Widget Snippets, dart-import
#11 Create a folder in any drive named FlutterExercise and drag and drop it in VS Code
#12 Open terminal of VS Code and write the following commands:
~ dir (to check if the project folder is correct)
~ flutter create helloflutter [app/project name] (to create new project and wait till find Main.dart file in lib folder)
#13 Don't touch the thing in android and ios Folder (sometimes have to do)
#14 Write the following command:
~ flutter devices (to check if any Emulator is available or not)
~ open -a simulator (for open up iphone simulator) [optional]
~ flutter run (to run the file)
#15 If get any error like: No pubspec.yaml file found.
Then go to "dir" and find the project file. Now get access of the project file using the following command:
~ cd helloflutter/ (Project file name)
#16 Now write the run command again to run the file
