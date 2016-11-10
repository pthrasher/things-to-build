# things-to-build
A list of things I wanna build, or have already been built

- [x] [Funny Sound Board iOS App](#funny-sound-board-ios-app)
    - [x] 1.0
    - [ ] 2.0
- [ ] [Spotify Favorite Tracks Helper](#spotify-favorite-tracks-helper)
    - [ ] 1.0
    - [ ] 2.0

# Funny Sound Board iOS App

Just a funny soundboard app for mobile with sound bytes from people I know, or funny youtube vids.

- **1.0**
    - Add 1 single page of buttons for first pass of sounds.
    - Make sure the buttons resize / reorient for different device screen sizes / orientations.
    - Group sounds by source vid.

- **2.0**
    - Add second page with more sounds
    - Clean up sound bytes so they have less "dead space" before the track starts.

# Spotify Favorite Tracks Helper

The idea here is to monitor my spotify listening when working. I want to log the time of day I listened to a specific song, and whether or not I listened to it without skipping. The reason for this... Is because music helps me work, but some songs that I like earlier in the day bother me later in the day and I end up skipping songs a lot more. I thought I could simply create playlists for certain times of the day, but this is a major hassle to manage manually. Also, it's error prone. I think data and real statistics could help build playlists better by time of day.

- **1.0**
    - If I listen to a song all the way through from any playlist, put it in a "magic" playlist.
    - If I skip a song more than one time after it's been placed in that playlist, remove it from that playlist.
    - Save in a database of some kind the time of day I skipped a particular track.
    - Save in a database of some kind the time of day I fully listened to a particular track.
 
 
- **2.0**
    - If I skip a song, put it in a different playlist... Add it back to the magic playlist after a set timeout period.
    - This can be prevented by deleting it from the "deleted" playlist.
