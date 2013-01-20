dehairdev
=========

dehair for Android by PhoneGap
http://rhomobi.com/topics/105

PhoneGap & Android 开发环境必备条件
=========
```bash
•Download and install Eclipse Classic* 
•Download and install Android SDK* 
•Download and install ADT Plugin* 
•Download the latest copy of Cordova* and extract its contents. We will be working with the Android directory.
•Download and install Apache ANT 1.8.x*

export PATH=${PATH}:/Development/android-sdk-macosx/platform-tools:/Development/android-sdk-macosx/tools 
```

•Finally, you may need to include %ANT_HOME%\bin to your PATH as well. To check to see if this is required, run a command prompt and type ant. If the program can not be found add %ANT_HOME%\bin to the PATH. You may need to specify the full path instead of using the %ANT_HOME% environment variable.

Setup New Project :
>•In a terminal window, navigate to the bin directory within the android subfolder of the Cordova distribution.

```bash
./create <project_folder_path> <package_name> <project_name> 
```

then press "Enter"

```bash
<project_folder_path> is the path to your new Cordova Android project
<package_name> is the package name, e.g. com.YourCompany.YourAppName
<project_name> is the project name, e.g. YourApp (Must not contain spaces)
```
