mhd-berlin-2014
===============

Created during the Berlin Music Hack Day 2014, using the Rdio API.  [Try it out now](http://rstecker.github.io/mhd-berlin-2014/)

![The Setup](https://raw.githubusercontent.com/rstecker/mhd-berlin-2014/master/vr_rdio.JPG)

How it works
-------------

Written using WebGL, it requires an Rdio account to use. Does not currently work on a desktop browser. Tested only with a Nexus 4.

Be aware that you are required to click a "It's okay to play music" button when the page loads every time (so don't hold the cardboard to your face till you do).  This is a Chrome thing, not an Rdio thing-- it's still being activitly debated, (track the issue in Chromium)[https://code.google.com/p/chromium/issues/detail?id=178297]

If you focus on an album cube it'll grow in size and after a second it'll start playing a random track from the album, and start somewhere between 0% and 66% of the way through the track.

So as not to make your ears bleed the volume goes from 0 -> max when the track actually kicks in (rather than starting at max)

A blue background to the environment means a track is loading/buffering. Slowness is sadness, sorry.

Features
-------------

- [x] Play random track in album at random time
- [x] Detect which direction you're looking in
- [ ] Shuffle out content behind you so that when you turn around there's new ones
- [ ] Detect motion (shake? tilt?) to re-queue/skip/pauses content
- [ ] GO FASTER!
- [ ] Oculus integration?
