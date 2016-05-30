# Photogram
Telegram Android application + "Instagram-style" photo and video editing features

This is an "upgrade" of the open source code of Telegram ( https://github.com/DrKLO/Telegram ) with added features for photo and video editing. In particular, it has been modified:

- the photo editor with "filters presets" like the ones available in Instagram
- the video editor with "filters presets" like Instagram, a "GIF" creator and a "crop" functionality

The modification have been made inside:

- "PhotoFilterView" for the photo part
- "VideoEditorActivity" and the "video_editor_layout.xml" for the video part

The libraries that have been used are:

- JavaCV ( https://github.com/bytedeco/javacv ) with "FFmpegFrameFilter", "FFmpegFrameRecorder", "FFmpegFrameGrabber"

NOTE: if you want to compile this code in Android Studio you must:

- import the project folder in Android Studio

- obtain a Telegram API key as explained in https://github.com/DrKLO/Telegram README 

- obtain a Google key and the JSON file: follow the steps to "GET A CONFIGURATION FILE" at "https://developers.google.com/identity/sign-in/android/start-integrating#prerequisites" . You will need to create your own project with an arbitrary name BUT IN THE PACKAGE NAME FIELD YOU MUST USE "org.telegram.messenger" ! You will also have to download a JSON file that you must insert in the "TmessageProj" folder inside the project.

- obtain an Hockey App key (https://www.hockeyapp.net)

- create a keystore on your PC by going in Android Studio->Build->Generate Signed APK . Insert all the needed fields and you will generate a keystore file in a defined path.

- insert all the keys and the path of your keystore in the correct spots in TmessageProj/build.gradle 

You should be ready to go, enjoy!


