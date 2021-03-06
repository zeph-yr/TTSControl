# TTSControl

### _"You ain't heard yet? You not get the message?"_ Now they will.

Ever asked your lovely viewers to kindly give you a moment during a high pp play but sometimes a few don't get it or don't want to respect you? Worry no more, you can have silence with the click of a button! Your viewers can continue the discussion in chat and you get hear your own thoughts so everyone wins ^^

For those using browser based TTS. Toggles the volume on your browser On/Off with controller buttons in map and via UI button in main lobby. Designed to be easier to mute than to unmute to minimize accidently unmuting when you really need a moment to yourself.

This is an early release! Please feel free to reach out if you have feedback :)

![screenshot](https://github.com/zeph-yr/TTSControl/blob/main/ttscontrol_menu_small.png)

## How To Use
- Requires a freeware tool SoundVolumeView (not written by me). Get it here https://www.nirsoft.net/utils/soundvolumeview.zip and put the .exe in your /Beat Saber directory
- Place TTSControl.dll in your Plugins directory
- Run the game to generate config file. Type in the name of your browser's executable (e.g "chrome.exe" or "msedge.exe", etc) and save
- Start your browser TTS. If your browser's mute state doesnt match the button because you muted it before entering BS, click the lobby button twice.
- In Map: Press RIGHT primary button (B on Touch2) to mute. Press LEFT primary button (Y on Touch2) to unmute
- In Lobby: Button displays current state of TTS. Click to change it
- To swap left/right behavior, edit value in json to "true"
- Requires: BSIPA, BSML, BS_Utils, SiraUtil. Only for Windows (sorry linux peeps)
- ~~In Map: Pull RIGHT trigger to mute. Pull LEFT trigger to unmute. You can use the Pause menu buttons unaffected :)~~
- ~~**Note for Introskip:** I understand this has implications for Introskip during the skip periods. Skipping will trigger mute/ummute so please skip with the L or R trigger accordingly. Or use the lobby button if you want to mute/unmute before going into a map :)~~

## Coming Soon / Notes
- Done: Support for browser of your choice
- Done: Support for swapping left/right
- Not likely to bring back using the triggers. Probably hard to avoid accidental clicks for most players.
- **Tested on Oculus Touch 2 controllers with Rift S playing in Steamvr mode.** Binding might be different on other VR setups - let me know how it goes for you :)

## About
My 3rd mod, written from scratch and mostly for myself. If you enjoy this, I appreciate your feedback :)

And yes, the lobby button appears slightly "out of place"... because if it's lined up with the game menu, its hitbox gets occluded KEKW.
