Hermes Controller extension for Alfred
======================================
An AppleScript so you can control [Hermes](http://alexcrichton.com/hermes/) from [Alfred App](http://www.alfredapp.com)

Installation
------------
Download [Hermes Controller.alfredextension](http://tresni.github.com/HermesController.alfredextension)

How To Use
----------
`hermes play`
`hermes >` - Start playing selected station or unpause.

`hermes pause`
`hermes #` - Pause current track, use `hermes play` to resume

`hermes playpause`
`hermes pp` - Old behavior, toggling Hermes' play/pause state

`hermes next`
`hermes skip`
`hermes ~`  - Skip current track

`hermes like`
`hermes good`
`hermes +` - Thumbs up/Like a song

`hermes dislike`
`hermes bad`
`hermes -` - Thumbs down/Dislike a song

`hermes tired`
`hermes !` - Mark song as being overplayed

`hermes mute`
`hermes silence`
`hermes m` - Mute Hermes volume

`hermes unmute`
`hermes u` - Restore Hermes full volume

`hermes volume [#]`
`hermes v [#]`- Set current Hermes volume to [#]

`hermes stations [#|name]`
`hermes switch [#|name]` - Switch to the station by id or name.  Name must be an exact match.

`hermes activate`
`hermes show`
`hermes a` - bring the hermes window forward

Version History
---------------
1.3 - 25 February 2012
 - Fixed thumbs up actually marking as "tired of song"
 - Fixed "hermes -" not working.
1.2 - 15 February 2012
 - REQUIRES HERMES 1.0.18 or later
 - Added support for setting exact volume
 - Added support for switching stations
 - Added additional single character commands
1.1.1 - 12 February 2012
 - Fixed to work as a background script
1.1.0 - 21 November 2011
 - REQUIRES HERMES 1.0.13 or later
 - Use Hermes' new AppleScript support
 - Add mute, unmute, playpause support
 - play/pause no longer act as toggles
1.0.1 - 28 October 2011
 - Added some additional single character commands
1.0.0 - 27 October 2011
 - Initial Release
