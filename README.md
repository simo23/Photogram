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

