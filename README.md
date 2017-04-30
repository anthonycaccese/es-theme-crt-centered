# CRT Centered, an EmulationStation theme with video support
A simple theme for Emulation Station and RetroPie with support for the video view added by fieldofcows.  Originally based on the awesome Carbon theme by Eric Hettervik; and then rebuilt from scratch so I could learn the theming system for ES

---

### Updates

*4/30/2017*
- Fixed box art scaling issue on video view
- Added 4x3 layout option
- Added backward compatibility check for older versions of retropie without video support

---

## Preview

### Video Walkthrough
https://www.youtube.com/embed/_elwCV5hxeA

### Screenshots

*Video View*
![Video View](http://i.imgur.com/JFpJIhV.png)

*Detailed View*
![Detailed View](http://i.imgur.com/ax142A1.png)

*Basic View*
![Basic View](http://i.imgur.com/npqHCZy.png)

[For more images view the album on Imgur](http://imgur.com/a/2CSSk)

## Details

- Has support for system, basic, detailed and video views
- Does not display metadata
- Matching splashscreens are included in the \_inc/images folder
- 16x9 layout Tested on 720p and 1080p resolutions
- 4x3 layout tested on 480p/480i resolutions

## How to use

- Requires a Pi2/3 (videos are very choppy on a Pi0/1)
- Install latest version of retropie through the setup script (I know versions after 4.1.8 work)
- Add <video> elements to your gamelist to reference videos for each game on your pi (videos can be stored anywhere just like images)

## Possible Future Updates

- Support for marquee tag
- System specific backgrounds that match historical poster designs for a given system (I built an NES example to check out here: http://i.imgur.com/XCx3Tko.png)

## Acknowledgments

- Inspired by old console poster designs (see: http://imgur.com/J4eeTun and http://imgur.com/Ut0SWfJ for examples) 
- All Logo graphics are from the default Carbom theme made by Eric Hettervik (see: https://github.com/RetroPie/es-theme-carbon/)
- Static.mp4 default video from OldRoom theme by Nismo (see: https://retropie.org.uk/forum/topic/5823/looking-for-testers-for-es-video-preview-on-raspberry-pi/20)
- Video support possible because of work done by fieldofcows (see: https://retropie.org.uk/forum/topic/4820/video-preview-in-emulationstation)
- Theme tutorial written by mattrixk was a huge help in learning how to build this (see: https://github.com/RetroPie/RetroPie-Setup/wiki/Creating-Your-Own-EmulationStation-Theme)