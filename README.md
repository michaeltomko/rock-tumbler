# Rock Tumbler 

Rock Tumbler takes the pain out of listening to playlists in Spotify. Some might even say that it smoothes out the edges of rock.

## Getting Started

1. Clone this repo into your `~/Spotify` directory. (Hint: You may need to create the path first.)

2. Login here [to upgrade your Spotify account to a "Developer" account](https://developer.spotify.com/login/).

3. Launch Spotify.

4. Type `spotify:app:rock-tumbler` into the search bar and then click "add" to add the app to your favorites. (Note, this will need to be done every time that you launch Spotify.)

5. Drag any playlist into the dashed drop box and once loaded, use the player to the right to begin playing the playlist. Rock Tumbler will remember what you have already listened to and automatically make those song ineligble to be played until you've made it all of the way through the playlist, even if you close the app!

6. Enjoy!

## Helpful Hints

* When on the app screen, `CMD+OPT+R` will reload the app.

* You can drop as many playlists into the dropbox as you wish. Rock Tumbler will play the last playlist dropped and will ignore duplicate drops.

* Rock Tumbler keeps track of changes that you make to your playlists — like adding and removing tracks — and will even keep your history if you rename a playlist.

## Feedback is Welcome

Feel free to contact me at: [tomko@theablefew.com](mailto://tomko@theablefew.com)

## Release History
* __2013/05/13__ - _0.5.0_ - Performance improvements and bug fixes.
* __2013/05/12__ - _0.4.1_ - Critical bug fix.
* __2013/05/12__ - _0.4.0_ - Lots of bug fixes. Previous button should now work while hitting multiple next events. Playlist and Played List now show track count and playlist duration.
* __2013/05/07__ - _0.3.3_ - Switched to LZW compression for data stored in localStorage. Fixed issue with large amount of next events, or other situations, causing playlist to lose context. Fixed issue with end event usurping control from queued next events. Added messaging for when playlists have been completed.
* __2013/05/05__ - _0.3.2_ - Repeatedly dropping playlists now works as expected. Cleaned up race conditions and oddness that occurred with the first track on some playlists.
* __2013/05/05__ - _0.3.1_ - Bug fixes. Minor UI tweaks.
* __2013/05/05__ - _0.3.0_ - Bug fixes. First version UI. Player context is now set on playlist drop.
* __2013/05/04__ - _0.2.0_ - Bug fixes. Playlists are de-duplicated before shuffling. Refactored sessions.
* __2013/05/04__ - _0.1.1_ - Bug fixes. Switched to Lo-Dash.js. Added logger.
* __2013/05/02__ - _0.1.0_ - Initial functional release

----
The Able Few - [St. Louis Ruby on Rails & NodeJS development](http://theablefew.com/?utm_source=GitHub&utm_medium=link&utm_campaign=rock-tumbler)
