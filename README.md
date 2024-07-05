# okapilabLogFiles
This is an extension for the wonderful software GPTAvatar created by Seth Robinson, https://github.com/SethRobinson/GPTAvatar

The class LogFiles is part of Maximilian C. Fink's OKAPILabExtensions for GPTAvatar.
The class allows to create logfiles for educational/psychological/other research.
In order to create good logfiles, the xAPI logfile standard is used: https://xapi.com/.
This extension can be used in the desktop versions of GPTAvatar. It has been tested on Windows and could potentially also work on MacOS and Linux.
It will probably not work well on WebGL builds and on builds for Android/IOS. At least files will be written to a different file path that's hard to discover.

To use this extension, the following steps have to be done:
1) Copy this file in Unity somehwere under your assets (e.g., in a separate folder OKAPILabExtensions)
2) Click in the Unity hierarchy on "Canvas" and open the child object "Panel"
4) Click on the "Panel" component on "Add Component" and then type/select "LogFiles" -> this adds the C# file
  Now everything should run as intended. No further changes should be neccessary. Try it in play mode and make builds :)

When using GPTAvatar the following has to be done
1) Enter the PIN/code of the user for whom you want to create logfile in the textbox that appears upon start and presse enter
 -> this will be the file name of the created .csv
2) After using GPTAvatar, the log file will be in this folder 
C:\Users\USERNAME\AppData\LocalLow\Robinson Technologies\GPTAvatar\
The relevant folder should look like this (Tester was the user name I entered)
![grafik](https://github.com/MCF3389/okapilabLogFiles/assets/29815773/b758d2ad-fd60-4942-b647-f1964ea2b3e0)

4) Search for the user name
5) For correct formating of the .csv file, click on column A. Then click on data -> text in columns -> separated -> comma as seperator

The resulting logfiles should look like this in Excel
![grafik](https://github.com/MCF3389/okapilabLogFiles/assets/29815773/ae75f96b-ac13-430c-a7c2-10dd045b5d76)


If you use GPTAvatar for psychological/educational research, please either cite our article 
http://www.dx.doi.org/10.3389/feduc.2024.1416307/abstract or Seth Robinson's github repository.
If you need more code modification or want to collaborate for scientific purposes, please reach out to Maximilian C. Fink (maximilian.fink@yahoo.com)
I'm always happy to help and conduct research together :)

