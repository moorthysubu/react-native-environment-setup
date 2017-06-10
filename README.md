# react-native-environment-setup
This project has steps to setup environment for react-native projects

# For reference visit 

https://facebook.github.io/react-native/docs/getting-started.html

## Steps to setup environment.

### 1.chocolatey Installation :

copy and paste the following command in cmd. make sure you have opened cmd as administrator user in windows.

>@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"

To check whether chocolate installed or not in system check chocolate version by below command

>choco -version or choco -v

### 2.Install node & Python

>choco install nodejs.install - responsible for node js installation

>choco install python2 - responsible for python2 installation

Note: If you have already installed Node on your system, make sure it is version 4 or newer. 
If you already have a JDK on your system, make sure it is version 8 or newer.

### 3.Installing Java (For Android Support.)

If you have already java installed machine skip this option or otherwise install java from 
http://www.oracle.com or else use below command

>choco install jdk8

### 4.JDK Setup

Make sure you have set Jdk path as environment variable as ####JAVA_HOME as system variable.

### 5.Install The React Native CLI 

Install this using 

>npm install -g react-native-cli

### 6.Download Android SDK

Download Android studio from https://developer.android.com/studio/index.html.

### 7.SetUp Android SDK.

Make sure you have set Android SDK path as environment variable as ####ANDROID_HOME as system variable.

### 8.Create New Project (Application)

Create ReactNative Project by using below command

>react-native init AwesomeProject

then move the project directory by using below
>cd AwesomeProject

then run project using 

>react-native run-android 

Note: If you want to run server in separate window use 
>react-native start 

command.
















