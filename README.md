# NoticeBoard

This is a notice board android app, where college faculty from different department can post notice. Faculty member and Students can receive the notice from departments.
- Download apk from [here](https://github.com/shivambangwal/Flutter-NOTICE-BOARD-APP/blob/main/Noticeboard.apk).

## Overview

Only faculty members can post notice. The students can receive notice from their respective department only.
For example, The student studding in mechanical engineering can receive notice from Mechanical department only, not from other academic department. In addition to that, students also receive notice from  non academic department like, library, Office, Sports, etc.



 #### Quick explanation of project directory :
1. [cloud function](https://github.com/shivambangwal/Flutter-NOTICE-BOARD-APP/tree/main/cloud%20function) : It contains single file named index.js having two cloud function.
2. [screenshot](https://github.com/shivambangwal/Flutter-NOTICE-BOARD-APP/tree/main/Screenshot): Sample screenshot from mobile emulator, tablet and real mobile device. It also includes firebase database screenshot.
3. [code](): The android app code.

### Prerequisites

- Firebase project with Realtime database for android having package name "coms.dypatil.noticeboard".
- google-services.json:  during firebase project creation, you will get the google-services.json file, download and save this file.
- Android SDK v28
-  Android Support Repository

### Open and Run Project

<b>For Android App:</b>
1. open android studio, select File -> Import -> "Existing Projects into your workspace".
2. Go to the path where you cloned the Repo: (repoFolder)\code
3. paste the google-services.json to "app" folder.
4. rebuild the project and run.

<b>For cloud function:</b>
1. initialize Firebase SDK for Cloud Functions as explained [here](https://firebase.google.com/docs/functions/get-started),
2. open index.js and paste the code from  "(repoFolder)\cloud function\index.js".
3. deploy the cloud function.


### Built With

- MVVM architecture
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture/) : Live  data, View Model, Room
- Language:  kotlin for android, javascript for cloud function.
- [Firebase](https://firebase.google.com) : Realtime database, Firebase Auth, Firebase storage, Firebase config, Functions, Remote config.
- [RXJava2](https://github.com/ReactiveX/RxJava)




### License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- This project is licensed under the **[MIT license](http://opensource.org/licenses/mit-license.php)**

