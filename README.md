# Finamp

Finamp is a Jellyfin music player for Android and iOS. Its main feature is the ability to download songs for offline listening.

## Downloading

[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png"
    alt="Get it on F-Droid"
    height="80">](https://f-droid.org/packages/com.unicornsonlsd.finamp/)

<a href="https://apps.apple.com/us/app/finamp/id1574922594?itsct=apps_box_badge&amp;itscg=30200" style="display: inline-block; overflow: hidden; border-radius: 13px; width: 250px; height: 83px;"><img src="https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/en-us?size=250x83&amp;releaseDate=1625961600&h=0067f8fdf531d0712bd7138120c0ff43" alt="Download on the App Store" style="border-radius: 13px; width: 250px; height: 83px;"></a>

(Play Store link coming soon)
    
Note: The F-Droid release may take a day or two to get updates because since [F-Droid only builds once a day](https://www.f-droid.org/en/docs/FAQ_-_App_Developers/#ive-published-a-new-release-why-is-it-not-in-the-repository).

The app is also available as an APK from the [releases page](https://github.com/UnicornsOnLSD/finamp/releases).

## Known Issues

This app is still a work in progress, and has some bugs/issues that haven't been fixed yet. Here is a list of currently known issues:

* Deleting large items (such as playlists) will cause the app to freeze for a few seconds
* Download indicators don't update properly
* Very occasionally, the audio player will break and start playing songs from previous queues. If this happens, you have to force stop the app to stop audio playback (I think this was fixed in 0.4.0). If this happens to you, please make a new Github issue with your logs, which you can get in the logs screen.
* Seeking doesn't work with transcoded songs

## Planned Features

* Album art in offline mode
* Transcoding support for downloads
* Multiple users/servers
* Translation support

In the long run, I would like to look into video playback. I'm pretty sure I'll be able to implement it in a way that will allow for native playback of complex video formats, such as H265 and ASS subtitles. That's a long way off though ;).

## Screenshots

| | |
|:-------------------------:|:-------------------------:|
|<img src=https://raw.githubusercontent.com/UnicornsOnLSD/finamp/master/fastlane/metadata/android/en-US/images/phoneScreenshots/1.png> | <img src=https://raw.githubusercontent.com/UnicornsOnLSD/finamp/master/fastlane/metadata/android/en-US/images/phoneScreenshots/2.png>
| <img src=https://raw.githubusercontent.com/UnicornsOnLSD/finamp/master/fastlane/metadata/android/en-US/images/phoneScreenshots/3.png> | <img src=https://raw.githubusercontent.com/UnicornsOnLSD/finamp/master/fastlane/metadata/android/en-US/images/phoneScreenshots/4.png> |


Name source: https://www.reddit.com/r/jellyfin/comments/hjxshn/jellyamp_crossplatform_desktop_music_player/fwqs5i0/
