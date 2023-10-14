# MPVClean - a fork of ModernX based on VLC
An MPV OSC script based on [mpv-osc-modern](https://github.com/maoiscat/mpv-osc-modern/) that aims to mirror the functionality of MPV's stock OSC while with a more modern-looking interface.

# How to install

Locate your MPV folder. It is typically located at `\%APPDATA%\mpv\` on Windows and `~/.config/mpv/` on Linux/MacOS. See the [Files section](https://mpv.io/manual/master/#files) in mpv's manual for more info.

> [!NOTE]
> If you have data in this folder already, please delete it or move it elsewhere (unless you know what you're doing?).

Extract the contents of the zip file into the above-mentioned folder. That's it!

# How to config
you can edit a LOT of stuff. You can choose custom keyboard shortcuts by editing the input.conf file. You can also edit osc.conf in "\~\~/script-opts/" folder, however many options are changed, so refer to the user_opts variable in the script file for details.

# Thumbnails

To enable thumbnails in timeline, install [thumbfast](https://github.com/po5/thumbfast). No other step necessary.

# Keyboard Shortcuts
* spacebar -------- play/pause
* right arrow ----- seek +3
* left arrow ------ seek -3
* shift+right ----- seek +30
* shift+left ------ seek -30
* m --------------- mute on/off
* up arrow -------- add volume +5
* down arrow ------ add volume -5
* / --------------- set volume to 100
* \[ --------------- playback speed -0.25
* \] --------------- playback speed +0.25
* \ --------------- set playback speed to 1
* q --------------- quit (MPV default)

# Buttons

like the built-in script, some buttons may accept multiple mouse actions, here is a list:

## Seekbar
* Left mouse button: seek to chosen position.
* Right mouse button: seek to the head of chosen chapter
## Playlist back/forward buttons
* Left mouse button: play previous/next file.
* Right mouse button: show playlist.
## Skip back/forward buttons
* Left mouse button: go to previous/next chapter.
* Right mouse button: show chapter list.
## Jump back/forward buttons
* Left mouse button: Jumps forwards/backwards by 5 seconds, or by the amount set in `user_opts`.
* Right mouse button: Jumps forwards/backwards by 1 minute.
* Shift + Left mouse button: Skips to the previous/next frame.
## Cycle audio/subtitle buttons
* Left mouse button/Right mouse button: cycle to next/previous track.
* Middle mouse button: show track list.
## Playback time
* Left mouse button: display time in milliseconds
## Duration
* Left mouse button: display total time instead of remaining time
