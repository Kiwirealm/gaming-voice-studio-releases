# Gaming Voice Studio · Clips

A local Windows editor for turning Marvel Rivals recordings into kill clips
and music montages.

[**Download the latest Windows installer**](https://github.com/kincinasmindaugas-kiwirealm/gaming-voice-studio-releases/releases/latest)

Choose the file ending in **Setup.exe** under Assets.
This repository contains release information and installers attached to
releases. Development files and personal recordings are kept separately.

## What you can do

- Import multiple gameplay recordings and find kills from the kill feed.
- Choose seconds before and after a kill; keep nearby multi-kills together.
- Review clips in the editor, remove unwanted ones and combine a montage.
- Add your own music, adjust beat timing, slow motion and impact effects.
- Export landscape video or TikTok/YouTube Shorts framing.
- Save editable projects and return to them later.

## First use

Requires Windows 10/11 on an x64 PC. Python and .NET are included. First
installation needs internet to download the video tools (about 110 MB).
Editing then runs on your PC. A NVIDIA GPU is not required for Clips.

Kill detection expects an uncropped 16:9 Marvel Rivals recording. The supplied
nickname sample is ZeroAlibi. For another player, set the nickname in
Detection & video settings, then use Tools > Set nickname from screenshot
with that player's green killer name. Review detections before exporting;
hidden or unclear names can be missed. It is not a universal game detector.

Project files link original recordings and music. Keep those sources when
moving projects. Preview quality is reduced; use the final video export for
the finished file.

## Updates

Connected releases check for new versions on startup. You can turn this off
or check manually in Help > Version, updates & voice. Downloads and setup
start only when you choose. Save your project, close the app and keep the
same installation folder when applying an update. Version 1.0.1 predates
online updates and must be upgraded once using a newer connected Setup.

This is the Clips package. A separate voice-model add-on is not available yet.
The initial release should be tested on a few independent PCs before wider
distribution. Windows publisher code signing has not been configured.

See PRIVACY.md for network behavior. Component license notices are included
with the installed app.
